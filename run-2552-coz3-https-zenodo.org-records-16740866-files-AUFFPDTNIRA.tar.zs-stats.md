# .

* SAT 0
* UNSAT 139
* TIMEOUT 27
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/AUFFPDTNIRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-AUFFPDTNIRA.tar.zs
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFFPDTNIRA.tar.zst?download=1
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
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_217_55_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |    0.024s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_233_62_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |    0.025s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e82fbc_homothetical-T-defqtvc__00.smt2 |    0.030s | 19.932MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_45_index_check___00.smt2 |    0.030s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_11_4_range_check___00.smt2 |    0.034s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_25_33_discriminant_check___00.smt2 |    0.038s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6ce0dc_homothetical-T-defqtvc__00.smt2 |    0.039s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_236_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.046s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_004a8e_homothetical-T-defqtvc__00.smt2 |    0.046s | 20.316MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/O429-046__flow_tasking_cfg__test.adb_8_36_division_check___00.smt2 |    0.046s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB29-020__float_bounds__floats.adb_13_16_assert___00.smt2 |    0.046s | 20.632MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_15_23_range_check___00.smt2 |    0.047s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_39_10_index_check___00.smt2 |    0.048s | 20.076MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bd1d22_homothetical-T-defqtvc__00.smt2 |    0.049s | 21.144MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_71_20_assert___00.smt2 |    0.049s | 21.376MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB28-028__float_bounds__floats.adb_4_22_assert___00.smt2 |    0.051s | 20.424MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_efd45c_homothetical-T-defqtvc__00.smt2 |    0.051s | 20.076MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_16_23_range_check___00.smt2 |    0.051s | 21.256MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_63f7dc_homothetical-T-defqtvc__00.smt2 |    0.052s | 20.092MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_af2921_homothetical-T-defqtvc__00.smt2 |    0.052s | 19.756MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7e45aa_homothetical-T-defqtvc__00.smt2 |    0.052s | 20.084MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_39_19_index_check___00.smt2 |    0.052s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_26_33_discriminant_check___00.smt2 |    0.052s | 19.816MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5fb9ed_homothetical-T-defqtvc__00.smt2 |    0.054s | 21.132MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_49_initialization___00.smt2 |    0.054s | 20.792MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0564ae_homothetical-T-defqtvc__00.smt2 |    0.054s | 19.912MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_47_29_index_check___00.smt2 |    0.056s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_23_index_check___00.smt2 |    0.056s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_74_9_ceiling__priority_protocol___00.smt2 |    0.056s | 20.332MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_17_23_range_check___00.smt2 |    0.058s | 21.088MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7b9ee6_homothetical-T-defqtvc__00.smt2 |    0.059s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_24_initialization___00.smt2 |    0.059s | 21.144MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_18_initialization___00.smt2 |    0.061s | 21.344MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P920-005__inline__access_inline.adb_18_7_access_inline.adb_22_4_range_check___00.smt2 |    0.061s | 22.756MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_40_27_discriminant_check___00.smt2 |    0.061s | 19.872MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_213_56_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.062s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_51_27_index_check___00.smt2 |    0.062s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_71ca97_homothetical-T-defqtvc__00.smt2 |    0.063s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-unconstrained_array_lemmas.ads_56_39_a.adb_7_4_index_check___00.smt2 |    0.063s | 20.84MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_22_49_range_check___00.smt2 |    0.063s | 19.628MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d9d866_homothetical-T-defqtvc__00.smt2 |    0.063s | 19.956MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_40_10_index_check___00.smt2 |    0.065s | 20.072MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_41_27_discriminant_check___00.smt2 |    0.065s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB28-028__float_bounds__floats.adb_5_22_assert___00.smt2 |    0.066s | 20.944MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_20_19_assert___00.smt2 |    0.067s | 20.848MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_38_32_range_check___00.smt2 |    0.068s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bec82f_homothetical-T-defqtvc__00.smt2 |    0.068s | 21.384MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c213c3_homothetical-T-defqtvc__00.smt2 |    0.068s | 20.86MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB29-020__float_bounds__floats.adb_11_16_assert___00.smt2 |    0.070s | 20.636MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/O429-046__flow_tasking_cfg__test.adb_6_11_ceiling__priority_protocol___00.smt2 |    0.071s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c64ebb_homothetical-T-defqtvc__00.smt2 |    0.072s | 19.712MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__spark-test_array_lemmas.ads_73_19_index_check___00.smt2 |    0.072s | 20.408MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_215_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.074s | 23.792MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_211_33_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.075s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_232_35_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.075s | 23.952MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_226_30_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.075s | 20.376MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_75_39_range_check___00.smt2 |    0.076s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_37_28_index_check___00.smt2 |    0.077s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_50_46_discriminant_check___00.smt2 |    0.077s | 19.772MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_131422_homothetical-T-defqtvc__00.smt2 |    0.077s | 20.392MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_23_28_range_check___00.smt2 |    0.078s | 21.1MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ed87a5_homothetical-T-defqtvc__00.smt2 |    0.078s | 20.076MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bc608c_homothetical-T-defqtvc__00.smt2 |    0.078s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_11_58_division_check___00.smt2 |    0.079s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB28-028__float_bounds__floats.adb_6_22_assert___00.smt2 |    0.080s | 20.672MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_236_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |    0.081s | 23.876MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_58_15_loop_invariant_preserv___00.smt2 |    0.082s | 21.24MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_50_25_index_check___00.smt2 |    0.082s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_211_33_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |    0.083s | 23.952MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_29_index_check___00.smt2 |    0.084s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_32_24_discriminant_check___00.smt2 |    0.084s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_41_52_discriminant_check___00.smt2 |    0.084s | 20.332MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_219_27_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.084s | 23.68MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_209_39_test_prime_and_coprime_numbers.adb_6_4_precondition___00.smt2 |    0.087s | 19.66MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_57adbf_homothetical-T-defqtvc__00.smt2 |    0.088s | 20.348MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_21_19_assert___00.smt2 |    0.089s | 21.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_be413e_homothetical-T-defqtvc__00.smt2 |    0.089s | 20.92MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ff67ae_homothetical-T-defqtvc__00.smt2 |    0.089s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB29-020__float_bounds__floats.adb_12_16_assert___00.smt2 |    0.089s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_70_5_precondition___00.smt2 |    0.090s | 21.132MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_58_15_loop_invariant_init___00.smt2 |    0.091s | 21.144MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_22_34_range_check___00.smt2 |    0.091s | 20.572MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_11_19_assert___00.smt2 |    0.092s | 20.628MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P920-005__inline__access_inline.adb_18_22_access_inline.adb_22_4_fp_overflow_check___00.smt2 |    0.094s | 23.416MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_235_41_test_prime_and_coprime_numbers.adb_6_4_overflow_check___00.smt2 |    0.097s | 24.136MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_229_62_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.100s | 20.584MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_216_29_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.101s | 23.736MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_23_22_assert___00.smt2 |    0.103s | 22.928MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_adae78_homothetical-T-defqtvc__00.smt2 |    0.103s | 20.756MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_65_21_range_check___00.smt2 |    0.103s | 20.028MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_64_21_range_check___00.smt2 |    0.104s | 20.324MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d741d4_generic_float_tests-T-defqtvc__00.smt2 |    0.104s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a965f2_homothetical-T-defqtvc__00.smt2 |    0.105s | 21.548MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_35_7_range_check___00.smt2 |    0.107s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_15_28_length_check___00.smt2 |    0.109s | 21.348MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_239_35_test_prime_and_coprime_numbers.adb_6_4_overflow_check___00.smt2 |    0.109s | 24.204MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_222_26_test_prime_and_coprime_numbers.adb_6_4_overflow_check___00.smt2 |    0.110s | 24.096MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_22_9_precondition___00.smt2 |    0.113s | 21.684MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a146b6_homothetical-T-defqtvc__00.smt2 |    0.118s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-unconstrained_array_lemmas.ads_56_56_a.adb_7_4_index_check___00.smt2 |    0.121s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_26_58_discriminant_check___00.smt2 |    0.122s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_237_47_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |    0.122s | 19.976MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.ads_7_19_postcondition___00.smt2 |    0.122s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-test_array_lemmas.ads_73_31_index_check___00.smt2 |    0.123s | 20.864MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-unconstrained_array_lemmas.ads_56_46_a.adb_7_4_overflow_check___00.smt2 |    0.124s | 20.68MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_dd9334_generic_float_tests-T-defqtvc__00.smt2 |    0.125s | 20.528MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ad70de_homothetical-T-defqtvc__00.smt2 |    0.125s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_50_42_index_check___00.smt2 |    0.126s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_59_23_index_check___00.smt2 |    0.126s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_52_initialization___00.smt2 |    0.127s | 20.752MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8ff0d3_homothetical-T-defqtvc__00.smt2 |    0.127s | 20.072MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_14_23_range_check___00.smt2 |    0.128s | 21.124MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_10_19_assert___00.smt2 |    0.128s | 20.928MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_47_index_check___00.smt2 |    0.128s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_51_31_discriminant_check___00.smt2 |    0.129s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_10cdb1_homothetical-T-defqtvc__00.smt2 |    0.129s | 21.136MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_34_24_discriminant_check___00.smt2 |    0.129s | 19.956MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_46_21_postcondition___00.smt2 |    0.129s | 20.92MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.ads_7_45_overflow_check___00.smt2 |    0.129s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P920-005__inline__access_inline.adb_18_22_access_inline.adb_22_4_range_check___00.smt2 |    0.133s | 23.168MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_13_23_range_check___00.smt2 |    0.134s | 20.9MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_235_63_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |    0.149s | 24.22MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_213_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.168s | 24.716MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_231_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.173s | 25.816MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_229_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.218s | 25.356MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_231_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |    0.254s | 26.248MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_89_15_postcondition___00.smt2 |    0.256s | 26.692MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_229_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |    0.257s | 25.492MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_237_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.307s | 28.812MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_721390_homothetical-T-defqtvc__00.smt2 |    0.419s | 108.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6ba6c3_homothetical-T-defqtvc__00.smt2 |    0.448s | 110.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_139120_homothetical-T-defqtvc__00.smt2 |    0.478s | 124.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_372ec1_homothetical-T-defqtvc__00.smt2 |    0.519s | 124.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_26_58_initialization___00.smt2 |    1.365s | 86.104MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_38_15_loop_invariant_init___00.smt2 |    1.468s | 86.544MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_23_21_postcondition___00.smt2 |    1.505s | 88.692MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_41_52_initialization___00.smt2 |    1.992s | 86.128MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-011__expbug__repr.adb_16_30_fp_overflow_check___00.smt2 |    6.170s | 49.972MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_38_15_loop_invariant_preserv___00.smt2 |    8.825s | 281.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_11_52_range_check___00.smt2 |   20.032s | 30.144MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/NC06-004__init__circle_demo.adb_14_14_precondition___00.smt2 |   20.045s | 184.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_166_16_precondition___00.smt2 |   20.047s | 110.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_70_60_fp_overflow_check___00.smt2 |   20.049s | 185.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_69_60_fp_overflow_check___00.smt2 |   20.055s | 175.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_31_7_range_check___00.smt2 |   20.057s | 237.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_158_16_precondition___00.smt2 |   20.060s | 89.016MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_213_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.061s | 110.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_215_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.064s | 328.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f25daf_homothetical-T-defqtvc__00.smt2 |   20.066s | 125.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_199_22_assert___00.smt2 |   20.066s | 79.288MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.adb_33_25_overflow_check___00.smt2 |   20.070s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_198_22_assert___00.smt2 |   20.085s | 104.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_200_22_assert___00.smt2 |   20.087s | 81.036MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_209_39_test_prime_and_coprime_numbers.adb_6_4_range_check___00.smt2 |   20.090s | 27.784MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_197_22_assert___00.smt2 |   20.095s | 67.972MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_17_22_range_check___00.smt2 |   20.096s | 201.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.adb_33_25_range_check___00.smt2 |   20.099s | 195.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_71_60_fp_overflow_check___00.smt2 |   20.099s | 187.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_237_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.100s | 318.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_32_30_range_check___00.smt2 |   20.103s | 538.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.ads_32_19_postcondition___00.smt2 |   20.109s | 340.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-011__expbug__repr.adb_16_27_index_check___00.smt2 |   20.117s | 94.9MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_122_22_assert___00.smt2 |   20.117s | 81.296MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_135_16_precondition___00.smt2 |   20.119s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/Q328-034__mut_discr__values.adb_30_10_raise___00.smt2 |   20.123s | 394.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_198_16_test_prime_and_coprime_numbers.adb_6_4_postcondition___00.smt2 |   20.127s | 226.0MiB| timeout | 0 |  |  |
