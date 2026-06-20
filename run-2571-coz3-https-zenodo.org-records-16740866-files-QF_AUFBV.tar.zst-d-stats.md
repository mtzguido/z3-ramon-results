# .

* SAT 9
* UNSAT 34
* TIMEOUT 32
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_AUFBV.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_AUFBV.tar.zst-d
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_AUFBV.tar.zst?download=1
Z3 commit message: Fix constant array UNSAT missed for small-domain store chains (#9907)

Z3 incorrectly returns SAT for formulas like `store(store(const(x), i0,
e0), i1, e1) = store(store(const(y), i0, e0), i1, e1) ∧ x ≠ y` when the
index sort has a small finite domain (e.g. `(_ BitVec 2)` = 4 elements).
The quantifier-based encoding of the same constraint correctly returns
UNSAT.

## Changes

### `src/sat/smt/array_solver.cpp` — `add_parent_lambda()`

When a store is added to an array's `m_parent_lambdas` after that array
already has `m_has_default = true` (i.e., a `default(array)` term
already exists in the e-graph), the default axiom for the new store was
silently dropped. This breaks the propagation chain:

```
default(const(x)) = x
  ↓ [via store default axiom]
default(store(const(x), i, v)) = x
  ↓ [via store default axiom]
default(store(store(const(x), ...), ...)) = x
  ↓ [EUF congruence from store equality]
x = y  →  contradiction
```

Fix: push `default_axiom(lambda)` in `add_parent_lambda` when
`m_has_default` is already set, so late-arriving stores still get their
default axioms instantiated.

```cpp
void solver::add_parent_lambda(theory_var v_child, euf::enode* lambda) {
    auto& d = get_var_data(find(v_child));
    ctx.push_vec(d.m_parent_lambdas, lambda);
    if (should_prop_upward(d))
        propagate_select_axioms(d, lambda);
    if (d.m_has_default)           // new: fire default axiom retroactively
        push_axiom(default_axiom(lambda));
}
```

### Known remaining gap

`mk_eq_core` in `array_rewriter.cpp` also has a related issue: the
unconditional store-chain expansion fires only when `domain_size >
num_lhs + num_rhs` (line 893), but the correct threshold is `domain_size
> max(num_lhs, num_rhs)`. With 4-element domain and 2 stores per side,
`2+2 = 4` equals the domain size so the expansion is skipped. The
variant gated by `m_expand_store_eq` already uses `max()` correctly
(line 911); the unconditional path needs the same fix.

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div10.short.smt2 |    0.031s | 20.0MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner23.short.smt2 |    0.038s | 28.544MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2/gzip/250_gzip.smt2  |    0.041s | 21.472MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add1.short.smt2 |    0.048s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner12.short.smt2 |    0.050s | 21.632MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init2.short.smt2 |    0.051s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init.short.smt2 |    0.052s | 20.536MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div1.short.smt2 |    0.055s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner22.short.smt2 |    0.057s | 21.596MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner13.short.smt2 |    0.057s | 28.552MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div14.short.smt2 |    0.059s | 21.16MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init1.short.smt2 |    0.059s | 20.224MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner3.short.smt2 |    0.059s | 22.144MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner4.short.smt2 |    0.060s | 28.936MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.group_red1.short.smt2 |    0.066s | 28.564MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub1.short.smt2 |    0.067s | 33.184MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div12.short.smt2 |    0.070s | 22.52MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub2.short.smt2 |    0.071s | 33.236MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add2.short.smt2 |    0.074s | 29.9MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add4.short.smt2 |    0.075s | 31.24MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2-partial-undef/gzip/322_gzip.smt2 |    0.078s | 22.852MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal.smt2 |    0.092s | 24.676MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub3.short.smt2 |    0.092s | 33.428MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2/gzip/272_gzip.smt2  |    0.093s | 22.824MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux4.short.smt2 |    0.101s | 32.404MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2-partial-undef/gzip/332_gzip.smt2 |    0.106s | 22.984MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal.smt2 |    0.107s | 25.376MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux3.short.smt2 |    0.115s | 32.316MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux2.short.smt2 |    0.127s | 32.36MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash4.short.smt2 |    0.167s | 63.368MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash3.short.smt2 |    0.191s | 63.392MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash5.short.smt2 |    0.196s | 63.24MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add3.short.smt2 |    0.201s | 45.388MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2 |    0.351s | 44.684MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux12.short.smt2 |    0.394s | 93.712MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux1.short.smt2 |    0.414s | 93.536MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux11.short.smt2 |    0.444s | 93.648MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2 |    0.606s | 46.576MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2 |    0.853s | 73.136MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2/ph7/708_ph7.smt2    |    1.550s | 131.0MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2-partial-undef/gcc/204_gcc.smt2 |    4.207s | 34.948MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.verifySignature.short.smt2 |    4.455s | 68.86MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2 |    8.482s | 131.0MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAY_QF_AUFBV_NONINCR.smt2 |   20.023s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2 |   20.026s | 201.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2 |   20.028s | 161.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2 |   20.028s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2-partial-undef/sqlite3/891_sqlite3.smt2 |   20.035s | 71.548MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2/gcc/033_gcc.smt2    |   20.042s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2 |   20.044s | 69.98MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2 |   20.046s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2 |   20.047s | 86.896MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2 |   20.050s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal_no_rewrite.smt2 |   20.052s | 523.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2 |   20.053s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2 |   20.058s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2/sqlite3/906_sqlite3.smt2 |   20.060s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2 |   20.060s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCY_QF_AUFBV_NONINCR.smt2 |   20.064s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2    |   20.070s | 388.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2 |   20.074s | 219.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |   20.076s | 528.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |   20.076s | 672.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2 |   20.080s | 220.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2 |   20.095s | 281.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |   20.116s | 1095.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2 |   20.143s | 1705.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2 |   20.159s | 1161.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2 |   20.166s | 993.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2 |   20.222s | 1997.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2 |   20.271s | 3621.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2 |   20.336s | 2525.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2 |   20.368s | 3595.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2 |   20.498s | 4301.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2 |   20.611s | 6917.0MiB| timeout | 0 |  |  |
