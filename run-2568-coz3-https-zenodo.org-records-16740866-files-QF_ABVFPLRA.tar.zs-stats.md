# .

* SAT 56
* UNSAT 1
* TIMEOUT 17
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_ABVFPLRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_ABVFPLRA.tar.zs
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_ABVFPLRA.tar.zst?download=1
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
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0662a_true-unreach-call.c_1.smt2 |    0.021s | 19.868MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_8.smt2 |    0.022s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_182.smt2 |    0.022s | 19.596MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0680a_true-unreach-call.c_1.smt2 |    0.023s | 19.596MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0550b_true-unreach-call.c_1.smt2 |    0.023s | 19.856MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_334.smt2 |    0.023s | 20.012MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_3.smt2 |    0.024s | 20.356MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_73.smt2 |    0.025s | 19.912MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_320.smt2 |    0.025s | 19.636MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0330a_true-unreach-call.c_1.smt2 |    0.026s | 20.608MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_186.smt2 |    0.026s | 19.84MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_332.smt2 |    0.026s | 20.096MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_6.smt2 |    0.030s | 20.144MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0550b_true-unreach-call.c_5.smt2 |    0.032s | 20.572MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_184.smt2 |    0.032s | 19.612MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0660b_true-unreach-call.c_1.smt2 |    0.036s | 19.476MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_poly2_false-unreach-call.c_0.smt2 |    0.036s | 20.372MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0685a_true-unreach-call.c_9.smt2 |    0.037s | 19.452MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_1.smt2 |    0.037s | 19.632MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0874_true-unreach-call.c_4.smt2 |    0.037s | 19.604MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0550b_true-unreach-call.c_2.smt2 |    0.039s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_9.smt2 |    0.041s | 20.112MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_5.smt2 |    0.041s | 19.432MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0883_true-unreach-call.c_2.smt2 |    0.041s | 19.572MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_7.smt2 |    0.043s | 20.156MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/sin_interpolated_bigrange_loose_true-unreach-call.c_0.smt2 |    0.043s | 19.82MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_72.smt2 |    0.043s | 20.112MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_10.smt2 |    0.044s | 19.852MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_56.smt2 |    0.045s | 19.844MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_alt_true-unreach-call.c_39.smt2 |    0.046s | 19.596MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_324.smt2 |    0.051s | 19.64MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_323.smt2 |    0.052s | 19.596MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_45.smt2 |    0.052s | 19.648MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_0.smt2 |    0.053s | 19.856MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_3.smt2 |    0.054s | 19.86MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_335.smt2 |    0.055s | 20.108MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_alt_true-unreach-call.c_8.smt2 |    0.055s | 19.844MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_185.smt2 |    0.055s | 19.596MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_2.smt2 |    0.056s | 19.844MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0883_true-unreach-call.c_1.smt2 |    0.056s | 19.588MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0873a_true-unreach-call.c_2.smt2 |    0.056s | 19.592MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_0.smt2 |    0.056s | 19.604MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_10.smt2 |    0.056s | 20.104MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter_iir_true-unreach-call.c_27.smt2 |    0.056s | 19.604MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0870b_true-unreach-call.c_4.smt2 |    0.057s | 19.616MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0876_true-unreach-call.c_5.smt2 |    0.058s | 19.828MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0330a_true-unreach-call.c_2.smt2 |    0.058s | 19.836MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_336.smt2 |    0.058s | 20.344MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_8.smt2 |    0.058s | 19.892MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter_iir_true-unreach-call.c_34.smt2 |    0.058s | 19.596MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/sin_interpolated_index_false-unreach-call.c_0.smt2 |    0.058s | 19.96MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0220b_true-unreach-call.c_0.smt2 |    0.062s | 24.56MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0620b_true-unreach-call.c_7.smt2 |    0.070s | 23.052MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0240b_true-unreach-call.c_0.smt2 |    0.079s | 24.508MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/inv_Newton_false-unreach-call.c.p+cfa-reducer.c_AllErrorsAtOnce_Iteration4_TraceCheck_0.smt2 |    8.243s | 98.0MiB| unsat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/interpolation_true-unreach-call.c.p+cfa-reducer.c_1.smt2 |   12.553s | 108.0MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/interpolation2_true-unreach-call_true-termination.c_0.smt2 |   19.390s | 109.0MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter2_alt_true-unreach-call.c_AllErrorsAtOnce_Iteration2_TraceCheck_0.smt2 |   20.022s | 78.204MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/interpolation2_true-unreach-call.c.v+cfa-reducer.c_0.smt2 |   20.029s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/interpolation_true-unreach-call.c.p+cfa-reducer.c_0.smt2 |   20.031s | 115.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/inv_Newton_false-unreach-call.c_AllErrorsAtOnce_Iteration2_TraceCheck_0.smt2 |   20.034s | 101.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/sin_interpolated_smallrange_true-unreach-call.c_AllErrorsAtOnce_Iteration2_TraceCheck_0.smt2 |   20.054s | 233.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/sin_interpolated_index_false-unreach-call_true-termination.c_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.057s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_poly2_false-unreach-call.c_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.057s | 242.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/sin_interpolated_index_true-unreach-call_true-termination.c_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.062s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_330.smt2 |   20.063s | 418.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_329.smt2 |   20.070s | 420.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter_iir_true-unreach-call.c_0.smt2 |   20.072s | 482.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_322.smt2 |   20.072s | 417.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_321.smt2 |   20.076s | 417.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_70.smt2 |   20.076s | 417.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_327.smt2 |   20.078s | 420.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_71.smt2 |   20.079s | 418.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_331.smt2 |   20.102s | 418.0MiB| timeout | 0 |  |  |
