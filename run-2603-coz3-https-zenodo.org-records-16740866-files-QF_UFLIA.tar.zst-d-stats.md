# .

* SAT 427
* UNSAT 187
* TIMEOUT 45
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFLIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFLIA.tar.zst-d
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFLIA.tar.zst?download=1
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
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_15.smt2    |    0.022s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_14.smt2    |    0.022s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_13.smt2    |    0.022s | 19.808MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_06.smt2    |    0.023s | 19.64MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_15.smt2    |    0.023s | 19.652MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_07.smt2    |    0.023s | 20.368MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_08.smt2    |    0.023s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.666105.smt2       |    0.024s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_16.smt2    |    0.024s | 19.74MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.675482.smt2       |    0.025s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-05-12-1-4-2-1.smt2  |    0.026s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-05-08-4-2-5-4.smt2  |    0.026s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_5_5.smt2                   |    0.028s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_12.smt2    |    0.028s | 21.124MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_15.smt2    |    0.028s | 19.568MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.621344.smt2       |    0.029s | 19.996MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.686091.smt2       |    0.029s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_15.smt2    |    0.029s | 21.236MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-07-13-5-3-2-1.smt2  |    0.030s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard4.smt2 |    0.030s | 20.376MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.602033.smt2       |    0.031s | 19.5MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium9.smt2 |    0.031s | 20.404MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_13_13.smt2                 |    0.032s | 20.616MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.639533.smt2       |    0.032s | 19.852MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_09.smt2    |    0.032s | 21.456MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_18.smt2    |    0.032s | 19.98MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-06-12-5-4-2-5.smt2  |    0.032s | 20.46MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-09-4-2-3-5.smt2  |    0.032s | 21.068MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium6.smt2 |    0.032s | 20.208MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_05.smt2    |    0.033s | 20.6MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_10.smt2    |    0.033s | 21.572MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-12-3-4-4-3.smt2  |    0.033s | 20.996MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_08.smt2    |    0.034s | 21.556MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-08-20-3-2-4-5.smt2  |    0.034s | 20.852MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-20-5-1-5-4.smt2  |    0.034s | 21.044MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_17.smt2    |    0.035s | 21.768MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_04.smt2    |    0.035s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_03.smt2    |    0.036s | 20.876MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-06-10-1-4-2-5.smt2  |    0.036s | 19.96MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_13.smt2    |    0.037s | 20.404MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-07-15-4-4-1-5.smt2  |    0.037s | 20.596MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-13-5-4-1-2.smt2  |    0.037s | 20.908MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-09-05-2-4-4-5.smt2  |    0.037s | 20.544MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium18.smt2 |    0.037s | 20.824MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_14.smt2    |    0.038s | 21.432MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-07-19-5-3-2-5.smt2  |    0.038s | 20.468MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-13-10-4-3-1-3.smt2  |    0.038s | 20.788MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium13.smt2 |    0.038s | 20.612MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_10_10.smt2                 |    0.039s | 20.92MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_10.smt2    |    0.039s | 20.572MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_20.smt2    |    0.039s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-10-4-5-2-3.smt2  |    0.039s | 21.084MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-06-14-3-1-5-2.smt2  |    0.039s | 20.196MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_27_37.smt2                 |    0.040s | 21.632MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_32_52.smt2                 |    0.040s | 21.888MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.602046.smt2       |    0.040s | 19.936MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_10.smt2    |    0.040s | 21.732MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-11-15-4-4-5-5.smt2  |    0.040s | 20.636MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_38_48.smt2                 |    0.041s | 22.336MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_7_17.smt2                  |    0.041s | 20.18MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_08.smt2    |    0.041s | 20.692MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-08-14-2-3-3-5.smt2  |    0.041s | 20.564MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_30_40.smt2                 |    0.042s | 21.864MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_29_29.smt2                 |    0.042s | 21.668MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-06-2-3-1-3.smt2  |    0.042s | 21.212MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-09-12-5-2-1-5.smt2  |    0.042s | 20.644MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-05-5-5-1-3.smt2  |    0.044s | 21.004MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard7.smt2 |    0.044s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.606727.smt2       |    0.045s | 20.016MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_10.smt2    |    0.046s | 21.468MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-17-5-4-5-4.smt2  |    0.047s | 21.1MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_13.smt2    |    0.048s | 21.552MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_05.smt2    |    0.049s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_18.smt2    |    0.049s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_18.smt2    |    0.051s | 21.38MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_14.smt2    |    0.052s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_18.smt2    |    0.052s | 20.38MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_13.smt2    |    0.053s | 20.432MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_04.smt2    |    0.053s | 20.608MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_37_37.smt2                 |    0.054s | 22.824MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.604654.smt2       |    0.054s | 20.076MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_17.smt2    |    0.054s | 20.616MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.675513.smt2       |    0.055s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_17.smt2    |    0.055s | 19.648MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_5_10.smt2                  |    0.056s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_14.smt2    |    0.056s | 20.876MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_17.smt2    |    0.056s | 19.548MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_03.smt2    |    0.056s | 19.632MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_10.smt2    |    0.056s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_03.smt2    |    0.056s | 20.368MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.675451.smt2       |    0.057s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_08.smt2    |    0.057s | 20.22MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_06.smt2    |    0.057s | 19.588MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_16.smt2    |    0.057s | 19.632MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_20.smt2    |    0.057s | 20.848MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_7_12.smt2                  |    0.058s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_03.smt2    |    0.058s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_11.smt2    |    0.058s | 20.348MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_06.smt2    |    0.058s | 20.152MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_14.smt2    |    0.058s | 20.612MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_19.smt2    |    0.058s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-15-13-4-5-2-4.smt2  |    0.058s | 21.048MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_14_19.smt2                 |    0.059s | 20.916MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_6_16.smt2                  |    0.059s | 20.416MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_12.smt2    |    0.059s | 20.48MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_12.smt2    |    0.059s | 20.148MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_13.smt2    |    0.059s | 21.756MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_09.smt2    |    0.059s | 20.376MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_14.smt2    |    0.059s | 20.256MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-12-08-5-2-5-3.smt2  |    0.059s | 20.868MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-12-11-1-4-4-3.smt2  |    0.059s | 20.62MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_04.smt2    |    0.060s | 20.564MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_03.smt2    |    0.060s | 20.38MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_04.smt2    |    0.060s | 19.448MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_16.smt2    |    0.060s | 20.388MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_06.smt2    |    0.060s | 20.412MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_09.smt2    |    0.060s | 20.44MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_20.smt2    |    0.060s | 19.636MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_20.smt2    |    0.060s | 20.304MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-10-14-2-1-4-4.smt2  |    0.060s | 21.012MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-06-13-5-3-5-5.smt2  |    0.060s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-05-19-1-4-2-1.smt2  |    0.060s | 20.176MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-14-15-1-1-3-3.smt2  |    0.060s | 20.86MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.686056.smt2       |    0.061s | 19.636MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_10.smt2    |    0.061s | 19.66MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_20.smt2    |    0.061s | 20.92MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_04.smt2    |    0.061s | 20.616MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_03.smt2    |    0.061s | 20.288MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_12.smt2    |    0.061s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_05.smt2    |    0.061s | 19.636MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_06.smt2    |    0.062s | 20.684MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_05.smt2    |    0.062s | 20.34MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_17.smt2    |    0.062s | 21.048MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_16.smt2    |    0.062s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-09-10-5-1-5-2.smt2  |    0.062s | 21.12MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-08-10-5-2-5-3.smt2  |    0.062s | 20.712MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-11-4-4-1-3.smt2  |    0.062s | 21.136MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-09-1-5-4-4.smt2  |    0.062s | 21.136MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-07-1-2-1-1.smt2  |    0.062s | 20.908MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.688318.smt2       |    0.063s | 19.836MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.666132.smt2       |    0.063s | 20.084MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_15.smt2    |    0.063s | 20.416MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_11.smt2    |    0.063s | 20.872MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_04.smt2    |    0.063s | 20.9MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_12.smt2    |    0.063s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_12.smt2    |    0.063s | 21.32MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-13-06-1-1-2-4.smt2  |    0.063s | 20.8MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-15-2-2-2-4.smt2  |    0.063s | 20.86MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-06-07-4-5-4-2.smt2  |    0.063s | 20.28MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-15-10-1-3-5-1.smt2  |    0.063s | 21.36MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-13-4-4-2-1.smt2  |    0.063s | 20.956MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_07.smt2    |    0.064s | 20.764MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_10.smt2    |    0.064s | 20.732MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_03.smt2    |    0.064s | 20.412MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_03.smt2    |    0.064s | 20.888MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_11.smt2    |    0.064s | 19.684MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_17.smt2    |    0.064s | 20.808MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_10.smt2    |    0.064s | 20.36MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_05.smt2    |    0.064s | 20.372MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_19.smt2    |    0.064s | 20.664MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_05.smt2    |    0.064s | 19.736MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-10-09-1-4-4-1.smt2  |    0.064s | 20.62MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-13-11-5-3-5-3.smt2  |    0.064s | 21.024MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-17-4-5-2-4.smt2  |    0.064s | 21.068MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-15-07-3-1-5-5.smt2  |    0.064s | 21.336MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-16-4-4-1-4.smt2  |    0.064s | 20.968MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-12-09-5-5-2-4.smt2  |    0.064s | 20.72MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-15-12-2-2-3-4.smt2  |    0.064s | 20.888MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-07-5-1-2-1.smt2  |    0.064s | 21.016MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_04.smt2    |    0.065s | 20.408MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_07.smt2    |    0.065s | 20.28MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_11.smt2    |    0.065s | 20.52MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_15.smt2    |    0.065s | 20.32MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_11.smt2    |    0.065s | 21.216MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_07.smt2    |    0.065s | 20.5MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_05.smt2    |    0.065s | 20.272MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-08-5-3-2-5.smt2  |    0.065s | 21.156MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_08.smt2    |    0.066s | 20.772MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_16.smt2    |    0.066s | 21.988MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-10-3-5-2-5.smt2  |    0.066s | 21.148MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-14-13-4-2-1-3.smt2  |    0.066s | 21.144MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-15-2-3-4-4.smt2  |    0.066s | 21.18MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-06-20-5-1-5-1.smt2  |    0.066s | 20.296MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_11.smt2    |    0.067s | 21.884MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_16.smt2    |    0.067s | 20.404MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_11.smt2    |    0.067s | 20.656MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_09.smt2    |    0.067s | 19.532MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-12-20-1-1-5-2.smt2  |    0.067s | 20.776MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-09-20-5-5-1-5.smt2  |    0.067s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_19.smt2    |    0.068s | 22.032MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-08-17-4-1-2-2.smt2  |    0.068s | 20.856MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_26_26.smt2                 |    0.069s | 21.66MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_14.smt2    |    0.069s | 21.112MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_13.smt2    |    0.069s | 20.912MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_06.smt2    |    0.069s | 20.904MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_07.smt2    |    0.069s | 21.324MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-15-2-2-4-2.smt2  |    0.069s | 21.16MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-09-06-1-5-3-2.smt2  |    0.069s | 20.576MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-13-15-5-3-4-1.smt2  |    0.069s | 21.02MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_5_15.smt2                  |    0.070s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_15_15.smt2                 |    0.070s | 21.188MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_31_51.smt2                 |    0.070s | 21.66MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_20.smt2    |    0.070s | 21.156MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_19.smt2    |    0.070s | 20.872MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_08.smt2    |    0.070s | 20.348MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_14.smt2    |    0.070s | 19.656MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_11.smt2    |    0.070s | 21.4MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-11-5-1-3-4.smt2  |    0.070s | 21.192MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_22_22.smt2                 |    0.071s | 21.388MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_12.smt2    |    0.071s | 22.116MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_09.smt2    |    0.071s | 20.796MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_11.smt2    |    0.071s | 19.66MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_16.smt2    |    0.071s | 21.436MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_11.smt2    |    0.071s | 19.636MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_10_15.smt2                 |    0.072s | 20.704MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_26_36.smt2                 |    0.072s | 21.388MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.606691.smt2       |    0.072s | 19.76MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_18.smt2    |    0.072s | 21.98MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_18.smt2    |    0.072s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_07.smt2    |    0.072s | 20.436MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_19.smt2    |    0.072s | 21.576MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-13-17-4-2-1-5.smt2  |    0.072s | 20.884MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_32_32.smt2                 |    0.073s | 21.668MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_24_34.smt2                 |    0.073s | 21.612MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_15.smt2    |    0.073s | 22.032MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_09.smt2    |    0.073s | 20.56MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_06.smt2    |    0.073s | 20.212MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_12.smt2    |    0.073s | 21.08MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-09-17-2-1-4-1.smt2  |    0.073s | 20.724MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-05-14-4-3-1-1.smt2  |    0.073s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_9_14.smt2                  |    0.074s | 20.68MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_12.smt2    |    0.074s | 21.548MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_19.smt2    |    0.074s | 20.592MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_09.smt2    |    0.074s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_12.smt2    |    0.074s | 19.508MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_15.smt2    |    0.074s | 20.72MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_03.smt2    |    0.075s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_09.smt2    |    0.075s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_08.smt2    |    0.075s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_04.smt2    |    0.075s | 20.84MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-17-5-5-3-5.smt2  |    0.075s | 21.144MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_14_14.smt2                 |    0.076s | 21.14MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_05.smt2    |    0.076s | 20.404MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_03.smt2    |    0.076s | 20.108MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_20.smt2    |    0.076s | 22.452MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_20.smt2    |    0.076s | 19.628MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_08.smt2    |    0.076s | 21.24MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-13-12-5-3-4-4.smt2  |    0.076s | 20.808MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-09-18-1-3-4-5.smt2  |    0.076s | 20.656MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_19.smt2    |    0.077s | 19.704MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_20.smt2    |    0.077s | 21.64MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_16.smt2    |    0.077s | 22.564MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_8_18.smt2                  |    0.078s | 20.896MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_08.smt2    |    0.078s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-10-07-4-1-1-5.smt2  |    0.078s | 20.76MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-06-09-3-5-5-3.smt2  |    0.078s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_19_19.smt2                 |    0.079s | 21.1MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.666078.smt2       |    0.079s | 20.2MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-10-12-4-1-1-4.smt2  |    0.079s | 20.696MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_19.smt2    |    0.080s | 22.852MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_14.smt2    |    0.080s | 20.8MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_17.smt2    |    0.080s | 22.032MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_05.smt2    |    0.080s | 20.932MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_28_28.smt2                 |    0.081s | 21.372MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_40_40.smt2                 |    0.081s | 22.684MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_30_30.smt2                 |    0.081s | 21.624MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_06.smt2    |    0.081s | 20.544MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_17.smt2    |    0.081s | 22.792MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_05.smt2    |    0.081s | 20.496MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_13.smt2    |    0.081s | 20.848MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-11-07-3-4-2-3.smt2  |    0.081s | 20.78MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-11-14-5-3-1-2.smt2  |    0.081s | 20.876MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard10.smt2 |    0.081s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_09.smt2    |    0.082s | 20.304MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_12.smt2    |    0.082s | 20.628MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_09.smt2    |    0.082s | 21.784MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_07.smt2    |    0.082s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-07-18-1-1-4-1.smt2  |    0.082s | 20.484MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_12_12.smt2                 |    0.083s | 20.708MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_07.smt2    |    0.083s | 21.036MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_20.smt2    |    0.083s | 23.056MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-09-11-2-4-1-5.smt2  |    0.083s | 20.644MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_14.smt2    |    0.084s | 21.848MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_18.smt2    |    0.084s | 22.7MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_35_45.smt2                 |    0.085s | 21.884MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_08.smt2    |    0.085s | 20.996MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_14.smt2    |    0.085s | 22.312MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_18.smt2    |    0.085s | 20.704MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_13.smt2    |    0.085s | 21.244MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-13-09-3-2-3-2.smt2  |    0.085s | 20.888MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-14-2-4-1-4.smt2  |    0.085s | 20.944MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-13-08-3-2-1-3.smt2  |    0.085s | 20.664MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_05_17.smt2    |    0.086s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_07.smt2    |    0.086s | 21.008MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_7_7.smt2                   |    0.087s | 20.812MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_35_35.smt2                 |    0.087s | 21.964MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_16_16.smt2                 |    0.087s | 21.136MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_39_39.smt2                 |    0.087s | 22.74MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_10.smt2    |    0.087s | 20.792MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_15.smt2    |    0.087s | 21.608MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-09-4-3-5-5.smt2  |    0.087s | 20.92MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-13-2-1-3-1.smt2  |    0.087s | 21.028MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_13.smt2    |    0.088s | 19.468MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-14-11-4-2-2-1.smt2  |    0.088s | 20.824MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_10_20.smt2                 |    0.089s | 21.148MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_19_29.smt2                 |    0.089s | 21.516MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_13.smt2    |    0.089s | 19.568MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-11-12-5-4-4-2.smt2  |    0.089s | 20.588MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-12-05-3-3-5-4.smt2  |    0.089s | 20.648MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_04.smt2    |    0.090s | 20.756MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-11-17-5-2-4-4.smt2  |    0.090s | 20.972MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_06.smt2    |    0.091s | 20.464MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-11-2-1-5-2.smt2  |    0.091s | 20.96MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-14-06-4-4-1-2.smt2  |    0.091s | 20.82MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-10-05-5-2-1-5.smt2  |    0.091s | 20.656MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium16.smt2 |    0.091s | 20.696MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.598294.smt2       |    0.092s | 20.012MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_13.smt2    |    0.092s | 22.02MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_10.smt2    |    0.092s | 19.648MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_6_6.smt2                   |    0.093s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_31_31.smt2                 |    0.094s | 21.796MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_15.smt2    |    0.094s | 21.468MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-14-07-1-4-1-3.smt2  |    0.096s | 20.824MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard6.smt2 |    0.096s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_16.smt2    |    0.097s | 21.516MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_09.smt2    |    0.097s | 21.128MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_05.smt2    |    0.097s | 20.968MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-15-14-5-5-5-1.smt2  |    0.097s | 21.28MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-14-2-4-3-1.smt2  |    0.097s | 20.88MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-16-4-4-1-4.smt2  |    0.097s | 21.384MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_06.smt2    |    0.098s | 19.608MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_07.smt2    |    0.099s | 19.916MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_18.smt2    |    0.099s | 20.464MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-12-14-3-5-4-4.smt2  |    0.099s | 20.732MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-10-19-3-4-2-4.smt2  |    0.099s | 20.8MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_03_04.smt2    |    0.100s | 19.624MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-12-06-3-4-5-1.smt2  |    0.100s | 20.668MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_6_QF_UFLIA.smt2 |    0.101s | 22.164MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_07_17.smt2    |    0.102s | 21.304MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_04.smt2    |    0.102s | 20.152MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_17.smt2    |    0.102s | 20.248MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-06-4-1-3-5.smt2  |    0.102s | 21.016MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_37_57.smt2                 |    0.103s | 22.152MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_05_16.smt2    |    0.103s | 20.652MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_07.smt2    |    0.103s | 19.652MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_11.smt2    |    0.103s | 20.412MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-08-19-2-2-3-1.smt2  |    0.103s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-06-19-3-3-4-4.smt2  |    0.103s | 20.612MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_6_11.smt2                  |    0.104s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_08.smt2    |    0.104s | 20.42MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_uns_04_19.smt2    |    0.104s | 19.62MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-09-16-3-4-1-5.smt2  |    0.104s | 20.696MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-05-09-5-1-2-5.smt2  |    0.105s | 19.944MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_11_11.smt2                 |    0.107s | 20.836MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_03_10.smt2    |    0.107s | 20.376MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_06.smt2    |    0.107s | 21.208MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_04_03.smt2    |    0.107s | 20.16MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-05-16-1-5-4-3.smt2  |    0.107s | 20.42MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-05-13-2-4-5-3.smt2  |    0.107s | 20.284MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_32_42.smt2                 |    0.108s | 21.712MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_16.smt2    |    0.108s | 21.044MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-05-2-5-4-2.smt2  |    0.108s | 20.892MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-05-11-2-5-3-2.smt2  |    0.108s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-10-4-3-1-3.smt2  |    0.108s | 20.768MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_17_17.smt2                 |    0.109s | 21.376MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_08_20.smt2    |    0.109s | 21.956MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_9_9.smt2                   |    0.110s | 20.5MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.602059.smt2       |    0.110s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_19.smt2    |    0.110s | 21.144MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-15-09-3-5-5-3.smt2  |    0.110s | 20.78MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-19-3-4-4-1.smt2  |    0.110s | 21.036MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-09-4-2-1-5.smt2  |    0.110s | 20.788MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium15.smt2 |    0.110s | 20.736MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.686126.smt2       |    0.111s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-08-16-4-4-5-1.smt2  |    0.111s | 20.512MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-15-16-2-4-2-5.smt2  |    0.111s | 20.816MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-14-12-4-4-1-3.smt2  |    0.111s | 20.916MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_20_20.smt2                 |    0.112s | 21.184MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_8_8.smt2                   |    0.112s | 20.62MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_8_13.smt2                  |    0.112s | 20.684MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-06-4-3-2-1.smt2  |    0.112s | 21.136MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard18.smt2 |    0.112s | 21.148MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium5.smt2 |    0.112s | 20.204MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-11-06-4-4-5-5.smt2  |    0.113s | 20.752MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_06_18.smt2    |    0.114s | 21.268MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-11-10-2-5-3-2.smt2  |    0.114s | 20.776MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-18-2-2-2-5.smt2  |    0.114s | 21.228MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-12-07-3-4-1-2.smt2  |    0.114s | 20.668MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-06-4-2-1-1.smt2  |    0.114s | 20.848MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-08-07-3-2-3-1.smt2  |    0.115s | 20.412MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard11.smt2 |    0.115s | 20.696MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_14_24.smt2                 |    0.116s | 20.888MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_33_43.smt2                 |    0.116s | 21.916MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_12_17.smt2                 |    0.116s | 21.392MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_23_23.smt2                 |    0.116s | 21.132MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-18-4-2-3-1.smt2  |    0.116s | 21.132MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-14-16-4-1-1-5.smt2  |    0.116s | 21.068MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-07-09-3-4-4-3.smt2  |    0.116s | 20.292MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-07-05-5-2-3-5.smt2  |    0.117s | 20.184MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium11.smt2 |    0.117s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_35_55.smt2                 |    0.118s | 22.104MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_27_27.smt2                 |    0.118s | 21.372MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_15_20.smt2                 |    0.118s | 21.176MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_19.smt2    |    0.118s | 22.284MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-13-2-5-2-3.smt2  |    0.118s | 21.14MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-09-07-1-3-3-2.smt2  |    0.119s | 20.584MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-05-06-2-2-5-1.smt2  |    0.119s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium10.smt2 |    0.119s | 20.468MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium8.smt2 |    0.119s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_22_32.smt2                 |    0.120s | 21.8MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-05-17-1-5-1-5.smt2  |    0.120s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_39_49.smt2                 |    0.121s | 22.38MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-05-5-4-4-2.smt2  |    0.121s | 21.136MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-10-08-2-2-4-5.smt2  |    0.121s | 20.728MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-13-05-5-4-1-5.smt2  |    0.121s | 20.672MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_9_19.smt2                  |    0.122s | 20.688MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-07-3-4-4-3.smt2  |    0.122s | 21.02MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-10-11-1-3-5-5.smt2  |    0.122s | 20.804MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-15-17-2-1-1-4.smt2  |    0.122s | 21.272MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-15-18-4-1-3-5.smt2  |    0.122s | 21.324MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_10_15.smt2    |    0.123s | 22.468MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Hash/hash_sat_09_18.smt2    |    0.123s | 22.152MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-06-17-2-2-4-1.smt2  |    0.123s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-12-16-5-2-2-3.smt2  |    0.123s | 20.732MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-05-07-4-5-1-2.smt2  |    0.123s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium17.smt2 |    0.123s | 20.856MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_11_21.smt2                 |    0.124s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_11_16.smt2                 |    0.124s | 20.852MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-07-08-4-4-4-2.smt2  |    0.124s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-13-4-1-4-5.smt2  |    0.125s | 20.94MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-12-13-3-4-2-3.smt2  |    0.125s | 20.78MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_13_18.smt2                 |    0.126s | 20.916MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-15-06-3-5-4-4.smt2  |    0.126s | 20.976MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.606709.smt2       |    0.127s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-16-2-2-1-4.smt2  |    0.127s | 21.06MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-09-08-1-1-5-3.smt2  |    0.127s | 20.668MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-15-4-1-3-1.smt2  |    0.127s | 20.844MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-15-19-3-1-4-1.smt2  |    0.128s | 20.884MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-06-15-4-1-4-1.smt2  |    0.128s | 20.26MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-10-17-5-2-2-5.smt2  |    0.128s | 21.016MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard14.smt2 |    0.128s | 21.116MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/TwoSquares/smtlib.769286.smt2       |    0.129s | 20.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-13-07-1-5-2-3.smt2  |    0.129s | 20.72MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-12-4-2-4-5.smt2  |    0.130s | 21.076MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-14-18-5-5-3-2.smt2  |    0.130s | 20.864MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-10-16-3-5-2-4.smt2  |    0.130s | 20.696MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-19-3-3-3-4.smt2  |    0.130s | 21.048MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-08-15-4-2-1-4.smt2  |    0.131s | 20.684MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-09-15-5-3-2-3.smt2  |    0.131s | 20.744MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-17-2-2-5-1.smt2  |    0.131s | 20.96MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_18_28.smt2                 |    0.132s | 21.492MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_40_60.smt2                 |    0.134s | 22.7MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-08-05-1-5-4-2.smt2  |    0.134s | 20.596MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-14-3-3-5-3.smt2  |    0.134s | 21.252MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-14-20-3-5-3-5.smt2  |    0.134s | 20.888MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-09-1-5-4-2.smt2  |    0.135s | 21.092MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-11-05-3-1-5-3.smt2  |    0.135s | 20.68MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-14-2-3-3-3.smt2  |    0.135s | 21.18MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-12-10-4-4-3-1.smt2  |    0.136s | 20.588MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-11-19-4-5-1-1.smt2  |    0.137s | 20.92MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-12-18-1-3-1-2.smt2  |    0.137s | 20.848MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-18-1-4-4-3.smt2  |    0.137s | 20.924MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard9.smt2 |    0.137s | 20.544MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium7.smt2 |    0.137s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_34_34.smt2                 |    0.138s | 22.372MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-07-20-2-5-1-4.smt2  |    0.138s | 20.608MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium12.smt2 |    0.138s | 20.604MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium14.smt2 |    0.138s | 20.704MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-12-3-4-4-1.smt2  |    0.139s | 20.884MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-06-18-1-2-1-5.smt2  |    0.139s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-07-16-2-4-3-5.smt2  |    0.139s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-13-14-4-5-4-2.smt2  |    0.139s | 20.86MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-18-3-4-5-4.smt2  |    0.140s | 21.188MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-15-05-2-1-2-3.smt2  |    0.140s | 20.756MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-11-3-3-4-5.smt2  |    0.140s | 20.92MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-11-08-3-4-3-5.smt2  |    0.140s | 20.652MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-07-14-1-1-1-1.smt2  |    0.141s | 20.428MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_12_22.smt2                 |    0.142s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-12-2-5-3-4.smt2  |    0.143s | 20.98MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-06-05-5-2-5-5.smt2  |    0.143s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-14-08-5-1-1-4.smt2  |    0.143s | 21.132MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/63058_aa742630eef64f949de269382c1f9035_25_UFLIA.smt2 |    0.143s | 24.556MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-05-20-5-1-4-2.smt2  |    0.144s | 20.448MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-11-13-4-4-5-2.smt2  |    0.145s | 20.7MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-07-4-2-4-4.smt2  |    0.145s | 20.928MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard5.smt2 |    0.145s | 20.604MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-10-13-5-5-4-5.smt2  |    0.146s | 20.768MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-15-08-4-5-4-1.smt2  |    0.147s | 21.18MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium20.smt2 |    0.147s | 20.972MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-05-5-3-1-1.smt2  |    0.148s | 21.188MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_20_30.smt2                 |    0.149s | 21.668MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard8.smt2 |    0.149s | 20.636MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/medium/medium19.smt2 |    0.149s | 21.168MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-09-13-2-3-1-3.smt2  |    0.150s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-12-19-1-4-1-2.smt2  |    0.150s | 21.184MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-05-18-1-3-1-3.smt2  |    0.151s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-12-3-1-5-2.smt2  |    0.151s | 21.172MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-06-08-5-1-5-3.smt2  |    0.151s | 20.416MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-14-09-3-3-4-4.smt2  |    0.151s | 20.876MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-15-11-5-2-2-2.smt2  |    0.152s | 21.004MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_25_35.smt2                 |    0.153s | 21.948MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-16-4-4-4-1.smt2  |    0.153s | 21.168MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-08-5-3-1-5.smt2  |    0.154s | 21.152MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-07-06-4-1-5-3.smt2  |    0.154s | 20.424MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_21_21.smt2                 |    0.155s | 21.628MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_18_18.smt2                 |    0.156s | 21.58MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-10-5-3-2-1.smt2  |    0.157s | 20.864MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-20-1-4-2-1.smt2  |    0.158s | 20.892MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-14-10-3-4-2-2.smt2  |    0.158s | 20.812MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-08-4-5-2-5.smt2  |    0.158s | 21.044MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-08-06-4-5-4-1.smt2  |    0.159s | 20.736MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-19-4-1-1-5.smt2  |    0.159s | 20.932MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-07-11-1-1-1-1.smt2  |    0.159s | 20.54MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-05-2-1-1-2.smt2  |    0.160s | 20.944MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-10-5-5-5-4.smt2  |    0.160s | 21.152MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-11-18-3-3-4-1.smt2  |    0.161s | 20.852MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-11-5-3-1-1.smt2  |    0.162s | 20.996MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-14-17-5-4-3-1.smt2  |    0.163s | 20.928MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-17-06-5-5-4-1.smt2  |    0.164s | 20.94MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-13-19-4-5-5-5.smt2  |    0.164s | 20.88MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-13-20-2-2-4-4.smt2  |    0.165s | 20.924MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-08-4-1-1-1.smt2  |    0.166s | 21.172MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-20-19-2-2-2-5.smt2  |    0.166s | 21.496MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-07-1-1-4-2.smt2  |    0.166s | 20.944MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-12-15-3-2-1-5.smt2  |    0.171s | 20.856MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard12.smt2 |    0.172s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard13.smt2 |    0.172s | 20.932MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_29_39.smt2                 |    0.175s | 22.58MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_17_27.smt2                 |    0.176s | 21.32MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard19.smt2 |    0.179s | 21.248MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-18-14-3-5-2-3.smt2  |    0.182s | 20.84MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_24_24.smt2                 |    0.184s | 21.972MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-08-12-3-1-3-4.smt2  |    0.186s | 20.488MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_28_38.smt2                 |    0.187s | 22.044MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-07-10-2-4-5-3.smt2  |    0.190s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-20-1-1-2-2.smt2  |    0.190s | 20.996MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_16_26.smt2                 |    0.191s | 21.388MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-13-16-3-1-4-1.smt2  |    0.192s | 21.152MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-08-1-4-4-5.smt2  |    0.192s | 20.976MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-08-11-4-3-2-2.smt2  |    0.193s | 20.616MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard20.smt2 |    0.193s | 21.344MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-16-20-5-1-4-4.smt2  |    0.194s | 20.892MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard15.smt2 |    0.194s | 20.904MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard16.smt2 |    0.195s | 21.016MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_21_31.smt2                 |    0.196s | 21.74MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-10-06-1-1-5-2.smt2  |    0.196s | 20.616MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-11-09-1-2-1-3.smt2  |    0.197s | 20.912MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-19-15-3-1-3-4.smt2  |    0.197s | 21.092MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-08-09-4-5-5-4.smt2  |    0.198s | 20.612MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-14-05-1-4-4-5.smt2  |    0.199s | 20.908MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/EufLaArithmetic/hard/hard17.smt2 |    0.199s | 21.152MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_7_QF_UFLIA.smt2 |    0.199s | 26.452MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_28_48.smt2                 |    0.203s | 22.196MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_23_33.smt2                 |    0.207s | 21.916MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_25_25.smt2                 |    0.210s | 21.996MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_34_QF_UFLIA.smt2 |    0.211s | 26.072MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-10-18-2-2-5-3.smt2  |    0.218s | 20.956MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_40_QF_UFLIA.smt2 |    0.234s | 25.104MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_13_23.smt2                 |    0.242s | 20.928MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_33_33.smt2                 |    0.247s | 22.876MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/mathsat/Wisa/xs-11-20-5-2-5-3.smt2  |    0.251s | 20.908MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_34_54.smt2                 |    0.279s | 23.04MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_38_58.smt2                 |    0.284s | 23.384MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_31_41.smt2                 |    0.285s | 22.908MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_37_47.smt2                 |    0.287s | 23.152MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_38_38.smt2                 |    0.310s | 23.228MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_8_QF_UFLIA.smt2 |    0.329s | 26.696MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_40_50.smt2                 |    0.383s | 23.74MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_36_46.smt2                 |    0.384s | 23.228MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_36_36.smt2                 |    0.388s | 23.656MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_15_25.smt2                 |    0.406s | 21.472MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_36_56.smt2                 |    0.408s | 23.248MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_16_36.smt2                 |    0.445s | 21.328MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_34_44.smt2                 |    0.452s | 23.436MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_33_53.smt2                 |    0.510s | 23.068MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_39_59.smt2                 |    0.522s | 23.744MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2 |    0.526s | 35.48MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_17_37.smt2                 |    0.540s | 21.64MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_29_49.smt2                 |    0.559s | 22.54MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_58_QF_UFLIA.smt2 |    0.586s | 31.14MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_27_47.smt2                 |    0.597s | 22.688MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_35_QF_UFLIA.smt2 |    0.603s | 37.068MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_30_50.smt2                 |    0.926s | 22.644MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_18_38.smt2                 |    1.325s | 21.92MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_19_39.smt2                 |    1.725s | 23.228MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2 |    1.729s | 43.076MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_26_46.smt2                 |    1.860s | 22.824MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_20_40.smt2                 |    2.451s | 24.492MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_60_QF_UFLIA.smt2 |    2.515s | 58.188MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_24_44.smt2                 |    2.824s | 22.904MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_21_41.smt2                 |    3.039s | 25.46MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_63_QF_UFLIA.smt2 |    3.197s | 35.46MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_41_QF_UFLIA.smt2 |    3.680s | 53.732MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2 |    5.002s | 86.288MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_70_QF_UFLIA.smt2 |    5.215s | 74.76MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_62_QF_UFLIA.smt2 |    6.107s | 44.576MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_22_42.smt2                 |    6.290s | 25.972MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_18_QF_UFLIA.smt2 |    6.374s | 92.024MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_14_QF_UFLIA.smt2 |    6.903s | 100.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_46_QF_UFLIA.smt2 |    7.672s | 76.752MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_17_QF_UFLIA.smt2 |    8.030s | 100.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_72_QF_UFLIA.smt2 |    9.887s | 541.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/72771_f9d228efc97cf1458e38_64_QF_UFLIA.smt2 |   10.612s | 45.748MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_23_43.smt2                 |   10.626s | 29.384MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFLIA.smt2 |   10.801s | 120.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_44_QF_UFLIA.smt2 |   11.784s | 105.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/63058_55d6bef5390186355f11_26_QF_UFLIA.smt2 |   12.496s | 185.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFLIA.smt2 |   14.719s | 224.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_45_QF_UFLIA.smt2 |   14.884s | 85.452MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_48_QF_UFLIA.smt2 |   15.172s | 49.904MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_23_QF_UFLIA.smt2 |   15.503s | 184.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_22_QF_UFLIA.smt2 |   16.076s | 177.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_59_QF_UFLIA.smt2 |   16.811s | 108.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFLIA.smt2 |   18.419s | 174.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFLIA.smt2 |   20.024s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_31_QF_UFLIA.smt2 |   20.026s | 150.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/93493_4ea6163ed03941199c785278ccc42812_49_QF_UFLIA.smt2 |   20.027s | 179.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_57_QF_UFLIA.smt2 |   20.032s | 32.94MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_1_UFLIA.smt2 |   20.033s | 235.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFLIA.smt2 |   20.039s | 232.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFLIA.smt2 |   20.040s | 98.416MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_56_QF_UFLIA.smt2 |   20.050s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2 |   20.051s | 293.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_55_QF_UFLIA.smt2 |   20.052s | 27.12MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/93493_798593962ee29ad45ac8_52_QF_UFLIA.smt2 |   20.055s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_28_QF_UFLIA.smt2 |   20.056s | 434.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFLIA.smt2 |   20.056s | 109.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_32_QF_UFLIA.smt2 |   20.059s | 282.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFLIA.smt2 |   20.060s | 149.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_38_QF_UFLIA.smt2 |   20.061s | 372.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_33_QF_UFLIA.smt2 |   20.061s | 304.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_39_QF_UFLIA.smt2 |   20.062s | 120.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2 |   20.062s | 92.56MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_30_QF_UFLIA.smt2 |   20.064s | 289.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_5_QF_UFLIA.smt2 |   20.067s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_4_UFLIA.smt2 |   20.070s | 588.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/93493_5990a6bf5f2740164f77_50_QF_UFLIA.smt2 |   20.070s | 196.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_3_UFLIA.smt2 |   20.072s | 373.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_24_QF_UFLIA.smt2 |   20.080s | 193.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2 |   20.083s | 602.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2 |   20.088s | 578.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_27_QF_UFLIA.smt2 |   20.088s | 445.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/wisas/xs_25_45.smt2                 |   20.090s | 34.064MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2 |   20.090s | 403.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_36_QF_UFLIA.smt2 |   20.091s | 340.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_2_UFLIA.smt2 |   20.091s | 176.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_47_QF_UFLIA.smt2 |   20.091s | 48.216MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_61_QF_UFLIA.smt2 |   20.096s | 69.368MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2 |   20.104s | 927.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2 |   20.108s | 538.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2 |   20.133s | 479.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2 |   20.136s | 474.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_71_QF_UFLIA.smt2 |   20.136s | 161.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_0_UFLIA.smt2 |   20.137s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2 |   20.147s | 577.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_15_QF_UFLIA.smt2 |   20.155s | 377.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2 |   20.159s | 1185.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2 |   20.182s | 591.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFLIA/20230314-Jaroslav-Bendik-Certora/38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2 |   20.209s | 1255.0MiB| timeout | 0 |  |  |
