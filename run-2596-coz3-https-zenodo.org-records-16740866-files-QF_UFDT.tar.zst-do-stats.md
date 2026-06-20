# .

* SAT 3
* UNSAT 1
* TIMEOUT 199
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFDT.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFDT.tar.zst-do
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFDT.tar.zst?download=1
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
|non-incremental/QF_UFDT/20170428-Barrett/cdt-cade2015/data/afp/coinductive_list/x2015_09_10_17_01_00_473_1716450.smt_in.smt2 |    0.023s | 19.396MiB| sat | 0 |  |  |
|non-incremental/QF_UFDT/20170428-Barrett/cdt-cade2015/data/distro/stream_processor/x2015_09_10_16_45_47_401_987519.smt_in.smt2 |    0.024s | 19.86MiB| sat | 0 |  |  |
|non-incremental/QF_UFDT/20170428-Barrett/cdt-cade2015/data/distro/stream_processor/x2015_09_10_16_45_54_875_1000989.smt_in.smt2 |    0.053s | 19.856MiB| sat | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e10.smt2     |   13.103s | 34.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e85.smt2     |   20.017s | 38.284MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e94.smt2     |   20.018s | 32.256MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k52.smt2     |   20.018s | 37.576MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k15.smt2     |   20.019s | 34.144MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e29.smt2     |   20.020s | 33.872MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k61.smt2     |   20.020s | 37.388MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e86.smt2     |   20.020s | 31.416MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e13.smt2     |   20.020s | 31.464MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k26.smt2     |   20.020s | 34.696MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e74.smt2     |   20.020s | 37.68MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e95.smt2     |   20.020s | 39.496MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k75.smt2     |   20.021s | 37.144MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k50.smt2     |   20.021s | 38.636MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k92.smt2     |   20.022s | 72.78MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k16.smt2     |   20.023s | 32.796MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e20.smt2     |   20.026s | 36.076MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k47.smt2     |   20.026s | 77.82MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e15.smt2     |   20.027s | 31.14MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e51.smt2     |   20.027s | 33.832MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e49.smt2     |   20.027s | 32.608MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k49.smt2     |   20.027s | 33.328MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e35.smt2     |   20.029s | 37.956MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e55.smt2     |   20.030s | 31.012MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e92.smt2     |   20.031s | 33.968MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e48.smt2     |   20.032s | 31.14MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k66.smt2     |   20.032s | 29.488MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k95.smt2     |   20.032s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k86.smt2     |   20.032s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k76.smt2     |   20.033s | 37.712MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e37.smt2     |   20.033s | 38.04MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k09.smt2     |   20.034s | 37.944MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e75.smt2     |   20.034s | 29.496MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k27.smt2     |   20.035s | 38.544MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e14.smt2     |   20.035s | 38.608MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k67.smt2     |   20.035s | 32.376MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e17.smt2     |   20.036s | 38.288MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e32.smt2     |   20.036s | 35.3MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e21.smt2     |   20.036s | 31.912MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k07.smt2     |   20.038s | 45.612MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k85.smt2     |   20.038s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e56.smt2     |   20.038s | 33.916MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k25.smt2     |   20.038s | 33.592MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e63.smt2     |   20.039s | 36.812MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k00.smt2     |   20.039s | 36.988MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e81.smt2     |   20.039s | 29.2MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k89.smt2     |   20.040s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k38.smt2     |   20.040s | 35.248MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k68.smt2     |   20.041s | 37.312MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k20.smt2     |   20.042s | 31.336MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k11.smt2     |   20.042s | 40.108MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k69.smt2     |   20.043s | 53.736MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e65.smt2     |   20.044s | 37.288MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e18.smt2     |   20.044s | 32.552MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e57.smt2     |   20.044s | 35.164MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e61.smt2     |   20.045s | 35.004MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e79.smt2     |   20.045s | 39.96MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k12.smt2     |   20.045s | 37.744MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e30.smt2     |   20.046s | 30.128MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e46.smt2     |   20.046s | 35.192MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k30.smt2     |   20.046s | 30.748MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k60.smt2     |   20.046s | 34.7MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k73.smt2     |   20.047s | 31.3MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e76.smt2     |   20.047s | 34.856MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k62.smt2     |   20.047s | 38.792MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e43.smt2     |   20.048s | 27.964MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e03.smt2     |   20.048s | 34.724MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e33.smt2     |   20.048s | 35.38MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e73.smt2     |   20.048s | 38.224MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k03.smt2     |   20.049s | 38.888MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k36.smt2     |   20.049s | 32.756MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e78.smt2     |   20.050s | 33.068MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k94.smt2     |   20.051s | 35.58MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e93.smt2     |   20.054s | 30.088MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e59.smt2     |   20.054s | 36.22MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k31.smt2     |   20.056s | 30.328MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e88.smt2     |   20.056s | 30.644MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k05.smt2     |   20.056s | 43.856MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k01.smt2     |   20.057s | 34.56MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k14.smt2     |   20.057s | 30.532MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k32.smt2     |   20.057s | 31.276MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e98.smt2     |   20.059s | 33.856MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k84.smt2     |   20.059s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e12.smt2     |   20.059s | 32.348MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k24.smt2     |   20.059s | 31.568MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k08.smt2     |   20.059s | 45.636MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e07.smt2     |   20.060s | 34.492MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e62.smt2     |   20.060s | 35.976MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k34.smt2     |   20.060s | 34.552MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k23.smt2     |   20.060s | 32.828MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k42.smt2     |   20.060s | 40.012MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k18.smt2     |   20.061s | 30.144MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e42.smt2     |   20.061s | 31.108MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k04.smt2     |   20.061s | 43.776MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k06.smt2     |   20.061s | 45.36MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k35.smt2     |   20.062s | 41.684MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k54.smt2     |   20.062s | 185.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k40.smt2     |   20.063s | 35.024MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k21.smt2     |   20.063s | 37.756MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e99.smt2     |   20.064s | 38.12MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k74.smt2     |   20.064s | 35.284MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k57.smt2     |   20.064s | 87.264MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k44.smt2     |   20.064s | 184.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e67.smt2     |   20.066s | 36.864MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k51.smt2     |   20.066s | 35.08MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e77.smt2     |   20.068s | 29.924MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e44.smt2     |   20.068s | 34.864MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e84.smt2     |   20.068s | 32.612MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e02.smt2     |   20.069s | 33.432MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e40.smt2     |   20.069s | 34.444MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k91.smt2     |   20.069s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k63.smt2     |   20.069s | 87.38MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k10.smt2     |   20.069s | 49.304MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e80.smt2     |   20.069s | 37.3MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k13.smt2     |   20.069s | 29.36MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e68.smt2     |   20.070s | 28.844MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k71.smt2     |   20.070s | 86.372MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k64.smt2     |   20.070s | 33.748MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e38.smt2     |   20.070s | 32.788MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k28.smt2     |   20.070s | 31.86MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e31.smt2     |   20.070s | 32.92MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e39.smt2     |   20.070s | 32.496MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e64.smt2     |   20.071s | 36.96MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e52.smt2     |   20.071s | 37.26MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e06.smt2     |   20.072s | 31.788MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k41.smt2     |   20.072s | 34.648MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e08.smt2     |   20.072s | 32.944MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k22.smt2     |   20.072s | 29.372MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e45.smt2     |   20.073s | 33.512MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k02.smt2     |   20.073s | 34.296MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e60.smt2     |   20.073s | 35.884MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e01.smt2     |   20.074s | 31.62MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e82.smt2     |   20.074s | 36.864MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e72.smt2     |   20.074s | 38.416MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e41.smt2     |   20.075s | 32.38MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e19.smt2     |   20.076s | 31.848MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e54.smt2     |   20.076s | 34.456MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k88.smt2     |   20.077s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e89.smt2     |   20.077s | 37.188MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e66.smt2     |   20.078s | 38.24MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e11.smt2     |   20.079s | 34.496MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k17.smt2     |   20.079s | 45.06MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e25.smt2     |   20.079s | 33.8MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e50.smt2     |   20.079s | 31.624MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e58.smt2     |   20.081s | 33.92MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k46.smt2     |   20.081s | 76.268MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k37.smt2     |   20.081s | 70.236MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e47.smt2     |   20.082s | 32.876MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k90.smt2     |   20.082s | 34.392MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k65.smt2     |   20.082s | 37.56MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k58.smt2     |   20.082s | 32.38MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k72.smt2     |   20.082s | 97.512MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k43.smt2     |   20.083s | 72.692MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e16.smt2     |   20.083s | 34.952MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e87.smt2     |   20.083s | 35.896MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e69.smt2     |   20.084s | 39.74MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e91.smt2     |   20.084s | 33.836MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e09.smt2     |   20.084s | 36.436MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k33.smt2     |   20.084s | 38.6MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e83.smt2     |   20.088s | 30.828MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k80.smt2     |   20.089s | 62.884MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k59.smt2     |   20.090s | 31.84MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e97.smt2     |   20.091s | 182.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e71.smt2     |   20.092s | 36.06MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k99.smt2     |   20.092s | 179.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k98.smt2     |   20.092s | 179.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k39.smt2     |   20.092s | 72.32MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k48.smt2     |   20.093s | 76.524MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k96.smt2     |   20.093s | 180.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k87.smt2     |   20.095s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k55.smt2     |   20.096s | 188.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e00.smt2     |   20.096s | 32.568MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e26.smt2     |   20.097s | 32.784MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k29.smt2     |   20.098s | 38.488MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k70.smt2     |   20.098s | 37.58MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e05.smt2     |   20.098s | 35.236MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k82.smt2     |   20.100s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k45.smt2     |   20.100s | 186.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k93.smt2     |   20.101s | 179.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k77.smt2     |   20.103s | 37.48MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e34.smt2     |   20.104s | 33.576MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e90.smt2     |   20.104s | 37.832MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e04.smt2     |   20.105s | 31.236MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k78.smt2     |   20.107s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e24.smt2     |   20.107s | 33.516MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k83.smt2     |   20.109s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e70.smt2     |   20.110s | 35.364MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e96.smt2     |   20.114s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e27.smt2     |   20.115s | 35.948MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k53.smt2     |   20.116s | 168.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e22.smt2     |   20.118s | 32.668MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e53.smt2     |   20.118s | 40.204MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k79.smt2     |   20.119s | 33.32MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e28.smt2     |   20.122s | 33.812MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k19.smt2     |   20.124s | 31.376MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e36.smt2     |   20.124s | 30.58MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k56.smt2     |   20.124s | 34.36MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e23.smt2     |   20.125s | 32.836MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k97.smt2     |   20.126s | 180.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k81.smt2     |   20.131s | 178.0MiB| timeout | 0 |  |  |
