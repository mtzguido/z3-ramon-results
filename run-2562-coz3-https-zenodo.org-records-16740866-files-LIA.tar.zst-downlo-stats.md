# .

* SAT 164
* UNSAT 265
* TIMEOUT 106
* UNKNOWN 1

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/LIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-LIA.tar.zst-downlo
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/LIA.tar.zst?download=1
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
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_557.smt2 |    0.021s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_527.smt2 |    0.025s | 19.636MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI031=1.smt2                       |    0.025s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI056=1.smt2                       |    0.025s | 19.924MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_817.smt2 |    0.026s | 20.656MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI572=1.smt2                       |    0.026s | 20.672MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/NUM871=1.smt2                       |    0.026s | 19.608MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_788.smt2 |    0.027s | 19.568MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_574.smt2 |    0.027s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_798.smt2 |    0.027s | 19.688MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1785.smt2 |    0.027s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI591=1.smt2                       |    0.027s | 20.108MiB| unknown | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1778.smt2 |    0.028s | 20.716MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_887.smt2 |    0.028s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1879.smt2 |    0.028s | 19.488MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1736.smt2 |    0.028s | 19.688MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/156.smt2                           |    0.028s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_9.smt2 |    0.030s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_597.smt2 |    0.030s | 19.76MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/141.smt2                           |    0.031s | 20.88MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_179.smt2 |    0.032s | 19.604MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1575.smt2 |    0.032s | 19.496MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1749.smt2 |    0.034s | 20.604MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_1.smt2 |    0.035s | 20.84MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/015.smt2                           |    0.035s | 21.364MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1170.smt2 |    0.036s | 19.52MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1789.smt2 |    0.036s | 19.664MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_7.smt2 |    0.039s | 21.004MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1737.smt2 |    0.039s | 20.824MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1722.smt2 |    0.039s | 20.748MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_6.smt2 |    0.040s | 20.908MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_657.smt2 |    0.040s | 20.644MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_927.smt2 |    0.040s | 20.768MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_2147.smt2 |    0.040s | 20.524MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/MADWiFi-encode_ie_ok_true-unreach-call.i_7.smt2 |    0.041s | 20.656MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1752.smt2 |    0.041s | 19.652MiB| unsat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_2_3_5.smt2        |    0.041s | 21.164MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/166.smt2                           |    0.041s | 20.956MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/177.smt2                           |    0.042s | 20.8MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_15.smt2 |    0.047s | 20.824MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_71.smt2 |    0.047s | 20.896MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1107.smt2 |    0.047s | 20.408MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1172.smt2 |    0.047s | 19.496MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1777.smt2 |    0.047s | 20.28MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/151.smt2                           |    0.047s | 20.724MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_9.smt2 |    0.048s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_473.smt2 |    0.048s | 20.796MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1679.smt2 |    0.049s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_537.smt2 |    0.049s | 19.952MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1427.smt2 |    0.050s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_2_3.smt2          |    0.050s | 21.128MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_187.smt2 |    0.051s | 20.968MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/NUM889=1.smt2                       |    0.051s | 19.388MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_175.smt2 |    0.052s | 20.972MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1764.smt2 |    0.052s | 20.64MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI038=1.smt2                       |    0.052s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/NUM897=1.smt2                       |    0.052s | 19.896MiB| sat | 0 |  |  |
|non-incremental/LIA/tptp/NUM918=1.smt2                       |    0.052s | 19.872MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/NUM875=1.smt2                       |    0.052s | 19.82MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/128.smt2                           |    0.052s | 21.512MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1723.smt2 |    0.053s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1728.smt2 |    0.053s | 20.656MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/NUM869=1.smt2                       |    0.053s | 20.396MiB| sat | 0 |  |  |
|non-incremental/LIA/tptp/ARI079=1.smt2                       |    0.053s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/095.smt2                           |    0.054s | 22.32MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_1478.smt2 |    0.055s | 20.568MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1337.smt2 |    0.055s | 19.632MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI052=1.smt2                       |    0.055s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/s3_srvr_2_true-unreach-call_true-no-overflow_false-termination.BV.c.cil.c_0.smt2 |    0.056s | 20.676MiB| sat | 0 |  |  |
|non-incremental/LIA/tptp/ARI032=1.smt2                       |    0.056s | 21.072MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_127.smt2 |    0.057s | 19.672MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_237.smt2 |    0.057s | 19.576MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/143.smt2                           |    0.057s | 20.924MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/001.smt2                           |    0.057s | 20.684MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1795.smt2 |    0.058s | 20.948MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1437.smt2 |    0.058s | 20.652MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_670.smt2 |    0.058s | 20.864MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_276.smt2 |    0.058s | 20.676MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI004=1.smt2                       |    0.058s | 20.632MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/NUM895=1.smt2                       |    0.059s | 19.52MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI013=1.smt2                       |    0.059s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/NUM874=1.smt2                       |    0.059s | 20.116MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_14.smt2 |    0.060s | 21.184MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/026.smt2                           |    0.060s | 21.432MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_14.smt2 |    0.061s | 20.904MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_13.smt2 |    0.061s | 20.76MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_287.smt2 |    0.062s | 19.7MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/129.smt2                           |    0.063s | 21.452MiB| sat | 0 |  |  |
|non-incremental/LIA/tptp/NUM899=1.smt2                       |    0.064s | 19.892MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/142.smt2                           |    0.064s | 21.636MiB| sat | 0 |  |  |
|non-incremental/LIA/tptp/NUM916=1.smt2                       |    0.065s | 19.96MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_5.smt2 |    0.067s | 21.092MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1471.smt2 |    0.067s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_8.smt2 |    0.068s | 20.86MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_2.smt2 |    0.068s | 20.96MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1117.smt2 |    0.068s | 20.756MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_357.smt2 |    0.068s | 20.78MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI011=1.smt2                       |    0.068s | 20.648MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/171.smt2                           |    0.068s | 21.184MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/NUM915=1.smt2                       |    0.069s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_2.smt2 |    0.070s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/106.smt2                           |    0.070s | 21.236MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_870.smt2 |    0.071s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/152.smt2                           |    0.071s | 21.12MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_2175.smt2 |    0.072s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI040=1.smt2                       |    0.072s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI026=1.smt2                       |    0.072s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/147.smt2                           |    0.072s | 21.156MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/167.smt2                           |    0.072s | 21.128MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_0.smt2 |    0.073s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_6.smt2 |    0.073s | 20.916MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_746.smt2 |    0.073s | 20.728MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/111.smt2                           |    0.073s | 21.884MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_7.smt2 |    0.074s | 20.916MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1798.smt2 |    0.074s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_1735.smt2 |    0.074s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_3227.smt2 |    0.074s | 20.312MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_762.smt2 |    0.074s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/190.smt2                           |    0.074s | 21.884MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1767.smt2 |    0.075s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_378.smt2 |    0.075s | 21.08MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/003.smt2                           |    0.075s | 20.916MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/023.smt2                           |    0.075s | 21.084MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_507.smt2 |    0.076s | 20.448MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_720.smt2 |    0.076s | 19.712MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1741.smt2 |    0.076s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/049.smt2                           |    0.076s | 22.192MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1755.smt2 |    0.077s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/027.smt2                           |    0.077s | 21.568MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_10.smt2 |    0.078s | 20.824MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/123.smt2                           |    0.078s | 21.616MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_5.smt2 |    0.079s | 20.936MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1748.smt2 |    0.079s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_785.smt2 |    0.079s | 20.608MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/179.smt2                           |    0.079s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_4.smt2 |    0.080s | 20.668MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_12.smt2 |    0.080s | 20.932MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1578.smt2 |    0.080s | 20.092MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI054=1.smt2                       |    0.080s | 20.688MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/154.smt2                           |    0.080s | 21.136MiB| sat | 0 |  |  |
|non-incremental/LIA/tptp/ARI025=1.smt2                       |    0.081s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/173.smt2                           |    0.081s | 21.348MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_3.smt2 |    0.083s | 20.764MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_627.smt2 |    0.083s | 20.552MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/NUM917=1.smt2                       |    0.083s | 19.968MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/144.smt2                           |    0.083s | 21.168MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_297.smt2 |    0.084s | 19.948MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/005.smt2                           |    0.084s | 21.388MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_2715.smt2 |    0.085s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1357.smt2 |    0.085s | 20.78MiB| unsat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_3_5.smt2          |    0.085s | 21.148MiB| sat | 0 |  |  |
|non-incremental/LIA/tptp/ARI012=1.smt2                       |    0.086s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1479.smt2 |    0.088s | 21.12MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1307.smt2 |    0.089s | 19.62MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1070.smt2 |    0.089s | 20.608MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_470.smt2 |    0.090s | 20.788MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/NUM898=1.smt2                       |    0.090s | 20.04MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/112.smt2                           |    0.090s | 21.424MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/013.smt2                           |    0.090s | 21.38MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/104.smt2                           |    0.090s | 20.744MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_947.smt2 |    0.091s | 20.804MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_1657.smt2 |    0.091s | 19.464MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/134.smt2                           |    0.091s | 21.876MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/170.smt2                           |    0.091s | 21.04MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1597.smt2 |    0.092s | 20.832MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_670.smt2 |    0.092s | 19.772MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/175.smt2                           |    0.092s | 20.64MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/163.smt2                           |    0.092s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_11.smt2 |    0.093s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_497.smt2 |    0.093s | 19.804MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1379.smt2 |    0.093s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1792.smt2 |    0.093s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_187.smt2 |    0.094s | 19.648MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/066.smt2                           |    0.094s | 21.164MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/125.smt2                           |    0.094s | 21.896MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/105.smt2                           |    0.094s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1317.smt2 |    0.095s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/075.smt2                           |    0.095s | 21.896MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/029.smt2                           |    0.095s | 21.732MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/139.smt2                           |    0.095s | 20.976MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/155.smt2                           |    0.095s | 21.184MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_73.smt2 |    0.096s | 20.648MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/061.smt2                           |    0.096s | 20.776MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/021.smt2                           |    0.096s | 21.076MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_3.smt2 |    0.097s | 20.928MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/103.smt2                           |    0.097s | 20.756MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/062.smt2                           |    0.097s | 20.72MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_10.smt2 |    0.098s | 20.956MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_12.smt2 |    0.098s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_278.smt2 |    0.098s | 20.744MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_703.smt2 |    0.098s | 19.7MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_713.smt2 |    0.098s | 20.94MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_755.smt2 |    0.098s | 20.744MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1874.smt2 |    0.098s | 20.804MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/098.smt2                           |    0.098s | 22.156MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/113.smt2                           |    0.098s | 21.696MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/135.smt2                           |    0.098s | 22.076MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_8.smt2 |    0.099s | 20.996MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_597.smt2 |    0.099s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_876.smt2 |    0.099s | 20.788MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/178.smt2                           |    0.099s | 20.792MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/110.smt2                           |    0.099s | 21.668MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/002.smt2                           |    0.099s | 20.688MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/067.smt2                           |    0.099s | 21.132MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_874.smt2 |    0.100s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1370.smt2 |    0.100s | 20.984MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/019.smt2                           |    0.100s | 20.876MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/093.smt2                           |    0.100s | 22.204MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/004.smt2                           |    0.100s | 20.792MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1875.smt2 |    0.101s | 19.952MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_847.smt2 |    0.101s | 19.68MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI053=1.smt2                       |    0.101s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/063.smt2                           |    0.101s | 21.416MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1817.smt2 |    0.102s | 20.604MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/097.smt2                           |    0.102s | 22.436MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/187.smt2                           |    0.102s | 21.236MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/188.smt2                           |    0.102s | 21.392MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/162.smt2                           |    0.102s | 20.94MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/068.smt2                           |    0.102s | 21.312MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_2317.smt2 |    0.103s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI590=1.smt2                       |    0.103s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/127.smt2                           |    0.103s | 21.176MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1738.smt2 |    0.104s | 20.588MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/028.smt2                           |    0.104s | 21.792MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/094.smt2                           |    0.104s | 22.0MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/193.smt2                           |    0.104s | 21.124MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/185.smt2                           |    0.104s | 21.676MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/172.smt2                           |    0.104s | 21.384MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_4.smt2 |    0.105s | 20.848MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1371.smt2 |    0.105s | 20.524MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/180.smt2                           |    0.105s | 20.616MiB| sat | 0 |  |  |
|non-incremental/LIA/tptp/NUM870=1.smt2                       |    0.106s | 20.144MiB| sat | 0 |  |  |
|non-incremental/LIA/tptp/NUM865=1.smt2                       |    0.106s | 19.492MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/NUM896=1.smt2                       |    0.106s | 19.996MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/031.smt2                           |    0.106s | 21.848MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_744.smt2 |    0.107s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_277.smt2 |    0.107s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI005=1.smt2                       |    0.107s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/NUM864=1.smt2                       |    0.107s | 19.668MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI039=1.smt2                       |    0.107s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/008.smt2                           |    0.107s | 21.86MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/007.smt2                           |    0.107s | 21.312MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/069.smt2                           |    0.107s | 21.172MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1732.smt2 |    0.108s | 20.668MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_707.smt2 |    0.108s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_575.smt2 |    0.108s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/NUM893=1.smt2                       |    0.108s | 20.608MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI018=1.smt2                       |    0.108s | 20.844MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI044=1.smt2                       |    0.108s | 20.164MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI017=1.smt2                       |    0.108s | 20.004MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI027=1.smt2                       |    0.108s | 20.9MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/118.smt2                           |    0.108s | 21.252MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/157.smt2                           |    0.108s | 20.96MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/137.smt2                           |    0.108s | 22.624MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/024.smt2                           |    0.108s | 21.292MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1847.smt2 |    0.109s | 20.668MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_725.smt2 |    0.109s | 20.64MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/116.smt2                           |    0.109s | 21.396MiB| sat | 0 |  |  |
|non-incremental/LIA/tptp/NUM868=1.smt2                       |    0.110s | 20.46MiB| sat | 0 |  |  |
|non-incremental/LIA/tptp/ARI592=1.smt2                       |    0.110s | 20.952MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/161.smt2                           |    0.110s | 20.876MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/018.smt2                           |    0.110s | 20.864MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/149.smt2                           |    0.110s | 21.204MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/136.smt2                           |    0.110s | 23.304MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1784.smt2 |    0.111s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI083=1.smt2                       |    0.111s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/011.smt2                           |    0.111s | 20.816MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/176.smt2                           |    0.111s | 20.9MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/126.smt2                           |    0.111s | 21.916MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/168.smt2                           |    0.111s | 20.912MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1739.smt2 |    0.112s | 19.968MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1726.smt2 |    0.112s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/071.smt2                           |    0.112s | 22.244MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/022.smt2                           |    0.112s | 21.14MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/124.smt2                           |    0.112s | 21.644MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/108.smt2                           |    0.112s | 21.116MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/181.smt2                           |    0.112s | 20.824MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/107.smt2                           |    0.112s | 21.12MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1761.smt2 |    0.113s | 19.716MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_671.smt2 |    0.113s | 19.7MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/109.smt2                           |    0.113s | 21.12MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/096.smt2                           |    0.113s | 22.104MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/064.smt2                           |    0.113s | 21.276MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_678.smt2 |    0.114s | 19.72MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_7.smt2 |    0.114s | 20.788MiB| unsat | 0 |  |  |
|non-incremental/LIA/tptp/ARI045=1.smt2                       |    0.114s | 20.476MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/088.smt2                           |    0.114s | 22.164MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/016.smt2                           |    0.114s | 21.904MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/012.smt2                           |    0.114s | 21.144MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/072.smt2                           |    0.114s | 22.208MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/158.smt2                           |    0.114s | 21.176MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/079.smt2                           |    0.114s | 21.948MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_2207.smt2 |    0.115s | 20.6MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_17.smt2 |    0.115s | 20.768MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/132.smt2                           |    0.115s | 21.168MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/077.smt2                           |    0.115s | 22.108MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/159.smt2                           |    0.115s | 21.2MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/099.smt2                           |    0.116s | 22.192MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/039.smt2                           |    0.116s | 22.224MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/034.smt2                           |    0.116s | 21.92MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1786.smt2 |    0.117s | 20.54MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_173.smt2 |    0.117s | 20.648MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1781.smt2 |    0.117s | 20.84MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/194.smt2                           |    0.117s | 21.88MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/164.smt2                           |    0.117s | 21.18MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/146.smt2                           |    0.117s | 21.132MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/074.smt2                           |    0.117s | 21.9MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/153.smt2                           |    0.117s | 21.144MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1072.smt2 |    0.118s | 20.628MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/092.smt2                           |    0.118s | 22.16MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/119.smt2                           |    0.118s | 21.58MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/020.smt2                           |    0.118s | 21.056MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_1757.smt2 |    0.119s | 20.632MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_447.smt2 |    0.119s | 21.284MiB| unsat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_3_5_7.smt2        |    0.119s | 21.416MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/047.smt2                           |    0.119s | 21.896MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/030.smt2                           |    0.119s | 21.956MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/025.smt2                           |    0.119s | 21.2MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_3872.smt2 |    0.120s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1475.smt2 |    0.120s | 20.656MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1375.smt2 |    0.120s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_751.smt2 |    0.120s | 19.564MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/006.smt2                           |    0.121s | 21.416MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_573.smt2 |    0.124s | 19.64MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/122.smt2                           |    0.124s | 21.42MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/055.smt2                           |    0.125s | 22.288MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/036.smt2                           |    0.125s | 22.176MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/014.smt2                           |    0.125s | 21.384MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/050.smt2                           |    0.125s | 22.196MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1877.smt2 |    0.126s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_73.smt2 |    0.126s | 19.688MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/081.smt2                           |    0.126s | 21.9MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/131.smt2                           |    0.126s | 21.14MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/048.smt2                           |    0.127s | 22.496MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/121.smt2                           |    0.127s | 21.628MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/057.smt2                           |    0.127s | 22.408MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/148.smt2                           |    0.127s | 21.444MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/054.smt2                           |    0.128s | 22.172MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1707.smt2 |    0.129s | 20.812MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/045.smt2                           |    0.129s | 22.052MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/114.smt2                           |    0.129s | 21.364MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/042.smt2                           |    0.129s | 21.924MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/160.smt2                           |    0.130s | 21.308MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1677.smt2 |    0.131s | 20.296MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_728.smt2 |    0.132s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested6_true-unreach-call.i_7.smt2 |    0.132s | 20.568MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/051.smt2                           |    0.132s | 22.408MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/010.smt2                           |    0.133s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/009.smt2                           |    0.134s | 20.856MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/140.smt2                           |    0.134s | 21.38MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_807.smt2 |    0.135s | 20.728MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/117.smt2                           |    0.135s | 21.9MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1887.smt2 |    0.136s | 20.612MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/032.smt2                           |    0.136s | 22.204MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/085.smt2                           |    0.136s | 22.068MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1676.smt2 |    0.137s | 19.688MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1477.smt2 |    0.137s | 20.576MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/086.smt2                           |    0.137s | 22.16MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/138.smt2                           |    0.137s | 22.716MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_367.smt2 |    0.138s | 20.636MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/100.smt2                           |    0.138s | 22.388MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/115.smt2                           |    0.139s | 21.68MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1720.smt2 |    0.140s | 20.732MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/MADWiFi-encode_ie_ok_true-unreach-call.i_17.smt2 |    0.140s | 20.676MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1878.smt2 |    0.140s | 20.748MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/078.smt2                           |    0.140s | 22.336MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/174.smt2                           |    0.140s | 21.736MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_637.smt2 |    0.143s | 21.024MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/133.smt2                           |    0.143s | 21.536MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/082.smt2                           |    0.143s | 22.004MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/087.smt2                           |    0.143s | 22.188MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/044.smt2                           |    0.143s | 22.196MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/145.smt2                           |    0.144s | 21.408MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1770.smt2 |    0.145s | 20.64MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_753.smt2 |    0.146s | 19.928MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_775.smt2 |    0.147s | 19.648MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_763.smt2 |    0.148s | 20.82MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_673.smt2 |    0.148s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_2746.smt2 |    0.148s | 20.888MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/043.smt2                           |    0.148s | 22.036MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1729.smt2 |    0.149s | 20.672MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/076.smt2                           |    0.149s | 22.152MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/073.smt2                           |    0.149s | 21.9MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1758.smt2 |    0.151s | 19.612MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/186.smt2                           |    0.151s | 20.604MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_780.smt2 |    0.152s | 20.888MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1897.smt2 |    0.152s | 21.14MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1703.smt2 |    0.152s | 20.72MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_379.smt2 |    0.152s | 20.648MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_766.smt2 |    0.152s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/065.smt2                           |    0.153s | 21.112MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/053.smt2                           |    0.153s | 22.656MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/080.smt2                           |    0.153s | 22.18MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/035.smt2                           |    0.155s | 22.048MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/037.smt2                           |    0.156s | 21.796MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/090.smt2                           |    0.157s | 22.144MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/189.smt2                           |    0.159s | 21.132MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/017.smt2                           |    0.159s | 20.616MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/058.smt2                           |    0.159s | 22.42MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/165.smt2                           |    0.160s | 21.384MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/169.smt2                           |    0.160s | 21.232MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/091.smt2                           |    0.160s | 21.676MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/033.smt2                           |    0.162s | 22.156MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/130.smt2                           |    0.163s | 21.396MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/120.smt2                           |    0.163s | 21.384MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/195.smt2                           |    0.164s | 21.896MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/150.smt2                           |    0.164s | 21.488MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/196.smt2                           |    0.171s | 21.86MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/089.smt2                           |    0.172s | 22.068MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/038.smt2                           |    0.172s | 22.092MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/041.smt2                           |    0.175s | 22.152MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/070.smt2                           |    0.178s | 21.724MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/101.smt2                           |    0.179s | 22.408MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/040.smt2                           |    0.184s | 22.244MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/084.smt2                           |    0.185s | 22.316MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/052.smt2                           |    0.187s | 22.468MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/083.smt2                           |    0.195s | 22.16MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/102.smt2                           |    0.195s | 22.18MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/046.smt2                           |    0.200s | 22.192MiB| unsat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_5_7.smt2          |    0.206s | 21.396MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/056.smt2                           |    0.217s | 22.32MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_5_7_11.smt2       |    0.231s | 21.816MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_7_11.smt2         |    0.341s | 22.368MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_7_11_13.smt2      |    0.376s | 22.252MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_11_13.smt2        |    1.452s | 24.152MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_11_13_17.smt2     |    1.617s | 24.204MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_13_17_19.smt2     |    4.615s | 26.004MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_17_19_23.smt2     |    4.949s | 26.476MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_13_17.smt2        |    6.060s | 25.828MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_17_19.smt2        |   16.801s | 30.7MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_251_257.smt2      |   20.015s | 30.816MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_223_227.smt2      |   20.016s | 35.708MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_167_173.smt2      |   20.016s | 32.656MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_109_113_127.smt2  |   20.016s | 33.72MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_151_157_163.smt2  |   20.017s | 34.928MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_163_167.smt2      |   20.018s | 37.148MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_79_83.smt2        |   20.018s | 34.136MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_79_83_89.smt2     |   20.018s | 34.948MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_277_281.smt2      |   20.018s | 32.908MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_193_197_199.smt2  |   20.019s | 37.464MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_199_211_223.smt2  |   20.021s | 30.204MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_127_131_137.smt2  |   20.021s | 41.584MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_89_97.smt2        |   20.024s | 35.056MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_43_47.smt2        |   20.027s | 32.404MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_127_131.smt2      |   20.029s | 32.868MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_163_167_173.smt2  |   20.036s | 31.664MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_73_79_83.smt2     |   20.038s | 36.044MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_53_59.smt2        |   20.042s | 32.048MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_139_149.smt2      |   20.042s | 34.536MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_73_79.smt2        |   20.043s | 32.608MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_257_263.smt2      |   20.044s | 34.748MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_157_163.smt2      |   20.044s | 33.5MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_269_271_277.smt2  |   20.045s | 35.896MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_41_43_47.smt2     |   20.045s | 31.08MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_239_241_251.smt2  |   20.045s | 30.56MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_23_29_31.smt2     |   20.046s | 29.816MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_37_41_43.smt2     |   20.046s | 32.464MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_29_31.smt2        |   20.051s | 30.156MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_71_73_79.smt2     |   20.052s | 33.092MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_89_97_101.smt2    |   20.052s | 32.92MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_263_269.smt2      |   20.052s | 32.26MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_193_197.smt2      |   20.053s | 34.584MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_241_251_257.smt2  |   20.053s | 38.888MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_113_127.smt2      |   20.053s | 33.644MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_47_53.smt2        |   20.053s | 31.292MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_239_241.smt2      |   20.053s | 38.784MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_67_71_73.smt2     |   20.053s | 32.38MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_227_229_233.smt2  |   20.053s | 31.828MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_227_229.smt2      |   20.053s | 45.684MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_179_181_191.smt2  |   20.054s | 41.456MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_149_151_157.smt2  |   20.056s | 35.576MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_191_193_197.smt2  |   20.056s | 35.088MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_233_239_241.smt2  |   20.057s | 38.308MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_59_61_67.smt2     |   20.058s | 31.956MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_29_31_37.smt2     |   20.058s | 31.14MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_83_89.smt2        |   20.060s | 31.612MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_97_101.smt2       |   20.061s | 34.256MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_47_53_59.smt2     |   20.062s | 31.784MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_181_191_193.smt2  |   20.062s | 39.856MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_271_277.smt2      |   20.063s | 37.5MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_157_163_167.smt2  |   20.063s | 39.74MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_197_199_211.smt2  |   20.064s | 31.448MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_167_173_179.smt2  |   20.065s | 30.844MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_31_37_41.smt2     |   20.066s | 32.4MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_43_47_53.smt2     |   20.066s | 33.088MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_37_41.smt2        |   20.069s | 32.272MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_83_89_97.smt2     |   20.070s | 29.784MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_61_67_71.smt2     |   20.070s | 33.48MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_179_181.smt2      |   20.072s | 35.496MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_101_103.smt2      |   20.074s | 36.772MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_211_223_227.smt2  |   20.074s | 37.34MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_107_109.smt2      |   20.075s | 32.872MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_71_73.smt2        |   20.075s | 31.636MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_19_23.smt2        |   20.075s | 31.636MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_113_127_131.smt2  |   20.076s | 36.352MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_139_149_151.smt2  |   20.077s | 33.44MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_241_251.smt2      |   20.081s | 35.448MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_263_269_271.smt2  |   20.081s | 36.052MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_173_179_181.smt2  |   20.083s | 37.972MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_149_151.smt2      |   20.083s | 35.268MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_281_283_293.smt2  |   20.086s | 34.62MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_131_137.smt2      |   20.091s | 36.284MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_41_43.smt2        |   20.091s | 32.428MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_19_23_29.smt2     |   20.091s | 30.784MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_173_179.smt2      |   20.092s | 31.696MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_103_107.smt2      |   20.092s | 33.168MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_269_271.smt2      |   20.092s | 39.244MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_137_139.smt2      |   20.092s | 35.76MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_271_277_281.smt2  |   20.093s | 35.144MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_31_37.smt2        |   20.093s | 32.12MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_223_227_229.smt2  |   20.093s | 37.9MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_229_233.smt2      |   20.093s | 36.648MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_137_139_149.smt2  |   20.094s | 32.544MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_199_211.smt2      |   20.103s | 32.244MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_251_257_263.smt2  |   20.106s | 30.44MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_197_199.smt2      |   20.107s | 33.244MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_107_109_113.smt2  |   20.109s | 33.092MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_211_223.smt2      |   20.112s | 30.808MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_61_67.smt2        |   20.112s | 33.284MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_59_61.smt2        |   20.113s | 31.928MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_281_283.smt2      |   20.114s | 40.3MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_67_71.smt2        |   20.114s | 32.636MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_53_59_61.smt2     |   20.120s | 31.932MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_151_157.smt2      |   20.121s | 34.66MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_229_233_239.smt2  |   20.122s | 36.752MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_23_29.smt2        |   20.124s | 31.804MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_233_239.smt2      |   20.125s | 36.488MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_131_137_139.smt2  |   20.127s | 35.504MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_277_281_283.smt2  |   20.127s | 33.648MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_191_193.smt2      |   20.129s | 40.744MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_103_107_109.smt2  |   20.130s | 32.096MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_181_191.smt2      |   20.130s | 37.78MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_101_103_107.smt2  |   20.132s | 39.116MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_109_113.smt2      |   20.133s | 31.94MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_257_263_269.smt2  |   20.133s | 37.024MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_97_101_103.smt2   |   20.133s | 38.932MiB| timeout | 0 |  |  |
