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
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFFPDTNIRA.tar.zst?download=1 | Source list: benchmarks-qf.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFFPDTNIRA.tar.
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2081918cea27e604b9077a6c36acb2ac28aa5b78
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFFPDTNIRA.tar.zst?download=1
Z3 commit message: cmake: skip std::atomic link check for Emscripten and single-threaded builds (#9932)

The "Python bindings (Pyodide)" CI job fails at CMake configure time
because Emscripten's cross-compiler cannot pass the `std::atomic` link
tests in `check_link_atomic.cmake`, resulting in a fatal error even
though Pyodide builds are single-threaded and never need `libatomic`.

## Change

- **`cmake/check_link_atomic.cmake`**: guard the entire atomic check
behind `if (NOT (EMSCRIPTEN OR Z3_SINGLE_THREADED))`. Emscripten sets
`EMSCRIPTEN` automatically via `emcmake`; Pyodide builds also pass
`-DZ3_SINGLE_THREADED=TRUE`, so either condition is sufficient to bypass
the check safely.

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-012__justification__numerics.ads_18_99_division_check___00.smt2 |    0.022s | 19.632MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ef0acb_generic_float_tests-T-defqtvc__00.smt2 |    0.025s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_19_28_division_check___00.smt2 |    0.027s | 19.604MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/S320-040__flow_blocking__a-ngelfu.ads_126_32_p.adb_7_4_division_check___00.smt2 |    0.029s | 19.652MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_847dc3_generic_float_tests-T-defqtvc__00.smt2 |    0.030s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_af6b6a_generic_interval_tests-T-defqtvc__00.smt2 |    0.042s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/K720-019__floats__pack.adb_5_17_fp_overflow_check___00.smt2 |    0.045s | 30.036MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c87e9d_generic_float_tests-T-defqtvc__00.smt2 |    0.046s | 28.528MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_3a913e_generic_float_tests-T-defqtvc__00.smt2 |    0.048s | 30.128MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d97549_generic_float_tests-T-defqtvc__00.smt2 |    0.050s | 19.728MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/S427-002__inline_dim__a-ngelfu.ads_117_36_dimensions.ads_379_4_division_check___00.smt2 |    0.050s | 19.636MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2d2300_generic_interval_tests-T-defqtvc__00.smt2 |    0.052s | 19.7MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O810-001__predicate__safety_pack.ads_63_10_predicate_check___00.smt2 |    0.052s | 19.56MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_828bbe_generic_float_tests-T-defqtvc__00.smt2 |    0.052s | 19.704MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_05d13b_generic_float_tests-T-defqtvc__00.smt2 |    0.053s | 19.608MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O810-001__predicate__safety_pack.ads_65_10_predicate_check___00.smt2 |    0.054s | 19.5MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_15_8_disjoint_contract_cases___00.smt2 |    0.055s | 20.628MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_59_11_disjoint_contract_cases___00.smt2 |    0.056s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__original_sample.ads_15_140_division_check___00.smt2 |    0.056s | 19.964MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2cb2b4_generic_float_tests-T-defqtvc__00.smt2 |    0.056s | 19.66MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_32_99_division_check___00.smt2 |    0.056s | 19.696MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8c7880_generic_float_tests-T-defqtvc__00.smt2 |    0.057s | 19.584MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c7ccdd_generic_float_tests-T-defqtvc__00.smt2 |    0.058s | 30.144MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_420942_generic_float_tests-T-defqtvc__00.smt2 |    0.058s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_15_8_complete_contract_cases___00.smt2 |    0.058s | 20.544MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O810-001__predicate__safety_pack.ads_69_10_predicate_check___00.smt2 |    0.060s | 28.044MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_eabfeb_generic_float_tests-T-defqtvc__00.smt2 |    0.060s | 20.416MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_eb2c36_generic_float_tests-T-defqtvc__00.smt2 |    0.060s | 19.608MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d9224d_generic_float_tests-T-defqtvc__00.smt2 |    0.060s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/OB04-007__float_conversion__floatround.adb_7_47_predicate_check___00.smt2 |    0.062s | 19.588MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8e174b_generic_float_tests-T-defqtvc__00.smt2 |    0.062s | 19.616MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/S603-051__dimensions__a-ngelfu.ads_127_36_dimensions.ads_379_4_division_check___00.smt2 |    0.062s | 20.628MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_47e135_generic_float_tests-T-defqtvc__00.smt2 |    0.062s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/N917-037__prover_sanity_cvc4__floats.adb_6_4_assert___00.smt2 |    0.064s | 28.1MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b2ba6e_generic_float_tests-T-defqtvc__00.smt2 |    0.065s | 28.056MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5adf4f_generic_float_tests-T-defqtvc__00.smt2 |    0.069s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O303-041__flow_pure_implies_null_global__a-ngelfu.ads_127_36_ff.ads_3_1_division_check___00.smt2 |    0.069s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O810-001__predicate__safety_pack.ads_67_10_predicate_check___00.smt2 |    0.070s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__sample.ads_13_140_division_check___00.smt2 |    0.070s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a95b75_generic_float_tests-T-defqtvc__00.smt2 |    0.071s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/S320-040__flow_blocking__a-ngelfu.ads_117_36_p.adb_7_4_division_check___00.smt2 |    0.071s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_6_17_range_check___00.smt2 |    0.072s | 29.132MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/S603-051__dimensions__a-ngelfu.ads_126_32_dimensions.ads_380_4_division_check___00.smt2 |    0.072s | 19.98MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_18_17_range_check___00.smt2 |    0.073s | 29.144MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e09c2c_reduced_02-T-defqtvc__00.smt2 |    0.074s | 29.572MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_13_17_range_check___00.smt2 |    0.074s | 29.104MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_127068_generic_float_tests-T-defqtvc__00.smt2 |    0.074s | 19.552MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e70d10_generic_float_tests-T-defqtvc__00.smt2 |    0.076s | 29.988MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_558_44_division_check___00.smt2 |    0.076s | 28.04MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5b82bd_generic_float_tests-T-defqtvc__00.smt2 |    0.079s | 29.972MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5fd830_generic_float_tests-T-defqtvc__00.smt2 |    0.080s | 28.692MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_59_11_complete_contract_cases___00.smt2 |    0.080s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_13fa28_generic_float_tests-T-defqtvc__00.smt2 |    0.080s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.ads_8_34_fp_overflow_check___00.smt2 |    0.081s | 29.952MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__sample.ads_13_128_fp_overflow_check___00.smt2 |    0.085s | 29.968MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__numerics.ads_23_99_fp_overflow_check___00.smt2 |    0.086s | 30.016MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/Q522-022__codepeer__proof.ads_11_14_fp_overflow_check___00.smt2 |    0.086s | 30.128MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_23_99_fp_overflow_check___00.smt2 |    0.090s | 29.932MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_748b19_generic_float_tests-T-defqtvc__00.smt2 |    0.092s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_26_99_fp_overflow_check___00.smt2 |    0.092s | 30.44MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/N313-022__float_div__example.adb_9_30_division_check___00.smt2 |    0.096s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5636a0_generic_float_tests-T-defqtvc__00.smt2 |    0.096s | 31.992MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_954270_generic_float_tests-T-defqtvc__00.smt2 |    0.101s | 29.84MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2bc3b7_generic_float_tests-T-defqtvc__00.smt2 |    0.102s | 31.888MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_1c77b0_generic_interval_tests-T-defqtvc__00.smt2 |    0.103s | 31.764MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_3acf14_generic_float_tests-T-defqtvc__00.smt2 |    0.107s | 19.624MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_95a19c_generic_float_tests-T-defqtvc__00.smt2 |    0.107s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_9b4426_generic_float_tests-T-defqtvc__00.smt2 |    0.108s | 29.324MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O810-001__predicate__safety_pack.ads_15_16_fp_overflow_check___00.smt2 |    0.108s | 30.184MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/MB01-007__floating_point__foo.adb_12_4_precondition___00.smt2 |    0.108s | 19.64MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__numerics.ads_29_99_division_check___00.smt2 |    0.109s | 19.756MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_323ba9_generic_float_tests-T-defqtvc__00.smt2 |    0.109s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d00566_generic_float_tests-T-defqtvc__00.smt2 |    0.109s | 20.032MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/MB01-007__floating_point__foo.adb_6_20_fp_overflow_check___00.smt2 |    0.109s | 32.172MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7a5c9e_generic_float_tests-T-defqtvc__00.smt2 |    0.113s | 30.188MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_567_49_division_check___00.smt2 |    0.115s | 28.168MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/O810-001__predicate__safety_pack.ads_17_16_fp_overflow_check___00.smt2 |    0.116s | 30.216MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b0d547_generic_float_tests-T-defqtvc__00.smt2 |    0.116s | 30.128MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_3943ed_generic_float_tests-T-defqtvc__00.smt2 |    0.117s | 28.3MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b7409d_generic_float_tests-T-defqtvc__00.smt2 |    0.118s | 28.116MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__original_sample.ads_15_128_fp_overflow_check___00.smt2 |    0.121s | 30.172MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_9_17_range_check___00.smt2 |    0.125s | 29.12MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_14_23_fp_overflow_check___00.smt2 |    0.129s | 30.1MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_19_23_fp_overflow_check___00.smt2 |    0.130s | 33.232MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7dad36_generic_float_tests-T-defqtvc__00.smt2 |    0.134s | 29.324MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__numerics.ads_20_99_fp_overflow_check___00.smt2 |    0.143s | 29.932MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0c5b8b_generic_float_tests-T-defqtvc__00.smt2 |    0.145s | 32.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6e6909_generic_float_tests-T-defqtvc__00.smt2 |    0.146s | 29.972MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e14883_generic_interval_tests-T-defqtvc__00.smt2 |    0.146s | 31.7MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a3ff0b_generic_interval_tests-T-defqtvc__00.smt2 |    0.153s | 31.904MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c7dfd8_generic_interval_tests-T-defqtvc__00.smt2 |    0.153s | 32.768MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0f94ea_generic_float_tests-T-defqtvc__00.smt2 |    0.172s | 31.688MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_776e4a_foo-T-defqtvc__00.smt2 |    0.173s | 31.4MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_826a12_generic_float_tests-T-defqtvc__00.smt2 |    0.180s | 31.144MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_26_23_range_check___00.smt2 |    0.182s | 37.404MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0b5f28_generic_interval_tests-T-defqtvc__00.smt2 |    0.184s | 32.44MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8ff7c6_generic_float_tests-T-defqtvc__00.smt2 |    0.186s | 58.516MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a662fe_generic_float_tests-T-defqtvc__00.smt2 |    0.192s | 32.192MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_29_99_fp_overflow_check___00.smt2 |    0.194s | 32.448MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/OA26-022__gnatprove_crash__eg.adb_5_16_fp_overflow_check___00.smt2 |    0.197s | 32.68MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__numerics.ads_26_99_fp_overflow_check___00.smt2 |    0.198s | 32.672MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_cdd303_generic_float_tests-T-defqtvc__00.smt2 |    0.199s | 29.964MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7931fb_generic_interval_tests-T-defqtvc__00.smt2 |    0.201s | 32.94MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a33e16_generic_float_tests-T-defqtvc__00.smt2 |    0.216s | 32.296MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_9fa525_generic_float_tests-T-defqtvc__00.smt2 |    0.220s | 32.184MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_29f8e7_generic_float_tests-T-defqtvc__00.smt2 |    0.220s | 29.836MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ca225b_generic_interval_tests-T-defqtvc__00.smt2 |    0.247s | 32.18MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2629df_generic_float_tests-T-defqtvc__00.smt2 |    0.248s | 32.328MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6a34dd_generic_float_tests-T-defqtvc__00.smt2 |    0.251s | 58.46MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2475ea_generic_float_tests-T-defqtvc__00.smt2 |    0.292s | 32.172MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_81dd6b_generic_float_tests-T-defqtvc__00.smt2 |    0.316s | 37.64MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ed697c_generic_float_tests-T-defqtvc__00.smt2 |    0.317s | 58.836MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f5486e_generic_float_tests-T-defqtvc__00.smt2 |    0.333s | 31.668MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e155c1_generic_float_tests-T-defqtvc__00.smt2 |    0.342s | 32.244MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/MB01-007__floating_point__foo.adb_6_25_fp_overflow_check___00.smt2 |    0.356s | 38.5MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_aa8637_generic_interval_tests-T-defqtvc__00.smt2 |    0.486s | 31.908MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_cd606f_generic_interval_tests-T-defqtvc__00.smt2 |    0.494s | 60.312MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_60f230_generic_interval_tests-T-defqtvc__00.smt2 |    0.523s | 64.308MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_49eeb1_generic_interval_tests-T-defqtvc__00.smt2 |    0.526s | 64.356MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_74557c_generic_interval_tests-T-defqtvc__00.smt2 |    0.532s | 60.036MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bac632_generic_interval_tests-T-defqtvc__00.smt2 |    0.540s | 60.696MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2b3a3d_generic_interval_tests-T-defqtvc__00.smt2 |    0.557s | 64.244MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_640d9e_generic_float_tests-T-defqtvc__00.smt2 |    0.566s | 35.452MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2d90c4_generic_float_tests-T-defqtvc__00.smt2 |    0.749s | 72.904MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-012__justification__numerics.ads_18_99_fp_overflow_check___00.smt2 |    0.827s | 81.092MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__numerics.ads_29_99_fp_overflow_check___00.smt2 |    0.839s | 80.896MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_558_44_fp_overflow_check___00.smt2 |    0.849s | 79.316MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0a0ce0_generic_float_tests-T-defqtvc__00.smt2 |    0.876s | 40.588MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_07a5cf_generic_interval_tests-T-defqtvc__00.smt2 |    0.882s | 76.76MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__original_sample.ads_15_140_fp_overflow_check___00.smt2 |    0.892s | 85.268MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__sample.ads_13_140_fp_overflow_check___00.smt2 |    0.902s | 85.152MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_32_99_fp_overflow_check___00.smt2 |    0.907s | 80.852MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2df025_generic_float_tests-T-defqtvc__00.smt2 |    0.910s | 77.056MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_dd5ac9_generic_float_tests-T-defqtvc__00.smt2 |    0.962s | 31.692MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ccb32f_generic_float_tests-T-defqtvc__00.smt2 |    0.976s | 77.168MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_382280_generic_float_tests-T-defqtvc__00.smt2 |    1.101s | 328.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_452d8a_generic_float_tests-T-defqtvc__00.smt2 |    1.219s | 328.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ef7f8e_generic_float_tests-T-defqtvc__00.smt2 |    1.248s | 39.632MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_736933_generic_float_tests-T-defqtvc__00.smt2 |    1.271s | 328.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_cefa4e_generic_float_tests-T-defqtvc__00.smt2 |    1.595s | 129.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_558_53_fp_overflow_check___00.smt2 |    1.658s | 97.572MiB| sat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6dccf4_generic_float_tests-T-defqtvc__00.smt2 |    4.311s | 387.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8fc10b_generic_float_tests-T-defqtvc__00.smt2 |    4.344s | 381.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_759541_generic_interval_tests-T-defqtvc__00.smt2 |    5.144s | 63.5MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_15e1a4_generic_interval_tests-T-defqtvc__00.smt2 |    5.396s | 393.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f8d0db_generic_float_tests-T-defqtvc__00.smt2 |    6.284s | 385.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_da0327_generic_interval_tests-T-defqtvc__00.smt2 |    9.990s | 65.636MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_30ca25_generic_float_tests-T-defqtvc__00.smt2 |   10.038s | 737.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_558_19_fp_overflow_check___00.smt2 |   20.035s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7d8b1a_generic_float_tests-T-defqtvc__00.smt2 |   20.042s | 45.216MiB| timeout | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c5e486_generic_float_tests-T-defqtvc__00.smt2 |   20.042s | 58.236MiB| timeout | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_567_49_fp_overflow_check___00.smt2 |   20.098s | 396.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_567_58_fp_overflow_check___00.smt2 |   20.134s | 447.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_567_19_fp_overflow_check___00.smt2 |   20.140s | 506.0MiB| timeout | 0 |  |  |
