# .

* SAT 34
* UNSAT 9
* TIMEOUT 37
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFDTNIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFDTNIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFDTNIA.tar.zst?download=1
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
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_40_QF_UFDTNIA.smt2 |    0.102s | 23.976MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_aa742630eef64f949de269382c1f9035_25_UFDTNIA.smt2 |    0.103s | 24.056MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_6_QF_UFDTNIA.smt2 |    0.121s | 22.372MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_60_QF_UFDTNIA.smt2 |    0.223s | 29.604MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_47_QF_UFDTNIA.smt2 |    0.242s | 27.156MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTNIA.smt2 |    0.266s | 29.088MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_59_QF_UFDTNIA.smt2 |    0.269s | 31.732MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTNIA.smt2 |    0.293s | 29.952MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_58_QF_UFDTNIA.smt2 |    0.363s | 28.792MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2 |    0.771s | 30.612MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_8_QF_UFDTNIA.smt2 |    0.924s | 25.968MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_48_QF_UFDTNIA.smt2 |    0.942s | 29.584MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_14_QF_UFDTNIA.smt2 |    0.961s | 43.86MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2 |    1.014s | 28.5MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_0_UFDTNIA.smt2 |    1.156s | 28.94MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_7_QF_UFDTNIA.smt2 |    1.178s | 26.172MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_17_QF_UFDTNIA.smt2 |    1.391s | 51.096MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_18_QF_UFDTNIA.smt2 |    1.432s | 51.908MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/72771_f9d228efc97cf1458e38_64_QF_UFDTNIA.smt2 |    1.582s | 30.328MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_22_QF_UFDTNIA.smt2 |    1.665s | 46.852MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_55d6bef5390186355f11_26_QF_UFDTNIA.smt2 |    2.139s | 53.012MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_15_QF_UFDTNIA.smt2 |    2.598s | 78.172MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_72_QF_UFDTNIA.smt2 |    2.719s | 84.936MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_24_QF_UFDTNIA.smt2 |    2.727s | 74.82MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_2_UFDTNIA.smt2 |    3.499s | 91.044MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2 |    3.549s | 25.28MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_39_QF_UFDTNIA.smt2 |    4.303s | 69.772MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_31_QF_UFDTNIA.smt2 |    4.332s | 60.276MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTNIA.smt2 |    4.643s | 67.144MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_23_QF_UFDTNIA.smt2 |    4.791s | 53.608MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_41_QF_UFDTNIA.smt2 |    4.952s | 39.22MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_44_QF_UFDTNIA.smt2 |    5.653s | 67.712MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_1_UFDTNIA.smt2 |    5.778s | 41.772MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTNIA.smt2 |    5.887s | 43.188MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_76_QF_UFDTNIA.smt2 |    6.920s | 140.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2 |    7.347s | 32.2MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTNIA.smt2 |    7.395s | 85.92MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_45_QF_UFDTNIA.smt2 |    7.482s | 59.8MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_27_QF_UFDTNIA.smt2 |    8.722s | 124.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTNIA.smt2 |    8.925s | 69.992MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_46_QF_UFDTNIA.smt2 |    9.270s | 62.844MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2 |   15.438s | 134.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_74_QF_UFDTNIA.smt2 |   19.829s | 170.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_62_QF_UFDTNIA.smt2 |   20.011s | 28.416MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_63_QF_UFDTNIA.smt2 |   20.013s | 28.976MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_71_QF_UFDTNIA.smt2 |   20.013s | 29.364MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_61_QF_UFDTNIA.smt2 |   20.013s | 35.44MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_34_QF_UFDTNIA.smt2 |   20.014s | 33.08MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTNIA.smt2 |   20.017s | 44.316MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTNIA.smt2 |   20.019s | 87.156MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_36_QF_UFDTNIA.smt2 |   20.024s | 35.1MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_57_QF_UFDTNIA.smt2 |   20.027s | 27.016MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_5_QF_UFDTNIA.smt2 |   20.032s | 40.576MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_55_QF_UFDTNIA.smt2 |   20.032s | 23.776MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_32_QF_UFDTNIA.smt2 |   20.033s | 197.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTNIA.smt2 |   20.034s | 88.656MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTNIA.smt2 |   20.034s | 75.744MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_70_QF_UFDTNIA.smt2 |   20.035s | 41.492MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2 |   20.037s | 38.608MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_73_QF_UFDTNIA.smt2 |   20.038s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_4_UFDTNIA.smt2 |   20.040s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_29_QF_UFDTNIA.smt2 |   20.041s | 186.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_3_UFDTNIA.smt2 |   20.047s | 46.772MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_525a1ca0331f2bcbf520_54_QF_UFDTNIA.smt2 |   20.048s | 125.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_798593962ee29ad45ac8_52_QF_UFDTNIA.smt2 |   20.049s | 71.752MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_38_QF_UFDTNIA.smt2 |   20.049s | 229.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_35_QF_UFDTNIA.smt2 |   20.049s | 33.96MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2 |   20.050s | 51.052MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_56_QF_UFDTNIA.smt2 |   20.050s | 58.768MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2 |   20.051s | 57.976MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTNIA.smt2 |   20.051s | 61.652MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20240410-certora/nia-splits/0010.smt2 |   20.052s | 116.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20240410-certora/lia-splits/0011.smt2 |   20.054s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20240410-certora/nia/0013.smt2    |   20.054s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_75_QF_UFDTNIA.smt2 |   20.055s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTNIA.smt2 |   20.061s | 191.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_5990a6bf5f2740164f77_50_QF_UFDTNIA.smt2 |   20.063s | 202.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20240410-certora/lia/0014.smt2    |   20.064s | 237.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_30_QF_UFDTNIA.smt2 |   20.066s | 180.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_33_QF_UFDTNIA.smt2 |   20.066s | 181.0MiB| timeout | 0 |  |  |
