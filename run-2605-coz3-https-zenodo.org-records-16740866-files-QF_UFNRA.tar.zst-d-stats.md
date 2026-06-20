# .

* SAT 31
* UNSAT 24
* TIMEOUT 3
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFNRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFNRA.tar.zst-d
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFNRA.tar.zst?download=1
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
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvVar1.smt2 |    0.042s | 20.868MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.630785.smt2              |    0.044s | 19.916MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/z3.641736.smt2                  |    0.044s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/l40f.smt2                       |    0.045s | 21.228MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631195.smt2              |    0.045s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631113.smt2              |    0.045s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.630949.smt2              |    0.045s | 19.872MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.640350.smt2              |    0.045s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631277.smt2              |    0.045s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.630867.smt2              |    0.045s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/z3.630166.smt2                  |    0.045s | 20.128MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvStep.smt2 |    0.045s | 20.788MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20190906-CLEARSY/0004/00003.smt2    |    0.047s | 20.116MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modSimpleTest.smt2 |    0.049s | 20.412MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvInitial.smt2 |    0.052s | 20.872MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631031.smt2              |    0.057s | 20.136MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/l40m.smt2                       |    0.068s | 21.224MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStepFinala.smt2 |    0.072s | 20.848MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStepFinal.smt2 |    0.094s | 20.908MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/m40.easy.smt2                   |    0.185s | 28.268MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/c40s.smt2                       |    0.224s | 29.496MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s50.smt2                      |    0.232s | 30.556MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/c40f.smt2                       |    0.268s | 31.34MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep2.smt2 |    0.436s | 21.176MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/l40s.smt2                       |    0.452s | 40.756MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/c40m.smt2                       |    0.468s | 33.38MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m25.smt2                      |    0.486s | 37.66MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f25.smt2                      |    0.557s | 34.616MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m50.smt2                      |    0.633s | 35.644MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep2a.smt2 |    0.730s | 21.392MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep4a.smt2 |    0.764s | 21.392MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f10.smt2                      |    0.780s | 38.164MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m99.smt2                      |    0.937s | 36.668MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s10.smt2                      |    0.979s | 39.816MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s25.smt2                      |    1.029s | 39.68MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f50.smt2                      |    1.138s | 35.74MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/20u10.09.smt2                   |    1.195s | 31.304MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep1.smt2 |    1.233s | 21.608MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep3a.smt2 |    1.234s | 21.56MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s99.smt2                      |    1.357s | 40.368MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m10.smt2                      |    1.514s | 41.096MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f99.smt2                      |    1.708s | 36.904MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep3.smt2 |    1.781s | 21.348MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep6.smt2 |    2.154s | 21.648MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep4.smt2 |    2.223s | 21.596MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep5.smt2 |    2.402s | 22.148MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/s40.smt2                        |    4.977s | 37.436MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep1a.smt2 |    5.310s | 21.38MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep6a.smt2 |    6.374s | 22.22MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep5a.smt2 |    7.502s | 22.596MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/20revert.u.smt2                 |    7.515s | 33.464MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/10u05.04.smt2                   |    9.092s | 25.604MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40u20.19.smt2                   |    9.454s | 56.224MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/m40.smt2                        |   13.273s | 56.84MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep7.smt2 |   14.791s | 23.288MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep7a.smt2 |   20.034s | 22.304MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/30u15.14.smt2                   |   20.037s | 41.108MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvFull.smt2 |   20.128s | 939.0MiB| timeout | 0 |  |  |
