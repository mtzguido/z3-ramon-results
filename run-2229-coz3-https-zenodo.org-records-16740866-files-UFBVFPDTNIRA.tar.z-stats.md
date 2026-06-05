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
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 30c74fccee4d195424588e28574ecaf0f9335f2c
Z3 branch: 30c74fccee4d195424588e28574ecaf0f9335f2c
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVFPDTNIRA.tar.zst?download=1
Z3 commit message: Go bindings: extract CGo slice-conversion helpers to eliminate boilerplate (#9465)

* Initial plan

* simplify Go bindings: extract CGo slice conversion helpers in z3.go

Agent-Logs-Url: https://github.com/Z3Prover/z3/sessions/eb6e05d8-f45a-40fb-b61f-17d4058bccb6

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.adb_28_22_assert___00.smt2 |    0.017s | 19.304MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_34_22_assert___00.smt2 |   20.005s | 23.02MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_587_27_range_check___00.smt2 |   20.005s | 24.096MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_37_22_assert___00.smt2 |   20.006s | 23.168MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_577_26_range_check___00.smt2 |   20.006s | 24.024MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_214_48_overflow_check___00.smt2 |   20.006s | 22.768MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_587_27_precondition___00.smt2 |   20.006s | 24.144MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_16_19_assert___00.smt2 |   20.006s | 27.232MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_21_25_assert___00.smt2 |   20.006s | 24.016MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_210_48_overflow_check___00.smt2 |   20.006s | 22.868MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.ads_26_14_postcondition___00.smt2 |   20.006s | 24.128MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_577_26_precondition___00.smt2 |   20.006s | 23.988MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_14_27_division_check___00.smt2 |   20.006s | 24.536MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_50_22_assert___00.smt2 |   20.006s | 22.976MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_597_27_range_check___00.smt2 |   20.007s | 23.932MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_40_22_assert___00.smt2 |   20.007s | 23.128MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_313_40_fp_overflow_check___00.smt2 |   20.007s | 22.88MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_270_45_range_check___00.smt2 |   20.007s | 22.768MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_39_22_assert___00.smt2 |   20.007s | 23.132MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_197_46_overflow_check___00.smt2 |   20.007s | 22.764MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_17_17_fp_overflow_check___00.smt2 |   20.007s | 24.436MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_53_22_assert___00.smt2 |   20.007s | 22.924MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.ads_42_32_range_check___00.smt2 |   20.007s | 23.084MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_51_22_assert___00.smt2 |   20.007s | 23.164MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__zero_and_unchecked.adb_14_22_zero_and_unchecked.adb_27_4_division_check___00.smt2 |   20.007s | 22.608MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.ads_26_77_division_check___00.smt2 |   20.007s | 23.996MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_38_22_assert___00.smt2 |   20.007s | 23.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_22_19_assert___00.smt2 |   20.008s | 25.916MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_44_22_assert___00.smt2 |   20.008s | 23.14MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_37_22_assert___00.smt2 |   20.008s | 23.148MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_25_17_postcondition___00.smt2 |   20.008s | 24.024MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_37_22_assert___00.smt2 |   20.008s | 23.396MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_72_22_assert___00.smt2 |   20.008s | 23.216MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_67_22_assert___00.smt2 |   20.009s | 23.104MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_193_42_overflow_check___00.smt2 |   20.009s | 22.668MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.ads_48_19_postcondition___00.smt2 |   20.009s | 23.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_15_17_postcondition___00.smt2 |   20.010s | 24.068MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_38_22_assert___00.smt2 |   20.010s | 23.156MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.ads_42_19_postcondition___00.smt2 |   20.010s | 23.144MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_28_19_assert___00.smt2 |   20.010s | 27.016MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_226_39_overflow_check___00.smt2 |   20.010s | 22.856MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_28_30_range_check___00.smt2 |   20.010s | 23.98MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_52_22_assert___00.smt2 |   20.010s | 23.136MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_22_17_fp_overflow_check___00.smt2 |   20.011s | 24.024MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.ads_41_19_postcondition___00.smt2 |   20.011s | 23.176MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_234_41_overflow_check___00.smt2 |   20.011s | 22.804MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_287_69_fp_overflow_check___00.smt2 |   20.011s | 22.796MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_39_22_assert___00.smt2 |   20.011s | 23.168MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_313_40_division_check___00.smt2 |   20.011s | 22.656MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_20_22_assert___00.smt2 |   20.012s | 24.636MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.ads_41_32_range_check___00.smt2 |   20.012s | 23.164MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_21_14_fp_overflow_check___00.smt2 |   20.013s | 24.604MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_283_64_fp_overflow_check___00.smt2 |   20.013s | 22.74MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_201_41_overflow_check___00.smt2 |   20.013s | 22.776MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_28_22_assert___00.smt2 |   20.013s | 23.144MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_21_14_division_check___00.smt2 |   20.014s | 24.648MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_60_22_assert___00.smt2 |   20.014s | 22.964MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_27_22_assert___00.smt2 |   20.014s | 23.12MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__zero_and_min.adb_14_25_zero_and_min.adb_26_4_assert___00.smt2 |   20.014s | 21.844MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_279_47_range_check___00.smt2 |   20.014s | 22.732MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_55_17_postcondition___00.smt2 |   20.015s | 23.984MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_205_45_overflow_check___00.smt2 |   20.015s | 22.864MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.adb_47_22_assert___00.smt2 |   20.017s | 24.02MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O220-024__floats__wibble.adb_11_3_precondition___00.smt2 |   20.017s | 24.004MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_35_22_assert___00.smt2 |   20.017s | 23.14MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_597_27_precondition___00.smt2 |   20.017s | 24.068MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_273_22_assert___00.smt2 |   20.018s | 22.736MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_71_22_assert___00.smt2 |   20.018s | 23.212MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_35_22_assert___00.smt2 |   20.018s | 23.128MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_36_22_assert___00.smt2 |   20.019s | 23.176MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_39_22_assert___00.smt2 |   20.019s | 23.144MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_287_69_division_check___00.smt2 |   20.019s | 22.732MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_35_17_postcondition___00.smt2 |   20.019s | 24.052MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_38_22_assert___00.smt2 |   20.023s | 23.388MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_45_17_postcondition___00.smt2 |   20.023s | 24.04MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_69_22_assert___00.smt2 |   20.023s | 23.128MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.ads_48_32_range_check___00.smt2 |   20.024s | 23.208MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_40_22_assert___00.smt2 |   20.024s | 23.172MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_218_45_overflow_check___00.smt2 |   20.025s | 22.744MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_46_25_assert___00.smt2 |   20.025s | 23.136MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_230_41_overflow_check___00.smt2 |   20.027s | 22.632MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_54_22_assert___00.smt2 |   20.027s | 23.148MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_22_17_division_check___00.smt2 |   20.028s | 24.08MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_27_28_assert___00.smt2 |   20.028s | 23.932MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_275_47_range_check___00.smt2 |   20.029s | 22.712MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_46_22_assert___00.smt2 |   20.029s | 23.132MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_48_25_assert___00.smt2 |   20.029s | 23.124MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_28_22_assert___00.smt2 |   20.029s | 23.12MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_28_31_range_check___00.smt2 |   20.032s | 24.68MiB| timeout | 0 |  |  |
