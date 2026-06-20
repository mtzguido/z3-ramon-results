# .

* SAT 15
* UNSAT 94
* TIMEOUT 151
* UNKNOWN 6

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFNIRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFNIRA.tar.zst-dow
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFNIRA.tar.zst?download=1
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
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U5_sol1.smt2 |    0.024s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U24_sol1.smt2 |    0.024s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U3_sol1.smt2 |    0.025s | 20.204MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U45_sol1.smt2 |    0.025s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U90_sol1.smt2 |    0.025s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U45_sol2.smt2 |    0.026s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U91_sol2.smt2 |    0.026s | 19.972MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U7_sol1.smt2 |    0.027s | 20.016MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol2.smt2 |    0.027s | 19.964MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U72_sol2.smt2 |    0.027s | 19.92MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U17.smt2 |    0.029s | 20.164MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U57_sol1.smt2 |    0.033s | 20.428MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U93_sol1.smt2 |    0.033s | 20.672MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol3.smt2 |    0.035s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U48_sol2.smt2 |    0.036s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol1.smt2 |    0.038s | 19.964MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U91_sol1.smt2 |    0.038s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U25_sol2.smt2 |    0.039s | 20.276MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U23_sol1.smt2 |    0.040s | 19.94MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U82_sol1.smt2 |    0.043s | 20.604MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U41.smt2 |    0.048s | 20.624MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C3_sol1.smt2 |    0.049s | 20.292MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U46.smt2 |    0.049s | 20.668MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C2_sol1.smt2 |    0.050s | 19.952MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U87_sol2.smt2 |    0.052s | 20.164MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U62.smt2 |    0.052s | 20.628MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9a_sol1.smt2 |    0.053s | 19.932MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol3.smt2 |    0.054s | 19.996MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U66.smt2 |    0.054s | 20.668MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U75_sol1.smt2 |    0.055s | 20.008MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U23.smt2 |    0.056s | 20.688MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U71_sol1.smt2 |    0.057s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U25_sol1.smt2 |    0.057s | 20.584MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U11_sol1.smt2 |    0.058s | 20.552MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U76_sol1.smt2 |    0.058s | 20.6MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U92_sol1.smt2 |    0.058s | 20.084MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U17_sol1.smt2 |    0.059s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U72.smt2 |    0.059s | 20.664MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U75.smt2 |    0.059s | 20.624MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9_sol1.smt2 |    0.060s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U2_sol1.smt2 |    0.060s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U71.smt2 |    0.060s | 20.636MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol1.smt2 |    0.061s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U66_sol2.smt2 |    0.061s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C12_sol1.smt2 |    0.061s | 20.016MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C10.smt2 |    0.061s | 20.152MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U57.smt2 |    0.061s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U54_sol2.smt2 |    0.062s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol2.smt2 |    0.062s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U66_sol1.smt2 |    0.063s | 19.916MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U68.smt2 |    0.063s | 20.856MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U68_sol1.smt2 |    0.065s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U13_sol1.smt2 |    0.067s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U46_sol2.smt2 |    0.067s | 20.008MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U27_sol1.smt2 |    0.068s | 20.596MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U53_sol1.smt2 |    0.069s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U51_sol1.smt2 |    0.069s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U89.smt2 |    0.069s | 20.896MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U10_sol1.smt2 |    0.070s | 19.928MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U6_sol1.smt2 |    0.070s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U87_sol1.smt2 |    0.071s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol1.smt2 |    0.072s | 19.964MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U39_sol1.smt2 |    0.073s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U46_sol1.smt2 |    0.073s | 20.088MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U72_sol1.smt2 |    0.074s | 19.956MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U49_sol2.smt2 |    0.075s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U51.smt2 |    0.075s | 20.616MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U48_sol1.smt2 |    0.077s | 20.18MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U26_sol1.smt2 |    0.077s | 20.172MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U26_sol2.smt2 |    0.077s | 20.588MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U81.smt2 |    0.077s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U20.smt2 |    0.077s | 20.676MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U62_sol1.smt2 |    0.078s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U48.smt2 |    0.078s | 20.788MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C6_sol1.smt2 |    0.079s | 19.928MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U1.smt2 |    0.080s | 20.872MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U54_sol1.smt2 |    0.081s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U44_sol2.smt2 |    0.082s | 20.728MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U81_sol1.smt2 |    0.084s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U4.smt2 |    0.087s | 21.328MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U56_sol1.smt2 |    0.088s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U37_sol1.smt2 |    0.090s | 21.156MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U61_sol1.smt2 |    0.093s | 20.724MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U79.smt2 |    0.094s | 32.352MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C5.smt2 |    0.096s | 20.584MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U56_sol2.smt2 |    0.099s | 19.996MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U14_sol1.smt2 |    0.100s | 20.508MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U4_sol1.smt2 |    0.102s | 20.68MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol2.smt2 |    0.103s | 20.328MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C4_sol1.smt2 |    0.108s | 19.952MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C5_sol1.smt2 |    0.109s | 20.94MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U26.smt2 |    0.110s | 22.3MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C13_sol1.smt2 |    0.111s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U42_sol1.smt2 |    0.113s | 20.16MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U9_sol1.smt2 |    0.117s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U19_sol1.smt2 |    0.122s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U44_sol1.smt2 |    0.129s | 20.688MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C1_sol1.smt2 |    0.137s | 20.136MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U64_sol1.smt2 |    0.141s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U89_sol1.smt2 |    0.141s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U49_sol1.smt2 |    0.141s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C10_sol1.smt2 |    0.143s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U8_sol2.smt2 |    0.147s | 19.972MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol3.smt2 |    0.147s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U8_sol1.smt2 |    0.154s | 20.164MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U75_sol2.smt2 |    0.154s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U67_sol1.smt2 |    0.160s | 20.348MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U11.smt2 |    0.161s | 20.38MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U12_sol1.smt2 |    0.183s | 21.096MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U7.smt2 |    5.004s | 26.544MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C6.smt2 |    7.845s | 45.384MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U14.smt2 |    8.681s | 29.696MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U14.smt2 |   10.801s | 30.468MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U16_sol1.smt2 |   13.911s | 33.184MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U17.smt2 |   16.687s | 143.0MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U12.smt2 |   20.047s | 34.684MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U27.smt2 |   20.048s | 23.392MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C5.smt2 |   20.049s | 22.864MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C7_sol1.smt2 |   20.052s | 32.256MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U93.smt2 |   20.052s | 27.98MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C3.smt2 |   20.053s | 64.9MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U66.smt2 |   20.053s | 31.324MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U81.smt2 |   20.053s | 57.104MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C9a.smt2 |   20.053s | 74.144MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U30.smt2 |   20.054s | 23.644MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C9.smt2 |   20.055s | 55.768MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C7.smt2 |   20.065s | 29.052MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U26.smt2 |   20.069s | 33.248MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C4.smt2 |   20.071s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U12.smt2 |   20.072s | 28.928MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C3.smt2 |   20.072s | 86.376MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U38.smt2 |   20.073s | 39.124MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U76.smt2 |   20.074s | 27.548MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U87.smt2 |   20.074s | 65.132MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U40_sol1.smt2 |   20.076s | 21.58MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol1.smt2 |   20.077s | 30.62MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U88.smt2 |   20.078s | 36.636MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U53.smt2 |   20.079s | 40.104MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U11.smt2 |   20.082s | 56.032MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U39.smt2 |   20.084s | 66.428MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U45.smt2 |   20.085s | 193.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U90.smt2 |   20.087s | 94.416MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U1_sol1.smt2 |   20.089s | 26.444MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C13.smt2 |   20.091s | 266.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U34.smt2 |   20.092s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U10.smt2 |   20.092s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C8_sol1.smt2 |   20.096s | 34.956MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U9.smt2 |   20.100s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U57.smt2 |   20.106s | 149.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U33.smt2 |   20.113s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C7.smt2 |   20.114s | 29.452MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U6.smt2 |   20.114s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U90.smt2 |   20.117s | 96.712MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U33.smt2 |   20.117s | 171.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U7.smt2 |   20.123s | 53.008MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U39.smt2 |   20.132s | 325.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U53.smt2 |   20.133s | 41.148MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C9.smt2 |   20.134s | 59.38MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U93.smt2 |   20.136s | 27.548MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U23.smt2 |   20.143s | 54.004MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U45.smt2 |   20.155s | 28.5MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C9a.smt2 |   20.163s | 48.164MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U76.smt2 |   20.164s | 29.384MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U27.smt2 |   20.164s | 25.48MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U44.smt2 |   20.167s | 41.928MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C10.smt2 |   20.171s | 261.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C4.smt2 |   20.226s | 261.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U68.smt2 |   20.227s | 420.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C13.smt2 |   20.228s | 239.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U4.smt2 |   20.229s | 442.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U6.smt2 |   20.245s | 192.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U28.smt2 |   20.255s | 418.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U9.smt2 |   20.272s | 183.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U44.smt2 |   20.279s | 515.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U72.smt2 |   20.294s | 301.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U10.smt2 |   20.294s | 261.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U33_sol1.smt2 |   20.318s | 560.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U16.smt2 |   20.359s | 267.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C6.smt2 |   20.369s | 311.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U91.smt2 |   20.440s | 559.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U19.smt2 |   20.457s | 714.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C2.smt2 |   20.465s | 568.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U71.smt2 |   20.515s | 639.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C8.smt2 |   20.544s | 630.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U91.smt2 |   20.574s | 1049.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U47.smt2 |   20.616s | 642.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U16.smt2 |   20.638s | 960.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C8.smt2 |   20.655s | 1211.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U70.smt2 |   20.840s | 1223.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U51.smt2 |   20.861s | 1398.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U92.smt2 |   20.917s | 1276.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U29.smt2 |   20.968s | 1606.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U43.smt2 |   20.978s | 1572.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U41.smt2 |   20.990s | 1825.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U43.smt2 |   20.992s | 1649.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U1.smt2 |   21.002s | 1424.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U37.smt2 |   21.015s | 1416.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U19.smt2 |   21.030s | 1772.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U82.smt2 |   21.034s | 1677.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U48.smt2 |   21.086s | 2009.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U67.smt2 |   21.091s | 1938.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U87.smt2 |   21.104s | 1797.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U5.smt2 |   21.113s | 2045.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U56.smt2 |   21.124s | 1903.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U42.smt2 |   21.128s | 2113.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U73.smt2 |   21.165s | 2055.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U15.smt2 |   21.201s | 2086.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U21.smt2 |   21.223s | 2035.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C11.smt2 |   21.229s | 2069.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U31.smt2 |   21.241s | 2135.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U50.smt2 |   21.243s | 2242.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C11.smt2 |   21.251s | 2261.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U61.smt2 |   21.253s | 2089.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U62.smt2 |   21.265s | 2155.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U22_sol1.smt2 |   21.266s | 2170.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U20.smt2 |   21.277s | 1921.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U73_sol1.smt2 |   21.285s | 2473.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U29.smt2 |   21.300s | 2113.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U61.smt2 |   21.305s | 1983.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol2.smt2 |   21.318s | 2034.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U54.smt2 |   21.318s | 2700.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U67.smt2 |   21.324s | 2233.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U37.smt2 |   21.330s | 2083.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U65.smt2 |   21.349s | 2891.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U22.smt2 |   21.372s | 2327.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U49.smt2 |   21.393s | 2963.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U92.smt2 |   21.414s | 2239.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U40.smt2 |   21.425s | 2465.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U21_sol1.smt2 |   21.458s | 2525.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U22.smt2 |   21.463s | 2885.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U56.smt2 |   21.467s | 2856.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U13.smt2 |   21.500s | 2714.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U25.smt2 |   21.501s | 2766.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U89.smt2 |   21.520s | 4593.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U8.smt2 |   21.530s | 2834.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U54.smt2 |   21.546s | 2645.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U40.smt2 |   21.560s | 2835.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U5.smt2 |   21.571s | 2532.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C12.smt2 |   21.574s | 3333.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U46.smt2 |   21.586s | 3355.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U50.smt2 |   21.595s | 3117.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C11_sol1.smt2 |   21.604s | 2648.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U15.smt2 |   21.604s | 3392.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U64.smt2 |   21.606s | 2761.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U49.smt2 |   21.613s | 3715.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U29_sol1.smt2 |   21.617s | 3467.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U73.smt2 |   21.646s | 4397.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U3.smt2 |   21.671s | 3066.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U2.smt2 |   21.691s | 4464.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U82.smt2 |   21.697s | 3145.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C12.smt2 |   21.708s | 3427.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U21.smt2 |   21.713s | 3393.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U24.smt2 |   21.715s | 3337.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U25.smt2 |   21.757s | 4176.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U8.smt2 |   21.762s | 2971.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U24.smt2 |   21.785s | 3610.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U2.smt2 |   21.785s | 4296.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U64.smt2 |   21.827s | 3381.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C1.smt2 |   21.852s | 3845.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U3.smt2 |   21.853s | 4220.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C2.smt2 |   21.924s | 7128.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U13.smt2 |   21.945s | 3998.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U42.smt2 |   22.006s | 4738.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C1.smt2 |   22.007s | 7338.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U75.smt2 |   22.091s | 7835.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U43_sol1.smt2 |   22.228s | 8028.0MiB| timeout | 0 |  |  |
