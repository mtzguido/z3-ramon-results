# .

* SAT 0
* UNSAT 0
* TIMEOUT 0
* UNKNOWN 0

* UNSET 89

* ERROR 89

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: UFBVFPDTNIRA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVFPDTNIRA.tar.zst?download=1
Z3 commit message: [code-simplifier] Simplify `api_ast.cpp` by removing unreachable branch and stray comment (#9570)

This change simplifies recently touched API code in
`src/api/api_ast.cpp` without altering semantics. It removes an
unreachable error path in `Z3_get_index_value` and deletes an empty
comment in `Z3_mk_rec_func_decl`.

- **`Z3_get_index_value`: remove dead branch**
- After validating `a` is non-null and of kind `AST_VAR`, the conversion
to `var*` is already guaranteed by existing AST casting invariants.
- The redundant null-check/error-return branch was removed, leaving a
direct index return.

- **`Z3_mk_rec_func_decl`: remove noise**
  - Deleted a stray empty `//` line.

```cpp
// before
var* va = to_var(_a);
if (va) {
    return va->get_idx();
}
SET_ERROR_CODE(Z3_INVALID_ARG, nullptr);
return 0;

// after
var* va = to_var(_a);
return va->get_idx();
```

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_22_19_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_67_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_234_41_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_40_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_37_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_275_47_range_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_193_42_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_313_40_fp_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_270_45_range_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_587_27_range_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_21_14_division_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.ads_41_19_postcondition___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_287_69_fp_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_22_17_division_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_39_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_44_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.ads_42_19_postcondition___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_577_26_range_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_60_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_46_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_27_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_35_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_214_48_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_587_27_precondition___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_28_19_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_37_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_20_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_34_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_48_25_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_279_47_range_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.ads_48_32_range_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_71_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_218_45_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_55_17_postcondition___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_283_64_fp_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_39_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_226_39_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_27_28_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_597_27_range_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_197_46_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_25_17_postcondition___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_28_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_16_19_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_37_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_597_27_precondition___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_273_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_17_17_fp_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_28_31_range_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_201_41_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_28_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_45_17_postcondition___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_313_40_division_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_53_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_35_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__zero_and_min.adb_14_25_zero_and_min.adb_26_4_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.ads_41_32_range_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_28_30_range_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_72_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_36_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.ads_42_32_range_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_21_25_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_52_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_51_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_210_48_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_230_41_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_40_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_54_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_46_25_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.adb_47_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_15_17_postcondition___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O220-024__floats__wibble.adb_11_3_precondition___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.adb_28_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_287_69_division_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.ads_26_14_postcondition___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_38_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__zero_and_unchecked.adb_14_22_zero_and_unchecked.adb_27_4_division_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_205_45_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_69_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_39_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.ads_26_77_division_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_38_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_577_26_precondition___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_14_27_division_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_38_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_35_17_postcondition___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_21_14_fp_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_22_17_fp_overflow_check___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.ads_48_19_postcondition___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_50_22_assert___00.smt2 | 1000.000s | -1B| unset | -1 |  |  |
