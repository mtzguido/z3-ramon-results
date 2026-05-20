# .

* SAT 66
* UNSAT 148
* TIMEOUT 33
* UNKNOWN 1

* UNSET 9

* ERROR 9

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: NIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/NIA.tar.zst?download=1
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
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_15.smt2 |    0.027s | 21.104MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_37.smt2 |    0.028s | 20.896MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_55.smt2 |    0.036s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_4.smt2 |    0.036s | 20.884MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_62.smt2 |    0.038s | 21.424MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_9.smt2 |    0.038s | 20.876MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_67.smt2 |    0.040s | 20.936MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_0.smt2 |    0.040s | 20.876MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_21.smt2 |    0.042s | 21.008MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_9.smt2 |    0.042s | 21.012MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_19.smt2 |    0.045s | 20.668MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/egcd2-ll.c_2.smt2 |    0.045s | 20.9MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_12.smt2 |    0.046s | 21.116MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_6.smt2 |    0.047s | 21.004MiB| sat | 0 |  |  |
|non-incremental/NIA/psyco/182.smt2                           |    0.047s | 20.904MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_11.smt2 |    0.048s | 21.604MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_94.smt2 |    0.048s | 20.896MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_68.smt2 |    0.049s | 20.796MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_13.smt2 |    0.049s | 21.088MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_27.smt2 |    0.050s | 20.916MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_66.smt2 |    0.051s | 21.068MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_60.smt2 |    0.052s | 21.216MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_12.smt2 |    0.053s | 21.056MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_13.smt2 |    0.053s | 20.852MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_78.smt2 |    0.056s | 21.136MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_6.smt2 |    0.056s | 21.612MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_9.smt2 |    0.056s | 20.832MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/sum02_false-unreach-call_true-no-overflow.c_0.smt2 |    0.056s | 20.444MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_33.smt2 |    0.056s | 20.996MiB| unsat | 0 |  |  |
|non-incremental/NIA/psyco/059.smt2                           |    0.056s | 21.088MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_26.smt2 |    0.057s | 20.952MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_0.smt2 |    0.057s | 20.624MiB| sat | 0 |  |  |
|non-incremental/NIA/psyco/060.smt2                           |    0.057s | 21.048MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_2.smt2 |    0.058s | 21.16MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_6.smt2 |    0.058s | 21.344MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_32.smt2 |    0.059s | 20.92MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/pals_lcr-var-start-time.6_true-unreach-call.ufo.UNBOUNDED.pals.c_1.smt2 |    0.059s | 21.16MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_45.smt2 |    0.059s | 20.936MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_23.smt2 |    0.060s | 21.336MiB| unsat | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de62.c_AllErrorsAtOnce_Iteration8_0.smt2 |    0.060s | 21.012MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_85.smt2 |    0.061s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_7.smt2 |    0.062s | 21.136MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_5.smt2 |    0.063s | 21.116MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_9.smt2 |    0.063s | 21.004MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_4.smt2 |    0.064s | 21.028MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/implicitunsignedconversion_true-unreach-call_true-termination.c_0.smt2 |    0.064s | 20.692MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_0.smt2 |    0.064s | 21.608MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_1.smt2 |    0.065s | 21.104MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_0.smt2 |    0.066s | 20.856MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_25.smt2 |    0.067s | 21.636MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_13.smt2 |    0.068s | 21.18MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_13.smt2 |    0.068s | 21.128MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_10.smt2 |    0.068s | 21.38MiB| sat | 0 |  |  |
|non-incremental/NIA/psyco/184.smt2                           |    0.068s | 21.68MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_70.smt2 |    0.069s | 22.124MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/ps4-ll.c_1.smt2 |    0.069s | 21.052MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_7.smt2 |    0.070s | 20.852MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_73.smt2 |    0.070s | 20.936MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_58.smt2 |    0.071s | 21.128MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_12.smt2 |    0.071s | 21.076MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_88.smt2 |    0.071s | 21.14MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gauss_sum.i_0.smt2 |    0.071s | 21.176MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_14.smt2 |    0.072s | 20.936MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_90.smt2 |    0.072s | 22.124MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_1.smt2 |    0.072s | 21.38MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_38.smt2 |    0.072s | 21.056MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_1.smt2 |    0.072s | 21.12MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_87.smt2 |    0.072s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_1.smt2 |    0.072s | 20.748MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_22.smt2 |    0.074s | 21.156MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_84.smt2 |    0.074s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/NIA/psyco/183.smt2                           |    0.074s | 21.74MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_7.smt2 |    0.075s | 21.132MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_5.smt2 |    0.075s | 21.392MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_11.smt2 |    0.075s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_76.smt2 |    0.075s | 21.596MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_39.smt2 |    0.076s | 21.032MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_2.smt2 |    0.076s | 20.66MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_21.smt2 |    0.076s | 21.148MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_3.smt2 |    0.077s | 20.652MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_18.smt2 |    0.077s | 21.084MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_5.smt2 |    0.077s | 20.904MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_44.smt2 |    0.077s | 21.204MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_16.smt2 |    0.077s | 20.624MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_65.smt2 |    0.078s | 20.768MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_7.smt2 |    0.078s | 20.792MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_42.smt2 |    0.078s | 21.116MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_2.smt2 |    0.079s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_81.smt2 |    0.079s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_30.smt2 |    0.079s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_77.smt2 |    0.079s | 20.824MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_18.smt2 |    0.079s | 21.184MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_59.smt2 |    0.079s | 21.28MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_20.smt2 |    0.080s | 21.184MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_3.smt2 |    0.080s | 20.884MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_49.smt2 |    0.080s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_10.smt2 |    0.080s | 20.912MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_75.smt2 |    0.080s | 21.384MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_17.smt2 |    0.080s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_2.smt2 |    0.081s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_10.smt2 |    0.081s | 21.104MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_1.smt2 |    0.082s | 20.852MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_16.smt2 |    0.083s | 21.236MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_91.smt2 |    0.083s | 21.172MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_93.smt2 |    0.083s | 21.012MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_63.smt2 |    0.083s | 20.864MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_23.smt2 |    0.083s | 21.052MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_61.smt2 |    0.083s | 21.388MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_0.smt2 |    0.083s | 20.636MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_92.smt2 |    0.084s | 21.224MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_64.smt2 |    0.084s | 20.956MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_8.smt2 |    0.084s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_11.smt2 |    0.086s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_6.smt2 |    0.086s | 21.424MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_71.smt2 |    0.086s | 22.172MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_24.smt2 |    0.086s | 20.888MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_41.smt2 |    0.087s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_3.smt2 |    0.088s | 21.396MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_3_true-unreach-call_true-no-overflow.i_1.smt2 |    0.088s | 21.1MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_4.smt2 |    0.088s | 21.556MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_95.smt2 |    0.088s | 21.64MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_74.smt2 |    0.088s | 21.2MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_8.smt2 |    0.089s | 21.004MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_11.smt2 |    0.090s | 20.424MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_7.smt2 |    0.090s | 21.388MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_48.smt2 |    0.090s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_36.smt2 |    0.090s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_10.smt2 |    0.090s | 21.12MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_25.smt2 |    0.092s | 21.08MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_8.smt2 |    0.092s | 20.968MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_34.smt2 |    0.092s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_19.smt2 |    0.093s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_20.smt2 |    0.093s | 21.616MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_11.smt2 |    0.093s | 20.824MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_18.smt2 |    0.093s | 21.132MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_89.smt2 |    0.093s | 20.84MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_28.smt2 |    0.094s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_72.smt2 |    0.096s | 22.188MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_82.smt2 |    0.097s | 21.78MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_86.smt2 |    0.098s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_35.smt2 |    0.098s | 20.896MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_4.smt2 |    0.099s | 21.436MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/sum02_false-unreach-call_true-no-overflow.c_1.smt2 |    0.100s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_79.smt2 |    0.101s | 21.0MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_80.smt2 |    0.101s | 20.92MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_4.smt2 |    0.101s | 21.888MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_7.smt2 |    0.101s | 21.096MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_3_true-unreach-call_true-no-overflow.i_2.smt2 |    0.105s | 21.136MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_24.smt2 |    0.108s | 20.94MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_46.smt2 |    0.108s | 20.864MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_40.smt2 |    0.108s | 20.916MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_3.smt2 |    0.109s | 21.084MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_9.smt2 |    0.109s | 21.132MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_43.smt2 |    0.109s | 21.056MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_31.smt2 |    0.110s | 21.18MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_0.smt2 |    0.110s | 21.0MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_2_true-unreach-call_true-no-overflow.i_0.smt2 |    0.118s | 21.648MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_69.smt2 |    0.119s | 20.932MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_5.smt2 |    0.120s | 21.112MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_2.smt2 |    0.121s | 20.744MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_22.smt2 |    0.122s | 21.332MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_29.smt2 |    0.124s | 20.904MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_83.smt2 |    0.127s | 21.72MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_15.smt2 |    0.131s | 21.948MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_97.smt2 |    0.131s | 21.9MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_0.smt2 |    0.135s | 21.644MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_13.smt2 |    0.136s | 22.72MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_2.smt2 |    0.156s | 21.396MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_3_true-unreach-call_true-no-overflow.i_0.smt2 |    0.173s | 21.904MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_18.smt2 |    0.173s | 22.204MiB| unsat | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de51.c_AllErrorsAtOnce_Iteration8_0.smt2 |    0.175s | 22.056MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_17.smt2 |    0.176s | 22.432MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_6.smt2 |    0.180s | 21.66MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_16.smt2 |    0.209s | 22.556MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_16.smt2 |    0.210s | 21.904MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_8.smt2 |    0.225s | 22.156MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_12.smt2 |    0.238s | 22.76MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_8.smt2 |    0.252s | 22.148MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_3.smt2 |    0.307s | 22.272MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_6.smt2 |    0.326s | 21.932MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_96.smt2 |    0.379s | 22.668MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_98.smt2 |    0.379s | 22.552MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_3.smt2 |    0.386s | 22.0MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_6.smt2 |    0.412s | 21.9MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_14.smt2 |    0.439s | 22.844MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_1.smt2 |    0.581s | 21.796MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_17.smt2 |    0.609s | 22.224MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_3.smt2 |    0.651s | 24.276MiB| unknown | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_18.smt2 |    1.067s | 22.752MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_15.smt2 |    1.801s | 26.42MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_2.smt2 |    1.955s | 23.18MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_4-2.c_0.smt2 |    2.276s | 24.964MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_10.smt2 |    2.793s | 23.944MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_3.smt2 |    3.050s | 26.096MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_1.smt2 |    3.327s | 30.068MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_12.smt2 |    5.940s | 51.796MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_2.smt2 |    6.028s | 52.052MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_5.smt2 |    6.166s | 52.048MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_13.smt2 |    6.197s | 51.828MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_3.smt2 |    6.209s | 51.968MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_6-1.c_0.smt2 |    6.449s | 24.536MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_10.smt2 |    7.312s | 54.476MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_14.smt2 |    7.323s | 54.488MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_16.smt2 |    7.335s | 54.88MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_4.smt2 |    7.361s | 55.692MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_8.smt2 |    7.442s | 54.756MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_9.smt2 |    7.487s | 54.548MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_17.smt2 |    7.527s | 54.56MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_15.smt2 |    7.554s | 54.456MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_11.smt2 |    7.664s | 54.724MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_7.smt2 |    7.741s | 54.68MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_6.smt2 |    9.560s | 53.864MiB| unsat | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/gsv2008.c.i.v+lhb-reducer.c_AllErrorsAtOnce_Iteration2_0.smt2 |   12.812s | 90.664MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_6-1.c_2.smt2 |   13.601s | 25.768MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_0.smt2 |   19.190s | 57.548MiB| unsat | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de41.c_AllErrorsAtOnce_Iteration5_0.smt2 |   20.026s | 92.436MiB| timeout | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/gsv2008.c.i.p+cfa-reducer.c_AllErrorsAtOnce_Iteration2_0.smt2 |   20.026s | 109.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de61.c_AllErrorsAtOnce_Iteration6_0.smt2 |   20.032s | 48.824MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_2.smt2 |   20.033s | 27.784MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_4.smt2 |   20.035s | 32.164MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_1.smt2 |   20.036s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/egcd2-ll.c_0.smt2 |   20.043s | 52.708MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_11.smt2 |   20.047s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/egcd2-ll.c_1.smt2 |   20.051s | 27.44MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_0.smt2 |   20.053s | 22.232MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_1.smt2 |   20.056s | 24.396MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_14.smt2 |   20.057s | 28.32MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_13.smt2 |   20.059s | 40.544MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_8.smt2 |   20.063s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_11.smt2 |   20.063s | 31.5MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_0.smt2 |   20.063s | 122.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_5.smt2 |   20.070s | 49.212MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_7.smt2 |   20.073s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_9.smt2 |   20.077s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_12.smt2 |   20.078s | 93.32MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_5.smt2 |   20.078s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_17.smt2 |   20.079s | 88.24MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_1.smt2 |   20.080s | 35.1MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_10.smt2 |   20.080s | 162.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_0.smt2 |   20.092s | 36.068MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_16.smt2 |   20.094s | 73.7MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_3.smt2 |   20.203s | 1773.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_0.smt2 |   20.250s | 2244.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_1.smt2 |   20.277s | 2282.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_8.smt2 |   20.478s | 4325.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_0.smt2 |   20.485s | 4802.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_1.smt2 |   20.549s | 4963.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_2.smt2 |   20.669s | 6974.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/tptp/NUM880=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/NIA/tptp/NUM881=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/NIA/tptp/ARI118=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/NIA/tptp/NUM885=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/NIA/tptp/NUM879=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/NIA/tptp/NUM878=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/NIA/tptp/NUM882=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/NIA/tptp/ARI123=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/NIA/tptp/NUM886=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
