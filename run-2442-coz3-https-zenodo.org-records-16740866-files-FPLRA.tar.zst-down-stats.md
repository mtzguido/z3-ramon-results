# .

* SAT 24
* UNSAT 0
* TIMEOUT 17
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/FPLRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-FPLRA.tar.zst-down
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/FPLRA.tar.zst?download=1
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
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_7.smt2 |    0.020s | 20.6MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_14.smt2 |    0.021s | 20.304MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0683a_true-unreach-call.c_7.smt2 |    0.022s | 20.308MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_5.smt2 |    0.022s | 20.824MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_6.smt2 |    0.023s | 20.056MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0683a_true-unreach-call.c_3.smt2 |    0.074s | 23.416MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0683a_true-unreach-call.c_4.smt2 |    0.083s | 23.244MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_219.smt2 |    0.097s | 25.196MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/float-div1_true-unreach-call.i_574.smt2 |    0.136s | 36.72MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_1289.smt2 |    0.247s | 29.46MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_679.smt2 |    0.265s | 29.424MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_677.smt2 |    0.273s | 29.24MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_12.smt2 |    0.278s | 29.48MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_1310.smt2 |    0.322s | 29.676MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_1294.smt2 |    0.347s | 29.532MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0683a_true-unreach-call.c_6.smt2 |    0.433s | 28.496MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_1288.smt2 |    0.445s | 34.588MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/inv_square_true-unreach-call.c_139.smt2 |    0.538s | 33.312MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0683a_true-unreach-call.c_5.smt2 |    0.554s | 28.416MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/exp_loop_true-unreach-call.c_850.smt2 |    0.576s | 32.364MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0832a_true-unreach-call.c_2.smt2 |    2.356s | 43.732MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0832a_true-unreach-call.c_1.smt2 |    3.163s | 48.348MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1122a_true-unreach-call.c_3.smt2 |    4.609s | 131.0MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/water_pid_true-unreach-call_true-termination.c_2.smt2 |   11.138s | 84.916MiB| sat | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/inv_square_true-unreach-call.c_70.smt2 |   20.008s | 45.876MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/inv_square_true-unreach-call.c_72.smt2 |   20.008s | 45.172MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/inv_square_true-unreach-call.c_110.smt2 |   20.008s | 54.568MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20170501-Heizmann-UltimateAutomizer/inv_square_true-unreach-call.c_154.smt2 |   20.009s | 46.888MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/water_pid_true-unreach-call_true-termination.c_6.smt2 |   20.010s | 94.08MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call_true-termination.c_4.smt2 |   20.011s | 101.0MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/water_pid_true-unreach-call_true-termination.c_4.smt2 |   20.019s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call.c.v+nlh-reducer.c_0.smt2 |   20.019s | 87.16MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call.c.v+nlh-reducer.c_1.smt2 |   20.020s | 94.916MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call.c.v+lhb-reducer.c_1.smt2 |   20.020s | 97.756MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call_true-termination.c_1.smt2 |   20.020s | 91.388MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call_true-termination.c_3.smt2 |   20.021s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/filter1_true-unreach-call_true-termination.c_2.smt2 |   20.023s | 92.968MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/water_pid_true-unreach-call_true-termination.c_5.smt2 |   20.024s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/water_pid_true-unreach-call_true-termination.c_1.smt2 |   20.024s | 134.0MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/water_pid_true-unreach-call_true-termination.c_3.smt2 |   20.025s | 174.0MiB| timeout | 0 |  |  |
|non-incremental/FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1122a_true-unreach-call.c_0.smt2 |   20.035s | 293.0MiB| timeout | 0 |  |  |
