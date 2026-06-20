# .

* SAT 94
* UNSAT 96
* TIMEOUT 65
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_RDL.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_RDL.tar.zst-dow
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_RDL.tar.zst?download=1
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
|non-incremental/QF_RDL/sal/fischer3-mutex-1.smt2             |    0.029s | 20.208MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-2.smt2             |    0.030s | 20.432MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking04.smt2 |    0.037s | 20.88MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-04.smt2 |    0.039s | 21.152MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-3.smt2             |    0.039s | 20.968MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking03.smt2 |    0.051s | 20.616MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-03.smt2 |    0.053s | 20.968MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-2.smt2 |    0.055s | 21.08MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-07.smt2 |    0.058s | 21.88MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-2.smt2             |    0.058s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-2.smt2 |    0.060s | 21.12MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking01.smt2 |    0.070s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking10.smt2 |    0.074s | 22.116MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_250.smt2             |    0.078s | 22.072MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-4.smt2             |    0.079s | 20.844MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-5.smt2             |    0.082s | 20.864MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking16.smt2 |    0.083s | 23.012MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking17.smt2 |    0.083s | 23.02MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking05.smt2 |    0.084s | 21.124MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking18.smt2 |    0.089s | 23.364MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-1.smt2             |    0.089s | 20.216MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/check/bignum_rdl1.smt2                |    0.093s | 20.328MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_700.smt2             |    0.094s | 22.456MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking19.smt2 |    0.096s | 23.396MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_330.smt2             |    0.100s | 22.88MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-08.smt2 |    0.101s | 21.876MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-8.smt2             |    0.101s | 21.604MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking22.smt2 |    0.103s | 24.072MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking06.smt2 |    0.104s | 21.104MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-1.smt2 |    0.105s | 20.12MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-05.smt2 |    0.106s | 21.524MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-7.smt2             |    0.106s | 22.112MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-06.smt2 |    0.107s | 21.428MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-09.smt2 |    0.107s | 22.276MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking12.smt2 |    0.109s | 22.256MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking13.smt2 |    0.112s | 22.268MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-1.smt2             |    0.114s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-6.smt2             |    0.114s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-3.smt2             |    0.114s | 20.58MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-9.smt2             |    0.115s | 21.9MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_700.smt2             |    0.116s | 23.276MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-6.smt2             |    0.117s | 23.1MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1000.smt2             |    0.118s | 23.404MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking15.smt2 |    0.120s | 22.92MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-10.smt2 |    0.120s | 22.104MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-matrix1x1.pddl.smt2 |    0.121s | 20.224MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-4.smt2             |    0.123s | 21.416MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-4.smt2             |    0.127s | 21.792MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-2.smt2             |    0.127s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking14.smt2 |    0.129s | 22.448MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_850.smt2             |    0.132s | 23.7MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-10.smt2            |    0.135s | 21.944MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking02.smt2 |    0.136s | 20.468MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking21.smt2 |    0.137s | 23.756MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-3.smt2 |    0.140s | 23.296MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-5.smt2             |    0.141s | 21.592MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_800.smt2             |    0.142s | 23.74MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking09.smt2 |    0.145s | 21.644MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-3.smt2             |    0.145s | 21.208MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking08.smt2 |    0.146s | 21.644MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking07.smt2 |    0.148s | 21.504MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/check/bignum_rdl2.smt2                |    0.151s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking11.smt2 |    0.153s | 22.236MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_800.smt2             |    0.155s | 23.708MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_700.smt2             |    0.158s | 23.668MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1400.smt2             |    0.163s | 24.256MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_800.smt2             |    0.167s | 23.688MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-7.smt2             |    0.176s | 21.26MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_800.smt2              |    0.181s | 23.716MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-6.smt2             |    0.181s | 22.056MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking20.smt2 |    0.184s | 23.612MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-5.smt2             |    0.194s | 22.26MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_1100.smt2             |    0.201s | 24.272MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-20.smt2 |    0.227s | 24.284MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-8.smt2             |    0.240s | 22.8MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-7.smt2             |    0.250s | 23.496MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-12.smt2            |    0.261s | 22.444MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_1000.smt2            |    0.284s | 24.7MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_900.smt2             |    0.293s | 24.2MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-13.smt2            |    0.298s | 22.688MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_1100.smt2            |    0.332s | 25.032MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_550.smt2             |    0.354s | 24.78MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_800.smt2             |    0.376s | 24.128MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-11.smt2            |    0.378s | 22.112MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_1000.smt2            |    0.418s | 24.472MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-5.base.cvc.smt2    |    0.419s | 50.248MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-9.smt2             |    0.420s | 23.416MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_1200.smt2            |    0.428s | 25.004MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_850.smt2             |    0.466s | 24.344MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-8.smt2             |    0.504s | 24.228MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-30.smt2 |    0.505s | 26.732MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_830.smt2             |    0.511s | 24.444MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa/skdmxa-3x3-5.smt2              |    0.527s | 34.708MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_950.smt2             |    0.541s | 24.716MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-6.base.cvc.smt2    |    0.628s | 56.112MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_1000.smt2             |    0.648s | 24.452MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-16.smt2            |    0.672s | 23.46MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_900.smt2              |    0.683s | 24.196MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-14.smt2            |    0.703s | 23.276MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-40.smt2 |    0.723s | 28.148MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-15.smt2            |    0.743s | 23.5MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-3.smt2 |    0.761s | 24.66MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_900.smt2             |    0.763s | 24.968MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1300.smt2             |    0.775s | 24.988MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-5.induction.cvc.smt2 |    0.779s | 66.6MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_943.smt2              |    0.866s | 24.496MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_1200.smt2            |    0.889s | 25.532MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-17.smt2            |    0.925s | 24.104MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_900.smt2             |    0.951s | 24.556MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_1100.smt2            |    0.969s | 25.304MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-11.smt2            |    0.985s | 25.368MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-10.smt2            |    1.011s | 24.508MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-18.smt2            |    1.066s | 24.428MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-9.smt2             |    1.077s | 25.288MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-7.base.cvc.smt2    |    1.104s | 60.24MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-12.smt2            |    1.209s | 24.98MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-19.smt2            |    1.310s | 24.688MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-9.base.cvc.smt2    |    1.326s | 87.64MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_1100.smt2            |    1.363s | 25.484MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-20.smt2            |    1.405s | 25.2MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_430.smt2             |    1.411s | 25.448MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-13.smt2            |    1.412s | 25.796MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_750.smt2               |    1.425s | 65.428MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_1200.smt2            |    1.461s | 25.936MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_1000.smt2            |    1.464s | 25.664MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_1200.smt2            |    1.552s | 25.972MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa/skdmxa-3x3-10.smt2             |    1.627s | 60.072MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-6.induction.cvc.smt2 |    1.640s | 84.104MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-7.induction.cvc.smt2 |    1.676s | 87.812MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-8.base.cvc.smt2    |    1.813s | 83.784MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_1000.smt2            |    1.892s | 25.884MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_750.smt2               |    1.904s | 66.4MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_750.smt2               |    2.110s | 65.6MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_900.smt2             |    2.182s | 24.96MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-4.smt2 |    2.374s | 28.092MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-9.induction.cvc.smt2 |    2.462s | 125.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_500.smt2              |    2.673s | 49.572MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-8.induction.cvc.smt2 |    2.695s | 107.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-10.smt2            |    2.812s | 27.604MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_900.smt2             |    2.964s | 25.772MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_1100.smt2            |    3.027s | 26.336MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-60.smt2 |    3.207s | 48.852MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-10.induction.cvc.smt2 |    3.253s | 127.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-11.smt2            |    3.283s | 27.6MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_934.smt2             |    3.536s | 26.236MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-11.induction.cvc.smt2 |    3.578s | 152.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1200.smt2             |    3.663s | 25.644MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_888.smt2             |    3.717s | 26.12MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-14.smt2            |    3.743s | 27.492MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-13.induction.cvc.smt2 |    3.847s | 184.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-10.base.cvc.smt2   |    4.080s | 98.2MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-12.induction.cvc.smt2 |    4.198s | 154.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-16.smt2            |    4.254s | 27.268MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_1000.smt2            |    4.654s | 26.26MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_1100.smt2            |    4.737s | 26.768MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-14.induction.cvc.smt2 |    4.799s | 185.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-80.smt2 |    5.268s | 44.88MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_397.smt2             |    5.397s | 26.72MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_900.smt2             |    5.637s | 26.864MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-11.base.cvc.smt2   |    5.642s | 104.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-15.smt2            |    5.721s | 27.84MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-16.induction.cvc.smt2 |    6.222s | 239.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_944.smt2             |    6.295s | 26.556MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-18.smt2            |    6.537s | 30.06MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-70.smt2 |    6.538s | 43.832MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_950.smt2             |    6.624s | 26.672MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_1005.smt2            |    6.638s | 27.044MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-15.induction.cvc.smt2 |    6.743s | 223.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-12.smt2            |    6.797s | 28.912MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_930.smt2             |    7.028s | 27.016MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-17.smt2            |    7.195s | 29.416MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_1100.smt2            |    7.830s | 27.528MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-17.induction.cvc.smt2 |    7.930s | 250.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-13.base.cvc.smt2   |    8.757s | 117.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_888.smt2             |    9.074s | 27.608MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-19.smt2            |    9.700s | 30.688MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-18.induction.cvc.smt2 |   10.457s | 275.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-90.smt2 |   10.899s | 47.548MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-14.smt2            |   11.024s | 30.912MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-12.base.cvc.smt2   |   11.065s | 112.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-19.induction.cvc.smt2 |   11.355s | 299.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1234.smt2             |   11.852s | 28.296MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_887.smt2             |   12.067s | 27.82MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-20.induction.cvc.smt2 |   13.060s | 371.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-13.smt2            |   13.364s | 32.54MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-14.base.cvc.smt2   |   14.157s | 125.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa/skdmxa-3x3-15.smt2             |   15.034s | 98.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-20.smt2            |   15.943s | 32.072MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-5.smt2 |   19.781s | 47.732MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_1000.smt2            |   20.012s | 28.892MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_894.smt2               |   20.019s | 86.716MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_827.smt2               |   20.020s | 81.004MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv13_3150.smt2            |   20.027s | 213.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_850.smt2               |   20.032s | 77.912MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_969.smt2               |   20.041s | 89.8MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_862.smt2               |   20.051s | 84.836MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-16.smt2            |   20.051s | 35.588MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_700.smt2              |   20.055s | 72.608MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_600.smt2              |   20.055s | 66.28MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_1059.smt2            |   20.055s | 29.552MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-4.smt2 |   20.056s | 45.992MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_800.smt2              |   20.057s | 76.208MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_860.smt2               |   20.057s | 85.432MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_950.smt2               |   20.058s | 92.292MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_3050.smt2            |   20.058s | 202.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_828.smt2               |   20.059s | 81.232MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_910.smt2               |   20.060s | 88.204MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-7.smt2 |   20.060s | 89.036MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_887.smt2               |   20.061s | 84.136MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_667.smt2              |   20.063s | 71.784MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_2900.smt2            |   20.063s | 208.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_919.smt2               |   20.065s | 87.236MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_670.smt2              |   20.065s | 72.48MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_950.smt2               |   20.066s | 89.624MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_950.smt2               |   20.066s | 88.756MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_890.smt2               |   20.067s | 88.796MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_850.smt2               |   20.067s | 81.984MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_950.smt2               |   20.067s | 90.752MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-15.base.cvc.smt2   |   20.067s | 140.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_2895.smt2            |   20.069s | 204.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-18.base.cvc.smt2   |   20.071s | 193.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-5.smt2 |   20.072s | 80.024MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-16.base.cvc.smt2   |   20.074s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_2983.smt2            |   20.077s | 200.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv13_3000.smt2            |   20.077s | 216.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_2972.smt2            |   20.077s | 210.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-6.smt2 |   20.077s | 56.064MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_1000.smt2            |   20.078s | 29.844MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_2905.smt2            |   20.078s | 212.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-17.smt2            |   20.078s | 36.72MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-17.base.cvc.smt2   |   20.078s | 192.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_2990.smt2            |   20.080s | 220.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_1005.smt2            |   20.081s | 29.108MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-6.smt2 |   20.081s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-20.smt2            |   20.081s | 36.992MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-19.base.cvc.smt2   |   20.081s | 227.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa/skdmxa-3x3-20.smt2             |   20.092s | 125.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_2992.smt2            |   20.094s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv13_3104.smt2            |   20.099s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_3000.smt2            |   20.102s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv13_3200.smt2            |   20.103s | 215.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_2800.smt2            |   20.105s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-18.smt2            |   20.116s | 36.708MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-15.smt2            |   20.117s | 34.464MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-matrix2x2.pddl.smt2 |   20.118s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-19.smt2            |   20.121s | 35.892MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_3050.smt2            |   20.125s | 220.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_691.smt2              |   20.126s | 73.852MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_1010.smt2            |   20.131s | 29.596MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_2900.smt2            |   20.133s | 204.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_2988.smt2            |   20.135s | 211.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_1000.smt2              |   20.136s | 92.616MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_2885.smt2            |   20.136s | 202.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_3004.smt2            |   20.137s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-20.base.cvc.smt2   |   20.140s | 224.0MiB| timeout | 0 |  |  |
