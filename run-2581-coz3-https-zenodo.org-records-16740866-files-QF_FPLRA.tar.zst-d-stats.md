# .

* SAT 31
* UNSAT 2
* TIMEOUT 26
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_FPLRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_FPLRA.tar.zst-d
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_FPLRA.tar.zst?download=1
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
|non-incremental/QF_FPLRA/schanda/spark/zeros_consistent_1.smt2 |    0.024s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/Double_div_bad_false-unreach-call.i_1.smt2 |    0.055s | 20.748MiB| unsat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c_3.smt2 |    1.335s | 331.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/Double_div_bad_false-unreach-call.i_0.smt2 |    1.921s | 161.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c.p+cfa-reducer.c_4.smt2 |    2.112s | 265.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0520_true-unreach-call.c_0.smt2 |    3.124s | 198.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0310_true-unreach-call.c_3.smt2 |    3.699s | 173.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0250b_true-unreach-call.c_4.smt2 |    3.964s | 295.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0320_true-unreach-call.c_7.smt2 |    4.513s | 368.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c.p+cfa-reducer.c_2.smt2 |    5.248s | 392.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0330a_true-unreach-call.c_6.smt2 |    5.267s | 487.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0320_true-unreach-call.c_5.smt2 |    5.692s | 486.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Newton_pseudoconstant_true-unreach-call.c_1.smt2 |    5.786s | 419.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0873a_true-unreach-call.c_3.smt2 |    6.119s | 360.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0470_true-unreach-call.c_12.smt2 |    6.676s | 390.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c.p+cfa-reducer.c_1.smt2 |    7.019s | 392.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0870b.c_1.smt2 |    8.066s | 209.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0260_true-unreach-call.c_1.smt2 |    8.408s | 677.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0490a_true-unreach-call.c_0.smt2 |    8.413s | 391.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0330b_true-unreach-call.c_10.smt2 |    8.588s | 490.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0490a_true-unreach-call.c_10.smt2 |    8.598s | 444.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_2.smt2 |    8.769s | 682.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0460_true-unreach-call.c_2.smt2 |    8.971s | 485.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0490a_true-unreach-call.c_9.smt2 |    9.209s | 390.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0870b_true-unreach-call.c_3.smt2 |    9.239s | 230.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c.p+cfa-reducer.c_3.smt2 |    9.736s | 766.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20170501-Heizmann-UltimateAutomizer/filter2_reinit_true-unreach-call.c_7.smt2 |   10.728s | 171.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20170501-Heizmann-UltimateAutomizer/image_filter_true-unreach-call.c_2.smt2 |   10.808s | 194.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0320_true-unreach-call.c_6.smt2 |   12.730s | 185.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/Rump_double_true-unreach-call_true-termination.c_0.smt2 |   15.349s | 2580.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/cos_polynomial_true-unreach-call_true-termination.c_0.smt2 |   16.030s | 522.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0240a_true-unreach-call.c_6.smt2 |   17.116s | 387.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_19.smt2 |   18.043s | 1341.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0874_true-unreach-call.c_3.smt2 |   20.042s | 221.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_11.smt2 |   20.073s | 410.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0550b_true-unreach-call.c_9.smt2 |   20.086s | 420.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20230321-UltimateAutomizerSvcomp2023/cos_polynomial.c_0.smt2 |   20.109s | 458.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0490a_true-unreach-call.c_2.smt2 |   20.112s | 488.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20170501-Heizmann-UltimateAutomizer/cos_polynomial_true-unreach-call.c_9.smt2 |   20.116s | 508.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0260_true-unreach-call.c_3.smt2 |   20.149s | 1077.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_21.smt2 |   20.150s | 1139.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0250a.c_1.smt2 |   20.164s | 1079.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_4.smt2 |   20.182s | 1084.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0460_true-unreach-call.c_3.smt2 |   20.200s | 1613.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/lnLaw.smt2            |   20.201s | 1901.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0490a_true-unreach-call.c_3.smt2 |   20.207s | 1611.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/expLaw.smt2           |   20.213s | 1914.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propLnExp0.smt2       |   20.221s | 1904.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propExpLn1.smt2       |   20.225s | 1900.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propLnExp2.smt2       |   20.231s | 1888.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propLnExp3.smt2       |   20.235s | 1898.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0490a.c_4.smt2 |   20.235s | 1626.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propExpLn2.smt2       |   20.252s | 1898.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propLnExp1.smt2       |   20.252s | 1903.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/expInUnit.smt2        |   20.258s | 1900.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propExpLn0.smt2       |   20.307s | 3682.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propExpLn3.smt2       |   20.366s | 3067.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/maxReward.smt2        |   20.881s | 9923.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/expInUnit2.smt2       |   20.950s | 10.793GiB| timeout | 0 |  |  |
