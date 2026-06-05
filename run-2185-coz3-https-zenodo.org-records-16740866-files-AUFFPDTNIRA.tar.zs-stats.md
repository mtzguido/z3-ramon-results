# .

* SAT 0
* UNSAT 32
* TIMEOUT 76
* UNKNOWN 58

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/AUFFPDTNIRA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-AUFFPDTNIRA.tar.zs
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 branch: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFFPDTNIRA.tar.zst?download=1
Z3 commit message: Use the minimum generation number among matching enodes (#9405)

* Compute term generations based on minimal match

* Tidy up get_*_f_app

* Update euf_mam to the minimum generation number among matches

* Update euf_mam.cpp

* Move the UNREACHABLE() test to smt_mam.cpp

* Enforce stickiness of max-generation

* Add current generation tracking to bind structure

* Fix build error

---------

Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_34_24_discriminant_check___00.smt2 |    0.025s | 19.896MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c213c3_homothetical-T-defqtvc__00.smt2 |    0.026s | 20.98MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d741d4_generic_float_tests-T-defqtvc__00.smt2 |    0.026s | 20.924MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB28-028__float_bounds__floats.adb_5_22_assert___00.smt2 |    0.028s | 20.94MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_52_initialization___00.smt2 |    0.029s | 20.728MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bc608c_homothetical-T-defqtvc__00.smt2 |    0.031s | 21.172MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-011__expbug__repr.adb_16_27_index_check___00.smt2 |    0.032s | 20.9MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_39_10_index_check___00.smt2 |    0.038s | 19.604MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_32_24_discriminant_check___00.smt2 |    0.039s | 20.164MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB28-028__float_bounds__floats.adb_6_22_assert___00.smt2 |    0.039s | 20.912MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_166_16_precondition___00.smt2 |    0.040s | 21.648MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_50_25_index_check___00.smt2 |    0.040s | 19.908MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bec82f_homothetical-T-defqtvc__00.smt2 |    0.041s | 21.16MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_39_19_index_check___00.smt2 |    0.041s | 19.868MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0564ae_homothetical-T-defqtvc__00.smt2 |    0.042s | 20.876MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c64ebb_homothetical-T-defqtvc__00.smt2 |    0.043s | 20.992MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_75_39_range_check___00.smt2 |    0.044s | 20.188MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6ba6c3_homothetical-T-defqtvc__00.smt2 |    0.044s | 20.924MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_135_16_precondition___00.smt2 |    0.044s | 21.888MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB29-020__float_bounds__floats.adb_12_16_assert___00.smt2 |    0.044s | 21.188MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_131422_homothetical-T-defqtvc__00.smt2 |    0.044s | 21.112MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_69_60_fp_overflow_check___00.smt2 |    0.045s | 20.876MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/O429-046__flow_tasking_cfg__test.adb_6_11_ceiling__priority_protocol___00.smt2 |    0.045s | 19.856MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB28-028__float_bounds__floats.adb_4_22_assert___00.smt2 |    0.046s | 21.0MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_63f7dc_homothetical-T-defqtvc__00.smt2 |    0.046s | 20.856MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_51_27_index_check___00.smt2 |    0.046s | 19.668MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__spark-test_array_lemmas.ads_73_19_index_check___00.smt2 |    0.047s | 20.492MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_23_28_range_check___00.smt2 |    0.047s | 20.884MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5fb9ed_homothetical-T-defqtvc__00.smt2 |    0.049s | 20.924MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_65_21_range_check___00.smt2 |    0.049s | 19.932MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d9d866_homothetical-T-defqtvc__00.smt2 |    0.049s | 20.884MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_51_31_discriminant_check___00.smt2 |    0.050s | 19.872MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_23_index_check___00.smt2 |    0.050s | 19.724MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_dd9334_generic_float_tests-T-defqtvc__00.smt2 |    0.050s | 20.816MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_40_10_index_check___00.smt2 |    0.051s | 19.808MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P920-005__inline__access_inline.adb_18_22_access_inline.adb_22_4_range_check___00.smt2 |    0.052s | 20.876MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_57adbf_homothetical-T-defqtvc__00.smt2 |    0.052s | 20.88MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_af2921_homothetical-T-defqtvc__00.smt2 |    0.053s | 20.88MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_18_initialization___00.smt2 |    0.054s | 20.924MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_71_60_fp_overflow_check___00.smt2 |    0.054s | 21.348MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_efd45c_homothetical-T-defqtvc__00.smt2 |    0.054s | 21.124MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ad70de_homothetical-T-defqtvc__00.smt2 |    0.054s | 20.936MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bd1d22_homothetical-T-defqtvc__00.smt2 |    0.054s | 20.972MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a965f2_homothetical-T-defqtvc__00.smt2 |    0.055s | 20.944MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_be413e_homothetical-T-defqtvc__00.smt2 |    0.056s | 20.892MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_58_15_loop_invariant_init___00.smt2 |    0.056s | 21.088MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a146b6_homothetical-T-defqtvc__00.smt2 |    0.057s | 20.872MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_004a8e_homothetical-T-defqtvc__00.smt2 |    0.057s | 20.792MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-unconstrained_array_lemmas.ads_56_56_a.adb_7_4_index_check___00.smt2 |    0.057s | 20.408MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_11_58_division_check___00.smt2 |    0.057s | 20.116MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_adae78_homothetical-T-defqtvc__00.smt2 |    0.058s | 21.164MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_71ca97_homothetical-T-defqtvc__00.smt2 |    0.058s | 21.008MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_139120_homothetical-T-defqtvc__00.smt2 |    0.059s | 20.884MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_47_index_check___00.smt2 |    0.059s | 20.116MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_70_5_precondition___00.smt2 |    0.060s | 21.096MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_37_28_index_check___00.smt2 |    0.061s | 19.628MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_200_22_assert___00.smt2 |    0.061s | 21.652MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6ce0dc_homothetical-T-defqtvc__00.smt2 |    0.062s | 20.916MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_89_15_postcondition___00.smt2 |    0.062s | 21.496MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_64_21_range_check___00.smt2 |    0.064s | 20.368MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_70_60_fp_overflow_check___00.smt2 |    0.065s | 20.868MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_372ec1_homothetical-T-defqtvc__00.smt2 |    0.067s | 20.872MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.ads_7_19_postcondition___00.smt2 |    0.068s | 19.86MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_74_9_ceiling__priority_protocol___00.smt2 |    0.068s | 20.408MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_198_22_assert___00.smt2 |    0.069s | 22.148MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_59_23_index_check___00.smt2 |    0.069s | 19.908MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-test_array_lemmas.ads_73_31_index_check___00.smt2 |    0.070s | 20.42MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P920-005__inline__access_inline.adb_18_22_access_inline.adb_22_4_fp_overflow_check___00.smt2 |    0.072s | 21.14MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_50_46_discriminant_check___00.smt2 |    0.072s | 19.76MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_35_7_range_check___00.smt2 |    0.072s | 19.94MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_10cdb1_homothetical-T-defqtvc__00.smt2 |    0.074s | 21.124MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_50_42_index_check___00.smt2 |    0.077s | 19.712MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8ff0d3_homothetical-T-defqtvc__00.smt2 |    0.077s | 20.928MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7b9ee6_homothetical-T-defqtvc__00.smt2 |    0.078s | 20.812MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-011__expbug__repr.adb_16_30_fp_overflow_check___00.smt2 |    0.083s | 21.036MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB29-020__float_bounds__floats.adb_11_16_assert___00.smt2 |    0.083s | 20.932MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_199_22_assert___00.smt2 |    0.083s | 21.656MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB29-020__float_bounds__floats.adb_13_16_assert___00.smt2 |    0.083s | 20.936MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f25daf_homothetical-T-defqtvc__00.smt2 |    0.084s | 20.848MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_721390_homothetical-T-defqtvc__00.smt2 |    0.084s | 20.836MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7e45aa_homothetical-T-defqtvc__00.smt2 |    0.085s | 20.984MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_197_22_assert___00.smt2 |    0.086s | 21.792MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e82fbc_homothetical-T-defqtvc__00.smt2 |    0.087s | 20.888MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.ads_7_45_overflow_check___00.smt2 |    0.090s | 20.364MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_11_4_range_check___00.smt2 |    0.092s | 19.688MiB| unsat | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ff67ae_homothetical-T-defqtvc__00.smt2 |    0.097s | 21.02MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P920-005__inline__access_inline.adb_18_7_access_inline.adb_22_4_range_check___00.smt2 |    0.098s | 20.972MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ed87a5_homothetical-T-defqtvc__00.smt2 |    0.104s | 20.776MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_158_16_precondition___00.smt2 |    0.110s | 21.532MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_122_22_assert___00.smt2 |    0.116s | 21.896MiB| unknown | 1 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_235_41_test_prime_and_coprime_numbers.adb_6_4_overflow_check___00.smt2 |   20.011s | 23.524MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_217_55_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |   20.012s | 23.66MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_236_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |   20.013s | 23.468MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_231_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |   20.013s | 23.584MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_213_56_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |   20.015s | 23.7MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_213_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |   20.016s | 23.432MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_229_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |   20.018s | 23.44MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_11_52_range_check___00.smt2 |   20.021s | 22.804MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_232_35_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |   20.022s | 23.7MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_226_30_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |   20.022s | 23.664MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_215_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.022s | 23.436MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_237_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |   20.026s | 23.728MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_198_16_test_prime_and_coprime_numbers.adb_6_4_postcondition___00.smt2 |   20.029s | 23.712MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_209_39_test_prime_and_coprime_numbers.adb_6_4_precondition___00.smt2 |   20.030s | 23.696MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_237_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.031s | 23.732MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_222_26_test_prime_and_coprime_numbers.adb_6_4_overflow_check___00.smt2 |   20.031s | 23.728MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_231_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.031s | 23.764MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_216_29_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |   20.033s | 23.684MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_236_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.034s | 23.496MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_14_23_range_check___00.smt2 |   20.035s | 233.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_13_23_range_check___00.smt2 |   20.035s | 233.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_219_27_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |   20.035s | 23.692MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.adb_33_25_overflow_check___00.smt2 |   20.036s | 47.072MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_233_62_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |   20.036s | 23.556MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_211_33_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.038s | 23.648MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_229_62_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |   20.039s | 23.492MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_239_35_test_prime_and_coprime_numbers.adb_6_4_overflow_check___00.smt2 |   20.039s | 23.468MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_229_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.041s | 23.952MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_213_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.042s | 23.6MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_209_39_test_prime_and_coprime_numbers.adb_6_4_range_check___00.smt2 |   20.043s | 23.572MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/NC06-004__init__circle_demo.adb_14_14_precondition___00.smt2 |   20.043s | 404.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_235_63_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |   20.043s | 23.472MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_215_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |   20.043s | 23.712MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.adb_33_25_range_check___00.smt2 |   20.045s | 61.476MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_38_32_range_check___00.smt2 |   20.046s | 401.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/Q328-034__mut_discr__values.adb_30_10_raise___00.smt2 |   20.048s | 365.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_47_29_index_check___00.smt2 |   20.050s | 375.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_15_23_range_check___00.smt2 |   20.054s | 233.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_15_28_length_check___00.smt2 |   20.055s | 23.584MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/O429-046__flow_tasking_cfg__test.adb_8_36_division_check___00.smt2 |   20.056s | 369.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_237_47_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |   20.056s | 23.688MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_29_index_check___00.smt2 |   20.058s | 375.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_58_15_loop_invariant_preserv___00.smt2 |   20.058s | 398.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_17_23_range_check___00.smt2 |   20.059s | 233.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_31_7_range_check___00.smt2 |   20.059s | 354.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_23_22_assert___00.smt2 |   20.060s | 290.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_41_52_initialization___00.smt2 |   20.062s | 270.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_16_23_range_check___00.smt2 |   20.068s | 233.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_26_58_initialization___00.smt2 |   20.071s | 401.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_45_index_check___00.smt2 |   20.072s | 375.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_11_19_assert___00.smt2 |   20.074s | 319.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_22_9_precondition___00.smt2 |   20.075s | 291.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_211_33_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |   20.076s | 23.56MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_26_33_discriminant_check___00.smt2 |   20.076s | 401.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_41_27_discriminant_check___00.smt2 |   20.077s | 401.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_22_34_range_check___00.smt2 |   20.077s | 290.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_21_19_assert___00.smt2 |   20.078s | 320.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-unconstrained_array_lemmas.ads_56_46_a.adb_7_4_overflow_check___00.smt2 |   20.080s | 283.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_25_33_discriminant_check___00.smt2 |   20.082s | 270.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_38_15_loop_invariant_init___00.smt2 |   20.082s | 401.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_32_30_range_check___00.smt2 |   20.083s | 270.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_41_52_discriminant_check___00.smt2 |   20.084s | 401.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_10_19_assert___00.smt2 |   20.085s | 320.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-unconstrained_array_lemmas.ads_56_39_a.adb_7_4_index_check___00.smt2 |   20.085s | 283.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_49_initialization___00.smt2 |   20.086s | 375.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_46_21_postcondition___00.smt2 |   20.086s | 407.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_24_initialization___00.smt2 |   20.088s | 375.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_71_20_assert___00.smt2 |   20.088s | 417.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_23_21_postcondition___00.smt2 |   20.089s | 401.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_20_19_assert___00.smt2 |   20.092s | 320.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_40_27_discriminant_check___00.smt2 |   20.093s | 269.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_26_58_discriminant_check___00.smt2 |   20.094s | 401.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_38_15_loop_invariant_preserv___00.smt2 |   20.099s | 401.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_17_22_range_check___00.smt2 |   20.099s | 366.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_22_49_range_check___00.smt2 |   20.103s | 290.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.ads_32_19_postcondition___00.smt2 |   20.247s | 3226.0MiB| timeout | 0 |  |  |
