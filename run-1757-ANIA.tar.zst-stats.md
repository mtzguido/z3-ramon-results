# .

* SAT 23
* UNSAT 9
* TIMEOUT 16
* UNKNOWN 30

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: ANIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/ANIA.tar.zst?download=1
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
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_20.smt2 |    0.026s | 21.368MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_11.smt2 |    0.027s | 20.82MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_10.smt2 |    0.028s | 21.084MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_6.smt2 |    0.029s | 21.132MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_4.smt2 |    0.029s | 20.868MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_56.smt2 |    0.029s | 20.8MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_5.smt2 |    0.030s | 21.088MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/sum_array-2-2.i_1.smt2 |    0.035s | 21.192MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_12.smt2 |    0.035s | 20.68MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_4.smt2 |    0.038s | 20.928MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_16.smt2 |    0.038s | 20.7MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_8.smt2 |    0.038s | 20.804MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_10.smt2 |    0.040s | 20.812MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_57.smt2 |    0.040s | 20.792MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_9.smt2 |    0.040s | 21.232MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_7.smt2 |    0.040s | 20.796MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_7.smt2 |    0.040s | 21.288MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_10.smt2 |    0.041s | 21.352MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_5.smt2 |    0.041s | 21.264MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_74.smt2 |    0.042s | 20.804MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_9.smt2 |    0.043s | 21.56MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/array_1-2.c_AllErrorsAtOnce_Iteration3_0.smt2 |    0.059s | 21.744MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_75.smt2 |    0.064s | 20.628MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_6.smt2 |    0.065s | 21.216MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_10.smt2 |    0.066s | 20.816MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_6.smt2 |    0.066s | 20.656MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_55.smt2 |    0.067s | 21.156MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_9.smt2 |    0.067s | 21.052MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_7.smt2 |    0.067s | 20.852MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_1.smt2 |    0.068s | 20.664MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_11.smt2 |    0.068s | 20.836MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/sum_array-2-2.i_2.smt2 |    0.068s | 21.168MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_9.smt2 |    0.068s | 20.644MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_6.smt2 |    0.068s | 21.304MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_53.smt2 |    0.069s | 20.872MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_5.smt2 |    0.069s | 20.928MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_52.smt2 |    0.069s | 21.104MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_17.smt2 |    0.069s | 21.12MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_4.smt2 |    0.069s | 20.88MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_7.smt2 |    0.069s | 20.664MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_8.smt2 |    0.070s | 21.176MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_8.smt2 |    0.070s | 20.912MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_50.smt2 |    0.070s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_2.smt2 |    0.070s | 20.872MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_76.smt2 |    0.070s | 20.816MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_1.smt2 |    0.070s | 21.392MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_9.smt2 |    0.070s | 21.012MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_3.smt2 |    0.070s | 21.128MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_11.smt2 |    0.071s | 21.14MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_4.smt2 |    0.071s | 20.88MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_8.smt2 |    0.072s | 20.92MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_3.smt2 |    0.072s | 21.076MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_5.smt2 |    0.072s | 21.136MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/running_example.i_6.smt2 |    0.079s | 21.672MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/condm.c_AllErrorsAtOnce_Iteration9_0.smt2 |    0.123s | 22.776MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/array_doub_access_init_const.c_AllErrorsAtOnce_Iteration3_0.smt2 |    0.220s | 24.98MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/nr2.c_AllErrorsAtOnce_Iteration8_0.smt2 |    0.803s | 40.712MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/skipped.c_AllErrorsAtOnce_Iteration5_0.smt2 |    0.973s | 24.776MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/benchmark52_polynomial.i_AllErrorsAtOnce_Iteration3_0.smt2 |    1.046s | 22.12MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/sum_array-2-2.i_0.smt2 |    2.167s | 303.0MiB| sat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/sep20-1.i_AllErrorsAtOnce_Iteration23_0.smt2 |    2.580s | 41.936MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/rew.c_AllErrorsAtOnce_Iteration5_0.smt2 |    4.865s | 29.536MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/mcmillan2006.i_AllErrorsAtOnce_Iteration5_0.smt2 |   20.018s | 32.532MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/linear_sea.ch.c_AllErrorsAtOnce_Iteration8_0.smt2 |   20.019s | 45.04MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/partial_lesser_bound-1.i_AllErrorsAtOnce_Iteration3_0.smt2 |   20.020s | 55.548MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/rewnifrev2.c_AllErrorsAtOnce_Iteration5_0.smt2 |   20.036s | 199.0MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/array_of_struct_break.i_AllErrorsAtOnce_Iteration5_0.smt2 |   20.042s | 51.624MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/sorting_selectionsort_ground-2.i_AllErrorsAtOnce_Iteration8_0.smt2 |   20.049s | 40.984MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/array_shadowinit.i_AllErrorsAtOnce_Iteration5_0.smt2 |   20.051s | 48.1MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_25.smt2 |   20.056s | 41.928MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/tree_max.c_0.smt2 |   20.056s | 36.976MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/aiob_3.c_AllErrorsAtOnce_Iteration3_0.smt2 |   20.057s | 68.516MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/aiob_4.c.v+lh-reducer.c_AllErrorsAtOnce_Iteration3_0.smt2 |   20.058s | 71.072MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/array_4.i_AllErrorsAtOnce_Iteration5_0.smt2 |   20.058s | 69.104MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/aiob_4.c.v+cfa-reducer.c_AllErrorsAtOnce_Iteration4_0.smt2 |   20.059s | 61.24MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/flag_loopdep_simple.i_AllErrorsAtOnce_Iteration8_0.smt2 |   20.062s | 97.516MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/aiob_2.c_AllErrorsAtOnce_Iteration3_0.smt2 |   20.066s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/aiob_4.c_AllErrorsAtOnce_Iteration3_0.smt2 |   20.098s | 433.0MiB| timeout | 0 |  |  |
