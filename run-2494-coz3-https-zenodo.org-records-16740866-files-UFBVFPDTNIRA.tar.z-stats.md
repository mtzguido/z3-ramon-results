# .

* SAT 0
* UNSAT 44
* TIMEOUT 45
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBVFPDTNIRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBVFPDTNIRA.tar.z
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVFPDTNIRA.tar.zst?download=1
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
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.ads_26_14_postcondition___00.smt2 |    0.017s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.adb_28_22_assert___00.smt2 |    0.018s | 19.352MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_14_27_division_check___00.smt2 |    0.018s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.ads_42_19_postcondition___00.smt2 |    0.020s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_287_69_division_check___00.smt2 |    0.024s | 19.696MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.ads_26_77_division_check___00.smt2 |    0.028s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_218_45_overflow_check___00.smt2 |    0.030s | 21.036MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_205_45_overflow_check___00.smt2 |    0.048s | 21.892MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_577_26_precondition___00.smt2 |    0.048s | 21.592MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_201_41_overflow_check___00.smt2 |    0.057s | 21.948MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_230_41_overflow_check___00.smt2 |    0.063s | 22.084MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_270_45_range_check___00.smt2 |    0.066s | 21.964MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_226_39_overflow_check___00.smt2 |    0.069s | 22.032MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_273_22_assert___00.smt2 |    0.071s | 22.056MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_197_46_overflow_check___00.smt2 |    0.072s | 21.912MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_214_48_overflow_check___00.smt2 |    0.080s | 22.344MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_275_47_range_check___00.smt2 |    0.082s | 22.184MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_234_41_overflow_check___00.smt2 |    0.084s | 22.216MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_279_47_range_check___00.smt2 |    0.090s | 22.464MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_21_14_division_check___00.smt2 |    0.106s | 36.212MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_193_42_overflow_check___00.smt2 |    0.116s | 21.928MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_21_25_assert___00.smt2 |    0.120s | 23.648MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_210_48_overflow_check___00.smt2 |    0.120s | 22.376MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_27_28_assert___00.smt2 |    0.129s | 52.432MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_28_30_range_check___00.smt2 |    0.133s | 52.316MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_587_27_precondition___00.smt2 |    0.137s | 22.924MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_577_26_range_check___00.smt2 |    0.163s | 23.888MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_22_17_division_check___00.smt2 |    0.204s | 23.612MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_587_27_range_check___00.smt2 |    0.205s | 25.352MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_597_27_precondition___00.smt2 |    0.328s | 25.72MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_597_27_range_check___00.smt2 |    0.374s | 28.112MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_45_17_postcondition___00.smt2 |    0.555s | 32.752MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.ads_41_32_range_check___00.smt2 |    0.810s | 173.0MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_46_22_assert___00.smt2 |    0.816s | 175.0MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.ads_42_32_range_check___00.smt2 |    1.028s | 248.0MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_22_17_fp_overflow_check___00.smt2 |    1.463s | 52.336MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.ads_48_32_range_check___00.smt2 |    1.763s | 481.0MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_55_17_postcondition___00.smt2 |    2.306s | 41.932MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_28_31_range_check___00.smt2 |    8.196s | 67.568MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_20_22_assert___00.smt2 |    8.381s | 41.244MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_21_14_fp_overflow_check___00.smt2 |    9.326s | 66.524MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_283_64_fp_overflow_check___00.smt2 |    9.996s | 44.584MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_17_17_fp_overflow_check___00.smt2 |   15.337s | 41.96MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_313_40_division_check___00.smt2 |   16.661s | 106.0MiB| unsat | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_16_19_assert___00.smt2 |   20.009s | 25.484MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_25_17_postcondition___00.smt2 |   20.011s | 61.176MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__zero_and_min.adb_14_25_zero_and_min.adb_26_4_assert___00.smt2 |   20.015s | 29.408MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.adb_47_22_assert___00.smt2 |   20.018s | 37.268MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_38_22_assert___00.smt2 |   20.018s | 245.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_22_19_assert___00.smt2 |   20.020s | 29.9MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_50_22_assert___00.smt2 |   20.022s | 304.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O220-024__floats__wibble.adb_11_3_precondition___00.smt2 |   20.023s | 31.276MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_37_22_assert___00.smt2 |   20.023s | 275.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__zero_and_unchecked.adb_14_22_zero_and_unchecked.adb_27_4_division_check___00.smt2 |   20.023s | 29.584MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_35_17_postcondition___00.smt2 |   20.024s | 55.192MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_51_22_assert___00.smt2 |   20.025s | 326.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_67_22_assert___00.smt2 |   20.028s | 368.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_28_19_assert___00.smt2 |   20.029s | 28.068MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_15_17_postcondition___00.smt2 |   20.030s | 55.268MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_34_22_assert___00.smt2 |   20.032s | 244.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_38_22_assert___00.smt2 |   20.044s | 248.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_287_69_fp_overflow_check___00.smt2 |   20.047s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_27_22_assert___00.smt2 |   20.049s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_37_22_assert___00.smt2 |   20.051s | 194.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_28_22_assert___00.smt2 |   20.052s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.ads_48_19_postcondition___00.smt2 |   20.054s | 858.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.ads_41_19_postcondition___00.smt2 |   20.057s | 242.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_40_22_assert___00.smt2 |   20.058s | 202.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_40_22_assert___00.smt2 |   20.059s | 279.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_46_25_assert___00.smt2 |   20.060s | 299.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_35_22_assert___00.smt2 |   20.062s | 193.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_313_40_fp_overflow_check___00.smt2 |   20.068s | 205.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_36_22_assert___00.smt2 |   20.069s | 246.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_28_22_assert___00.smt2 |   20.071s | 190.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_39_22_assert___00.smt2 |   20.073s | 251.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_39_22_assert___00.smt2 |   20.075s | 244.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_48_25_assert___00.smt2 |   20.078s | 298.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_38_22_assert___00.smt2 |   20.079s | 282.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_60_22_assert___00.smt2 |   20.079s | 491.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_35_22_assert___00.smt2 |   20.079s | 275.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_52_22_assert___00.smt2 |   20.079s | 328.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_37_22_assert___00.smt2 |   20.080s | 248.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_39_22_assert___00.smt2 |   20.080s | 280.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_44_22_assert___00.smt2 |   20.081s | 286.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_54_22_assert___00.smt2 |   20.083s | 340.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_71_22_assert___00.smt2 |   20.084s | 541.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_53_22_assert___00.smt2 |   20.084s | 337.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_72_22_assert___00.smt2 |   20.094s | 554.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_69_22_assert___00.smt2 |   20.104s | 512.0MiB| timeout | 0 |  |  |
