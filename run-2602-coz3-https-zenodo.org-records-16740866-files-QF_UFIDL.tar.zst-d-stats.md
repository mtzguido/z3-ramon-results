# .

* SAT 189
* UNSAT 312
* TIMEOUT 127
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFIDL.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFIDL.tar.zst-d
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFIDL.tar.zst?download=1
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
|non-incremental/QF_UFIDL/uclid/49s.smt2                      |    0.025s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/TwoSquares/smtlib.883203.smt2       |    0.034s | 19.504MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/32s.smt2                      |    0.035s | 20.848MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/TwoSquares/smtlib.877473.smt2       |    0.035s | 19.5MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/TwoSquares/smtlib.600181.smt2       |    0.036s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/TwoSquares/smtlib.693723.smt2       |    0.036s | 19.568MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/TwoSquares/smtlib.883218.smt2       |    0.036s | 19.464MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/TwoSquares/smtlib.600173.smt2       |    0.038s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/TwoSquares/smtlib.693706.smt2       |    0.038s | 19.404MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/OOO/OOO0.smt2            |    0.039s | 20.124MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded0.smt2 |    0.039s | 20.068MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/TwoSquares/smtlib.600189.smt2       |    0.039s | 20.204MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/TwoSquares/smtlib.877456.smt2       |    0.039s | 19.572MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/simple_cyclic0.smt2             |    0.040s | 20.292MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/reverse_acyclic0.smt2           |    0.042s | 20.116MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/aodv/aodv0.smt2          |    0.042s | 20.032MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8_s.smt2                     |    0.042s | 20.188MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9_s.smt2                     |    0.042s | 20.24MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10_s.smt2                    |    0.042s | 20.236MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/TwoSquares/smtlib.877439.smt2       |    0.042s | 19.404MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery0.smt2 |    0.043s | 19.98MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9n_s.smt2                    |    0.043s | 20.58MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7n_s.smt2                    |    0.043s | 20.424MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7b_s.smt2                    |    0.044s | 20.216MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7_s.smt2                     |    0.044s | 20.324MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/TwoSquares/smtlib.883173.smt2       |    0.045s | 19.588MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full0.smt2 |    0.046s | 20.132MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9b_s.smt2                    |    0.046s | 20.492MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/TwoSquares/smtlib.883188.smt2       |    0.046s | 19.44MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/set_union0.smt2                 |    0.047s | 20.18MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/sorted_list_insert_noalloc0.smt2 |    0.047s | 20.24MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6b_s.smt2                    |    0.047s | 20.188MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8b_s.smt2                    |    0.047s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/TwoSquares/smtlib.693740.smt2       |    0.047s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/5s.smt2                        |    0.049s | 20.52MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard3.smt2 |    0.049s | 20.292MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard2.smt2 |    0.049s | 20.204MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/simple_cyclic1.smt2             |    0.050s | 20.696MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6_s.smt2                     |    0.050s | 20.088MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10n_s.smt2                   |    0.050s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/DLX/DLX1C0.smt2          |    0.051s | 20.508MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/simple_cyclic2.smt2             |    0.052s | 20.656MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10b_s.smt2                   |    0.052s | 20.548MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/aodv/aodv1.smt2          |    0.053s | 20.764MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6i_s.smt2                    |    0.053s | 21.212MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded1.smt2 |    0.054s | 21.024MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/aodv/aodv2.smt2          |    0.055s | 20.816MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full1.smt2 |    0.056s | 20.584MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/simple_cyclic4.smt2             |    0.057s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/simple_cyclic3.smt2             |    0.057s | 20.648MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/OOO/OOO1.smt2            |    0.057s | 20.844MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/27s.smt2                      |    0.058s | 21.084MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery1.smt2 |    0.058s | 21.348MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6n_s.smt2                    |    0.058s | 20.58MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard4.smt2 |    0.058s | 20.5MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/46s.smt2                      |    0.060s | 21.184MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/ooo.rf6.smt2                  |    0.062s | 20.408MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full2.smt2 |    0.062s | 20.664MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g6.smt2                       |    0.063s | 21.06MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g6n.smt2                      |    0.063s | 21.268MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6bi_s.smt2                   |    0.064s | 21.58MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8n_s.smt2                    |    0.066s | 20.256MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/reverse_acyclic1.smt2           |    0.068s | 21.36MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded3.smt2 |    0.068s | 21.14MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/elf.rf6.smt2                  |    0.070s | 20.228MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/BRP/BRP3.smt2            |    0.070s | 21.308MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/aodv/aodv3.smt2          |    0.071s | 21.608MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/set_union1.smt2                 |    0.073s | 21.096MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full4.smt2 |    0.073s | 21.584MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full3.smt2 |    0.074s | 21.224MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/reverse_acyclic3.smt2           |    0.075s | 21.444MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/BRP/BRP2.smt2            |    0.075s | 21.228MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete3/bug_file6.smt2                |    0.076s | 22.1MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/reverse_acyclic5.smt2           |    0.077s | 21.604MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/OOO/OOO2.smt2            |    0.077s | 21.52MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded4.smt2 |    0.077s | 21.664MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6nidw_s.smt2                 |    0.077s | 22.328MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/BRP/BRP4.smt2            |    0.078s | 21.324MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded2.smt2 |    0.078s | 21.112MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g6i.smt2                      |    0.078s | 21.1MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/reverse_acyclic2.smt2           |    0.079s | 21.492MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery2.smt2 |    0.079s | 21.928MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6id_s.smt2                   |    0.079s | 21.8MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard5.smt2 |    0.080s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/ooo.rf7.smt2                  |    0.081s | 21.108MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/BRP/BRP9.smt2            |    0.081s | 21.332MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g6ni.smt2                     |    0.081s | 21.432MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/BRP/BRP8.smt2            |    0.082s | 21.34MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/elf.rf7.smt2                  |    0.083s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6idw_s.smt2                  |    0.083s | 21.928MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard6.smt2 |    0.083s | 20.468MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/44s.smt2                      |    0.084s | 21.624MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/reverse_acyclic4.smt2           |    0.084s | 21.612MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/BRP/BRP1.smt2            |    0.084s | 21.32MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/BRP/BRP6.smt2            |    0.084s | 21.432MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/reverse_acyclic6.smt2           |    0.085s | 21.508MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/set_union2.smt2                 |    0.086s | 21.824MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/BRP/BRP7.smt2            |    0.086s | 21.512MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/6stage-flush.smt2              |    0.087s | 21.592MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full6.smt2 |    0.087s | 22.084MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/RTCL/b13_tf_100/b13_tf_100.smt2     |    0.088s | 23.66MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard7.smt2 |    0.088s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/BRP/BRP5.smt2            |    0.089s | 21.428MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g6b.smt2                      |    0.089s | 21.3MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/DLX/DLX1C2.smt2          |    0.090s | 21.9MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f6.smt2                       |    0.090s | 21.492MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6bidw_s.smt2                 |    0.092s | 22.24MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/cache.inv8.smt2               |    0.094s | 21.116MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/DLX/DLX1C1.smt2          |    0.094s | 22.156MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6bid_s.smt2                  |    0.094s | 21.928MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7nidw_s.smt2                 |    0.094s | 23.096MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/set_union3.smt2                 |    0.096s | 21.96MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded5.smt2 |    0.097s | 22.712MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/fxs-safety.smt2                |    0.098s | 21.288MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7idw_s.smt2                  |    0.098s | 22.496MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery3.smt2 |    0.099s | 22.208MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6ni_s.smt2                   |    0.099s | 21.952MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/dlx1c.smt2                    |    0.101s | 21.464MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/set_union5.smt2                 |    0.101s | 22.316MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/set_union4.smt2                 |    0.103s | 22.148MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full5.smt2 |    0.103s | 22.256MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8idw_s.smt2                  |    0.104s | 23.092MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f6b.smt2                      |    0.104s | 22.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/dlx1c.rwmem.smt2              |    0.105s | 21.392MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10i_s.smt2                   |    0.105s | 23.648MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10idw_s.smt2                 |    0.106s | 23.996MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f6i.smt2                      |    0.107s | 21.808MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/dlx1c.rwmem1.smt2             |    0.108s | 21.368MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8bidw_s.smt2                 |    0.109s | 23.216MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/cxs-safety.smt2                |    0.110s | 21.22MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g6idw.smt2                    |    0.110s | 21.996MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/elf.rf8.smt2                  |    0.111s | 22.096MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/37s.smt2                      |    0.112s | 22.672MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g7b.smt2                      |    0.112s | 21.88MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid2/bug2.smt2                    |    0.113s | 21.376MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/ooo.tag8.smt2                 |    0.115s | 21.192MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/aodv/aodv4.smt2          |    0.115s | 22.88MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7bidw_s.smt2                 |    0.115s | 22.624MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g6bid.smt2                    |    0.116s | 22.072MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/ooo.tag10.smt2                |    0.118s | 22.56MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g7.smt2                       |    0.123s | 21.324MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10ni_s.smt2                  |    0.124s | 24.432MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/cxs.smt2                       |    0.130s | 21.176MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10id_s.smt2                  |    0.130s | 24.296MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f6ni.smt2                     |    0.130s | 22.272MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g7n.smt2                      |    0.131s | 21.672MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6nid_s.smt2                  |    0.131s | 22.76MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/DLX/DLX1C3.smt2          |    0.133s | 23.616MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g6bi.smt2                     |    0.133s | 21.504MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/25s.smt2                      |    0.135s | 22.916MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/sorted_list_insert_noalloc1.smt2 |    0.135s | 22.924MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g6nid.smt2                    |    0.135s | 21.948MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9idw_s.smt2                  |    0.135s | 23.748MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g6bidw.smt2                   |    0.135s | 22.316MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/fxs.smt2                       |    0.136s | 22.308MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9bidw_s.smt2                 |    0.136s | 23.928MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery7.smt2 |    0.137s | 23.484MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/fxs-bp-safety.smt2             |    0.138s | 22.192MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete3/bug_file1.smt2                |    0.139s | 25.44MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard9.smt2 |    0.140s | 20.688MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/ooo.rf8.smt2                  |    0.141s | 21.64MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g6id.smt2                     |    0.141s | 21.88MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10bid_s.smt2                 |    0.141s | 24.284MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/OOO/OOO3.smt2            |    0.142s | 23.66MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7_i.smt2                     |    0.143s | 21.424MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8nidw_s.smt2                 |    0.143s | 24.116MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f6bi.smt2                     |    0.143s | 22.52MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard8.smt2 |    0.143s | 20.744MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/fxs-bp-ex-safety.smt2          |    0.144s | 22.772MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full8.smt2 |    0.144s | 22.76MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10bidw_s.smt2                |    0.144s | 24.584MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g8.smt2                       |    0.145s | 22.04MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/cxs-bp.smt2                    |    0.147s | 21.644MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full7.smt2 |    0.147s | 22.816MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6_i.smt2                     |    0.147s | 21.14MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard11.smt2 |    0.150s | 21.056MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10bi_s.smt2                  |    0.151s | 24.144MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10nid_s.smt2                 |    0.151s | 25.544MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/10stage-flush.smt2             |    0.153s | 29.788MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/aodv/aodv5.smt2          |    0.153s | 23.372MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery5.smt2 |    0.155s | 23.092MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6.smt2                       |    0.155s | 21.312MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/fxs-bp.smt2                    |    0.159s | 23.168MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery6.smt2 |    0.159s | 23.412MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/cxs-bp-ex.smt2                 |    0.160s | 22.016MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery9.smt2 |    0.160s | 23.932MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f6n.smt2                      |    0.160s | 21.952MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid2/bug1.smt2                    |    0.160s | 22.964MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery8.smt2 |    0.161s | 23.824MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/cxs-bp-safety.smt2             |    0.163s | 21.724MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery4.smt2 |    0.165s | 23.024MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f6id.smt2                     |    0.166s | 23.316MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/OOO/OOO4.smt2            |    0.167s | 24.668MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/DLX/DLX1C4.smt2          |    0.168s | 24.228MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded6.smt2 |    0.175s | 24.468MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded7.smt2 |    0.176s | 24.46MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery11.smt2 |    0.181s | 24.468MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g8n.smt2                      |    0.181s | 22.416MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/fxs-bp-ex-inp-safety.smt2      |    0.185s | 23.064MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/ooo.tag12.smt2                |    0.187s | 23.936MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard15.smt2 |    0.191s | 21.44MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/OOO/OOO5.smt2            |    0.192s | 25.66MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard10.smt2 |    0.192s | 21.004MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full9.smt2 |    0.194s | 23.008MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10nidw_s.smt2                |    0.196s | 26.104MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete3/bug_file3.smt2                |    0.198s | 27.364MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g7idw.smt2                    |    0.201s | 22.968MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/aodv/aodv6.smt2          |    0.202s | 23.508MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/DLX/DLX1C5.smt2          |    0.204s | 24.62MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9nidw_s.smt2                 |    0.205s | 25.172MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8_i.smt2                     |    0.209s | 21.544MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/cxs-bp-ex-safety.smt2          |    0.213s | 22.188MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/IC-flush.smt2                  |    0.217s | 32.504MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery12.smt2 |    0.220s | 24.924MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete3/bug_file2.smt2                |    0.221s | 26.648MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9.smt2                       |    0.224s | 21.696MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/cxs-bp-ex-inp.smt2             |    0.225s | 22.196MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/OOO/OOO6.smt2            |    0.226s | 26.236MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g8b.smt2                      |    0.231s | 22.736MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/OOO/OOO8.smt2            |    0.234s | 26.756MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded9.smt2 |    0.234s | 26.364MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9_i.smt2                     |    0.234s | 21.552MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/sorted_list_insert_noalloc2.smt2 |    0.235s | 26.752MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7b_i.smt2                    |    0.238s | 21.708MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery13.smt2 |    0.239s | 24.8MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g6nidw.smt2                   |    0.241s | 22.148MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l75.smt2    |    0.245s | 30.536MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery10.smt2 |    0.246s | 24.516MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery15.smt2 |    0.247s | 24.676MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10_i.smt2                    |    0.250s | 21.836MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10.smt2                      |    0.252s | 22.072MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/fxs-bp-ex.smt2                 |    0.253s | 24.156MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard12.smt2 |    0.254s | 21.488MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/cxs-bp-ex-inp-safety.smt2      |    0.255s | 22.152MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6n_i.smt2                    |    0.257s | 21.724MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/fxs-bp-ex-inp.smt2             |    0.259s | 24.436MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8.smt2                       |    0.260s | 21.808MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery14.smt2 |    0.261s | 25.348MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g7bidw.smt2                   |    0.265s | 23.592MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded13.smt2 |    0.266s | 27.08MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6b_i.smt2                    |    0.269s | 21.744MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded11.smt2 |    0.270s | 26.384MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f6nid.smt2                    |    0.270s | 23.836MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery16.smt2 |    0.271s | 40.036MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded10.smt2 |    0.273s | 38.14MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g7nidw.smt2                   |    0.283s | 23.64MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete3/bug_file4.smt2                |    0.285s | 30.44MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/OOO/OOO7.smt2            |    0.289s | 26.448MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f7.smt2                       |    0.289s | 22.412MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded8.smt2 |    0.298s | 37.812MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f7b.smt2                      |    0.298s | 23.624MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/cache.inv10.smt2              |    0.299s | 22.436MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9b_i.smt2                    |    0.300s | 22.448MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l44.smt2    |    0.303s | 34.672MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l76.smt2    |    0.305s | 33.416MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g9.smt2                       |    0.306s | 22.792MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g8idw.smt2                    |    0.306s | 23.908MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded14.smt2 |    0.310s | 37.992MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f6bid.smt2                    |    0.310s | 24.02MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard13.smt2 |    0.311s | 21.412MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded12.smt2 |    0.317s | 38.148MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7.smt2                       |    0.323s | 21.644MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/elf.rf9.smt2                  |    0.327s | 24.2MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded15.smt2 |    0.330s | 27.24MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8b_i.smt2                    |    0.330s | 22.256MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8b.smt2                      |    0.337s | 22.476MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/sorted_list_insert_noalloc4.smt2 |    0.347s | 29.476MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g10b.smt2                     |    0.347s | 24.388MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded16.smt2 |    0.349s | 38.084MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g10.smt2                      |    0.349s | 23.292MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/43s.smt2                      |    0.350s | 23.996MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/sorted_list_insert_noalloc3.smt2 |    0.353s | 29.528MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l97.smt2    |    0.353s | 31.72MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f7n.smt2                      |    0.357s | 23.448MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l22.smt2    |    0.360s | 28.036MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10n_i.smt2                   |    0.363s | 22.948MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/sorted_list_insert_noalloc6.smt2 |    0.365s | 29.164MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/OOO/OOO9.smt2            |    0.366s | 26.548MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7n_i.smt2                    |    0.368s | 22.148MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10b.smt2                     |    0.369s | 23.12MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/sorted_list_insert_noalloc8.smt2 |    0.373s | 29.14MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8n_i.smt2                    |    0.379s | 22.668MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6n.smt2                      |    0.384s | 22.78MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/sorted_list_insert_noalloc7.smt2 |    0.404s | 29.22MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery17.smt2 |    0.405s | 25.448MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g9n.smt2                      |    0.405s | 23.408MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/22s.smt2                      |    0.409s | 24.272MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8n.smt2                      |    0.409s | 23.488MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/sorted_list_insert_noalloc5.smt2 |    0.415s | 29.344MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6b.smt2                      |    0.417s | 22.128MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/bakery/LamportBakery18.smt2 |    0.419s | 38.924MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7b.smt2                      |    0.422s | 22.368MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g8bidw.smt2                   |    0.425s | 24.828MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10b_i.smt2                   |    0.425s | 23.072MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9n_i.smt2                    |    0.427s | 22.78MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l29.smt2    |    0.432s | 39.72MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7n.smt2                      |    0.439s | 22.604MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f6idw.smt2                    |    0.450s | 24.668MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l08.smt2    |    0.455s | 36.936MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10n.smt2                     |    0.458s | 23.756MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/8stage-flush.smt2              |    0.465s | 23.896MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/RDS/sorted_list_insert_noalloc9.smt2 |    0.471s | 29.292MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f6nidw.smt2                   |    0.477s | 25.244MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l32.smt2    |    0.480s | 32.088MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard16.smt2 |    0.483s | 21.892MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g8nidw.smt2                   |    0.493s | 24.688MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9n.smt2                      |    0.502s | 23.816MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f6bidw.smt2                   |    0.529s | 25.444MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l94.smt2    |    0.530s | 34.196MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g10idw.smt2                   |    0.532s | 26.624MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6i.smt2                      |    0.535s | 22.696MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete3/bug_file5.smt2                |    0.536s | 27.7MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard18.smt2 |    0.541s | 22.304MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g9b.smt2                      |    0.549s | 23.856MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard17.smt2 |    0.552s | 21.996MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9b.smt2                      |    0.553s | 23.152MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g10i.smt2                     |    0.556s | 24.088MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard14.smt2 |    0.572s | 21.852MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l12.smt2    |    0.592s | 36.904MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard19.smt2 |    0.597s | 22.004MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g10bi.smt2                    |    0.599s | 25.12MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid2/ooo.tag15.smt2               |    0.606s | 28.568MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g9idw.smt2                    |    0.609s | 25.428MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/q2.10.smt2                    |    0.633s | 21.856MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/ooo.tag14.smt2                |    0.647s | 27.068MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f8.smt2                       |    0.656s | 23.636MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6i_i.smt2                    |    0.666s | 22.644MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l05.smt2    |    0.672s | 58.264MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l10.smt2    |    0.675s | 38.208MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g9bidw.smt2                   |    0.676s | 26.26MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l00.smt2    |    0.677s | 53.968MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l01.smt2    |    0.706s | 54.124MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6idw_i.smt2                  |    0.723s | 23.132MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g10bid.smt2                   |    0.731s | 27.176MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l09.smt2    |    0.756s | 60.04MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6idw.smt2                    |    0.761s | 23.36MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6id_i.smt2                   |    0.764s | 22.968MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6id.smt2                     |    0.792s | 23.28MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/ooo.rf9.smt2                  |    0.802s | 22.824MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l91.smt2    |    0.847s | 43.836MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g9nidw.smt2                   |    0.875s | 26.112MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6nidw_i.smt2                 |    0.892s | 24.228MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g10bidw.smt2                  |    0.904s | 28.012MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/cache.inv12.smt2              |    0.905s | 23.848MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/UCLID-pred/ibm_cache/ibm_cache_full_q_unbounded17.smt2 |    0.912s | 27.908MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6bi.smt2                     |    0.912s | 23.684MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l06.smt2    |    0.915s | 59.98MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid2/ooo.tag17.smt2               |    0.919s | 31.176MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f8b.smt2                      |    0.928s | 25.324MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g10n.smt2                     |    0.930s | 24.832MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l02.smt2    |    0.939s | 55.136MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6bi_i.smt2                   |    0.949s | 23.632MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6bid_i.smt2                  |    0.957s | 23.96MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l03.smt2    |    0.972s | 56.44MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l25.smt2    |    0.989s | 52.612MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/mathsat/EufLaArithmetic/vhard/vhard20.smt2 |    0.991s | 22.66MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l50.smt2    |    1.011s | 62.828MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l04.smt2    |    1.022s | 57.968MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6bidw.smt2                   |    1.023s | 24.428MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f8n.smt2                      |    1.073s | 25.548MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6nid_i.smt2                  |    1.075s | 24.364MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g10id.smt2                    |    1.080s | 26.012MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6ni_i.smt2                   |    1.152s | 23.728MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l38.smt2    |    1.165s | 59.224MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6nid.smt2                    |    1.187s | 25.024MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f7nidw.smt2                   |    1.187s | 27.876MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6nidw.smt2                   |    1.209s | 25.336MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g10ni.smt2                    |    1.210s | 25.708MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f7idw.smt2                    |    1.233s | 26.924MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f7bidw.smt2                   |    1.235s | 28.132MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g10nid.smt2                   |    1.262s | 27.152MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete/9stage-flush.smt2              |    1.286s | 25.244MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6bid.smt2                    |    1.324s | 24.12MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l18.smt2    |    1.351s | 76.688MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l59.smt2    |    1.360s | 66.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l17.smt2    |    1.373s | 86.356MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l27.smt2    |    1.393s | 65.34MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7idw_i.smt2                  |    1.409s | 24.348MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6ni.smt2                     |    1.424s | 24.728MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7idw.smt2                    |    1.443s | 24.388MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l21.smt2    |    1.461s | 77.096MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l54.smt2    |    1.515s | 65.352MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l35.smt2    |    1.523s | 97.492MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7nidw.smt2                   |    1.553s | 25.784MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l11.smt2    |    1.565s | 86.376MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7bidw_i.smt2                 |    1.608s | 25.264MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7bidw.smt2                   |    1.628s | 25.252MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l20.smt2    |    1.656s | 74.604MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f9.smt2                       |    1.676s | 25.392MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c7nidw_i.smt2                 |    1.718s | 25.376MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l30.smt2    |    1.719s | 96.132MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l34.smt2    |    1.727s | 96.904MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8bidw.smt2                   |    1.765s | 26.484MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c6bidw_i.smt2                 |    1.797s | 24.352MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l19.smt2    |    1.849s | 90.972MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l33.smt2    |    1.879s | 96.412MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9idw_i.smt2                  |    1.947s | 26.12MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l15.smt2    |    1.952s | 90.916MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l63.smt2    |    1.979s | 97.484MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8idw.smt2                    |    2.004s | 25.384MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l64.smt2    |    2.010s | 100.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8bidw_i.smt2                 |    2.071s | 26.092MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9nidw_i.smt2                 |    2.210s | 27.516MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid2/ooo.tag19.smt2               |    2.249s | 35.692MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l45.smt2    |    2.287s | 105.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l51.smt2    |    2.296s | 105.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l56.smt2    |    2.320s | 109.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8idw_i.smt2                  |    2.351s | 25.304MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/g10nidw.smt2                  |    2.372s | 28.336MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l42.smt2    |    2.373s | 114.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8nidw.smt2                   |    2.442s | 28.02MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l40.smt2    |    2.519s | 107.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c8nidw_i.smt2                 |    2.538s | 26.704MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l37.smt2    |    2.780s | 108.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l41.smt2    |    2.864s | 109.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9idw.smt2                    |    2.876s | 26.392MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l80.smt2    |    2.950s | 123.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l77.smt2    |    3.004s | 122.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l67.smt2    |    3.053s | 122.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10nid_i.smt2                 |    3.057s | 29.052MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10ni_i.smt2                  |    3.099s | 27.912MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9bidw.smt2                   |    3.107s | 27.94MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l36.smt2    |    3.128s | 129.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f9n.smt2                      |    3.142s | 27.804MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f9b.smt2                      |    3.184s | 27.88MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10bidw.smt2                  |    3.186s | 28.82MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f8nidw.smt2                   |    3.324s | 31.3MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f8idw.smt2                    |    3.379s | 29.404MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10bid_i.smt2                 |    3.409s | 28.784MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9bidw_i.smt2                 |    3.439s | 27.788MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l86.smt2    |    3.441s | 132.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10id.smt2                    |    3.458s | 27.468MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l88.smt2    |    3.464s | 131.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l60.smt2    |    3.495s | 133.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l84.smt2    |    3.571s | 173.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l78.smt2    |    3.628s | 178.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l74.smt2    |    3.657s | 156.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/q2.12.smt2                    |    3.669s | 23.188MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c9nidw.smt2                   |    3.678s | 30.196MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10bid.smt2                   |    3.716s | 28.804MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l81.smt2    |    3.816s | 136.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l69.smt2    |    3.821s | 172.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/elf.rf10.smt2                 |    3.932s | 27.632MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10nidw.smt2                  |    4.016s | 30.656MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l95.smt2    |    4.034s | 180.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l70.smt2    |    4.106s | 171.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10bidw_i.smt2                |    4.130s | 28.896MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l92.smt2    |    4.158s | 198.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f8bidw.smt2                   |    4.220s | 31.62MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l61.smt2    |    4.223s | 183.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/ooo.rf10.smt2                 |    4.257s | 25.016MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l85.smt2    |    4.294s | 174.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f10i.smt2                     |    4.307s | 28.656MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l89.smt2    |    4.311s | 196.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l99.smt2    |    4.326s | 192.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l72.smt2    |    4.367s | 206.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l43.smt2    |    4.415s | 205.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10ni.smt2                    |    4.428s | 30.16MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10idw_i.smt2                 |    4.489s | 27.804MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l90.smt2    |    4.505s | 178.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l83.smt2    |    4.508s | 178.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10nid.smt2                   |    4.508s | 31.092MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10bi_i.smt2                  |    4.564s | 28.568MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l55.smt2    |    4.616s | 195.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/cache.inv14.smt2              |    4.680s | 25.988MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l57.smt2    |    4.783s | 206.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l66.smt2    |    4.799s | 169.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10bi.smt2                    |    4.843s | 28.732MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10nidw_i.smt2                |    4.968s | 29.508MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10i.smt2                     |    5.059s | 27.1MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f10.smt2                      |    5.513s | 28.26MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10i_i.smt2                   |    5.567s | 27.008MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f9bidw.smt2                   |    5.658s | 35.26MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f10n.smt2                     |    5.684s | 31.332MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10id_i.smt2                  |    5.967s | 27.648MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/c10idw.smt2                   |    5.982s | 27.776MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l47.smt2    |    6.241s | 256.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l46.smt2    |    6.563s | 42.424MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f10ni.smt2                    |    6.796s | 32.144MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/q2.14.smt2                    |    7.383s | 24.34MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l07.smt2    |    7.463s | 55.78MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f10bi.smt2                    |    7.500s | 32.176MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l96.smt2    |    8.433s | 414.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l79.smt2    |    8.540s | 359.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f10b.smt2                     |    8.567s | 30.732MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l28.smt2    |    9.390s | 35.116MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l65.smt2    |    9.411s | 425.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l53.smt2    |    9.531s | 425.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid2/cache.inv15.smt2             |    9.813s | 27.528MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f9idw.smt2                    |   10.254s | 33.504MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l93.smt2    |   10.377s | 493.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f9nidw.smt2                   |   11.549s | 36.064MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f10id.smt2                    |   11.700s | 34.036MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l87.smt2    |   13.193s | 667.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l98.smt2    |   14.735s | 738.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f10bid.smt2                   |   14.891s | 37.52MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f10nid.smt2                   |   17.405s | 38.332MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f10bidw.smt2                  |   17.693s | 40.8MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f10idw.smt2                   |   18.384s | 37.536MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid2/cache.inv16.smt2             |   19.416s | 29.344MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/uclid2/ooo.rf11.smt2                |   19.724s | 28.328MiB| unsat | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f44.smt2    |   20.013s | 33.188MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/q2.18.smt2                    |   20.014s | 29.428MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f45.smt2    |   20.014s | 33.424MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f79.smt2    |   20.014s | 33.44MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f35.smt2    |   20.015s | 32.084MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f93.smt2    |   20.016s | 58.716MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f34.smt2    |   20.017s | 31.736MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f56.smt2    |   20.017s | 57.324MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l13.smt2    |   20.018s | 64.968MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f83.smt2    |   20.018s | 84.372MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f03.smt2    |   20.018s | 35.328MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f16.smt2    |   20.020s | 34.244MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f82.smt2    |   20.021s | 84.08MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f63.smt2    |   20.021s | 33.656MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f47.smt2    |   20.025s | 39.94MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f94.smt2    |   20.027s | 56.72MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f21.smt2    |   20.028s | 35.924MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f86.smt2    |   20.030s | 187.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f52.smt2    |   20.033s | 34.52MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/uclid2/cache.inv18.smt2             |   20.033s | 32.368MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f20.smt2    |   20.036s | 37.108MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f80.smt2    |   20.037s | 39.176MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f78.smt2    |   20.039s | 39.248MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f87.smt2    |   20.042s | 89.552MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/uclid2/ooo.rf12.smt2                |   20.042s | 29.992MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/q2.20.smt2                    |   20.043s | 31.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f54.smt2    |   20.044s | 34.816MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f51.smt2    |   20.045s | 35.476MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f38.smt2    |   20.045s | 53.684MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f33.smt2    |   20.051s | 34.604MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/pete2/f10nidw.smt2                  |   20.051s | 40.964MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f68.smt2    |   20.052s | 39.424MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f53.smt2    |   20.053s | 32.736MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f88.smt2    |   20.053s | 34.58MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f02.smt2    |   20.053s | 43.048MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f39.smt2    |   20.053s | 35.668MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/uclid2/ooo.rf13.smt2                |   20.053s | 31.872MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/q2.30.smt2                    |   20.054s | 35.616MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f31.smt2    |   20.055s | 36.352MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f99.smt2    |   20.056s | 53.412MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f81.smt2    |   20.056s | 33.812MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f50.smt2    |   20.056s | 34.664MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f42.smt2    |   20.057s | 34.796MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l58.smt2    |   20.057s | 54.896MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f65.smt2    |   20.058s | 42.212MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/uclid2/cache.inv17.smt2             |   20.058s | 30.892MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f08.smt2    |   20.059s | 36.216MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f25.smt2    |   20.059s | 34.484MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f61.smt2    |   20.060s | 34.108MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f77.smt2    |   20.061s | 39.796MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/uclid/q2.40.smt2                    |   20.062s | 42.624MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f22.smt2    |   20.062s | 33.024MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l49.smt2    |   20.062s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l62.smt2    |   20.063s | 80.696MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f69.smt2    |   20.065s | 37.58MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f27.smt2    |   20.065s | 36.76MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l24.smt2    |   20.065s | 54.7MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f71.smt2    |   20.067s | 41.676MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f28.smt2    |   20.067s | 36.96MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f17.smt2    |   20.068s | 52.836MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l71.smt2    |   20.069s | 75.312MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f29.smt2    |   20.069s | 38.572MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f40.smt2    |   20.069s | 36.512MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l73.smt2    |   20.069s | 68.18MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f01.smt2    |   20.070s | 37.076MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l16.smt2    |   20.070s | 76.884MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f90.smt2    |   20.071s | 36.5MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f18.smt2    |   20.075s | 33.384MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f76.smt2    |   20.077s | 32.332MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f62.smt2    |   20.081s | 40.116MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f37.smt2    |   20.082s | 33.024MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f12.smt2    |   20.083s | 34.188MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/uclid2/elf.rf12.smt2                |   20.083s | 39.492MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f19.smt2    |   20.086s | 36.32MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f43.smt2    |   20.087s | 33.128MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f15.smt2    |   20.087s | 32.104MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f74.smt2    |   20.089s | 40.428MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f46.smt2    |   20.089s | 33.608MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f09.smt2    |   20.089s | 36.728MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f64.smt2    |   20.090s | 36.624MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f07.smt2    |   20.090s | 31.612MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l39.smt2    |   20.090s | 66.48MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f91.smt2    |   20.092s | 36.168MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f13.smt2    |   20.092s | 35.356MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f95.smt2    |   20.092s | 65.448MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f14.smt2    |   20.095s | 35.796MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f06.smt2    |   20.096s | 35.12MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f41.smt2    |   20.096s | 39.292MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f04.smt2    |   20.097s | 35.412MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l31.smt2    |   20.098s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f85.smt2    |   20.098s | 60.996MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f57.smt2    |   20.098s | 34.6MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f23.smt2    |   20.098s | 36.588MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f59.smt2    |   20.098s | 34.616MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f10.smt2    |   20.099s | 35.816MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f96.smt2    |   20.099s | 61.668MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l14.smt2    |   20.099s | 70.156MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f98.smt2    |   20.100s | 52.4MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f67.smt2    |   20.100s | 31.944MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f55.smt2    |   20.100s | 35.168MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l23.smt2    |   20.100s | 72.772MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f75.smt2    |   20.101s | 34.656MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f30.smt2    |   20.101s | 38.58MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f60.smt2    |   20.101s | 38.66MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f36.smt2    |   20.101s | 38.388MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l26.smt2    |   20.102s | 67.776MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f84.smt2    |   20.102s | 35.932MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l68.smt2    |   20.103s | 70.34MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f24.smt2    |   20.104s | 35.444MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l48.smt2    |   20.104s | 79.612MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f97.smt2    |   20.107s | 89.264MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l52.smt2    |   20.117s | 66.84MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f05.smt2    |   20.118s | 36.984MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f92.smt2    |   20.120s | 61.816MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f11.smt2    |   20.121s | 38.608MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f66.smt2    |   20.126s | 34.424MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f49.smt2    |   20.129s | 33.6MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f72.smt2    |   20.130s | 34.66MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f58.smt2    |   20.133s | 33.744MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f70.smt2    |   20.134s | 35.28MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f32.smt2    |   20.137s | 52.164MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f48.smt2    |   20.138s | 33.5MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f73.smt2    |   20.139s | 39.116MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f00.smt2    |   20.139s | 35.856MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f89.smt2    |   20.139s | 33.084MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_f26.smt2    |   20.140s | 39.924MiB| timeout | 0 |  |  |
|non-incremental/QF_UFIDL/20210312-Bouvier/vlsat3_l82.smt2    |   20.154s | 248.0MiB| timeout | 0 |  |  |
