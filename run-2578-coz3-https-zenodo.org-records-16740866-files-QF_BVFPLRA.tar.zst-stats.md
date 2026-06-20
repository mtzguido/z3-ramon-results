# .

* SAT 77
* UNSAT 33
* TIMEOUT 67
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_BVFPLRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_BVFPLRA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_BVFPLRA.tar.zst?download=1
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
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_bad_false-unreach-call.i_6.smt2 |    0.025s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/schanda/spark/zeros_consistent_3.smt2 |    0.044s | 19.716MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_bad_false-unreach-call.i_AllErrorsAtOnce_Iteration2_TraceCheck_0.smt2 |    0.047s | 20.064MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Double_div_bad_false-unreach-call.i_AllErrorsAtOnce_Iteration2_TraceCheck_0.smt2 |    0.063s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_bad_false-unreach-call.i_2.smt2 |    0.069s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_bad_false-unreach-call.i_0.smt2 |    0.069s | 19.588MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/digits_bad_while_false-unreach-call.i_AllErrorsAtOnce_Iteration3_TraceCheck_0.smt2 |    0.070s | 19.668MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_bad_false-unreach-call.i_7.smt2 |    0.070s | 19.964MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |    0.073s | 19.588MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_bad_false-unreach-call.i_5.smt2 |    0.080s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/digits_while_true-unreach-call.i_AllErrorsAtOnce_Iteration3_TraceCheck_0.smt2 |    0.082s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_biNewton_pseudoconstant_true-unreach-call.c_2.smt2 |    0.092s | 30.164MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_bad_false-unreach-call.i_1.smt2 |    0.094s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Rump_double_true-unreach-call_true-termination.c_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |    0.095s | 20.06MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_true-unreach-call.i_4.smt2 |    0.097s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_true-unreach-call.i_3.smt2 |    0.222s | 39.864MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_true-unreach-call.i_5.smt2 |    0.275s | 40.044MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_true-unreach-call.i_0.smt2 |    0.278s | 40.02MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float21_true-unreach-call.i_0.smt2 |    0.427s | 32.2MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float21_true-unreach-call.i_1.smt2 |    0.428s | 33.128MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Double_div_true-unreach-call.i_AllErrorsAtOnce_Iteration2_TraceCheck_0.smt2 |    0.500s | 63.048MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_bad_false-unreach-call.i_4.smt2 |    0.689s | 45.016MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/digits_for_true-unreach-call.i_4.smt2 |    0.774s | 36.46MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/digits_bad_for_false-unreach-call.i_3.smt2 |    0.829s | 44.936MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_true-unreach-call.i_1.smt2 |    0.862s | 59.444MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_interval_true-unreach-call.c_2.smt2 |    0.878s | 108.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_interval_true-unreach-call.c_3.smt2 |    0.887s | 108.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/digits_while_true-unreach-call.i_2.smt2 |    1.144s | 51.628MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_interval_true-unreach-call.c_5.smt2 |    1.211s | 109.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_interval_true-unreach-call.c_4.smt2 |    1.213s | 109.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/digits_bad_while_false-unreach-call.i_3.smt2 |    1.220s | 51.476MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_bad_false-unreach-call.i_10.smt2 |    1.236s | 72.772MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_true-unreach-call.i_2.smt2 |    1.245s | 59.336MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/digits_bad_for_false-unreach-call.i_0.smt2 |    1.473s | 80.532MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/digits_bad_while_false-unreach-call.i_0.smt2 |    1.507s | 64.944MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call.c.v+lhb-reducer.c_3.smt2 |    1.667s | 115.0MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_bad_false-unreach-call.i_3.smt2 |    1.677s | 72.588MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_bad_false-unreach-call.i_9.smt2 |    1.751s | 73.152MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/digits_bad_for_false-unreach-call.i_4.smt2 |    1.765s | 37.188MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/square_5_true-unreach-call_true-termination.i_0.smt2 |    1.823s | 126.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0920b_true-unreach-call.c_3.smt2 |    1.839s | 82.012MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call.c.p+cfa-reducer.c_0.smt2 |    1.913s | 115.0MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c.p+cfa-reducer.c_5.smt2 |    1.927s | 110.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Float_div_bad_false-unreach-call.i_8.smt2 |    2.018s | 73.324MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0684a_true-unreach-call.c_1.smt2 |    2.070s | 338.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/digits_for_true-unreach-call.i_1.smt2 |    2.121s | 64.652MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0661a_true-unreach-call.c_0.smt2 |    2.256s | 338.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float-div1_true-unreach-call.i_1.smt2 |    2.328s | 111.0MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_interval_true-unreach-call.c_1.smt2 |    2.374s | 132.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/trunc_nondet_2_true-unreach-call.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |    2.404s | 28.756MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float-div1_true-unreach-call.i_0.smt2 |    2.434s | 111.0MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/inv_Newton_false-unreach-call.c_0.smt2 |    2.632s | 148.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_biNewton_pseudoconstant_true-unreach-call.c_1.smt2 |    2.673s | 338.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/trunc_nondet_2_true-unreach-call.i_11.smt2 |    2.695s | 37.48MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/inv_Newton_false-unreach-call.c.p+cfa-reducer.c_1.smt2 |    2.720s | 148.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_1_6_false-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |    3.083s | 198.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/trunc_nondet_2_true-unreach-call.i_7.smt2 |    3.159s | 37.964MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/trunc_nondet_2_true-unreach-call.i_9.smt2 |    3.241s | 38.148MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/trunc_nondet_2_true-unreach-call.i_2.smt2 |    3.244s | 37.164MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/trunc_nondet_2_true-unreach-call.i_0.smt2 |    3.487s | 37.196MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0470_true-unreach-call.c_2.smt2 |    3.535s | 198.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0320_true-unreach-call.c_8.smt2 |    3.810s | 276.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/trunc_nondet_2_true-unreach-call.i_4.smt2 |    3.827s | 36.696MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0310_true-unreach-call.c_0.smt2 |    3.963s | 190.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sine_2_false-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |    4.620s | 105.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/sqrt_Newton_pseudoconstant_true-unreach-call.c_188.smt2 |    4.645s | 280.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0550b_true-unreach-call.c_0.smt2 |    4.664s | 190.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0960a_true-unreach-call.c_0.smt2 |    4.912s | 240.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/inv_Newton_false-unreach-call.c.p+cfa-reducer.c_0.smt2 |    4.975s | 148.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0240a_true-unreach-call.c_0.smt2 |    5.415s | 207.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_0.smt2 |    5.511s | 241.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter2_set_true-unreach-call_true-termination.c_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |    6.057s | 112.0MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_1.smt2 |    6.158s | 240.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0931_true-unreach-call.c_0.smt2 |    6.241s | 237.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/square_1_false-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |    6.891s | 81.32MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_4.smt2 |    6.956s | 358.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0470_true-unreach-call.c_8.smt2 |    6.958s | 200.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c_2.smt2 |    7.409s | 416.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0920b_true-unreach-call.c_1.smt2 |    7.439s | 246.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c_1.smt2 |    7.789s | 480.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_biNewton_pseudoconstant_true-unreach-call.c_4.smt2 |    8.049s | 410.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0920b_true-unreach-call.c_0.smt2 |    8.170s | 248.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sine_1_false-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |    8.364s | 110.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c.p+cfa-reducer.c_0.smt2 |    8.554s | 559.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_2_8_false-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |    8.918s | 393.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_1_7_false-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |    9.092s | 202.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0310_true-unreach-call.c_2.smt2 |    9.217s | 158.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_1_8_false-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |    9.571s | 203.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0684a_true-unreach-call.c_0.smt2 |    9.791s | 604.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Newton_pseudoconstant_true-unreach-call.c_2.smt2 |    9.798s | 410.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_1_5_false-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   10.121s | 203.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sine_2_false-unreach-call_true-termination.i_0.smt2 |   11.266s | 480.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_17.smt2 |   11.273s | 690.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_2.smt2 |   11.320s | 710.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sine_8_true-unreach-call_true-termination.i_0.smt2 |   11.976s | 481.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0550b_true-unreach-call.c_8.smt2 |   12.453s | 798.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0550b_true-unreach-call.c_4.smt2 |   12.888s | 797.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_poly_true-unreach-call_true-termination.c_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   14.095s | 98.34MiB| unsat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_3.smt2 |   15.267s | 491.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/Muller_Kahan_true-unreach-call.c_179.smt2 |   15.293s | 977.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Muller_Kahan_true-unreach-call_true-termination.c_2.smt2 |   15.385s | 953.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Muller_Kahan_true-unreach-call_true-termination.c_1.smt2 |   15.504s | 955.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/digits_while_true-unreach-call.i_1.smt2 |   15.520s | 244.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0530a_true-unreach-call.c_7.smt2 |   15.797s | 801.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sine_3_false-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   16.347s | 108.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0971_true-unreach-call.c_1.smt2 |   16.825s | 173.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0882_true-unreach-call.c_1.smt2 |   17.617s | 401.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0330a_true-unreach-call.c_8.smt2 |   18.125s | 179.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20230321-UltimateAutomizerSvcomp2023/Rump_double.c_0.smt2 |   19.437s | 2696.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0530a_true-unreach-call.c_3.smt2 |   19.936s | 797.0MiB| sat | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/square_8_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.029s | 84.876MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20230321-UltimateAutomizerSvcomp2023/filter2.c_0.smt2 |   20.034s | 237.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20230321-UltimateAutomizerSvcomp2023/filter2_reinit.c_0.smt2 |   20.038s | 239.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/square_6_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.051s | 82.5MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/sqrt_Householder_constant_true-unreach-call.c_4.smt2 |   20.057s | 473.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/square_5_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.058s | 84.788MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_2_5_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.061s | 391.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/square_4_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.062s | 84.876MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sine_4_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.063s | 109.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0490b_true-unreach-call.c_1.smt2 |   20.065s | 637.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sine_8_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.065s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20230321-UltimateAutomizerSvcomp2023/sqrt_Householder_constant.c.p+cfa-reducer.c_2.smt2 |   20.070s | 553.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sine_5_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.071s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_1_4_false-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.072s | 203.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0490a.c_2.smt2 |   20.074s | 641.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0490b.c_2.smt2 |   20.076s | 641.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0832_true-unreach-call.c_3.smt2 |   20.078s | 676.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/square_3_false-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.079s | 82.712MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_1_2_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.080s | 205.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sine_6_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.080s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/square_7_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.081s | 82.648MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Newton_pseudoconstant_true-unreach-call.c_0.smt2 |   20.083s | 344.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_2_4_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.084s | 386.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/square_2_false-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.084s | 83.552MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter2_set_true-unreach-call_true-termination.c_0.smt2 |   20.085s | 337.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_1_1_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.085s | 202.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sine_7_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.086s | 109.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_true-unreach-call.c_11.smt2 |   20.087s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_2_1_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.088s | 388.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_2_2_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.089s | 388.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_2_7_false-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.091s | 392.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_1_3_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.092s | 204.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0931_true-unreach-call.c_0.smt2 |   20.095s | 859.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_2_3_true-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.099s | 389.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0920b_true-unreach-call.c_0.smt2 |   20.100s | 865.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_set_true-unreach-call.c_11.smt2 |   20.103s | 305.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/newton_2_6_false-unreach-call_true-termination.i_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.112s | 391.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_interval_true-unreach-call.c_0.smt2 |   20.114s | 523.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/arctan_Pade_true-unreach-call_true-termination.c_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.116s | 540.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0520_true-unreach-call.c_6.smt2 |   20.121s | 763.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0970b_true-unreach-call.c_1.smt2 |   20.122s | 859.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/sqrt_Newton_pseudoconstant_true-unreach-call.c_4.smt2 |   20.122s | 291.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0260_true-unreach-call.c_2.smt2 |   20.125s | 472.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0970a_true-unreach-call.c_0.smt2 |   20.126s | 863.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/cos_polynomial_true-unreach-call_true-termination.c_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.126s | 602.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0960b_true-unreach-call.c_1.smt2 |   20.130s | 863.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0686b_true-unreach-call.c_0.smt2 |   20.130s | 417.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0530a_true-unreach-call.c_1.smt2 |   20.131s | 763.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0883_true-unreach-call.c_1.smt2 |   20.131s | 333.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_biNewton_pseudoconstant_true-unreach-call.c_0.smt2 |   20.132s | 770.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Muller_Kahan_true-unreach-call_true-termination.c_4.smt2 |   20.135s | 938.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_3.smt2 |   20.138s | 676.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/sqrt_Householder_interval_true-unreach-call.c_4.smt2 |   20.141s | 473.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/sqrt_Householder_constant_true-unreach-call.c_274.smt2 |   20.148s | 475.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/sqrt_biNewton_pseudoconstant_true-unreach-call.c_4.smt2 |   20.149s | 483.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Muller_Kahan_true-unreach-call_true-termination.c_0.smt2 |   20.151s | 941.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/Muller_Kahan_true-unreach-call.c_422.smt2 |   20.152s | 947.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/Muller_Kahan_true-unreach-call_true-termination.c_3.smt2 |   20.155s | 930.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0250a.c_4.smt2 |   20.162s | 646.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0490a_true-unreach-call.c_1.smt2 |   20.164s | 640.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/Muller_Kahan_true-unreach-call.c_446.smt2 |   20.166s | 947.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/Muller_Kahan_true-unreach-call.c_430.smt2 |   20.167s | 941.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/Muller_Kahan_true-unreach-call.c_68.smt2 |   20.168s | 941.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/Muller_Kahan_true-unreach-call.c_414.smt2 |   20.170s | 941.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/2019-Gudemann/refPred1.smt2       |   20.194s | 1886.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/water_pid_true-unreach-call.c_372.smt2 |   20.194s | 939.0MiB| timeout | 0 |  |  |
|non-incremental/QF_BVFPLRA/20170501-Heizmann-UltimateAutomizer/Muller_Kahan_true-unreach-call.c_315.smt2 |   20.197s | 947.0MiB| timeout | 0 |  |  |
