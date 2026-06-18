# .

* SAT 22
* UNSAT 126
* TIMEOUT 6
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFFPDTNIRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFFPDTNIRA.tar.
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFFPDTNIRA.tar.zst?download=1
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
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8c7880_generic_float_tests-T-defqtvc__00.smt2 |    0.012s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d9224d_generic_float_tests-T-defqtvc__00.smt2 |    0.013s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_748b19_generic_float_tests-T-defqtvc__00.smt2 |    0.014s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_127068_generic_float_tests-T-defqtvc__00.smt2 |    0.014s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8e174b_generic_float_tests-T-defqtvc__00.smt2 |    0.015s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_59_11_disjoint_contract_cases___00.smt2 |    0.016s | 19.328MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ef0acb_generic_float_tests-T-defqtvc__00.smt2 |    0.016s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_3acf14_generic_float_tests-T-defqtvc__00.smt2 |    0.016s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_59_11_complete_contract_cases___00.smt2 |    0.016s | 19.488MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/MB01-007__floating_point__foo.adb_12_4_precondition___00.smt2 |    0.016s | 19.044MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5adf4f_generic_float_tests-T-defqtvc__00.smt2 |    0.016s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_847dc3_generic_float_tests-T-defqtvc__00.smt2 |    0.016s | 19.244MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/S427-002__inline_dim__a-ngelfu.ads_117_36_dimensions.ads_379_4_division_check___00.smt2 |    0.016s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/OB04-007__float_conversion__floatround.adb_7_47_predicate_check___00.smt2 |    0.017s | 18.908MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/S320-040__flow_blocking__a-ngelfu.ads_126_32_p.adb_7_4_division_check___00.smt2 |    0.017s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/S320-040__flow_blocking__a-ngelfu.ads_117_36_p.adb_7_4_division_check___00.smt2 |    0.017s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2cb2b4_generic_float_tests-T-defqtvc__00.smt2 |    0.017s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O810-001__predicate__safety_pack.ads_65_10_predicate_check___00.smt2 |    0.017s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_95a19c_generic_float_tests-T-defqtvc__00.smt2 |    0.017s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a95b75_generic_float_tests-T-defqtvc__00.smt2 |    0.018s | 19.048MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_19_28_division_check___00.smt2 |    0.018s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_13fa28_generic_float_tests-T-defqtvc__00.smt2 |    0.018s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O810-001__predicate__safety_pack.ads_67_10_predicate_check___00.smt2 |    0.019s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_323ba9_generic_float_tests-T-defqtvc__00.smt2 |    0.019s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__sample.ads_13_140_division_check___00.smt2 |    0.019s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_828bbe_generic_float_tests-T-defqtvc__00.smt2 |    0.019s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_567_49_division_check___00.smt2 |    0.021s | 27.688MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d97549_generic_float_tests-T-defqtvc__00.smt2 |    0.022s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_558_44_division_check___00.smt2 |    0.022s | 27.656MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2d2300_generic_interval_tests-T-defqtvc__00.smt2 |    0.022s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O810-001__predicate__safety_pack.ads_69_10_predicate_check___00.smt2 |    0.022s | 27.636MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_eabfeb_generic_float_tests-T-defqtvc__00.smt2 |    0.022s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O810-001__predicate__safety_pack.ads_63_10_predicate_check___00.smt2 |    0.023s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O303-041__flow_pure_implies_null_global__a-ngelfu.ads_127_36_ff.ads_3_1_division_check___00.smt2 |    0.023s | 19.488MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_3943ed_generic_float_tests-T-defqtvc__00.smt2 |    0.024s | 27.732MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_af6b6a_generic_interval_tests-T-defqtvc__00.smt2 |    0.024s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b7409d_generic_float_tests-T-defqtvc__00.smt2 |    0.024s | 27.676MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/N313-022__float_div__example.adb_9_30_division_check___00.smt2 |    0.024s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c87e9d_generic_float_tests-T-defqtvc__00.smt2 |    0.024s | 27.756MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_15_8_disjoint_contract_cases___00.smt2 |    0.025s | 19.984MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__numerics.ads_29_99_division_check___00.smt2 |    0.026s | 18.972MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_47e135_generic_float_tests-T-defqtvc__00.smt2 |    0.027s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-012__justification__numerics.ads_18_99_division_check___00.smt2 |    0.029s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_eb2c36_generic_float_tests-T-defqtvc__00.smt2 |    0.029s | 18.956MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_05d13b_generic_float_tests-T-defqtvc__00.smt2 |    0.029s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d00566_generic_float_tests-T-defqtvc__00.smt2 |    0.029s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_9_17_range_check___00.smt2 |    0.030s | 28.588MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_13_17_range_check___00.smt2 |    0.030s | 28.784MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_15_8_complete_contract_cases___00.smt2 |    0.031s | 19.992MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_420942_generic_float_tests-T-defqtvc__00.smt2 |    0.032s | 19.64MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b2ba6e_generic_float_tests-T-defqtvc__00.smt2 |    0.032s | 27.432MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__original_sample.ads_15_140_division_check___00.smt2 |    0.033s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_32_99_division_check___00.smt2 |    0.033s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_6_17_range_check___00.smt2 |    0.034s | 28.692MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_9b4426_generic_float_tests-T-defqtvc__00.smt2 |    0.036s | 28.536MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/S603-051__dimensions__a-ngelfu.ads_126_32_dimensions.ads_380_4_division_check___00.smt2 |    0.036s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/S603-051__dimensions__a-ngelfu.ads_127_36_dimensions.ads_379_4_division_check___00.smt2 |    0.036s | 20.196MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_3a913e_generic_float_tests-T-defqtvc__00.smt2 |    0.039s | 29.272MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/N917-037__prover_sanity_cvc4__floats.adb_6_4_assert___00.smt2 |    0.040s | 27.52MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5b82bd_generic_float_tests-T-defqtvc__00.smt2 |    0.042s | 29.448MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.ads_8_34_fp_overflow_check___00.smt2 |    0.043s | 29.368MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b0d547_generic_float_tests-T-defqtvc__00.smt2 |    0.044s | 29.52MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_18_17_range_check___00.smt2 |    0.045s | 28.756MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/Q522-022__codepeer__proof.ads_11_14_fp_overflow_check___00.smt2 |    0.045s | 29.504MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__sample.ads_13_128_fp_overflow_check___00.smt2 |    0.046s | 29.376MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/K720-019__floats__pack.adb_5_17_fp_overflow_check___00.smt2 |    0.046s | 29.372MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e70d10_generic_float_tests-T-defqtvc__00.smt2 |    0.047s | 29.412MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e09c2c_reduced_02-T-defqtvc__00.smt2 |    0.047s | 28.988MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_14_23_fp_overflow_check___00.smt2 |    0.048s | 29.428MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c7ccdd_generic_float_tests-T-defqtvc__00.smt2 |    0.049s | 29.584MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_26_99_fp_overflow_check___00.smt2 |    0.050s | 29.484MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_954270_generic_float_tests-T-defqtvc__00.smt2 |    0.050s | 29.248MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__numerics.ads_20_99_fp_overflow_check___00.smt2 |    0.050s | 29.544MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__original_sample.ads_15_128_fp_overflow_check___00.smt2 |    0.056s | 29.416MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_23_99_fp_overflow_check___00.smt2 |    0.057s | 29.452MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_1c77b0_generic_interval_tests-T-defqtvc__00.smt2 |    0.059s | 31.276MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5fd830_generic_float_tests-T-defqtvc__00.smt2 |    0.060s | 28.028MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5636a0_generic_float_tests-T-defqtvc__00.smt2 |    0.061s | 31.424MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O810-001__predicate__safety_pack.ads_15_16_fp_overflow_check___00.smt2 |    0.063s | 29.548MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2bc3b7_generic_float_tests-T-defqtvc__00.smt2 |    0.063s | 31.396MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/MB01-007__floating_point__foo.adb_6_20_fp_overflow_check___00.smt2 |    0.064s | 31.748MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__numerics.ads_23_99_fp_overflow_check___00.smt2 |    0.065s | 29.408MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0c5b8b_generic_float_tests-T-defqtvc__00.smt2 |    0.072s | 31.436MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e14883_generic_interval_tests-T-defqtvc__00.smt2 |    0.072s | 31.156MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7dad36_generic_float_tests-T-defqtvc__00.smt2 |    0.074s | 28.712MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O810-001__predicate__safety_pack.ads_17_16_fp_overflow_check___00.smt2 |    0.078s | 29.48MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7a5c9e_generic_float_tests-T-defqtvc__00.smt2 |    0.090s | 29.388MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_19_23_fp_overflow_check___00.smt2 |    0.093s | 32.504MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6e6909_generic_float_tests-T-defqtvc__00.smt2 |    0.107s | 29.352MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0f94ea_generic_float_tests-T-defqtvc__00.smt2 |    0.117s | 31.092MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a3ff0b_generic_interval_tests-T-defqtvc__00.smt2 |    0.119s | 31.144MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_26_23_range_check___00.smt2 |    0.126s | 36.76MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_cdd303_generic_float_tests-T-defqtvc__00.smt2 |    0.143s | 29.472MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7931fb_generic_interval_tests-T-defqtvc__00.smt2 |    0.154s | 31.956MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0b5f28_generic_interval_tests-T-defqtvc__00.smt2 |    0.161s | 32.112MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c7dfd8_generic_interval_tests-T-defqtvc__00.smt2 |    0.162s | 32.104MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_776e4a_foo-T-defqtvc__00.smt2 |    0.163s | 30.836MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/OA26-022__gnatprove_crash__eg.adb_5_16_fp_overflow_check___00.smt2 |    0.169s | 31.94MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a662fe_generic_float_tests-T-defqtvc__00.smt2 |    0.172s | 31.708MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__numerics.ads_26_99_fp_overflow_check___00.smt2 |    0.172s | 32.028MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_9fa525_generic_float_tests-T-defqtvc__00.smt2 |    0.177s | 31.732MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_29_99_fp_overflow_check___00.smt2 |    0.177s | 31.884MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_826a12_generic_float_tests-T-defqtvc__00.smt2 |    0.179s | 30.516MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_29f8e7_generic_float_tests-T-defqtvc__00.smt2 |    0.184s | 29.268MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6a34dd_generic_float_tests-T-defqtvc__00.smt2 |    0.212s | 57.844MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a33e16_generic_float_tests-T-defqtvc__00.smt2 |    0.235s | 31.764MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ca225b_generic_interval_tests-T-defqtvc__00.smt2 |    0.244s | 31.34MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ed697c_generic_float_tests-T-defqtvc__00.smt2 |    0.248s | 58.2MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8ff7c6_generic_float_tests-T-defqtvc__00.smt2 |    0.256s | 57.912MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2629df_generic_float_tests-T-defqtvc__00.smt2 |    0.260s | 31.344MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e155c1_generic_float_tests-T-defqtvc__00.smt2 |    0.266s | 31.772MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f5486e_generic_float_tests-T-defqtvc__00.smt2 |    0.296s | 31.212MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/MB01-007__floating_point__foo.adb_6_25_fp_overflow_check___00.smt2 |    0.302s | 37.884MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_81dd6b_generic_float_tests-T-defqtvc__00.smt2 |    0.324s | 36.96MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2475ea_generic_float_tests-T-defqtvc__00.smt2 |    0.344s | 31.596MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_aa8637_generic_interval_tests-T-defqtvc__00.smt2 |    0.483s | 31.148MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_640d9e_generic_float_tests-T-defqtvc__00.smt2 |    0.553s | 35.04MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_cd606f_generic_interval_tests-T-defqtvc__00.smt2 |    0.554s | 59.92MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_74557c_generic_interval_tests-T-defqtvc__00.smt2 |    0.555s | 59.5MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_60f230_generic_interval_tests-T-defqtvc__00.smt2 |    0.606s | 63.876MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_49eeb1_generic_interval_tests-T-defqtvc__00.smt2 |    0.609s | 63.748MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2b3a3d_generic_interval_tests-T-defqtvc__00.smt2 |    0.628s | 63.848MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bac632_generic_interval_tests-T-defqtvc__00.smt2 |    0.629s | 60.052MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2d90c4_generic_float_tests-T-defqtvc__00.smt2 |    0.775s | 72.404MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_32_99_fp_overflow_check___00.smt2 |    0.882s | 80.316MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_558_44_fp_overflow_check___00.smt2 |    0.923s | 78.788MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ccb32f_generic_float_tests-T-defqtvc__00.smt2 |    0.930s | 76.752MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2df025_generic_float_tests-T-defqtvc__00.smt2 |    0.934s | 76.268MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__numerics.ads_29_99_fp_overflow_check___00.smt2 |    0.934s | 80.404MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_dd5ac9_generic_float_tests-T-defqtvc__00.smt2 |    0.954s | 31.172MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_07a5cf_generic_interval_tests-T-defqtvc__00.smt2 |    0.957s | 76.256MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0a0ce0_generic_float_tests-T-defqtvc__00.smt2 |    0.960s | 40.088MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-012__justification__numerics.ads_18_99_fp_overflow_check___00.smt2 |    0.979s | 80.332MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__sample.ads_13_140_fp_overflow_check___00.smt2 |    1.036s | 84.628MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__original_sample.ads_15_140_fp_overflow_check___00.smt2 |    1.072s | 84.592MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_382280_generic_float_tests-T-defqtvc__00.smt2 |    1.104s | 328.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_736933_generic_float_tests-T-defqtvc__00.smt2 |    1.213s | 328.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_452d8a_generic_float_tests-T-defqtvc__00.smt2 |    1.238s | 328.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ef7f8e_generic_float_tests-T-defqtvc__00.smt2 |    1.379s | 39.032MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_cefa4e_generic_float_tests-T-defqtvc__00.smt2 |    1.749s | 128.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_558_53_fp_overflow_check___00.smt2 |    1.805s | 97.164MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6dccf4_generic_float_tests-T-defqtvc__00.smt2 |    4.389s | 386.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8fc10b_generic_float_tests-T-defqtvc__00.smt2 |    4.529s | 381.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_759541_generic_interval_tests-T-defqtvc__00.smt2 |    5.191s | 62.92MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_15e1a4_generic_interval_tests-T-defqtvc__00.smt2 |    5.588s | 392.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f8d0db_generic_float_tests-T-defqtvc__00.smt2 |    5.896s | 384.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_da0327_generic_interval_tests-T-defqtvc__00.smt2 |    9.920s | 65.196MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_30ca25_generic_float_tests-T-defqtvc__00.smt2 |   10.382s | 736.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c5e486_generic_float_tests-T-defqtvc__00.smt2 |   20.010s | 57.604MiB| timeout | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_558_19_fp_overflow_check___00.smt2 |   20.012s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7d8b1a_generic_float_tests-T-defqtvc__00.smt2 |   20.019s | 44.804MiB| timeout | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_567_49_fp_overflow_check___00.smt2 |   20.029s | 395.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_567_58_fp_overflow_check___00.smt2 |   20.036s | 447.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_567_19_fp_overflow_check___00.smt2 |   20.038s | 505.0MiB| timeout | 0 |  |  |
