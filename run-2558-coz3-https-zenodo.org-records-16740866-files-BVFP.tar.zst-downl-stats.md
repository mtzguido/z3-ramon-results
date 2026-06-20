# .

* SAT 161
* UNSAT 11
* TIMEOUT 32
* UNKNOWN 4

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/BVFP.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-BVFP.tar.zst-downl
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/BVFP.tar.zst?download=1
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
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0620b_true-unreach-call.c_3.smt2 |    0.024s | 20.112MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_16.smt2 |    0.025s | 20.776MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0470_true-unreach-call.c_6.smt2 |    0.025s | 20.908MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_14.smt2 |    0.028s | 21.144MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_11.smt2 |    0.028s | 20.672MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0680a_true-unreach-call.c_3.smt2 |    0.029s | 21.004MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0320_true-unreach-call.c_3.smt2 |    0.029s | 21.164MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270b_true-unreach-call.c_9.smt2 |    0.030s | 21.356MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0662a_true-unreach-call.c_2.smt2 |    0.030s | 20.876MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_15.smt2 |    0.031s | 21.112MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0680a_true-unreach-call.c_2.smt2 |    0.031s | 20.916MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0661b_true-unreach-call.c_5.smt2 |    0.036s | 22.088MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0320_true-unreach-call.c_2.smt2 |    0.039s | 21.4MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0685a_true-unreach-call.c_5.smt2 |    0.041s | 21.22MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0680b_true-unreach-call.c_2.smt2 |    0.045s | 20.888MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0683a_true-unreach-call.c_2.smt2 |    0.046s | 21.236MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0832_true-unreach-call.c_7.smt2 |    0.046s | 20.14MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0661a_true-unreach-call.c_4.smt2 |    0.046s | 22.452MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0683a_true-unreach-call.c_1.smt2 |    0.047s | 20.924MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_25.smt2 |    0.047s | 21.096MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0662b_true-unreach-call.c_3.smt2 |    0.048s | 20.888MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0682a_true-unreach-call.c_3.smt2 |    0.048s | 21.384MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_17.smt2 |    0.048s | 20.868MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0620b_true-unreach-call.c_4.smt2 |    0.048s | 21.148MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_7.smt2 |    0.049s | 20.916MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_14.smt2 |    0.049s | 20.872MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_11.smt2 |    0.049s | 21.54MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_8.smt2 |    0.049s | 20.972MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0681a_true-unreach-call.c_4.smt2 |    0.049s | 21.128MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_1.smt2 |    0.049s | 21.324MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0530a_true-unreach-call.c_5.smt2 |    0.050s | 21.152MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_3.smt2 |    0.051s | 21.932MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_5.smt2 |    0.051s | 21.168MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_0.smt2 |    0.051s | 20.924MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1250_true-unreach-call.c_1.smt2 |    0.051s | 20.304MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0686a_true-unreach-call.c_4.smt2 |    0.051s | 20.904MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_3.smt2 |    0.052s | 20.94MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1130b_true-unreach-call.c_0.smt2 |    0.052s | 21.1MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0681a_true-unreach-call.c_5.smt2 |    0.052s | 20.884MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0682b_true-unreach-call.c_1.smt2 |    0.052s | 20.88MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_2.smt2 |    0.052s | 21.068MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0685a_true-unreach-call.c_7.smt2 |    0.053s | 21.148MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_13.smt2 |    0.053s | 20.876MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_6.smt2 |    0.053s | 20.872MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_9.smt2 |    0.053s | 21.404MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0682a_true-unreach-call.c_7.smt2 |    0.054s | 20.996MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_21.smt2 |    0.054s | 20.688MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0686a_true-unreach-call.c_5.smt2 |    0.055s | 21.012MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0620b_true-unreach-call.c_1.smt2 |    0.055s | 20.112MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_12.smt2 |    0.056s | 21.052MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_22.smt2 |    0.056s | 20.772MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_15.smt2 |    0.056s | 21.132MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_23.smt2 |    0.056s | 20.848MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0883_true-unreach-call.c_7.smt2 |    0.057s | 21.168MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0490a_true-unreach-call.c_4.smt2 |    0.057s | 20.596MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_4.smt2 |    0.058s | 21.14MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0682a_true-unreach-call.c_5.smt2 |    0.058s | 21.048MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_26.smt2 |    0.058s | 21.152MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_24.smt2 |    0.058s | 20.928MiB| sat | 0 |  |  |
|non-incremental/BVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0663a.c_7.smt2 |    0.058s | 21.656MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_2.smt2 |    0.060s | 20.388MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_13.smt2 |    0.060s | 21.016MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1271a_true-unreach-call.c_3.smt2 |    0.060s | 23.868MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0883_true-unreach-call.c_5.smt2 |    0.060s | 21.288MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0740_true-unreach-call.c_0.smt2 |    0.061s | 20.904MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0663b_true-unreach-call.c_2.smt2 |    0.061s | 21.14MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0661b_true-unreach-call.c_9.smt2 |    0.061s | 22.424MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0250b_true-unreach-call.c_5.smt2 |    0.063s | 20.108MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0260_true-unreach-call.c_4.smt2 |    0.063s | 20.372MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0460_true-unreach-call.c_4.smt2 |    0.063s | 20.604MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1032a_true-unreach-call.c_0.smt2 |    0.063s | 21.396MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0685a_true-unreach-call.c_8.smt2 |    0.064s | 20.884MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0661a_true-unreach-call.c_5.smt2 |    0.064s | 22.984MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1250_true-unreach-call.c_0.smt2 |    0.064s | 20.112MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0680b_true-unreach-call.c_1.smt2 |    0.064s | 21.1MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_17.smt2 |    0.064s | 20.804MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0680b_true-unreach-call.c_0.smt2 |    0.064s | 20.884MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0661b_true-unreach-call.c_12.smt2 |    0.064s | 22.06MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1271a_true-unreach-call.c_2.smt2 |    0.064s | 21.192MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1032c_true-unreach-call.c_0.smt2 |    0.065s | 20.128MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_7.smt2 |    0.065s | 21.264MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0490a_true-unreach-call.c_11.smt2 |    0.065s | 20.108MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0930_true-unreach-call.c_13.smt2 |    0.066s | 21.424MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0685a_true-unreach-call.c_6.smt2 |    0.066s | 20.868MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_17.smt2 |    0.067s | 21.26MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_14.smt2 |    0.067s | 20.912MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_2.smt2 |    0.067s | 21.244MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_19.smt2 |    0.067s | 21.076MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_5.smt2 |    0.068s | 21.16MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0460_true-unreach-call.c_6.smt2 |    0.068s | 20.608MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0661b_true-unreach-call.c_10.smt2 |    0.068s | 22.464MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_10.smt2 |    0.069s | 20.872MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_25.smt2 |    0.069s | 21.412MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0661b_true-unreach-call.c_8.smt2 |    0.069s | 22.46MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0663b_true-unreach-call.c_1.smt2 |    0.069s | 20.74MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_18.smt2 |    0.069s | 21.188MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_16.smt2 |    0.069s | 20.712MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0682a_true-unreach-call.c_9.smt2 |    0.070s | 21.004MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0661b_true-unreach-call.c_11.smt2 |    0.073s | 22.452MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270b_true-unreach-call.c_0.smt2 |    0.073s | 22.396MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0661b_true-unreach-call.c_6.smt2 |    0.076s | 22.572MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0661a_true-unreach-call.c_3.smt2 |    0.077s | 22.38MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0490a_true-unreach-call.c_7.smt2 |    0.077s | 20.968MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0490a_true-unreach-call.c_13.smt2 |    0.079s | 21.096MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_3.smt2 |    0.080s | 21.16MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0730b_true-unreach-call.c_2.smt2 |    0.081s | 20.72MiB| sat | 0 |  |  |
|non-incremental/BVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0663a.c_8.smt2 |    0.081s | 21.64MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0682a_true-unreach-call.c_11.smt2 |    0.082s | 21.0MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0661b_true-unreach-call.c_7.smt2 |    0.082s | 23.096MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0670_true-unreach-call.c_2.smt2 |    0.084s | 26.36MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0490a_true-unreach-call.c_6.smt2 |    0.086s | 20.448MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0530a_true-unreach-call.c_2.smt2 |    0.086s | 21.124MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0681a_true-unreach-call.c_1.smt2 |    0.086s | 21.272MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0670_true-unreach-call.c_1.smt2 |    0.088s | 21.512MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_5.smt2 |    0.088s | 20.372MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0250b_true-unreach-call.c_1.smt2 |    0.089s | 20.136MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_16.smt2 |    0.089s | 20.492MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_18.smt2 |    0.091s | 20.796MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_27.smt2 |    0.092s | 20.828MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_19.smt2 |    0.093s | 20.876MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0685a_true-unreach-call.c_3.smt2 |    0.094s | 20.912MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0681a_true-unreach-call.c_2.smt2 |    0.099s | 20.884MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0730b_true-unreach-call.c_1.smt2 |    0.100s | 20.884MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_12.smt2 |    0.103s | 20.8MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_9.smt2 |    0.104s | 20.66MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_10.smt2 |    0.105s | 21.064MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0682a_true-unreach-call.c_12.smt2 |    0.105s | 20.888MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1250_true-unreach-call.c_2.smt2 |    0.106s | 20.308MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0730b_true-unreach-call.c_20.smt2 |    0.107s | 20.76MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_3.smt2 |    0.107s | 21.092MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0530a_true-unreach-call.c_6.smt2 |    0.107s | 21.296MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0682a_true-unreach-call.c_8.smt2 |    0.109s | 20.924MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0685a_true-unreach-call.c_4.smt2 |    0.109s | 20.852MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0685a_true-unreach-call.c_1.smt2 |    0.109s | 20.916MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0680b_true-unreach-call.c_3.smt2 |    0.115s | 20.812MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1271a_true-unreach-call.c_4.smt2 |    0.117s | 23.4MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0661b_true-unreach-call.c_1.smt2 |    0.118s | 22.64MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0661b_true-unreach-call.c_4.smt2 |    0.119s | 22.912MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0310_true-unreach-call.c_6.smt2 |    0.132s | 28.384MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1271a_true-unreach-call.c_0.smt2 |    0.271s | 27.74MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0670_true-unreach-call.c_6.smt2 |    0.281s | 27.88MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0670_true-unreach-call.c_4.smt2 |    0.309s | 27.9MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0670_true-unreach-call.c_3.smt2 |    0.313s | 27.892MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270b_true-unreach-call.c_8.smt2 |    0.367s | 26.868MiB| unsat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_4.smt2 |    0.681s | 64.384MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0620b_true-unreach-call.c_2.smt2 |    1.200s | 66.192MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_7.smt2 |    1.347s | 36.904MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012b_true-unreach-call.c_1.smt2 |    1.370s | 37.98MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270c_true-unreach-call.c_0.smt2 |    1.427s | 41.176MiB| unsat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_14.smt2 |    1.483s | 38.092MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_8.smt2 |    1.496s | 36.852MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_10.smt2 |    1.504s | 36.964MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_21.smt2 |    1.535s | 37.328MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012b_true-unreach-call.c_0.smt2 |    1.546s | 36.824MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_9.smt2 |    1.574s | 36.676MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_13.smt2 |    1.638s | 39.112MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_6.smt2 |    1.640s | 38.604MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_1.smt2 |    1.645s | 38.764MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012b_true-unreach-call.c_3.smt2 |    1.662s | 38.744MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012b_true-unreach-call.c_2.smt2 |    1.695s | 38.192MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_18.smt2 |    1.742s | 38.436MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_3.smt2 |    1.774s | 39.692MiB| sat | 0 |  |  |
|non-incremental/BVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_1300.c_0.smt2 |    2.498s | 47.572MiB| unknown | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1121a_true-unreach-call.c_1.smt2 |    3.434s | 64.932MiB| sat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_2.smt2 |    3.733s | 62.872MiB| unknown | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270b_true-unreach-call.c_4.smt2 |    4.114s | 56.916MiB| unsat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270b_true-unreach-call.c_6.smt2 |    4.296s | 57.088MiB| unsat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270b_true-unreach-call.c_5.smt2 |    4.347s | 57.236MiB| unsat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270b_true-unreach-call.c_1.smt2 |    4.511s | 57.096MiB| unsat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_11.smt2 |    4.717s | 62.292MiB| unknown | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1012a_true-unreach-call.c_12.smt2 |    4.816s | 62.612MiB| unknown | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270c_true-unreach-call.c_1.smt2 |    7.264s | 84.28MiB| unsat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270c_true-unreach-call.c_3.smt2 |    7.956s | 84.288MiB| unsat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270b_true-unreach-call.c_2.smt2 |   10.561s | 97.024MiB| unsat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270b_true-unreach-call.c_3.smt2 |   11.029s | 96.808MiB| unsat | 0 |  |  |
|non-incremental/BVFP/20210301-Alive2/oggenc/412_oggenc.smt2  |   14.565s | 110.0MiB| unsat | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1271a_true-unreach-call.c_1.smt2 |   20.028s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270c_true-unreach-call.c_2.smt2 |   20.044s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20210301-Alive2/oggenc/374_oggenc.smt2  |   20.050s | 96.256MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0720_true-unreach-call.c_0.smt2 |   20.060s | 98.536MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1122a_true-unreach-call.c_1.smt2 |   20.078s | 291.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1122a_true-unreach-call.c_2.smt2 |   20.084s | 289.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0620a_true-unreach-call.c_7.smt2 |   20.087s | 167.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1122a_true-unreach-call.c_3.smt2 |   20.092s | 293.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20210301-Alive2/oggenc/390_oggenc.smt2  |   20.145s | 994.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20210301-Alive2/oggenc/301_oggenc.smt2  |   20.334s | 2652.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20210301-Alive2/oggenc/450_oggenc.smt2  |   20.452s | 2821.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1270b_true-unreach-call.c_7.smt2 |   20.548s | 3687.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0971_true-unreach-call.c_11.smt2 |   20.549s | 4487.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0971_true-unreach-call.c_9.smt2 |   20.568s | 3464.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0971_true-unreach-call.c_10.smt2 |   20.605s | 3462.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0971_true-unreach-call.c_7.smt2 |   20.641s | 4191.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1092a_true-unreach-call.c_11.smt2 |   20.726s | 4886.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1092a_true-unreach-call.c_10.smt2 |   20.726s | 5960.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_15.smt2 |   20.766s | 6026.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_13.smt2 |   20.767s | 5925.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_16.smt2 |   20.784s | 6377.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0971_true-unreach-call.c_8.smt2 |   20.788s | 6126.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0971_true-unreach-call.c_5.smt2 |   20.795s | 4331.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0971_true-unreach-call.c_6.smt2 |   20.813s | 4481.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_17.smt2 |   20.817s | 6497.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1092a_true-unreach-call.c_12.smt2 |   20.845s | 6500.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_18.smt2 |   20.871s | 5443.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_19.smt2 |   20.886s | 5374.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1052d_true-unreach-call.c_14.smt2 |   20.932s | 5704.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1092a_true-unreach-call.c_8.smt2 |   20.939s | 5933.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1092a_true-unreach-call.c_9.smt2 |   20.966s | 6428.0MiB| timeout | 0 |  |  |
|non-incremental/BVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1092a_true-unreach-call.c_13.smt2 |   21.006s | 6280.0MiB| timeout | 0 |  |  |
