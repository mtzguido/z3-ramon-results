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
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFFPDTNIRA.tar.zst?download=1
Z3 commit message: Fix instance of "flexible array member". (#9883)

This is another PR towards the goal of getting a clean build with clang,
using the compiler options used in building clang-tidy.

In https://github.com/Z3Prover/z3/pull/9800, we changed the build flags
to eliminate a warning for zero-length arrays. In that PR, I missed this
one: there was one instance of m_arr[] instead of m_arr[0]. In the
clang-tidy build, that gives warnings like:
```
/Users/daviddetlefs/llvm-project/build_dbg/_deps/z3-src/src/model/func_interp.h:43:12: warning: flexible array members are a C99 feature [-Wc99-extensions]
```

The PR fixes this, making it a zero-length array, the idiom used in all
the other similar cases. I also added the compiler flag that produced
this warning, so we can notice such changes in the future.

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_41_27_discriminant_check___00.smt2 |    0.015s | 19.408MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.ads_7_19_postcondition___00.smt2 |    0.015s | 19.308MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6ce0dc_homothetical-T-defqtvc__00.smt2 |    0.016s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ed87a5_homothetical-T-defqtvc__00.smt2 |    0.016s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c64ebb_homothetical-T-defqtvc__00.smt2 |    0.017s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_41_52_discriminant_check___00.smt2 |    0.017s | 19.368MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bc608c_homothetical-T-defqtvc__00.smt2 |    0.017s | 19.3MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_23_index_check___00.smt2 |    0.018s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_64_21_range_check___00.smt2 |    0.018s | 19.4MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_47_index_check___00.smt2 |    0.018s | 19.408MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_51_31_discriminant_check___00.smt2 |    0.019s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_211_33_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.019s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_11_58_division_check___00.smt2 |    0.019s | 19.352MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_51_27_index_check___00.smt2 |    0.019s | 19.38MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_39_10_index_check___00.smt2 |    0.019s | 19.332MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_59_23_index_check___00.smt2 |    0.019s | 19.412MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_237_47_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |    0.019s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_131422_homothetical-T-defqtvc__00.smt2 |    0.019s | 19.94MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_58_15_loop_invariant_init___00.smt2 |    0.020s | 20.328MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB29-020__float_bounds__floats.adb_11_16_assert___00.smt2 |    0.020s | 20.02MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c213c3_homothetical-T-defqtvc__00.smt2 |    0.020s | 20.28MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_45_index_check___00.smt2 |    0.020s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_adae78_homothetical-T-defqtvc__00.smt2 |    0.021s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/O429-046__flow_tasking_cfg__test.adb_6_11_ceiling__priority_protocol___00.smt2 |    0.021s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ad70de_homothetical-T-defqtvc__00.smt2 |    0.021s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_22_49_range_check___00.smt2 |    0.021s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_34_24_discriminant_check___00.smt2 |    0.022s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_dd9334_generic_float_tests-T-defqtvc__00.smt2 |    0.022s | 20.012MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_74_9_ceiling__priority_protocol___00.smt2 |    0.022s | 19.636MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_213_56_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.023s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_233_62_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |    0.023s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_29_index_check___00.smt2 |    0.023s | 19.408MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_22_34_range_check___00.smt2 |    0.023s | 19.964MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_26_58_discriminant_check___00.smt2 |    0.023s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_50_42_index_check___00.smt2 |    0.023s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_57adbf_homothetical-T-defqtvc__00.smt2 |    0.023s | 19.356MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-unconstrained_array_lemmas.ads_56_46_a.adb_7_4_overflow_check___00.smt2 |    0.023s | 19.816MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_236_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.024s | 19.252MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5fb9ed_homothetical-T-defqtvc__00.smt2 |    0.024s | 20.324MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_10_19_assert___00.smt2 |    0.024s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0564ae_homothetical-T-defqtvc__00.smt2 |    0.024s | 19.36MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ff67ae_homothetical-T-defqtvc__00.smt2 |    0.024s | 19.408MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_39_19_index_check___00.smt2 |    0.024s | 19.336MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_11_19_assert___00.smt2 |    0.024s | 20.036MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB28-028__float_bounds__floats.adb_6_22_assert___00.smt2 |    0.024s | 19.992MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-test_array_lemmas.ads_73_31_index_check___00.smt2 |    0.024s | 19.72MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB29-020__float_bounds__floats.adb_13_16_assert___00.smt2 |    0.024s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8ff0d3_homothetical-T-defqtvc__00.smt2 |    0.024s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_47_29_index_check___00.smt2 |    0.025s | 19.268MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a146b6_homothetical-T-defqtvc__00.smt2 |    0.025s | 19.236MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_13_23_range_check___00.smt2 |    0.025s | 20.16MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_63f7dc_homothetical-T-defqtvc__00.smt2 |    0.025s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-unconstrained_array_lemmas.ads_56_56_a.adb_7_4_index_check___00.smt2 |    0.025s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_be413e_homothetical-T-defqtvc__00.smt2 |    0.025s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_50_46_discriminant_check___00.smt2 |    0.025s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_26_33_discriminant_check___00.smt2 |    0.025s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_52_initialization___00.smt2 |    0.025s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_50_25_index_check___00.smt2 |    0.025s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.ads_7_45_overflow_check___00.smt2 |    0.025s | 20.024MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e82fbc_homothetical-T-defqtvc__00.smt2 |    0.026s | 19.368MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_14_23_range_check___00.smt2 |    0.026s | 20.28MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7b9ee6_homothetical-T-defqtvc__00.smt2 |    0.026s | 19.408MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_209_39_test_prime_and_coprime_numbers.adb_6_4_precondition___00.smt2 |    0.026s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_71ca97_homothetical-T-defqtvc__00.smt2 |    0.026s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_23_28_range_check___00.smt2 |    0.026s | 20.376MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_75_39_range_check___00.smt2 |    0.026s | 19.62MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_24_initialization___00.smt2 |    0.026s | 20.308MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bec82f_homothetical-T-defqtvc__00.smt2 |    0.026s | 20.408MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_217_55_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |    0.026s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-unconstrained_array_lemmas.ads_56_39_a.adb_7_4_index_check___00.smt2 |    0.026s | 20.004MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_15_23_range_check___00.smt2 |    0.026s | 20.452MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_004a8e_homothetical-T-defqtvc__00.smt2 |    0.027s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_38_32_range_check___00.smt2 |    0.027s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_efd45c_homothetical-T-defqtvc__00.smt2 |    0.027s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_229_62_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.027s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_35_7_range_check___00.smt2 |    0.027s | 19.572MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_15_28_length_check___00.smt2 |    0.028s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_21_19_assert___00.smt2 |    0.028s | 20.6MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_23_22_assert___00.smt2 |    0.028s | 22.504MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_37_28_index_check___00.smt2 |    0.028s | 19.304MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_40_10_index_check___00.smt2 |    0.028s | 19.312MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_226_30_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.028s | 19.748MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_46_21_postcondition___00.smt2 |    0.028s | 20.188MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB29-020__float_bounds__floats.adb_12_16_assert___00.smt2 |    0.028s | 20.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d9d866_homothetical-T-defqtvc__00.smt2 |    0.028s | 19.388MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d741d4_generic_float_tests-T-defqtvc__00.smt2 |    0.028s | 20.248MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_25_33_discriminant_check___00.smt2 |    0.029s | 19.412MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_32_24_discriminant_check___00.smt2 |    0.029s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7e45aa_homothetical-T-defqtvc__00.smt2 |    0.029s | 19.404MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bd1d22_homothetical-T-defqtvc__00.smt2 |    0.029s | 20.508MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_40_27_discriminant_check___00.smt2 |    0.029s | 19.308MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_49_initialization___00.smt2 |    0.030s | 20.152MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_65_21_range_check___00.smt2 |    0.030s | 19.432MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_11_4_range_check___00.smt2 |    0.030s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB28-028__float_bounds__floats.adb_5_22_assert___00.smt2 |    0.030s | 20.004MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__spark-test_array_lemmas.ads_73_19_index_check___00.smt2 |    0.031s | 19.732MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_58_15_loop_invariant_preserv___00.smt2 |    0.031s | 20.548MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_71_20_assert___00.smt2 |    0.031s | 20.348MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P920-005__inline__access_inline.adb_18_22_access_inline.adb_22_4_range_check___00.smt2 |    0.032s | 22.212MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P920-005__inline__access_inline.adb_18_22_access_inline.adb_22_4_fp_overflow_check___00.smt2 |    0.032s | 22.124MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a965f2_homothetical-T-defqtvc__00.smt2 |    0.032s | 20.796MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_16_23_range_check___00.smt2 |    0.032s | 20.304MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_20_19_assert___00.smt2 |    0.033s | 20.308MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_22_9_precondition___00.smt2 |    0.034s | 21.128MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_10cdb1_homothetical-T-defqtvc__00.smt2 |    0.034s | 20.48MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/O429-046__flow_tasking_cfg__test.adb_8_36_division_check___00.smt2 |    0.034s | 19.312MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB28-028__float_bounds__floats.adb_4_22_assert___00.smt2 |    0.035s | 19.984MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_17_23_range_check___00.smt2 |    0.035s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_af2921_homothetical-T-defqtvc__00.smt2 |    0.036s | 19.424MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_70_5_precondition___00.smt2 |    0.036s | 20.38MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_18_initialization___00.smt2 |    0.037s | 20.396MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P920-005__inline__access_inline.adb_18_7_access_inline.adb_22_4_range_check___00.smt2 |    0.037s | 22.428MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_215_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.040s | 23.252MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_222_26_test_prime_and_coprime_numbers.adb_6_4_overflow_check___00.smt2 |    0.040s | 23.636MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_235_63_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |    0.042s | 23.468MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_235_41_test_prime_and_coprime_numbers.adb_6_4_overflow_check___00.smt2 |    0.043s | 23.536MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_216_29_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.044s | 23.308MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_232_35_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.046s | 23.232MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_219_27_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.046s | 23.284MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_239_35_test_prime_and_coprime_numbers.adb_6_4_overflow_check___00.smt2 |    0.047s | 23.564MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_236_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |    0.050s | 23.26MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_211_33_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |    0.050s | 23.192MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_213_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.137s | 24.136MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_229_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.148s | 24.656MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_229_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |    0.176s | 24.8MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_231_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.208s | 25.48MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_89_15_postcondition___00.smt2 |    0.234s | 26.196MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_231_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |    0.241s | 25.668MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_237_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.292s | 28.292MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_721390_homothetical-T-defqtvc__00.smt2 |    0.355s | 108.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6ba6c3_homothetical-T-defqtvc__00.smt2 |    0.369s | 110.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_372ec1_homothetical-T-defqtvc__00.smt2 |    0.399s | 123.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_139120_homothetical-T-defqtvc__00.smt2 |    0.433s | 124.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_38_15_loop_invariant_init___00.smt2 |    1.547s | 85.924MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_26_58_initialization___00.smt2 |    1.583s | 85.496MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_23_21_postcondition___00.smt2 |    1.734s | 87.956MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_41_52_initialization___00.smt2 |    2.336s | 85.336MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-011__expbug__repr.adb_16_30_fp_overflow_check___00.smt2 |    6.388s | 49.484MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_38_15_loop_invariant_preserv___00.smt2 |   11.102s | 280.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_209_39_test_prime_and_coprime_numbers.adb_6_4_range_check___00.smt2 |   20.009s | 27.232MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_199_22_assert___00.smt2 |   20.010s | 77.66MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_197_22_assert___00.smt2 |   20.011s | 66.952MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_158_16_precondition___00.smt2 |   20.011s | 84.184MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_213_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.011s | 110.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_11_52_range_check___00.smt2 |   20.011s | 28.512MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.adb_33_25_overflow_check___00.smt2 |   20.012s | 110.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_135_16_precondition___00.smt2 |   20.012s | 122.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f25daf_homothetical-T-defqtvc__00.smt2 |   20.014s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_69_60_fp_overflow_check___00.smt2 |   20.014s | 173.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_70_60_fp_overflow_check___00.smt2 |   20.014s | 177.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/NC06-004__init__circle_demo.adb_14_14_precondition___00.smt2 |   20.015s | 183.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_166_16_precondition___00.smt2 |   20.015s | 109.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-011__expbug__repr.adb_16_27_index_check___00.smt2 |   20.015s | 94.332MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_198_22_assert___00.smt2 |   20.016s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_200_22_assert___00.smt2 |   20.016s | 79.168MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_31_7_range_check___00.smt2 |   20.020s | 233.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_71_60_fp_overflow_check___00.smt2 |   20.021s | 187.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_122_22_assert___00.smt2 |   20.023s | 79.324MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_237_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.026s | 318.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.adb_33_25_range_check___00.smt2 |   20.027s | 195.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_198_16_test_prime_and_coprime_numbers.adb_6_4_postcondition___00.smt2 |   20.027s | 226.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_17_22_range_check___00.smt2 |   20.032s | 201.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.ads_32_19_postcondition___00.smt2 |   20.036s | 339.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_215_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.038s | 327.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/Q328-034__mut_discr__values.adb_30_10_raise___00.smt2 |   20.041s | 394.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_32_30_range_check___00.smt2 |   20.049s | 538.0MiB| timeout | 0 |  |  |
