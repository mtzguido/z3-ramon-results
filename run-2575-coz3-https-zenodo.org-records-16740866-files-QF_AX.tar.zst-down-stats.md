# .

* SAT 272
* UNSAT 279
* TIMEOUT 0
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_AX.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_AX.tar.zst-down
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_AX.tar.zst?download=1
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
|non-incremental/QF_AX/storeinv/storeinv_invalid_t1_np_nf_ai_00007_001.cvc.smt2 |    0.025s | 20.108MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00007_005.cvc.smt2 |    0.026s | 20.192MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00010_002.cvc.smt2 |    0.026s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00006_002.cvc.smt2 |    0.027s | 20.112MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00020_007.cvc.smt2 |    0.027s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00010_003.cvc.smt2 |    0.028s | 20.356MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00010_001.cvc.smt2 |    0.028s | 20.148MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00020_005.cvc.smt2 |    0.028s | 20.472MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00002_002.cvc.smt2 |    0.029s | 19.868MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t1_np_nf_ai_00010_001.cvc.smt2 |    0.029s | 20.344MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00009_005.cvc.smt2 |    0.030s | 20.124MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00005_004.cvc.smt2 |    0.030s | 19.904MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00009_004.cvc.smt2 |    0.031s | 20.724MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00020_001.cvc.smt2 |    0.031s | 20.62MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00030_006.cvc.smt2 |    0.031s | 21.0MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00008_005.cvc.smt2 |    0.032s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t3_np_nf_ai_00008_001.cvc.smt2 |    0.032s | 20.28MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00010_003.cvc.smt2 |    0.033s | 20.288MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00010_006.cvc.smt2 |    0.033s | 20.136MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00006_004.cvc.smt2 |    0.033s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00030_003.cvc.smt2 |    0.033s | 20.868MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00030_005.cvc.smt2 |    0.033s | 20.624MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00003_007.cvc.smt2 |    0.034s | 19.86MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00010_009.cvc.smt2 |    0.035s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00040_006.cvc.smt2 |    0.036s | 21.228MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00050_001.cvc.smt2 |    0.038s | 21.7MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t3_np_nf_ai_00010_001.cvc.smt2 |    0.038s | 20.312MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00004_003.cvc.smt2 |    0.039s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00050_006.cvc.smt2 |    0.039s | 21.864MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00050_001.cvc.smt2 |    0.039s | 21.208MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00040_005.cvc.smt2 |    0.039s | 21.012MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00004_003.cvc.smt2 |    0.040s | 20.08MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00008_004.cvc.smt2 |    0.040s | 20.54MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00008_003.cvc.smt2 |    0.040s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00050_002.cvc.smt2 |    0.040s | 21.564MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00005_007.cvc.smt2 |    0.042s | 20.14MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00009_003.cvc.smt2 |    0.043s | 20.284MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00003_003.cvc.smt2 |    0.043s | 19.564MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00010_005.cvc.smt2 |    0.043s | 19.956MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00004_005.cvc.smt2 |    0.044s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00003_004.cvc.smt2 |    0.045s | 19.768MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00003_001.cvc.smt2 |    0.045s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00005_008.cvc.smt2 |    0.045s | 20.388MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00004_002.cvc.smt2 |    0.045s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00003_003.cvc.smt2 |    0.045s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00004_003.cvc.smt2 |    0.046s | 19.844MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00010_006.cvc.smt2 |    0.046s | 20.064MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00003_001.cvc.smt2 |    0.046s | 20.144MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00005_009.cvc.smt2 |    0.046s | 20.12MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00006_006.cvc.smt2 |    0.047s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00004_002.cvc.smt2 |    0.047s | 20.036MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00006_001.cvc.smt2 |    0.047s | 20.112MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00006_008.cvc.smt2 |    0.047s | 20.104MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00006_002.cvc.smt2 |    0.047s | 20.168MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00003_005.cvc.smt2 |    0.048s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00004_006.cvc.smt2 |    0.048s | 19.972MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00002_001.cvc.smt2 |    0.048s | 19.82MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00005_008.cvc.smt2 |    0.048s | 19.852MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00005_008.cvc.smt2 |    0.048s | 20.184MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00003_005.cvc.smt2 |    0.049s | 20.192MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00002_005.cvc.smt2 |    0.049s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00010_003.cvc.smt2 |    0.049s | 20.076MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00020_006.cvc.smt2 |    0.049s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t2_np_nf_ai_00001_001.cvc.smt2 |    0.049s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00005_003.cvc.smt2 |    0.050s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00009_002.cvc.smt2 |    0.050s | 20.46MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00002_006.cvc.smt2 |    0.050s | 19.964MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00004_009.cvc.smt2 |    0.050s | 20.232MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00008_008.cvc.smt2 |    0.050s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00004_009.cvc.smt2 |    0.050s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00020_003.cvc.smt2 |    0.050s | 20.316MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t1_np_sf_ai_00002_001.cvc.smt2 |    0.050s | 19.928MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00009_008.cvc.smt2 |    0.051s | 20.468MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t1_np_sf_ai_00010_001.cvc.smt2 |    0.051s | 20.388MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t3_np_nf_ai_00004_001.cvc.smt2 |    0.051s | 19.876MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t1_np_sf_ai_00006_001.cvc.smt2 |    0.051s | 20.22MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00004_001.cvc.smt2 |    0.052s | 19.956MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00008_006.cvc.smt2 |    0.052s | 20.256MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00008_001.cvc.smt2 |    0.052s | 20.292MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00003_008.cvc.smt2 |    0.052s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00003_002.cvc.smt2 |    0.052s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/cvc/read5.smt2                         |    0.052s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00020_006.cvc.smt2 |    0.052s | 20.208MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00003_004.cvc.smt2 |    0.053s | 19.852MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00005_007.cvc.smt2 |    0.053s | 20.06MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00002_005.cvc.smt2 |    0.053s | 19.96MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00007_007.cvc.smt2 |    0.053s | 20.348MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00005_005.cvc.smt2 |    0.053s | 20.416MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00008_007.cvc.smt2 |    0.054s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00006_009.cvc.smt2 |    0.054s | 20.152MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00010_008.cvc.smt2 |    0.054s | 20.04MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_nf_ai_00020_002.cvc.smt2 |    0.054s | 20.608MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00003_005.cvc.smt2 |    0.055s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00003_005.cvc.smt2 |    0.055s | 20.156MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00006_002.cvc.smt2 |    0.055s | 20.092MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00005_004.cvc.smt2 |    0.055s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00004_008.cvc.smt2 |    0.055s | 20.028MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00010_004.cvc.smt2 |    0.056s | 20.272MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00004_008.cvc.smt2 |    0.056s | 20.0MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00006_003.cvc.smt2 |    0.056s | 19.936MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00009_001.cvc.smt2 |    0.056s | 20.392MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00005_003.cvc.smt2 |    0.056s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00008_005.cvc.smt2 |    0.056s | 20.256MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t1_np_sf_ai_00009_001.cvc.smt2 |    0.056s | 20.388MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00006_008.cvc.smt2 |    0.057s | 20.164MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00006_008.cvc.smt2 |    0.057s | 20.236MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00004_004.cvc.smt2 |    0.057s | 20.184MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00008_003.cvc.smt2 |    0.057s | 19.948MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00004_009.cvc.smt2 |    0.057s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00020_006.cvc.smt2 |    0.057s | 20.612MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t3_np_nf_ai_00009_001.cvc.smt2 |    0.057s | 20.408MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00007_009.cvc.smt2 |    0.058s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00004_007.cvc.smt2 |    0.058s | 20.248MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00005_003.cvc.smt2 |    0.058s | 19.888MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00004_008.cvc.smt2 |    0.059s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00009_006.cvc.smt2 |    0.059s | 20.36MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00002_005.cvc.smt2 |    0.059s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00006_001.cvc.smt2 |    0.059s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00002_002.cvc.smt2 |    0.059s | 19.78MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00004_005.cvc.smt2 |    0.059s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00007_006.cvc.smt2 |    0.060s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00006_009.cvc.smt2 |    0.060s | 20.14MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00004_002.cvc.smt2 |    0.060s | 19.98MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00008_004.cvc.smt2 |    0.060s | 20.024MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00007_004.cvc.smt2 |    0.060s | 20.476MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00005_005.cvc.smt2 |    0.060s | 20.332MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00050_004.cvc.smt2 |    0.060s | 21.7MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00006_009.cvc.smt2 |    0.061s | 20.016MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00005_008.cvc.smt2 |    0.061s | 20.084MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00004_008.cvc.smt2 |    0.061s | 19.9MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00008_009.cvc.smt2 |    0.061s | 20.424MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00008_007.cvc.smt2 |    0.061s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00005_001.cvc.smt2 |    0.062s | 19.576MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00007_002.cvc.smt2 |    0.062s | 20.6MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00008_001.cvc.smt2 |    0.062s | 20.316MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00002_001.cvc.smt2 |    0.062s | 19.384MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00040_009.cvc.smt2 |    0.062s | 21.24MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00060_005.cvc.smt2 |    0.062s | 21.628MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00050_002.cvc.smt2 |    0.062s | 21.856MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00004_007.cvc.smt2 |    0.063s | 19.904MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00008_005.cvc.smt2 |    0.064s | 20.524MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00003_006.cvc.smt2 |    0.064s | 20.088MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_nf_ai_00050_002.cvc.smt2 |    0.064s | 21.508MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00007_005.cvc.smt2 |    0.065s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00003_007.cvc.smt2 |    0.065s | 20.092MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00005_003.cvc.smt2 |    0.066s | 20.1MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00007_007.cvc.smt2 |    0.066s | 19.956MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00007_009.cvc.smt2 |    0.066s | 20.76MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00010_002.cvc.smt2 |    0.066s | 20.124MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00030_002.cvc.smt2 |    0.066s | 20.784MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00008_002.cvc.smt2 |    0.067s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_sf_ai_00050_006.cvc.smt2 |    0.067s | 21.324MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00040_008.cvc.smt2 |    0.067s | 21.284MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00004_006.cvc.smt2 |    0.068s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00060_003.cvc.smt2 |    0.068s | 21.68MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00050_004.cvc.smt2 |    0.069s | 21.532MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00060_005.cvc.smt2 |    0.069s | 22.436MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00050_009.cvc.smt2 |    0.069s | 21.636MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_sf_ai_00010_008.cvc.smt2 |    0.069s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00050_003.cvc.smt2 |    0.069s | 21.132MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00007_003.cvc.smt2 |    0.070s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00002_008.cvc.smt2 |    0.070s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00003_002.cvc.smt2 |    0.070s | 20.076MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00010_002.cvc.smt2 |    0.070s | 20.836MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00006_004.cvc.smt2 |    0.071s | 20.54MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00007_006.cvc.smt2 |    0.071s | 20.188MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00003_001.cvc.smt2 |    0.071s | 19.864MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00009_008.cvc.smt2 |    0.071s | 20.164MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00005_006.cvc.smt2 |    0.071s | 19.852MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00003_008.cvc.smt2 |    0.071s | 19.764MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00006_006.cvc.smt2 |    0.071s | 20.368MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00006_001.cvc.smt2 |    0.071s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00040_006.cvc.smt2 |    0.071s | 21.128MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00050_005.cvc.smt2 |    0.071s | 21.616MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_sf_ai_00020_009.cvc.smt2 |    0.071s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00004_005.cvc.smt2 |    0.072s | 20.372MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00007_003.cvc.smt2 |    0.072s | 20.16MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00007_007.cvc.smt2 |    0.072s | 20.136MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00002_006.cvc.smt2 |    0.072s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00005_006.cvc.smt2 |    0.072s | 20.072MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00007_007.cvc.smt2 |    0.072s | 20.104MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00050_009.cvc.smt2 |    0.072s | 21.512MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00030_009.cvc.smt2 |    0.072s | 20.872MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00007_005.cvc.smt2 |    0.073s | 20.216MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00006_006.cvc.smt2 |    0.073s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00009_009.cvc.smt2 |    0.073s | 20.596MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00003_004.cvc.smt2 |    0.073s | 19.92MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00010_007.cvc.smt2 |    0.073s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00008_001.cvc.smt2 |    0.074s | 20.188MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00010_005.cvc.smt2 |    0.074s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00007_002.cvc.smt2 |    0.074s | 20.16MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00007_002.cvc.smt2 |    0.074s | 20.272MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00007_009.cvc.smt2 |    0.074s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00003_006.cvc.smt2 |    0.074s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00006_003.cvc.smt2 |    0.075s | 20.016MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00010_008.cvc.smt2 |    0.075s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00005_006.cvc.smt2 |    0.075s | 19.936MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00006_005.cvc.smt2 |    0.075s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00007_003.cvc.smt2 |    0.075s | 20.104MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00050_007.cvc.smt2 |    0.075s | 21.864MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00040_002.cvc.smt2 |    0.075s | 20.748MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00004_003.cvc.smt2 |    0.076s | 19.944MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00009_007.cvc.smt2 |    0.076s | 20.368MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00005_006.cvc.smt2 |    0.076s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00009_001.cvc.smt2 |    0.076s | 20.352MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00030_004.cvc.smt2 |    0.076s | 20.852MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00003_006.cvc.smt2 |    0.077s | 19.964MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00007_001.cvc.smt2 |    0.077s | 20.196MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00010_006.cvc.smt2 |    0.077s | 20.244MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00010_009.cvc.smt2 |    0.077s | 20.208MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00020_001.cvc.smt2 |    0.077s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00002_006.cvc.smt2 |    0.078s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00004_007.cvc.smt2 |    0.078s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00003_002.cvc.smt2 |    0.078s | 19.952MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00006_005.cvc.smt2 |    0.079s | 20.236MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00002_005.cvc.smt2 |    0.079s | 19.764MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00006_002.cvc.smt2 |    0.079s | 20.392MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00010_001.cvc.smt2 |    0.080s | 20.864MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00007_008.cvc.smt2 |    0.080s | 20.16MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00007_003.cvc.smt2 |    0.080s | 20.46MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00006_003.cvc.smt2 |    0.080s | 20.136MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00008_003.cvc.smt2 |    0.080s | 19.48MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00004_004.cvc.smt2 |    0.081s | 19.872MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00010_001.cvc.smt2 |    0.081s | 20.412MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00004_004.cvc.smt2 |    0.082s | 19.952MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00008_009.cvc.smt2 |    0.082s | 20.332MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_sf_ai_00020_005.cvc.smt2 |    0.082s | 20.284MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00010_007.cvc.smt2 |    0.082s | 20.056MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t1_np_sf_ai_00008_001.cvc.smt2 |    0.082s | 20.356MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00004_001.cvc.smt2 |    0.083s | 19.852MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00006_001.cvc.smt2 |    0.083s | 19.896MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00006_004.cvc.smt2 |    0.083s | 20.116MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00008_007.cvc.smt2 |    0.083s | 20.256MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00007_004.cvc.smt2 |    0.083s | 20.116MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00008_005.cvc.smt2 |    0.083s | 20.04MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00010_005.cvc.smt2 |    0.083s | 20.512MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00005_002.cvc.smt2 |    0.083s | 20.376MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00010_001.cvc.smt2 |    0.083s | 20.332MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00030_002.cvc.smt2 |    0.083s | 21.14MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00020_005.cvc.smt2 |    0.083s | 20.864MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00008_002.cvc.smt2 |    0.084s | 20.036MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00008_008.cvc.smt2 |    0.084s | 20.356MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00002_002.cvc.smt2 |    0.084s | 20.044MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00006_007.cvc.smt2 |    0.084s | 20.068MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00005_001.cvc.smt2 |    0.084s | 20.068MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00008_007.cvc.smt2 |    0.084s | 20.052MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00030_005.cvc.smt2 |    0.084s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00030_008.cvc.smt2 |    0.084s | 20.604MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00004_006.cvc.smt2 |    0.085s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00007_004.cvc.smt2 |    0.085s | 20.268MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00008_004.cvc.smt2 |    0.085s | 20.412MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00004_009.cvc.smt2 |    0.085s | 19.868MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00030_006.cvc.smt2 |    0.085s | 20.54MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00010_005.cvc.smt2 |    0.085s | 20.32MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00009_002.cvc.smt2 |    0.086s | 20.292MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00006_009.cvc.smt2 |    0.086s | 20.108MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00003_001.cvc.smt2 |    0.086s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_nf_ai_00050_006.cvc.smt2 |    0.086s | 21.16MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00050_009.cvc.smt2 |    0.086s | 21.492MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00007_004.cvc.smt2 |    0.087s | 19.92MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00006_005.cvc.smt2 |    0.087s | 20.376MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00050_008.cvc.smt2 |    0.087s | 21.864MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00050_005.cvc.smt2 |    0.087s | 21.376MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t1_np_sf_ai_00006_001.cvc.smt2 |    0.087s | 20.356MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00004_002.cvc.smt2 |    0.088s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00010_006.cvc.smt2 |    0.088s | 20.264MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00002_009.cvc.smt2 |    0.088s | 19.984MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00009_002.cvc.smt2 |    0.088s | 20.396MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00003_006.cvc.smt2 |    0.088s | 19.772MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00008_003.cvc.smt2 |    0.088s | 19.376MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00007_008.cvc.smt2 |    0.088s | 20.632MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00008_006.cvc.smt2 |    0.088s | 20.108MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00040_004.cvc.smt2 |    0.088s | 20.916MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00040_009.cvc.smt2 |    0.088s | 20.724MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00020_007.cvc.smt2 |    0.088s | 20.584MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00050_004.cvc.smt2 |    0.088s | 21.188MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00005_001.cvc.smt2 |    0.089s | 19.504MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00009_009.cvc.smt2 |    0.089s | 20.376MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_nf_ai_00050_001.cvc.smt2 |    0.089s | 21.272MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00030_001.cvc.smt2 |    0.089s | 20.624MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00050_002.cvc.smt2 |    0.089s | 21.468MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00030_005.cvc.smt2 |    0.089s | 21.14MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t1_np_sf_ai_00004_001.cvc.smt2 |    0.089s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00002_009.cvc.smt2 |    0.090s | 19.916MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00002_003.cvc.smt2 |    0.090s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00009_005.cvc.smt2 |    0.090s | 20.188MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00004_007.cvc.smt2 |    0.090s | 20.036MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00004_001.cvc.smt2 |    0.090s | 19.96MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00009_005.cvc.smt2 |    0.090s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00007_001.cvc.smt2 |    0.091s | 20.136MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00005_005.cvc.smt2 |    0.091s | 20.144MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00005_009.cvc.smt2 |    0.091s | 19.892MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00007_006.cvc.smt2 |    0.091s | 20.276MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t1_np_sf_ai_00002_001.cvc.smt2 |    0.091s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00005_004.cvc.smt2 |    0.092s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00006_005.cvc.smt2 |    0.092s | 20.092MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00005_001.cvc.smt2 |    0.092s | 19.944MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00004_005.cvc.smt2 |    0.092s | 19.964MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00030_003.cvc.smt2 |    0.092s | 20.848MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00060_001.cvc.smt2 |    0.092s | 21.624MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00005_005.cvc.smt2 |    0.093s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00008_002.cvc.smt2 |    0.093s | 20.5MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00009_001.cvc.smt2 |    0.093s | 20.572MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00002_008.cvc.smt2 |    0.093s | 20.076MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00002_006.cvc.smt2 |    0.093s | 19.912MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00010_006.cvc.smt2 |    0.093s | 20.14MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00060_004.cvc.smt2 |    0.093s | 22.352MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00005_002.cvc.smt2 |    0.094s | 20.124MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00007_008.cvc.smt2 |    0.094s | 20.204MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00009_006.cvc.smt2 |    0.094s | 20.484MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00010_008.cvc.smt2 |    0.094s | 20.564MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00008_002.cvc.smt2 |    0.094s | 20.232MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00007_005.cvc.smt2 |    0.094s | 20.152MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00005_004.cvc.smt2 |    0.094s | 19.852MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t3_np_sf_ai_00003_001.cvc.smt2 |    0.094s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00007_009.cvc.smt2 |    0.095s | 20.152MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00010_004.cvc.smt2 |    0.095s | 20.4MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00005_002.cvc.smt2 |    0.095s | 20.1MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00050_004.cvc.smt2 |    0.095s | 21.112MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00010_007.cvc.smt2 |    0.095s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00010_009.cvc.smt2 |    0.095s | 20.064MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00007_006.cvc.smt2 |    0.096s | 20.016MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00010_009.cvc.smt2 |    0.096s | 20.516MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_sf_ai_00010_005.cvc.smt2 |    0.096s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00040_008.cvc.smt2 |    0.096s | 21.244MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00010_008.cvc.smt2 |    0.097s | 20.276MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00060_001.cvc.smt2 |    0.097s | 22.264MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00010_005.cvc.smt2 |    0.097s | 20.108MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t1_np_sf_ai_00007_001.cvc.smt2 |    0.097s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00009_007.cvc.smt2 |    0.098s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00003_007.cvc.smt2 |    0.098s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00009_004.cvc.smt2 |    0.098s | 20.356MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00004_006.cvc.smt2 |    0.098s | 19.84MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00060_004.cvc.smt2 |    0.098s | 22.412MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00050_005.cvc.smt2 |    0.098s | 21.844MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00040_007.cvc.smt2 |    0.098s | 21.1MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t3_np_sf_ai_00004_001.cvc.smt2 |    0.098s | 20.076MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00005_009.cvc.smt2 |    0.099s | 20.016MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00009_003.cvc.smt2 |    0.099s | 20.384MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00005_009.cvc.smt2 |    0.099s | 20.088MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00008_006.cvc.smt2 |    0.099s | 20.456MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00003_004.cvc.smt2 |    0.099s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00003_008.cvc.smt2 |    0.099s | 19.752MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00003_007.cvc.smt2 |    0.099s | 19.848MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00060_009.cvc.smt2 |    0.099s | 22.604MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00020_007.cvc.smt2 |    0.099s | 20.368MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00004_001.cvc.smt2 |    0.100s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00003_008.cvc.smt2 |    0.100s | 19.956MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00005_007.cvc.smt2 |    0.100s | 19.972MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00010_003.cvc.smt2 |    0.100s | 20.26MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00009_007.cvc.smt2 |    0.100s | 20.152MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00040_009.cvc.smt2 |    0.100s | 21.348MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00030_004.cvc.smt2 |    0.100s | 20.824MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00050_005.cvc.smt2 |    0.100s | 21.324MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t3_np_nf_ai_00002_001.cvc.smt2 |    0.100s | 19.852MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00005_002.cvc.smt2 |    0.101s | 20.06MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00007_001.cvc.smt2 |    0.101s | 20.18MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00002_002.cvc.smt2 |    0.101s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00010_003.cvc.smt2 |    0.101s | 20.088MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00010_006.cvc.smt2 |    0.101s | 20.564MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00006_003.cvc.smt2 |    0.102s | 20.208MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00007_001.cvc.smt2 |    0.102s | 20.172MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00004_004.cvc.smt2 |    0.102s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00006_004.cvc.smt2 |    0.102s | 20.004MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00003_002.cvc.smt2 |    0.102s | 20.072MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00006_006.cvc.smt2 |    0.102s | 20.152MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00010_002.cvc.smt2 |    0.102s | 20.524MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00010_009.cvc.smt2 |    0.102s | 20.604MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00050_003.cvc.smt2 |    0.103s | 21.64MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00020_001.cvc.smt2 |    0.103s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00020_009.cvc.smt2 |    0.103s | 20.404MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00006_008.cvc.smt2 |    0.104s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00006_007.cvc.smt2 |    0.104s | 20.476MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00005_007.cvc.smt2 |    0.104s | 20.088MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00002_009.cvc.smt2 |    0.104s | 20.0MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00030_001.cvc.smt2 |    0.104s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00020_002.cvc.smt2 |    0.104s | 20.312MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00010_003.cvc.smt2 |    0.104s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t2_np_nf_ai_00004_001.cvc.smt2 |    0.104s | 20.136MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00009_002.cvc.smt2 |    0.105s | 20.276MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_sf_ai_00010_007.cvc.smt2 |    0.105s | 20.368MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00006_007.cvc.smt2 |    0.105s | 20.236MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00040_005.cvc.smt2 |    0.105s | 21.116MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_nf_ai_00020_003.cvc.smt2 |    0.105s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00040_003.cvc.smt2 |    0.105s | 20.824MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00040_009.cvc.smt2 |    0.105s | 21.144MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_sf_ai_00040_001.cvc.smt2 |    0.105s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00020_004.cvc.smt2 |    0.105s | 20.528MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00010_001.cvc.smt2 |    0.105s | 20.108MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00009_001.cvc.smt2 |    0.106s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_sf_ai_00040_007.cvc.smt2 |    0.106s | 20.836MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_nf_ai_00020_005.cvc.smt2 |    0.106s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00030_004.cvc.smt2 |    0.106s | 20.324MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00050_003.cvc.smt2 |    0.106s | 21.144MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00030_002.cvc.smt2 |    0.106s | 20.644MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00009_005.cvc.smt2 |    0.107s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00020_002.cvc.smt2 |    0.107s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_sf_ai_00030_003.cvc.smt2 |    0.107s | 20.356MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_nf_ai_00040_007.cvc.smt2 |    0.107s | 21.12MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00020_008.cvc.smt2 |    0.107s | 20.492MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00030_005.cvc.smt2 |    0.107s | 20.472MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00030_007.cvc.smt2 |    0.107s | 20.86MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00010_004.cvc.smt2 |    0.108s | 20.344MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00030_008.cvc.smt2 |    0.108s | 20.76MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00030_008.cvc.smt2 |    0.108s | 20.408MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00060_006.cvc.smt2 |    0.108s | 21.736MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00007_002.cvc.smt2 |    0.109s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00030_001.cvc.smt2 |    0.109s | 20.644MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00040_006.cvc.smt2 |    0.109s | 21.132MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00006_007.cvc.smt2 |    0.110s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00010_004.cvc.smt2 |    0.110s | 20.196MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00020_008.cvc.smt2 |    0.111s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00010_007.cvc.smt2 |    0.111s | 20.316MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00060_005.cvc.smt2 |    0.111s | 22.396MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00030_007.cvc.smt2 |    0.111s | 20.856MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00030_004.cvc.smt2 |    0.111s | 20.776MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t1_np_nf_ai_00010_002.cvc.smt2 |    0.112s | 20.54MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00050_007.cvc.smt2 |    0.112s | 21.652MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00010_006.cvc.smt2 |    0.112s | 20.156MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00020_002.cvc.smt2 |    0.112s | 20.624MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00030_003.cvc.smt2 |    0.112s | 20.392MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00030_009.cvc.smt2 |    0.112s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00040_002.cvc.smt2 |    0.112s | 20.852MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00040_004.cvc.smt2 |    0.112s | 21.18MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00020_004.cvc.smt2 |    0.112s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00020_003.cvc.smt2 |    0.112s | 20.152MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00010_004.cvc.smt2 |    0.112s | 20.068MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t2_np_nf_ai_00003_001.cvc.smt2 |    0.112s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00007_008.cvc.smt2 |    0.113s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00009_009.cvc.smt2 |    0.113s | 20.736MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00030_006.cvc.smt2 |    0.113s | 20.636MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00020_009.cvc.smt2 |    0.113s | 20.604MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00020_008.cvc.smt2 |    0.113s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00030_007.cvc.smt2 |    0.113s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00040_002.cvc.smt2 |    0.114s | 21.092MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00010_001.cvc.smt2 |    0.114s | 20.7MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00050_001.cvc.smt2 |    0.114s | 21.664MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00010_008.cvc.smt2 |    0.114s | 20.324MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t1_np_sf_ai_00005_001.cvc.smt2 |    0.114s | 20.58MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00010_007.cvc.smt2 |    0.115s | 20.396MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_sf_ai_00008_001.cvc.smt2 |    0.115s | 20.368MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00020_007.cvc.smt2 |    0.115s | 20.616MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t3_np_sf_ai_00007_001.cvc.smt2 |    0.115s | 20.02MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t2_np_sf_ai_00001_001.cvc.smt2 |    0.115s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00008_004.cvc.smt2 |    0.116s | 20.432MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_sf_ai_00010_002.cvc.smt2 |    0.116s | 19.912MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t3_np_nf_ai_00008_001.cvc.smt2 |    0.116s | 20.328MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00040_002.cvc.smt2 |    0.117s | 20.968MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00040_004.cvc.smt2 |    0.117s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00030_002.cvc.smt2 |    0.117s | 20.388MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_sf_ai_00020_003.cvc.smt2 |    0.117s | 20.088MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00050_003.cvc.smt2 |    0.117s | 21.648MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_sf_ai_00040_008.cvc.smt2 |    0.117s | 20.86MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_nf_ai_00040_003.cvc.smt2 |    0.117s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00040_005.cvc.smt2 |    0.117s | 20.808MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00030_007.cvc.smt2 |    0.117s | 20.508MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00030_008.cvc.smt2 |    0.117s | 20.552MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t3_np_sf_ai_00005_001.cvc.smt2 |    0.117s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t3_np_nf_ai_00005_001.cvc.smt2 |    0.117s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00009_007.cvc.smt2 |    0.118s | 20.508MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00009_003.cvc.smt2 |    0.118s | 20.572MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00010_005.cvc.smt2 |    0.118s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_nf_ai_00060_008.cvc.smt2 |    0.118s | 21.94MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t1_np_nf_ai_00005_001.cvc.smt2 |    0.118s | 19.884MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t3_np_nf_ai_00006_001.cvc.smt2 |    0.118s | 20.34MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00010_008.cvc.smt2 |    0.119s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00040_001.cvc.smt2 |    0.119s | 21.372MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00040_003.cvc.smt2 |    0.119s | 21.156MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00060_008.cvc.smt2 |    0.119s | 22.276MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00008_008.cvc.smt2 |    0.120s | 20.432MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t1_np_sf_ai_00009_001.cvc.smt2 |    0.120s | 20.5MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00010_008.cvc.smt2 |    0.121s | 20.648MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00008_009.cvc.smt2 |    0.121s | 20.48MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00040_007.cvc.smt2 |    0.121s | 21.12MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00040_005.cvc.smt2 |    0.121s | 21.1MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00020_009.cvc.smt2 |    0.121s | 20.444MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00060_005.cvc.smt2 |    0.121s | 21.88MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t3_np_sf_ai_00008_001.cvc.smt2 |    0.121s | 20.312MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t3_np_nf_ai_00006_001.cvc.smt2 |    0.121s | 20.264MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00060_008.cvc.smt2 |    0.122s | 22.364MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00060_007.cvc.smt2 |    0.122s | 22.252MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00030_009.cvc.smt2 |    0.122s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00040_001.cvc.smt2 |    0.122s | 21.104MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00020_006.cvc.smt2 |    0.122s | 20.412MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00010_006.cvc.smt2 |    0.122s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t1_np_nf_ai_00002_001.cvc.smt2 |    0.122s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t2_np_nf_ai_00007_001.cvc.smt2 |    0.122s | 20.324MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t3_np_sf_ai_00003_001.cvc.smt2 |    0.122s | 19.864MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00008_006.cvc.smt2 |    0.123s | 20.392MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00010_004.cvc.smt2 |    0.123s | 20.756MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00030_001.cvc.smt2 |    0.123s | 20.696MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00050_007.cvc.smt2 |    0.123s | 21.156MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00060_009.cvc.smt2 |    0.123s | 21.684MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00040_003.cvc.smt2 |    0.123s | 21.392MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t1_np_nf_ai_00009_001.cvc.smt2 |    0.123s | 20.112MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_nf_ai_00060_003.cvc.smt2 |    0.124s | 21.548MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_nf_ai_00050_007.cvc.smt2 |    0.124s | 21.18MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00010_004.cvc.smt2 |    0.124s | 20.1MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_invalid_t1_np_nf_ai_00003_001.cvc.smt2 |    0.124s | 20.4MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00009_003.cvc.smt2 |    0.125s | 20.668MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00050_008.cvc.smt2 |    0.125s | 21.48MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00050_009.cvc.smt2 |    0.125s | 21.62MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00020_004.cvc.smt2 |    0.125s | 20.68MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00020_008.cvc.smt2 |    0.125s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_nf_ai_00040_006.cvc.smt2 |    0.125s | 20.904MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storeinv/storeinv_t3_np_sf_ai_00010_001.cvc.smt2 |    0.125s | 20.748MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00020_004.cvc.smt2 |    0.126s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_sf_ai_00020_001.cvc.smt2 |    0.126s | 20.26MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00008_008.cvc.smt2 |    0.127s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_sf_ai_00060_008.cvc.smt2 |    0.128s | 21.992MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_nf_ai_00030_009.cvc.smt2 |    0.128s | 20.624MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_nf_ai_00060_007.cvc.smt2 |    0.128s | 21.576MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00030_006.cvc.smt2 |    0.128s | 20.6MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00060_009.cvc.smt2 |    0.128s | 21.508MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00060_004.cvc.smt2 |    0.128s | 21.74MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00040_001.cvc.smt2 |    0.129s | 21.012MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00009_008.cvc.smt2 |    0.130s | 20.412MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_nf_ai_00040_008.cvc.smt2 |    0.130s | 20.952MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00050_006.cvc.smt2 |    0.130s | 21.652MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_sf_ai_00060_001.cvc.smt2 |    0.131s | 22.296MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_sf_ai_00060_003.cvc.smt2 |    0.131s | 22.356MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t2_np_sf_ai_00060_001.cvc.smt2 |    0.131s | 21.928MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00060_002.cvc.smt2 |    0.131s | 22.276MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00008_009.cvc.smt2 |    0.132s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00040_004.cvc.smt2 |    0.132s | 21.376MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00010_005.cvc.smt2 |    0.133s | 20.588MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00050_008.cvc.smt2 |    0.134s | 21.172MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00050_008.cvc.smt2 |    0.135s | 21.28MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t1_np_sf_ai_00060_004.cvc.smt2 |    0.136s | 21.732MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_invalid_t3_np_nf_ai_00010_009.cvc.smt2 |    0.137s | 20.388MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_t3_np_nf_ai_00060_002.cvc.smt2 |    0.139s | 21.584MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t3_np_nf_ai_00060_003.cvc.smt2 |    0.140s | 22.3MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t2_np_sf_ai_00060_009.cvc.smt2 |    0.140s | 22.504MiB| sat | 0 |  |  |
|non-incremental/QF_AX/storecomm/storecomm_invalid_t1_np_nf_ai_00060_006.cvc.smt2 |    0.145s | 22.376MiB| sat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00009_008.cvc.smt2 |    0.148s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00009_009.cvc.smt2 |    0.156s | 20.692MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_sf_ai_00010_004.cvc.smt2 |    0.169s | 20.608MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00009_006.cvc.smt2 |    0.176s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00009_006.cvc.smt2 |    0.179s | 20.904MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00009_004.cvc.smt2 |    0.195s | 21.392MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00010_003.cvc.smt2 |    0.214s | 21.056MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00010_001.cvc.smt2 |    0.228s | 21.496MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00010_007.cvc.smt2 |    0.256s | 21.192MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_sf_ai_00010_003.cvc.smt2 |    0.264s | 21.128MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00009_004.cvc.smt2 |    0.264s | 21.412MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_nf_ai_00010_007.cvc.smt2 |    0.267s | 21.168MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00010_001.cvc.smt2 |    0.457s | 21.616MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t1_np_nf_ai_00010_009.cvc.smt2 |    0.488s | 22.048MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00010_009.cvc.smt2 |    0.520s | 21.664MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t3_np_sf_ai_00010_002.cvc.smt2 |    1.690s | 23.276MiB| unsat | 0 |  |  |
|non-incremental/QF_AX/swap/swap_t2_np_nf_ai_00010_002.cvc.smt2 |    2.362s | 23.456MiB| unsat | 0 |  |  |
