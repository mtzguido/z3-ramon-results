# .

* SAT 204
* UNSAT 13
* TIMEOUT 48
* UNKNOWN 1

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/BVFPLRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-BVFPLRA.tar.zst-do
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/BVFPLRA.tar.zst?download=1
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
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0460_true-unreach-call.c_5.smt2 |    0.027s | 20.376MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_1.smt2 |    0.029s | 20.896MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0960a_true-unreach-call.c_2.smt2 |    0.030s | 21.328MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_10.smt2 |    0.032s | 21.12MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float-rounding1_true-unreach-call.i_0.smt2 |    0.034s | 21.432MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0530a_true-unreach-call.c_8.smt2 |    0.038s | 21.396MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_17.smt2 |    0.044s | 21.392MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0870b_true-unreach-call.c_2.smt2 |    0.044s | 20.884MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_0.smt2 |    0.045s | 20.88MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_26.smt2 |    0.052s | 21.3MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0930_true-unreach-call.c_2.smt2 |    0.054s | 21.0MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0960a_true-unreach-call.c_4.smt2 |    0.056s | 21.16MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_27.smt2 |    0.058s | 20.736MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1092a_true-unreach-call.c_4.smt2 |    0.059s | 20.876MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0620a_true-unreach-call.c_5.smt2 |    0.060s | 20.348MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0920b_true-unreach-call.c_2.smt2 |    0.062s | 21.264MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0920b_true-unreach-call.c_3.smt2 |    0.064s | 21.192MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_8.smt2 |    0.066s | 21.024MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_9.smt2 |    0.067s | 21.176MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_6.smt2 |    0.070s | 21.132MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_15.smt2 |    0.071s | 21.224MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_5.smt2 |    0.072s | 20.672MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_19.smt2 |    0.072s | 21.464MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_5.smt2 |    0.072s | 20.868MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0832b_true-unreach-call.c_0.smt2 |    0.073s | 21.352MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0920b_true-unreach-call.c_4.smt2 |    0.073s | 20.34MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0686a_true-unreach-call.c_2.smt2 |    0.074s | 20.72MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1092a_true-unreach-call.c_2.smt2 |    0.075s | 21.1MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_10.smt2 |    0.076s | 21.48MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0470_true-unreach-call.c_14.smt2 |    0.077s | 21.436MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_16.smt2 |    0.078s | 21.404MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0910a_true-unreach-call.c_5.smt2 |    0.080s | 20.9MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_6.smt2 |    0.080s | 20.976MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0682a_true-unreach-call.c_2.smt2 |    0.082s | 20.964MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0883_true-unreach-call.c_8.smt2 |    0.082s | 20.62MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0883_true-unreach-call.c_7.smt2 |    0.084s | 20.404MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_5.smt2 |    0.085s | 20.928MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_20.smt2 |    0.086s | 21.848MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0920b_true-unreach-call.c_4.smt2 |    0.087s | 21.132MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0250a_true-unreach-call.c_5.smt2 |    0.088s | 20.432MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0960a_true-unreach-call.c_7.smt2 |    0.088s | 21.12MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1092a_true-unreach-call.c_0.smt2 |    0.090s | 21.056MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1092a_true-unreach-call.c_6.smt2 |    0.092s | 21.116MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_2.smt2 |    0.092s | 20.14MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0250a_true-unreach-call.c_4.smt2 |    0.093s | 20.408MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1092a_true-unreach-call.c_5.smt2 |    0.095s | 21.228MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_2.smt2 |    0.096s | 20.876MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_8.smt2 |    0.096s | 21.732MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_3.smt2 |    0.096s | 20.4MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_21.smt2 |    0.097s | 20.616MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0686a_true-unreach-call.c_3.smt2 |    0.097s | 20.868MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_3.smt2 |    0.098s | 20.88MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_11.smt2 |    0.098s | 21.452MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_2.smt2 |    0.099s | 20.984MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0910a_true-unreach-call.c_4.smt2 |    0.099s | 20.836MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0883_true-unreach-call.c_8.smt2 |    0.099s | 20.632MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0960a_true-unreach-call.c_5.smt2 |    0.100s | 21.136MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0910a_true-unreach-call.c_10.smt2 |    0.101s | 21.396MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0910a_true-unreach-call.c_2.smt2 |    0.102s | 21.26MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_6.smt2 |    0.102s | 21.136MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_12.smt2 |    0.102s | 21.012MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270b_true-unreach-call.c_10.smt2 |    0.103s | 23.736MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1092a_true-unreach-call.c_3.smt2 |    0.105s | 20.872MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0685a_true-unreach-call.c_10.smt2 |    0.105s | 20.672MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0910a_true-unreach-call.c_11.smt2 |    0.105s | 20.4MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0931_true-unreach-call.c_4.smt2 |    0.106s | 20.352MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_8.smt2 |    0.106s | 20.868MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0470_true-unreach-call.c_4.smt2 |    0.106s | 20.876MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0685a_true-unreach-call.c_2.smt2 |    0.107s | 20.88MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0686a_true-unreach-call.c_6.smt2 |    0.108s | 20.868MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0883_true-unreach-call.c_3.smt2 |    0.108s | 20.468MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0470_true-unreach-call.c_3.smt2 |    0.108s | 20.888MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_8.smt2 |    0.108s | 21.376MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0910a_true-unreach-call.c_8.smt2 |    0.108s | 21.136MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0910a_true-unreach-call.c_7.smt2 |    0.108s | 20.36MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_9.smt2 |    0.109s | 21.108MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_10.smt2 |    0.110s | 21.208MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_5.smt2 |    0.111s | 21.02MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_16.smt2 |    0.111s | 20.976MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_4.smt2 |    0.112s | 21.136MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0490a_true-unreach-call.c_2.smt2 |    0.112s | 20.836MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_20.smt2 |    0.113s | 20.72MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0910a_true-unreach-call.c_3.smt2 |    0.113s | 20.876MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_25.smt2 |    0.113s | 20.656MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_9.smt2 |    0.114s | 21.44MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0931_true-unreach-call.c_1.smt2 |    0.114s | 22.692MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_5.smt2 |    0.114s | 21.032MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_6.smt2 |    0.114s | 21.12MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_9.smt2 |    0.114s | 20.452MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_10.smt2 |    0.114s | 21.516MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_18.smt2 |    0.115s | 21.176MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_17.smt2 |    0.115s | 20.98MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0910a_true-unreach-call.c_1.smt2 |    0.115s | 20.42MiB| unsat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_11.smt2 |    0.116s | 21.136MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_6.smt2 |    0.116s | 21.168MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0490a_true-unreach-call.c_5.smt2 |    0.116s | 20.424MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_7.smt2 |    0.117s | 20.912MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0832a_true-unreach-call.c_0.smt2 |    0.117s | 20.748MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_18.smt2 |    0.117s | 21.132MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_10.smt2 |    0.117s | 20.328MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0490a_true-unreach-call.c_7.smt2 |    0.117s | 20.408MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_12.smt2 |    0.117s | 21.076MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0832_true-unreach-call.c_8.smt2 |    0.117s | 21.492MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_4.smt2 |    0.117s | 20.872MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0460_true-unreach-call.c_7.smt2 |    0.118s | 20.312MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_5.smt2 |    0.118s | 20.36MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_2.smt2 |    0.118s | 20.992MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_4.smt2 |    0.118s | 20.388MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_18.smt2 |    0.118s | 21.3MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_4.smt2 |    0.118s | 20.896MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_2.smt2 |    0.118s | 20.848MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_11.smt2 |    0.118s | 21.168MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0490a_true-unreach-call.c_12.smt2 |    0.119s | 20.924MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_14.smt2 |    0.119s | 21.152MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0530b_true-unreach-call.c_3.smt2 |    0.119s | 21.008MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_19.smt2 |    0.119s | 21.62MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_20.smt2 |    0.120s | 21.12MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0960a_true-unreach-call.c_3.smt2 |    0.120s | 21.132MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0960a_true-unreach-call.c_1.smt2 |    0.120s | 20.936MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_12.smt2 |    0.120s | 21.64MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_8.smt2 |    0.120s | 20.86MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0910a_true-unreach-call.c_9.smt2 |    0.120s | 21.204MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0960a_true-unreach-call.c_6.smt2 |    0.120s | 20.624MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_7.smt2 |    0.120s | 23.736MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0920b_true-unreach-call.c_5.smt2 |    0.121s | 21.428MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0883_true-unreach-call.c_6.smt2 |    0.121s | 20.976MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1092a_true-unreach-call.c_7.smt2 |    0.121s | 21.088MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_24.smt2 |    0.121s | 21.04MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_17.smt2 |    0.122s | 21.136MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_16.smt2 |    0.122s | 21.16MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_7.smt2 |    0.123s | 20.768MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float-rounding1_true-unreach-call.i_1.smt2 |    0.123s | 21.372MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_20.smt2 |    0.125s | 21.452MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_16.smt2 |    0.125s | 21.384MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0260_true-unreach-call.c_6.smt2 |    0.126s | 20.616MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0931_true-unreach-call.c_2.smt2 |    0.126s | 24.26MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_7.smt2 |    0.127s | 21.388MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_20.smt2 |    0.129s | 21.428MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0910a_true-unreach-call.c_6.smt2 |    0.129s | 21.116MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1092a_true-unreach-call.c_1.smt2 |    0.130s | 20.924MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_21.smt2 |    0.131s | 21.648MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/filter1_true-unreach-call.c_348.smt2 |    0.131s | 27.34MiB| unsat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/filter1_true-unreach-call.c_344.smt2 |    0.132s | 27.18MiB| unsat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0920b_true-unreach-call.c_2.smt2 |    0.134s | 21.056MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1052b_true-unreach-call.c_0.smt2 |    0.135s | 25.232MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1052b_true-unreach-call.c_1.smt2 |    0.149s | 25.288MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0931_true-unreach-call.c_3.smt2 |    0.195s | 27.372MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float-rounding1_true-unreach-call.i_3.smt2 |    0.232s | 27.968MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_960.smt2 |    0.294s | 27.176MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1091_true-unreach-call.c_0.smt2 |    0.357s | 28.368MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1051_true-unreach-call.c_0.smt2 |    0.360s | 28.392MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float-rounding1_true-unreach-call.i_2.smt2 |    0.368s | 29.476MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0670_true-unreach-call.c_7.smt2 |    0.375s | 27.904MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_13.smt2 |    0.424s | 30.3MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_1063.smt2 |    0.615s | 29.06MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/inv_square_true-unreach-call.c_87.smt2 |    0.685s | 27.928MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/inv_square_true-unreach-call.c_79.smt2 |    0.715s | 27.936MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_1699.smt2 |    0.900s | 27.64MiB| unsat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_1466.smt2 |    0.982s | 30.176MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_1098.smt2 |    1.389s | 31.844MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_1100.smt2 |    1.403s | 31.92MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_1081.smt2 |    1.413s | 38.852MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_1000.smt2 |    1.478s | 29.092MiB| unsat | 0 |  |  |
|non-incremental/BVFPLRA/20230321-UltimateAutomizerSvcomp2023/filter1.c.p+cfa-reducer.c_3.smt2 |    1.542s | 31.648MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/float20_true-unreach-call.i_54.smt2 |    1.582s | 42.66MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20230321-UltimateAutomizerSvcomp2023/filter1.c_7.smt2 |    1.591s | 31.672MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_1457.smt2 |    1.642s | 30.508MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0530b_true-unreach-call.c_4.smt2 |    1.775s | 37.432MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_877.smt2 |    1.797s | 30.68MiB| unsat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_1104.smt2 |    2.110s | 37.232MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/filter1_true-unreach-call.c_281.smt2 |    2.154s | 31.648MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20230321-UltimateAutomizerSvcomp2023/filter1.c.p+cfa-reducer.c_5.smt2 |    2.205s | 31.628MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012b_true-unreach-call.c_5.smt2 |    2.238s | 37.372MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_0.smt2 |    2.241s | 37.184MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_875.smt2 |    2.249s | 30.636MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_1768.smt2 |    2.271s | 31.788MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_5.smt2 |    2.306s | 37.368MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_4.smt2 |    2.384s | 37.544MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_20.smt2 |    2.539s | 37.436MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_tight_true-unreach-call.c_113.smt2 |    2.721s | 66.936MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_1067.smt2 |    3.228s | 38.132MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_159.smt2 |    3.944s | 152.0MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/float-div1_true-unreach-call.i_366.smt2 |    4.007s | 97.356MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/bary_diverge_true-unreach-call.c_2067.smt2 |    4.286s | 37.46MiB| unsat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/bary_diverge_true-unreach-call.c_2065.smt2 |    4.363s | 37.424MiB| unsat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_964.smt2 |    4.443s | 34.34MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20230321-UltimateAutomizerSvcomp2023/loop3.c_9.smt2 |    5.040s | 69.332MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_tight_true-unreach-call.c_38.smt2 |    5.226s | 99.0MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/bary_diverge_true-unreach-call.c_1264.smt2 |    5.552s | 39.884MiB| unsat | 0 |  |  |
|non-incremental/BVFPLRA/20230321-UltimateAutomizerSvcomp2023/filter1.c.p+cfa-reducer.c_4.smt2 |    6.396s | 38.816MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_8.smt2 |    6.643s | 41.744MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_1697.smt2 |    6.772s | 46.5MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/filter1_true-unreach-call.c_342.smt2 |    7.067s | 52.808MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20230321-UltimateAutomizerSvcomp2023/filter1.c_8.smt2 |    7.299s | 53.512MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/rlim_invariant_true-unreach-call.c_1073.smt2 |    7.383s | 60.78MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/bary_diverge_true-unreach-call_true-termination.c_2.smt2 |    7.728s | 38.416MiB| unsat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_158.smt2 |    7.775s | 102.0MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sin_interpolated_smallrange_true-unreach-call.c_0.smt2 |    7.945s | 68.328MiB| unknown | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/bary_diverge_true-unreach-call.c_2063.smt2 |    8.674s | 45.008MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20230321-UltimateAutomizerSvcomp2023/filter1.c_9.smt2 |    8.730s | 54.112MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/filter1_true-unreach-call.c_352.smt2 |    8.740s | 56.128MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/float-div1_true-unreach-call.i_365.smt2 |    9.139s | 77.708MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/bary_diverge_true-unreach-call.c_3021.smt2 |    9.489s | 63.468MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_40.smt2 |   10.599s | 100.0MiB| unsat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/bary_diverge_true-unreach-call.c_3038.smt2 |   11.001s | 61.916MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/bary_diverge_true-unreach-call.c_3028.smt2 |   11.870s | 61.44MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_tight_true-unreach-call.c_37.smt2 |   11.927s | 102.0MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/bary_diverge_true-unreach-call.c_3026.smt2 |   11.991s | 79.612MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_tight_true-unreach-call.c_39.smt2 |   12.403s | 103.0MiB| unsat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/bary_diverge_true-unreach-call.c_3022.smt2 |   12.745s | 72.472MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_38.smt2 |   13.392s | 105.0MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/bary_diverge_true-unreach-call.c_3029.smt2 |   14.044s | 70.82MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/float-div1_true-unreach-call.i_563.smt2 |   15.799s | 77.652MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/float-div1_true-unreach-call.i_367.smt2 |   16.259s | 76.392MiB| unsat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/bary_diverge_true-unreach-call.c_3025.smt2 |   16.523s | 89.764MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/bary_diverge_true-unreach-call.c_3024.smt2 |   16.862s | 78.08MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/bary_diverge_true-unreach-call_true-termination.c_0.smt2 |   17.432s | 89.104MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/bary_diverge_true-unreach-call_true-termination.c_1.smt2 |   18.722s | 80.732MiB| sat | 0 |  |  |
|non-incremental/BVFPLRA/20230321-UltimateAutomizerSvcomp2023/filter1.c_6.smt2 |   20.019s | 57.372MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call.c.v+nlh-reducer.c_6.smt2 |   20.025s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call.c.v+nlh-reducer.c_4.smt2 |   20.026s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/trunc_nondet_2_true-unreach-call.i_3.smt2 |   20.030s | 45.608MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sin_interpolated_smallrange_true-unreach-call.c_4.smt2 |   20.033s | 88.276MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/trunc_nondet_2_true-unreach-call.i_6.smt2 |   20.035s | 47.692MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20230321-UltimateAutomizerSvcomp2023/filter1.c.p+cfa-reducer.c_1.smt2 |   20.040s | 57.408MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20230321-UltimateAutomizerSvcomp2023/filter1.c_2.smt2 |   20.041s | 59.216MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20230321-UltimateAutomizerSvcomp2023/filter1.c.p+cfa-reducer.c_2.smt2 |   20.042s | 57.272MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/trunc_nondet_2_true-unreach-call.i_5.smt2 |   20.049s | 52.2MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call.c.v+nlh-reducer.c_2.smt2 |   20.054s | 109.0MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/filter1_true-unreach-call.c_175.smt2 |   20.064s | 57.588MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call_true-termination.c_5.smt2 |   20.066s | 85.116MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_36.smt2 |   20.070s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0620a_true-unreach-call.c_4.smt2 |   20.075s | 295.0MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/filter1_true-unreach-call.c_182.smt2 |   20.075s | 57.536MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_117.smt2 |   20.078s | 75.868MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_114.smt2 |   20.079s | 73.512MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_115.smt2 |   20.080s | 72.196MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/bary_diverge_true-unreach-call.c_3023.smt2 |   20.080s | 79.096MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_156.smt2 |   20.080s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_tight_true-unreach-call.c_116.smt2 |   20.082s | 72.416MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_112.smt2 |   20.084s | 75.376MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_161.smt2 |   20.084s | 72.472MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_tight_true-unreach-call.c_114.smt2 |   20.084s | 73.616MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_39.smt2 |   20.084s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sin_interpolated_smallrange_true-unreach-call.c_5.smt2 |   20.086s | 87.22MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/trunc_nondet_2_true-unreach-call.i_12.smt2 |   20.086s | 55.928MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/trunc_nondet_2_true-unreach-call.i_10.smt2 |   20.086s | 52.596MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_tight_true-unreach-call.c_115.smt2 |   20.086s | 73.436MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_tight_true-unreach-call.c_41.smt2 |   20.086s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_160.smt2 |   20.086s | 104.0MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_41.smt2 |   20.089s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sin_interpolated_smallrange_true-unreach-call.c_3.smt2 |   20.090s | 74.724MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/bary_diverge_true-unreach-call.c_3027.smt2 |   20.090s | 69.04MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sin_interpolated_smallrange_true-unreach-call.c_1.smt2 |   20.091s | 66.552MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_loose_true-unreach-call.c_157.smt2 |   20.091s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_tight_true-unreach-call.c_117.smt2 |   20.094s | 74.52MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/sin_interpolated_smallrange_true-unreach-call.c_2.smt2 |   20.095s | 66.78MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20170501-Heizmann-UltimateAutomizer/zonotope_tight_true-unreach-call.c_135.smt2 |   20.095s | 68.712MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call.c.v+nlh-reducer.c_3.smt2 |   20.098s | 94.668MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call.c.v+nlh-reducer.c_5.smt2 |   20.099s | 95.84MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call_true-termination.c_0.smt2 |   20.099s | 92.944MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call.c.v+lhb-reducer.c_0.smt2 |   20.108s | 87.972MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0620a_true-unreach-call.c_6.smt2 |   20.115s | 300.0MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_26.smt2 |   20.523s | 4407.0MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_22.smt2 |   20.528s | 4491.0MiB| timeout | 0 |  |  |
|non-incremental/BVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_23.smt2 |   20.623s | 5071.0MiB| timeout | 0 |  |  |
