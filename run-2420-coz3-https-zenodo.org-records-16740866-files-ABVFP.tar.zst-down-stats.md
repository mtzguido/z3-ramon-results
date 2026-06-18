# .

* SAT 30
* UNSAT 2
* TIMEOUT 9
* UNKNOWN 19

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/ABVFP.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-ABVFP.tar.zst-down
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/ABVFP.tar.zst?download=1
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
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_2.smt2 |    0.016s | 20.152MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0620b_true-unreach-call.c_6.smt2 |    0.018s | 19.536MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0663b.c_7.smt2 |    0.018s | 20.556MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/test_mutex_unbounded-1.i_52.smt2 |    0.018s | 20.708MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_4.smt2 |    0.019s | 19.536MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0530b_true-unreach-call.c_7.smt2 |    0.021s | 20.288MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0682a_true-unreach-call.c_13.smt2 |    0.021s | 20.448MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0620a_true-unreach-call.c_3.smt2 |    0.021s | 19.984MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_7.smt2 |    0.021s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0530a_true-unreach-call.c_4.smt2 |    0.025s | 19.92MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_3.smt2 |    0.025s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0530b_true-unreach-call.c_5.smt2 |    0.026s | 19.764MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/test_mutex_unbounded-1.i_53.smt2 |    0.026s | 20.824MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0320_true-unreach-call.c_4.smt2 |    0.027s | 20.568MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_13.smt2 |    0.027s | 20.34MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0530b_true-unreach-call.c_8.smt2 |    0.027s | 19.8MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_4.smt2 |    0.028s | 21.052MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_15.smt2 |    0.028s | 20.308MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_4.smt2 |    0.028s | 20.344MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0663b.c_9.smt2 |    0.029s | 21.104MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_0.smt2 |    0.029s | 20.184MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0530b_true-unreach-call.c_2.smt2 |    0.031s | 19.724MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_16.smt2 |    0.031s | 20.308MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_17.smt2 |    0.033s | 20.404MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/test_mutex_unbounded-2.i_64.smt2 |    0.033s | 20.788MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0620a_true-unreach-call.c_1.smt2 |    0.034s | 19.764MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_1.smt2 |    0.034s | 19.7MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_49.smt2 |    0.034s | 20.308MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/test_mutex_unbounded-2.i_63.smt2 |    0.034s | 20.808MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_1.smt2 |    0.035s | 20.328MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_6.smt2 |    0.035s | 20.568MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_14.smt2 |    0.035s | 20.052MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_34.smt2 |    0.036s | 20.332MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0663b.c_8.smt2 |    0.036s | 20.508MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1210_false-unreach-call.c_0.smt2 |    0.037s | 20.3MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_3.smt2 |    0.037s | 20.816MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_1.smt2 |    0.038s | 21.76MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_2.smt2 |    0.043s | 22.356MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_0.smt2 |    0.048s | 22.044MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_10.smt2 |    0.050s | 23.4MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_8.smt2 |    0.076s | 24.008MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float_req_bl_1130a.c_1.smt2 |    0.136s | 22.82MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_6.smt2 |    0.141s | 24.74MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_9.smt2 |    0.153s | 24.492MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0670_true-unreach-call.c_5.smt2 |    0.246s | 27.484MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0670_true-unreach-call.c_8.smt2 |    0.352s | 27.74MiB| sat | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_12.smt2 |    0.516s | 34.444MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_1300.c_2.smt2 |    2.677s | 48.76MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_1300.c_3.smt2 |    3.212s | 48.82MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_1300.c_1.smt2 |    4.063s | 50.308MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_1300.c_4.smt2 |    4.397s | 52.156MiB| unknown | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_13.smt2 |   20.010s | 45.024MiB| timeout | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_11.smt2 |   20.011s | 45.784MiB| timeout | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_10.smt2 |   20.013s | 45.6MiB| timeout | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_5.smt2 |   20.014s | 60.408MiB| timeout | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_11.smt2 |   20.024s | 96.324MiB| timeout | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_12.smt2 |   20.024s | 44.88MiB| timeout | 0 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_5.smt2 |   20.025s | 169.0MiB| timeout | 0 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float_req_bl_1130a.c_0.smt2 |   20.026s | 59.468MiB| timeout | 0 |  |  |
|non-incremental/ABVFP/20170501-Heizmann-UltimateAutomizer/filter_iir_true-unreach-call.c_35.smt2 |   20.030s | 145.0MiB| timeout | 0 |  |  |
