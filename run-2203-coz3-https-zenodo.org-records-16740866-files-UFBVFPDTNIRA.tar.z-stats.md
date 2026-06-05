# .

* SAT 0
* UNSAT 1
* TIMEOUT 88
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBVFPDTNIRA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBVFPDTNIRA.tar.z
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 branch: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVFPDTNIRA.tar.zst?download=1
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
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.adb_28_22_assert___00.smt2 |    0.037s | 20.36MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.ads_41_19_postcondition___00.smt2 |   20.012s | 23.696MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_16_19_assert___00.smt2 |   20.012s | 28.188MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_313_40_division_check___00.smt2 |   20.013s | 23.356MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_193_42_overflow_check___00.smt2 |   20.014s | 23.304MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_577_26_range_check___00.smt2 |   20.021s | 24.624MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_587_27_precondition___00.smt2 |   20.021s | 24.684MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_27_22_assert___00.smt2 |   20.022s | 23.528MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_53_22_assert___00.smt2 |   20.023s | 23.832MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_22_17_fp_overflow_check___00.smt2 |   20.025s | 24.68MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_21_25_assert___00.smt2 |   20.025s | 24.54MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_14_27_division_check___00.smt2 |   20.025s | 25.288MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_597_27_range_check___00.smt2 |   20.026s | 24.82MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_275_47_range_check___00.smt2 |   20.026s | 23.176MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_71_22_assert___00.smt2 |   20.026s | 23.568MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_218_45_overflow_check___00.smt2 |   20.026s | 23.316MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_226_39_overflow_check___00.smt2 |   20.026s | 23.296MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_54_22_assert___00.smt2 |   20.026s | 23.948MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_40_22_assert___00.smt2 |   20.026s | 23.688MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_69_22_assert___00.smt2 |   20.026s | 23.96MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_230_41_overflow_check___00.smt2 |   20.027s | 23.308MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_35_22_assert___00.smt2 |   20.027s | 23.688MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_214_48_overflow_check___00.smt2 |   20.027s | 23.56MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_48_25_assert___00.smt2 |   20.027s | 23.712MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_17_17_fp_overflow_check___00.smt2 |   20.027s | 25.508MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_205_45_overflow_check___00.smt2 |   20.027s | 23.34MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_577_26_precondition___00.smt2 |   20.027s | 24.872MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_22_17_division_check___00.smt2 |   20.028s | 24.604MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.ads_48_32_range_check___00.smt2 |   20.028s | 23.652MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_201_41_overflow_check___00.smt2 |   20.028s | 23.36MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_46_25_assert___00.smt2 |   20.032s | 23.588MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_20_22_assert___00.smt2 |   20.033s | 25.096MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_273_22_assert___00.smt2 |   20.038s | 23.392MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_287_69_division_check___00.smt2 |   20.041s | 23.26MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_597_27_precondition___00.smt2 |   20.045s | 24.716MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_28_22_assert___00.smt2 |   20.045s | 23.72MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_38_22_assert___00.smt2 |   20.045s | 23.848MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_15_17_postcondition___00.smt2 |   20.046s | 24.692MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_234_41_overflow_check___00.smt2 |   20.046s | 23.656MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_21_14_division_check___00.smt2 |   20.046s | 25.024MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_28_22_assert___00.smt2 |   20.046s | 23.692MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_28_31_range_check___00.smt2 |   20.047s | 25.28MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_279_47_range_check___00.smt2 |   20.047s | 23.348MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_37_22_assert___00.smt2 |   20.047s | 24.1MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_35_22_assert___00.smt2 |   20.047s | 23.692MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_22_19_assert___00.smt2 |   20.048s | 28.076MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_39_22_assert___00.smt2 |   20.048s | 23.72MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_39_22_assert___00.smt2 |   20.048s | 23.728MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_28_30_range_check___00.smt2 |   20.048s | 24.604MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_287_69_fp_overflow_check___00.smt2 |   20.049s | 23.332MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_39_22_assert___00.smt2 |   20.049s | 23.744MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_21_14_fp_overflow_check___00.smt2 |   20.050s | 25.144MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.adb_47_22_assert___00.smt2 |   20.051s | 24.504MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_34_22_assert___00.smt2 |   20.051s | 23.712MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_67_22_assert___00.smt2 |   20.051s | 23.632MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_72_22_assert___00.smt2 |   20.051s | 23.668MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.ads_41_32_range_check___00.smt2 |   20.051s | 23.68MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.ads_48_19_postcondition___00.smt2 |   20.051s | 23.684MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_40_22_assert___00.smt2 |   20.052s | 23.692MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_587_27_range_check___00.smt2 |   20.052s | 24.92MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_37_22_assert___00.smt2 |   20.052s | 23.568MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_197_46_overflow_check___00.smt2 |   20.052s | 23.384MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_52_22_assert___00.smt2 |   20.052s | 23.804MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_50_22_assert___00.smt2 |   20.052s | 23.72MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_27_28_assert___00.smt2 |   20.053s | 24.596MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_45_17_postcondition___00.smt2 |   20.053s | 24.704MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.ads_42_32_range_check___00.smt2 |   20.053s | 23.928MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_51_22_assert___00.smt2 |   20.053s | 23.724MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_210_48_overflow_check___00.smt2 |   20.053s | 23.54MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__zero_and_unchecked.adb_14_22_zero_and_unchecked.adb_27_4_division_check___00.smt2 |   20.053s | 23.228MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.ads_42_19_postcondition___00.smt2 |   20.055s | 24.028MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_283_64_fp_overflow_check___00.smt2 |   20.055s | 23.272MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_25_17_postcondition___00.smt2 |   20.055s | 24.532MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.ads_26_77_division_check___00.smt2 |   20.055s | 24.632MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_38_22_assert___00.smt2 |   20.056s | 23.564MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_38_22_assert___00.smt2 |   20.056s | 24.028MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_36_22_assert___00.smt2 |   20.056s | 23.692MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_55_17_postcondition___00.smt2 |   20.057s | 24.64MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_44_22_assert___00.smt2 |   20.057s | 23.684MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O220-024__floats__wibble.adb_11_3_precondition___00.smt2 |   20.057s | 25.412MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__zero_and_min.adb_14_25_zero_and_min.adb_26_4_assert___00.smt2 |   20.057s | 22.708MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_35_17_postcondition___00.smt2 |   20.057s | 24.676MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_37_22_assert___00.smt2 |   20.058s | 23.696MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_313_40_fp_overflow_check___00.smt2 |   20.058s | 23.344MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_270_45_range_check___00.smt2 |   20.058s | 23.268MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_60_22_assert___00.smt2 |   20.058s | 23.688MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_46_22_assert___00.smt2 |   20.058s | 23.692MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_28_19_assert___00.smt2 |   20.058s | 28.056MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.ads_26_14_postcondition___00.smt2 |   20.058s | 24.624MiB| timeout | 0 |  |  |
