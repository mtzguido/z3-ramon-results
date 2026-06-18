# .

* SAT 25
* UNSAT 9
* TIMEOUT 16
* UNKNOWN 28

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/ANIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-ANIA.tar.zst-downl
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/ANIA.tar.zst?download=1
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
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_53.smt2 |    0.016s | 20.18MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_12.smt2 |    0.016s | 20.364MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_4.smt2 |    0.016s | 20.204MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_9.smt2 |    0.016s | 20.256MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_76.smt2 |    0.016s | 20.124MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_9.smt2 |    0.017s | 20.084MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_6.smt2 |    0.018s | 20.448MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_11.smt2 |    0.018s | 20.056MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_8.smt2 |    0.019s | 20.756MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_3.smt2 |    0.019s | 20.304MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_2.smt2 |    0.020s | 20.204MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_7.smt2 |    0.020s | 20.296MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_4.smt2 |    0.020s | 20.344MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_1.smt2 |    0.020s | 20.304MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_9.smt2 |    0.021s | 20.856MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_1.smt2 |    0.025s | 20.048MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_56.smt2 |    0.025s | 20.184MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_7.smt2 |    0.026s | 20.788MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/running_example.i_6.smt2 |    0.027s | 20.82MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_10.smt2 |    0.028s | 20.308MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_75.smt2 |    0.028s | 20.028MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_7.smt2 |    0.028s | 20.364MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_8.smt2 |    0.029s | 20.348MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_17.smt2 |    0.029s | 20.096MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_8.smt2 |    0.030s | 20.132MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_10.smt2 |    0.031s | 20.18MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_55.smt2 |    0.031s | 20.096MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_4.smt2 |    0.031s | 20.22MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_5.smt2 |    0.031s | 20.156MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_10.smt2 |    0.031s | 20.092MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_11.smt2 |    0.031s | 20.164MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_11.smt2 |    0.031s | 20.288MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_6.smt2 |    0.031s | 20.032MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_20.smt2 |    0.031s | 20.336MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_57.smt2 |    0.032s | 20.192MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_52.smt2 |    0.032s | 20.104MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_8.smt2 |    0.032s | 20.416MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_16.smt2 |    0.032s | 20.288MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_50.smt2 |    0.032s | 19.72MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_6.smt2 |    0.032s | 20.772MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_9.smt2 |    0.032s | 20.332MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_9.smt2 |    0.033s | 20.464MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_5.smt2 |    0.035s | 20.216MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_74.smt2 |    0.036s | 20.168MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_5.smt2 |    0.036s | 20.548MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_5.smt2 |    0.036s | 20.476MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_7.smt2 |    0.037s | 20.26MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_4.smt2 |    0.038s | 20.28MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_6.smt2 |    0.038s | 20.284MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_10.smt2 |    0.038s | 20.652MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_3.smt2 |    0.039s | 20.18MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/sum_array-2-2.i_1.smt2 |    0.040s | 20.564MiB| sat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/sum_array-2-2.i_2.smt2 |    0.040s | 20.552MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/array_1-2.c_AllErrorsAtOnce_Iteration3_0.smt2 |    0.053s | 21.3MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/mcmillan2006.i_AllErrorsAtOnce_Iteration5_0.smt2 |    0.093s | 22.076MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/condm.c_AllErrorsAtOnce_Iteration9_0.smt2 |    0.139s | 23.628MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/array_doub_access_init_const.c_AllErrorsAtOnce_Iteration3_0.smt2 |    0.173s | 25.848MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/array_shadowinit.i_AllErrorsAtOnce_Iteration5_0.smt2 |    0.801s | 29.424MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/benchmark52_polynomial.i_AllErrorsAtOnce_Iteration3_0.smt2 |    0.986s | 21.736MiB| unknown | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/sum_array-2-2.i_0.smt2 |    1.003s | 102.0MiB| sat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/sep20-1.i_AllErrorsAtOnce_Iteration23_0.smt2 |    1.750s | 41.02MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/skipped.c_AllErrorsAtOnce_Iteration5_0.smt2 |    1.945s | 29.144MiB| unsat | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/tree_max.c_0.smt2 |   20.007s | 36.028MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/linear_sea.ch.c_AllErrorsAtOnce_Iteration8_0.smt2 |   20.008s | 42.424MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/rew.c_AllErrorsAtOnce_Iteration5_0.smt2 |   20.008s | 43.108MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/sorting_selectionsort_ground-2.i_AllErrorsAtOnce_Iteration8_0.smt2 |   20.009s | 46.464MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/aiob_4.c.v+cfa-reducer.c_AllErrorsAtOnce_Iteration4_0.smt2 |   20.010s | 68.328MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/partial_lesser_bound-1.i_AllErrorsAtOnce_Iteration3_0.smt2 |   20.011s | 75.652MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/flag_loopdep_simple.i_AllErrorsAtOnce_Iteration8_0.smt2 |   20.011s | 96.792MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/array_of_struct_break.i_AllErrorsAtOnce_Iteration5_0.smt2 |   20.011s | 61.96MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/aiob_3.c_AllErrorsAtOnce_Iteration3_0.smt2 |   20.016s | 72.408MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_25.smt2 |   20.018s | 39.92MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/aiob_2.c_AllErrorsAtOnce_Iteration3_0.smt2 |   20.020s | 115.0MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/rewnifrev2.c_AllErrorsAtOnce_Iteration5_0.smt2 |   20.022s | 301.0MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/array_4.i_AllErrorsAtOnce_Iteration5_0.smt2 |   20.023s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/aiob_4.c.v+lh-reducer.c_AllErrorsAtOnce_Iteration3_0.smt2 |   20.024s | 64.092MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/aiob_4.c_AllErrorsAtOnce_Iteration3_0.smt2 |   20.035s | 428.0MiB| timeout | 0 |  |  |
|non-incremental/ANIA/20240413-AutomizerLoopAcceleration/nr2.c_AllErrorsAtOnce_Iteration8_0.smt2 |   20.036s | 190.0MiB| timeout | 0 |  |  |
