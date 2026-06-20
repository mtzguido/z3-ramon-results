# .

* SAT 52
* UNSAT 71
* TIMEOUT 53
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_ALIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_ALIA.tar.zst-do
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_ALIA.tar.zst?download=1
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
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00002_001.cvc.smt2 |    0.024s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00003_001.cvc.smt2 |    0.025s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-invalid-5.smt2 |    0.030s | 20.876MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_174f4d.smt2                |    0.031s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/misc/stack-th1-6.smt2 |    0.034s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_ed9849.smt2                |    0.036s | 20.9MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_cb19c7.smt2                |    0.038s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/misc/queue-th1-6.smt2 |    0.045s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00007_001.cvc.smt2 |    0.047s | 20.152MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00007_001.cvc.smt2 |    0.050s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/cvc/pp-dmem2.smt2                    |    0.051s | 21.976MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00005_001.cvc.smt2 |    0.051s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00006_001.cvc.smt2 |    0.052s | 20.344MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/misc/stack-th2-6.smt2 |    0.053s | 19.636MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00011_001.cvc.smt2 |    0.054s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00001_001.cvc.smt2 |    0.054s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.5.smt2        |    0.054s | 21.132MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_5b181b.smt2                |    0.056s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00009_001.cvc.smt2 |    0.056s | 20.596MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00001_001.cvc.smt2 |    0.056s | 20.168MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00014_001.cvc.smt2 |    0.057s | 20.38MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/misc/stack-invalid-6.smt2 |    0.058s | 20.14MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/cvc/read2.smt2                       |    0.058s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00015_001.cvc.smt2 |    0.058s | 20.632MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00011_001.cvc.smt2 |    0.058s | 20.256MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00002_001.cvc.smt2 |    0.060s | 20.408MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_408ff0.smt2                |    0.061s | 21.38MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_fdec13.smt2                |    0.061s | 20.976MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-safe-5.smt2 |    0.062s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_ffa5fa.smt2                |    0.062s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00006_001.cvc.smt2 |    0.062s | 20.272MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00004_001.cvc.smt2 |    0.063s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00008_001.cvc.smt2 |    0.063s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00003_001.cvc.smt2 |    0.063s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00013_001.cvc.smt2 |    0.064s | 20.576MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-invalid-10.smt2 |    0.065s | 21.908MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00012_001.cvc.smt2 |    0.065s | 20.416MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00008_001.cvc.smt2 |    0.066s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00010_001.cvc.smt2 |    0.067s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00013_001.cvc.smt2 |    0.069s | 20.424MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00009_001.cvc.smt2 |    0.073s | 20.376MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00005_001.cvc.smt2 |    0.075s | 20.58MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/misc/queue-th2-6.smt2 |    0.076s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_7fd2c4.smt2                |    0.077s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-safe-10.smt2 |    0.079s | 21.124MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_d421cb.smt2                |    0.079s | 20.556MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00010_001.cvc.smt2 |    0.079s | 20.3MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00015_001.cvc.smt2 |    0.080s | 20.592MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/cvc/pp-bloaddata.smt2                |    0.087s | 22.16MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.7.smt2        |    0.087s | 21.668MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/cvc/pp-bloaddata-a.smt2              |    0.088s | 21.952MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00014_001.cvc.smt2 |    0.089s | 20.844MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00004_001.cvc.smt2 |    0.089s | 20.276MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_22b1f2.smt2                |    0.090s | 21.968MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00012_001.cvc.smt2 |    0.090s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-invalid-20.smt2 |    0.093s | 23.8MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_f5059f.smt2                |    0.094s | 22.084MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_13f61c.smt2                |    0.094s | 20.676MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.5.smt2             |    0.096s | 20.664MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.8.smt2        |    0.098s | 21.968MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.6.smt2        |    0.098s | 21.64MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.6.smt2             |    0.099s | 20.996MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-bug-5.smt2 |    0.100s | 20.88MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-mutex-5.smt2 |    0.101s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_3031c9.smt2                |    0.103s | 22.58MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/cvc/pp-dmem-a.smt2                   |    0.104s | 21.892MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_509c40.smt2                |    0.106s | 22.136MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-invalid-15.smt2 |    0.114s | 23.112MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_46582a.smt2                |    0.116s | 22.076MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-safe-15.smt2 |    0.132s | 21.928MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-bug-10.smt2 |    0.177s | 22.46MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-bug2-10.smt2 |    0.182s | 22.672MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-safe-20.smt2 |    0.188s | 22.788MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.9.smt2        |    0.205s | 22.676MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.7.smt2             |    0.259s | 21.164MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.10.smt2       |    0.279s | 23.304MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.11.smt2       |    0.305s | 24.088MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.13.smt2       |    0.395s | 24.684MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.12.smt2       |    0.438s | 23.832MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-bug-15.smt2 |    0.444s | 24.912MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.8.smt2             |    0.459s | 21.9MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.14.smt2       |    0.545s | 25.2MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.15.smt2       |    0.655s | 25.988MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_stateful-1.i_3.smt2 |    0.802s | 31.376MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_stateful-1.i_2.smt2 |    0.814s | 31.536MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.15.smt2            |    0.830s | 25.816MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_stateful-1.i_1.smt2 |    0.849s | 31.372MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_stateful-1.i_4.smt2 |    0.863s | 31.54MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.9.smt2             |    0.898s | 22.356MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.16.smt2            |    0.954s | 26.26MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_lazy.i_7.smt2 |    1.000s | 34.78MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_lazy.i_3.smt2 |    1.018s | 34.852MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_lazy.i_6.smt2 |    1.073s | 34.764MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.17.smt2       |    1.080s | 27.772MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.18.smt2            |    1.209s | 27.968MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.18.smt2       |    1.416s | 30.688MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-bug2-15.smt2 |    1.686s | 26.5MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.20.smt2            |    1.748s | 29.752MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.11.smt2            |    1.813s | 23.476MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.10.smt2            |    1.824s | 23.02MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-bug2-20.smt2 |    1.827s | 29.832MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-mutex-10.smt2 |    2.066s | 23.212MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.16.smt2       |    2.122s | 28.492MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.19.smt2            |    2.213s | 28.512MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_7.smt2 |    2.510s | 46.58MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_6.smt2 |    2.941s | 46.508MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.17.smt2            |    3.427s | 28.964MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_5.smt2 |    3.668s | 59.992MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.22.smt2            |    4.147s | 32.116MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.21.smt2            |    4.585s | 33.404MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_read_write_lock-1.i_0.smt2 |    4.986s | 45.672MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.12.smt2            |    5.823s | 25.652MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.13.smt2            |    6.532s | 25.508MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.20.smt2       |    8.566s | 36.636MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_1.smt2 |    9.914s | 66.164MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_2.smt2 |   10.139s | 66.056MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.14.smt2            |   10.665s | 26.916MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-bug-20.smt2 |   10.892s | 33.936MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-mutex-15.smt2 |   12.697s | 27.044MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-3.i_7.smt2 |   13.716s | 351.0MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.21.smt2       |   16.741s | 42.416MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.19.smt2       |   17.861s | 40.56MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/AllInterval-011.c_AllErrorsAtOnce_Iteration2_0.smt2 |   19.177s | 26.0MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/AllInterval-016.c_AllErrorsAtOnce_Iteration2_0.smt2 |   20.011s | 26.836MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.26.smt2            |   20.013s | 37.124MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-mutex-20.smt2 |   20.015s | 32.368MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_dekker.i_0.smt2 |   20.016s | 70.352MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.29.smt2       |   20.016s | 46.468MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_sync.i_0.smt2 |   20.020s | 57.94MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_sync.i_6.smt2 |   20.021s | 55.46MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_3.smt2 |   20.027s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_0.smt2 |   20.028s | 116.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.24.smt2            |   20.028s | 37.108MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.28.smt2       |   20.031s | 54.896MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.28.smt2            |   20.034s | 38.564MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.30.smt2            |   20.037s | 39.936MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.26.smt2       |   20.038s | 54.34MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.23.smt2            |   20.039s | 36.036MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.23.smt2       |   20.040s | 43.928MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.29.smt2            |   20.042s | 38.308MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.27.smt2            |   20.046s | 40.416MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_sync.i_1.smt2 |   20.048s | 60.372MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_lamport.i_0.smt2 |   20.048s | 72.112MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_9.smt2 |   20.049s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_sync.i_3.smt2 |   20.049s | 60.564MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.30.smt2       |   20.049s | 77.728MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.25.smt2            |   20.049s | 38.176MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_2.smt2 |   20.050s | 118.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.27.smt2       |   20.050s | 43.62MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_time_var_mutex.i_0.smt2 |   20.051s | 74.952MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_sync.i_4.smt2 |   20.051s | 57.7MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/CostasArray-15.c_AllErrorsAtOnce_Iteration2_0.smt2 |   20.051s | 28.932MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_10.smt2 |   20.051s | 125.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_queue-2.i_0.smt2 |   20.054s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_1.smt2 |   20.054s | 104.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_peterson.i_0.smt2 |   20.056s | 73.04MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.22.smt2       |   20.056s | 77.42MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.24.smt2       |   20.057s | 39.944MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-3.i_6.smt2 |   20.059s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_5.smt2 |   20.059s | 109.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_6.smt2 |   20.060s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_4.smt2 |   20.061s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_8.smt2 |   20.062s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_7.smt2 |   20.062s | 122.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.25.smt2       |   20.062s | 47.596MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/AllInterval-019.c_AllErrorsAtOnce_Iteration2_0.smt2 |   20.063s | 28.456MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_fib-1.i_0.smt2 |   20.066s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_fib_longer-1.i_0.smt2 |   20.067s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/AllInterval-015.c_AllErrorsAtOnce_Iteration2_0.smt2 |   20.067s | 25.932MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_11.smt2 |   20.068s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_sync.i_2.smt2 |   20.076s | 55.988MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_0.smt2 |   20.077s | 60.576MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_read_write_lock-2.i_0.smt2 |   20.080s | 58.928MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_fib-2.i_0.smt2 |   20.087s | 116.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_fib_longer-2.i_0.smt2 |   20.088s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_queue-1.i_0.smt2 |   20.088s | 119.0MiB| timeout | 0 |  |  |
