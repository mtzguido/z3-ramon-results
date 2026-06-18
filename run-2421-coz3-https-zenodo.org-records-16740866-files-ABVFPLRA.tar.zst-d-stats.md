# .

* SAT 59
* UNSAT 4
* TIMEOUT 0
* UNKNOWN 14

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/ABVFPLRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-ABVFPLRA.tar.zst-d
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/ABVFPLRA.tar.zst?download=1
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
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_7.smt2 |    0.014s | 20.02MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_15.smt2 |    0.014s | 19.58MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0832_true-unreach-call.c_9.smt2 |    0.015s | 19.792MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_7.smt2 |    0.015s | 20.076MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_8.smt2 |    0.015s | 20.22MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_15.smt2 |    0.016s | 20.276MiB| unknown | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_10.smt2 |    0.017s | 20.6MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0682a_true-unreach-call.c_1.smt2 |    0.017s | 20.58MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_11.smt2 |    0.018s | 20.8MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_15.smt2 |    0.018s | 20.304MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_15.smt2 |    0.019s | 20.352MiB| unknown | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0832_true-unreach-call.c_5.smt2 |    0.020s | 20.472MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_23.smt2 |    0.020s | 20.348MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_11.smt2 |    0.020s | 20.34MiB| unknown | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_6.smt2 |    0.021s | 20.052MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_12.smt2 |    0.021s | 20.424MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_21.smt2 |    0.021s | 21.088MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_18.smt2 |    0.021s | 20.604MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_28.smt2 |    0.021s | 20.488MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_8.smt2 |    0.021s | 21.32MiB| unsat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_12.smt2 |    0.022s | 20.28MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_14.smt2 |    0.022s | 20.084MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_24.smt2 |    0.022s | 20.188MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_10.smt2 |    0.024s | 20.82MiB| unknown | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_17.smt2 |    0.024s | 20.212MiB| unknown | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_8.smt2 |    0.025s | 20.68MiB| unknown | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1032d_true-unreach-call.c_0.smt2 |    0.025s | 19.708MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_10.smt2 |    0.026s | 20.224MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_25.smt2 |    0.026s | 21.152MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_5.smt2 |    0.026s | 19.988MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_6.smt2 |    0.026s | 20.076MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_9.smt2 |    0.027s | 20.256MiB| unknown | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_14.smt2 |    0.027s | 20.976MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_12.smt2 |    0.027s | 20.644MiB| unknown | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_18.smt2 |    0.027s | 20.54MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_4.smt2 |    0.027s | 20.184MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_9.smt2 |    0.027s | 20.1MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_8.smt2 |    0.027s | 20.308MiB| unknown | 0 |  |  |
|non-incremental/ABVFPLRA/20230321-UltimateAutomizerSvcomp2023/float_req_bl_0683a.c_5.smt2 |    0.027s | 20.096MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20230321-UltimateAutomizerSvcomp2023/float_req_bl_0683a.c_7.smt2 |    0.027s | 20.152MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_7.smt2 |    0.028s | 19.992MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_12.smt2 |    0.029s | 20.06MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_9.smt2 |    0.029s | 20.424MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0883_true-unreach-call.c_5.smt2 |    0.029s | 20.156MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_18.smt2 |    0.030s | 20.608MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_13.smt2 |    0.030s | 20.276MiB| unknown | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_12.smt2 |    0.030s | 20.632MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_21.smt2 |    0.031s | 21.188MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_11.smt2 |    0.032s | 20.1MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_13.smt2 |    0.032s | 20.144MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_19.smt2 |    0.032s | 20.32MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_15.smt2 |    0.032s | 20.248MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_11.smt2 |    0.033s | 21.16MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_27.smt2 |    0.034s | 20.532MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_23.smt2 |    0.034s | 20.884MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0832_true-unreach-call.c_4.smt2 |    0.035s | 21.072MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_16.smt2 |    0.035s | 20.28MiB| unknown | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_13.smt2 |    0.035s | 20.3MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_5.smt2 |    0.036s | 20.132MiB| unknown | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_14.smt2 |    0.037s | 20.856MiB| unknown | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_22.smt2 |    0.037s | 20.764MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_22.smt2 |    0.038s | 21.072MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_3.smt2 |    0.039s | 20.776MiB| unknown | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_29.smt2 |    0.039s | 20.564MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_24.smt2 |    0.040s | 21.084MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0832_true-unreach-call.c_6.smt2 |    0.041s | 20.348MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_13.smt2 |    0.042s | 23.036MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_16.smt2 |    0.045s | 22.86MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_18.smt2 |    0.073s | 24.124MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_17.smt2 |    0.167s | 26.8MiB| unsat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_19.smt2 |    0.183s | 30.172MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_20.smt2 |    0.337s | 30.996MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_13.smt2 |    0.442s | 31.744MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_16.smt2 |    0.482s | 33.536MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_11.smt2 |    0.667s | 33.288MiB| sat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_14.smt2 |    2.688s | 52.232MiB| unsat | 0 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_17.smt2 |    4.954s | 126.0MiB| unsat | 0 |  |  |
