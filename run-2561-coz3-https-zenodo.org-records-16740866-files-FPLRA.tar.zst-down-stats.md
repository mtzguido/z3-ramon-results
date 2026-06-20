# .

* SAT 24
* UNSAT 0
* TIMEOUT 17
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/FPLRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-FPLRA.tar.zst-down
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/FPLRA.tar.zst?download=1
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
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0683a_true-unreach-call.c_7.smt2 |    0.026s | 20.908MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_7.smt2 |    0.029s | 21.42MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_14.smt2 |    0.029s | 20.868MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_5.smt2 |    0.032s | 21.392MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_6.smt2 |    0.034s | 20.704MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0683a_true-unreach-call.c_3.smt2 |    0.073s | 24.312MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0683a_true-unreach-call.c_4.smt2 |    0.087s | 23.696MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_219.smt2 |    0.105s | 26.092MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/float-div1_true-unreach-call.i_574.smt2 |    0.143s | 37.044MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_1289.smt2 |    0.222s | 29.984MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_679.smt2 |    0.267s | 29.972MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_677.smt2 |    0.267s | 29.78MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_1310.smt2 |    0.277s | 30.24MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_12.smt2 |    0.281s | 30.08MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_1294.smt2 |    0.313s | 30.396MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0683a_true-unreach-call.c_6.smt2 |    0.405s | 28.928MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_1288.smt2 |    0.410s | 35.2MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/inv_square_true-unreach-call.c_139.smt2 |    0.452s | 33.648MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0683a_true-unreach-call.c_5.smt2 |    0.555s | 29.032MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_850.smt2 |    0.562s | 32.928MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0832a_true-unreach-call.c_2.smt2 |    2.032s | 44.188MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0832a_true-unreach-call.c_1.smt2 |    3.359s | 48.86MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1122a_true-unreach-call.c_3.smt2 |    4.033s | 131.0MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/water_pid_true-unreach-call_true-termination.c_2.smt2 |   10.318s | 85.464MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/inv_square_true-unreach-call.c_154.smt2 |   20.012s | 46.98MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call.c.v+nlh-reducer.c_0.smt2 |   20.017s | 88.556MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call.c.v+lhb-reducer.c_1.smt2 |   20.017s | 98.276MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call_true-termination.c_1.smt2 |   20.018s | 92.028MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call_true-termination.c_3.smt2 |   20.021s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/inv_square_true-unreach-call.c_110.smt2 |   20.023s | 55.4MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call.c.v+nlh-reducer.c_1.smt2 |   20.024s | 95.28MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/inv_square_true-unreach-call.c_72.smt2 |   20.025s | 48.988MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/water_pid_true-unreach-call_true-termination.c_3.smt2 |   20.026s | 176.0MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/inv_square_true-unreach-call.c_70.smt2 |   20.026s | 46.432MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/water_pid_true-unreach-call_true-termination.c_4.smt2 |   20.027s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/water_pid_true-unreach-call_true-termination.c_6.smt2 |   20.027s | 162.0MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call_true-termination.c_2.smt2 |   20.029s | 93.432MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call_true-termination.c_4.smt2 |   20.029s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/water_pid_true-unreach-call_true-termination.c_5.smt2 |   20.030s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/water_pid_true-unreach-call_true-termination.c_1.smt2 |   20.036s | 134.0MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1122a_true-unreach-call.c_0.smt2 |   20.046s | 293.0MiB| timeout | 0 |  |  |
