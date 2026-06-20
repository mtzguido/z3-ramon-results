# .

* SAT 71
* UNSAT 153
* TIMEOUT 33
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/NIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-NIA.tar.zst-downlo
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/NIA.tar.zst?download=1
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
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_87.smt2 |    0.028s | 20.888MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_32.smt2 |    0.029s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_38.smt2 |    0.030s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/NIA/tptp/NUM885=1.smt2                       |    0.030s | 20.108MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_75.smt2 |    0.031s | 21.132MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_43.smt2 |    0.031s | 20.992MiB| unsat | 0 |  |  |
|non-incremental/NIA/tptp/NUM878=1.smt2                       |    0.031s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_27.smt2 |    0.032s | 21.116MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_26.smt2 |    0.033s | 20.888MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_3.smt2 |    0.034s | 21.056MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_37.smt2 |    0.035s | 21.244MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_9.smt2 |    0.036s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_17.smt2 |    0.040s | 21.192MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_23.smt2 |    0.041s | 21.392MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_68.smt2 |    0.041s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_44.smt2 |    0.041s | 21.128MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_15.smt2 |    0.043s | 20.896MiB| unsat | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de62.c_AllErrorsAtOnce_Iteration8_0.smt2 |    0.043s | 21.092MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_61.smt2 |    0.045s | 21.568MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_1.smt2 |    0.046s | 20.664MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_48.smt2 |    0.047s | 21.36MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_86.smt2 |    0.047s | 21.076MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_62.smt2 |    0.048s | 21.62MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_10.smt2 |    0.048s | 20.896MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_3.smt2 |    0.050s | 21.108MiB| sat | 0 |  |  |
|non-incremental/NIA/tptp/NUM881=1.smt2                       |    0.051s | 19.484MiB| sat | 0 |  |  |
|non-incremental/NIA/tptp/NUM882=1.smt2                       |    0.053s | 19.868MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_1.smt2 |    0.054s | 21.388MiB| unsat | 0 |  |  |
|non-incremental/NIA/tptp/NUM880=1.smt2                       |    0.054s | 20.544MiB| sat | 0 |  |  |
|non-incremental/NIA/tptp/NUM886=1.smt2                       |    0.054s | 20.396MiB| sat | 0 |  |  |
|non-incremental/NIA/tptp/NUM879=1.smt2                       |    0.055s | 20.104MiB| sat | 0 |  |  |
|non-incremental/NIA/tptp/ARI118=1.smt2                       |    0.056s | 20.812MiB| unsat | 0 |  |  |
|non-incremental/NIA/tptp/ARI123=1.smt2                       |    0.056s | 20.908MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_1.smt2 |    0.057s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_89.smt2 |    0.057s | 21.128MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_84.smt2 |    0.058s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_18.smt2 |    0.058s | 21.12MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_6.smt2 |    0.059s | 21.5MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_29.smt2 |    0.060s | 20.896MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_95.smt2 |    0.060s | 21.64MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_34.smt2 |    0.060s | 20.888MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_5.smt2 |    0.061s | 21.18MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_13.smt2 |    0.062s | 20.904MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/implicitunsignedconversion_true-unreach-call_true-termination.c_0.smt2 |    0.062s | 20.84MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_36.smt2 |    0.062s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/sum02_false-unreach-call_true-no-overflow.c_0.smt2 |    0.062s | 20.54MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_25.smt2 |    0.063s | 21.108MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_58.smt2 |    0.063s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_92.smt2 |    0.064s | 21.136MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_11.smt2 |    0.064s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_2.smt2 |    0.065s | 21.196MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_1.smt2 |    0.065s | 20.868MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_7.smt2 |    0.066s | 20.876MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_16.smt2 |    0.066s | 20.676MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_10.smt2 |    0.066s | 21.372MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_2.smt2 |    0.067s | 21.22MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_94.smt2 |    0.068s | 21.128MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_11.smt2 |    0.068s | 20.756MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_2.smt2 |    0.069s | 21.344MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_20.smt2 |    0.070s | 21.028MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_5.smt2 |    0.070s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_81.smt2 |    0.070s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_22.smt2 |    0.071s | 20.94MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_13.smt2 |    0.071s | 20.876MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_0.smt2 |    0.071s | 20.864MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_7.smt2 |    0.072s | 21.092MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_18.smt2 |    0.072s | 21.132MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_28.smt2 |    0.072s | 21.004MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_39.smt2 |    0.073s | 21.34MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_0.smt2 |    0.073s | 21.088MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_76.smt2 |    0.073s | 21.648MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_16.smt2 |    0.074s | 20.964MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_5.smt2 |    0.074s | 21.168MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_31.smt2 |    0.074s | 21.116MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_5.smt2 |    0.074s | 20.796MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_59.smt2 |    0.074s | 21.764MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gauss_sum.i_0.smt2 |    0.074s | 21.396MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_93.smt2 |    0.075s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_3_true-unreach-call_true-no-overflow.i_1.smt2 |    0.075s | 20.86MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/sum02_false-unreach-call_true-no-overflow.c_1.smt2 |    0.075s | 20.536MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_0.smt2 |    0.076s | 20.768MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/ps4-ll.c_1.smt2 |    0.076s | 21.176MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_12.smt2 |    0.077s | 21.192MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_7.smt2 |    0.077s | 21.46MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_19.smt2 |    0.078s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_9.smt2 |    0.078s | 21.012MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_10.smt2 |    0.078s | 21.012MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_3.smt2 |    0.079s | 21.148MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_1.smt2 |    0.079s | 20.832MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_42.smt2 |    0.079s | 21.14MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_0.smt2 |    0.080s | 21.168MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_41.smt2 |    0.080s | 20.968MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_11.smt2 |    0.080s | 21.152MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_11.smt2 |    0.080s | 20.656MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_24.smt2 |    0.081s | 21.036MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_49.smt2 |    0.081s | 20.932MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_9.smt2 |    0.081s | 20.924MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_13.smt2 |    0.081s | 21.448MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_18.smt2 |    0.081s | 21.236MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_4.smt2 |    0.083s | 20.988MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_8.smt2 |    0.083s | 21.156MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_63.smt2 |    0.083s | 21.14MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_80.smt2 |    0.083s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_8.smt2 |    0.083s | 21.248MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/pals_lcr-var-start-time.6_true-unreach-call.ufo.UNBOUNDED.pals.c_1.smt2 |    0.083s | 21.144MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_8.smt2 |    0.083s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_3.smt2 |    0.084s | 20.652MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_23.smt2 |    0.084s | 20.908MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_77.smt2 |    0.084s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_6.smt2 |    0.085s | 21.152MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_12.smt2 |    0.085s | 20.76MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_2.smt2 |    0.085s | 20.848MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_7.smt2 |    0.085s | 21.08MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_3.smt2 |    0.087s | 21.232MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_0.smt2 |    0.087s | 20.792MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_3_true-unreach-call_true-no-overflow.i_2.smt2 |    0.088s | 20.904MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_45.smt2 |    0.088s | 20.932MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_21.smt2 |    0.088s | 21.472MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_4.smt2 |    0.089s | 21.728MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_65.smt2 |    0.090s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_72.smt2 |    0.090s | 22.392MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_67.smt2 |    0.091s | 20.908MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_11.smt2 |    0.091s | 21.136MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_97.smt2 |    0.092s | 22.052MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_85.smt2 |    0.095s | 20.78MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_69.smt2 |    0.096s | 20.908MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_40.smt2 |    0.097s | 21.132MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_4.smt2 |    0.098s | 21.444MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_60.smt2 |    0.098s | 21.248MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_64.smt2 |    0.100s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_4.smt2 |    0.100s | 20.948MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_25.smt2 |    0.102s | 21.168MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_6.smt2 |    0.102s | 21.184MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_88.smt2 |    0.103s | 20.812MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_35.smt2 |    0.103s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_10.smt2 |    0.104s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_21.smt2 |    0.105s | 21.004MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_0.smt2 |    0.105s | 20.992MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_7.smt2 |    0.106s | 21.256MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_2_true-unreach-call_true-no-overflow.i_0.smt2 |    0.106s | 21.804MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_33.smt2 |    0.107s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_13.smt2 |    0.109s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_73.smt2 |    0.110s | 21.112MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_91.smt2 |    0.111s | 21.232MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_12.smt2 |    0.113s | 20.912MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_19.smt2 |    0.114s | 20.716MiB| sat | 0 |  |  |
|non-incremental/NIA/psyco/182.smt2                           |    0.114s | 21.124MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_14.smt2 |    0.115s | 21.12MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_2.smt2 |    0.115s | 21.456MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/egcd2-ll.c_2.smt2 |    0.115s | 21.18MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_46.smt2 |    0.116s | 21.196MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_66.smt2 |    0.117s | 21.12MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_6.smt2 |    0.117s | 20.816MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_74.smt2 |    0.117s | 21.156MiB| sat | 0 |  |  |
|non-incremental/NIA/psyco/060.smt2                           |    0.118s | 21.132MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_78.smt2 |    0.119s | 21.096MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_9.smt2 |    0.119s | 20.976MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_55.smt2 |    0.120s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_70.smt2 |    0.120s | 22.192MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_9.smt2 |    0.120s | 21.528MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_24.smt2 |    0.120s | 20.876MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_79.smt2 |    0.121s | 21.176MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_4.smt2 |    0.121s | 21.384MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_30.smt2 |    0.121s | 21.472MiB| unsat | 0 |  |  |
|non-incremental/NIA/psyco/183.smt2                           |    0.121s | 21.928MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_22.smt2 |    0.122s | 21.684MiB| unsat | 0 |  |  |
|non-incremental/NIA/psyco/059.smt2                           |    0.124s | 20.884MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_71.smt2 |    0.126s | 22.152MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_82.smt2 |    0.132s | 21.72MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_83.smt2 |    0.132s | 21.832MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_2.smt2 |    0.134s | 21.616MiB| unsat | 0 |  |  |
|non-incremental/NIA/psyco/184.smt2                           |    0.137s | 21.644MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_90.smt2 |    0.139s | 22.032MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_7.smt2 |    0.141s | 21.124MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_15.smt2 |    0.142s | 22.088MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_12.smt2 |    0.155s | 22.928MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_3_true-unreach-call_true-no-overflow.i_0.smt2 |    0.160s | 21.932MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_17.smt2 |    0.163s | 22.484MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_0.smt2 |    0.177s | 21.728MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_13.smt2 |    0.184s | 22.916MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_8.smt2 |    0.192s | 21.808MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_18.smt2 |    0.218s | 22.448MiB| unsat | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de51.c_AllErrorsAtOnce_Iteration8_0.smt2 |    0.230s | 22.02MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_6-1.c_0.smt2 |    0.279s | 22.148MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_18.smt2 |    0.366s | 22.156MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_1.smt2 |    0.387s | 21.66MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_6-1.c_2.smt2 |    0.395s | 22.148MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_3.smt2 |    0.402s | 22.296MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_4-2.c_0.smt2 |    0.425s | 22.676MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_14.smt2 |    0.427s | 23.132MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_98.smt2 |    0.527s | 22.928MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_16.smt2 |    0.580s | 22.192MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_6.smt2 |    0.758s | 22.2MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_16.smt2 |    0.797s | 22.924MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_20.smt2 |    0.799s | 23.02MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_96.smt2 |    1.134s | 23.176MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_8.smt2 |    1.536s | 23.54MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_2.smt2 |    1.834s | 23.22MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_10.smt2 |    1.925s | 23.272MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_15.smt2 |    2.241s | 25.652MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_1.smt2 |    2.783s | 30.424MiB| sat | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/gsv2008.c.i.v+lhb-reducer.c_AllErrorsAtOnce_Iteration2_0.smt2 |    3.339s | 78.856MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_14.smt2 |    5.727s | 52.6MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_17.smt2 |    5.730s | 52.564MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_9.smt2 |    5.847s | 52.568MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_15.smt2 |    5.851s | 52.408MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_10.smt2 |    5.855s | 52.532MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_7.smt2 |    5.886s | 52.58MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_16.smt2 |    6.034s | 52.508MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_8.smt2 |    6.139s | 52.44MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_11.smt2 |    6.179s | 52.752MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_12.smt2 |    6.358s | 52.808MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_13.smt2 |    6.431s | 53.048MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_2.smt2 |    6.710s | 54.2MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_5.smt2 |    6.750s | 54.492MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_11.smt2 |    6.852s | 28.272MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_1.smt2 |    6.866s | 32.864MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_3.smt2 |    6.877s | 54.284MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_6.smt2 |    7.531s | 53.788MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_4.smt2 |    7.946s | 54.768MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_0.smt2 |   15.110s | 38.608MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_1.smt2 |   17.760s | 37.308MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_17.smt2 |   17.819s | 30.788MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_0.smt2 |   17.909s | 53.344MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_6.smt2 |   20.023s | 50.584MiB| timeout | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/gsv2008.c.i.p+cfa-reducer.c_AllErrorsAtOnce_Iteration2_0.smt2 |   20.024s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_16.smt2 |   20.041s | 42.804MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_3.smt2 |   20.042s | 31.06MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_5.smt2 |   20.046s | 70.684MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_5.smt2 |   20.052s | 45.236MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_13.smt2 |   20.053s | 34.9MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_7.smt2 |   20.054s | 33.984MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_10.smt2 |   20.055s | 149.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_4.smt2 |   20.056s | 36.948MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_14.smt2 |   20.057s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_3.smt2 |   20.075s | 25.052MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_11.smt2 |   20.079s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_8.smt2 |   20.079s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/egcd2-ll.c_0.smt2 |   20.081s | 41.844MiB| timeout | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de41.c_AllErrorsAtOnce_Iteration5_0.smt2 |   20.083s | 37.472MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_2.smt2 |   20.091s | 55.48MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_12.smt2 |   20.092s | 96.784MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_6.smt2 |   20.097s | 66.56MiB| timeout | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de61.c_AllErrorsAtOnce_Iteration6_0.smt2 |   20.097s | 42.084MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_1.smt2 |   20.098s | 51.244MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_0.smt2 |   20.099s | 22.3MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/egcd2-ll.c_1.smt2 |   20.100s | 42.896MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_9.smt2 |   20.101s | 125.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_0.smt2 |   20.108s | 89.452MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_17.smt2 |   20.112s | 128.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_3.smt2 |   20.267s | 1760.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_0.smt2 |   20.289s | 2241.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_1.smt2 |   20.299s | 2273.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_8.smt2 |   20.410s | 3748.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_1.smt2 |   20.518s | 4960.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_0.smt2 |   20.526s | 4855.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_2.smt2 |   20.714s | 6663.0MiB| timeout | 0 |  |  |
