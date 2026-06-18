# .

* SAT 29
* UNSAT 2
* TIMEOUT 28
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_FPLRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_FPLRA.tar.zst-d
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_FPLRA.tar.zst?download=1
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
|non-incremental/QF_FPLRA/schanda/spark/zeros_consistent_1.smt2 |    0.025s | 19.272MiB| unsat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/Double_div_bad_false-unreach-call.i_1.smt2 |    0.041s | 19.636MiB| unsat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c_3.smt2 |    1.572s | 330.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/Double_div_bad_false-unreach-call.i_0.smt2 |    2.655s | 160.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c.p+cfa-reducer.c_4.smt2 |    2.801s | 264.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0520_true-unreach-call.c_0.smt2 |    4.121s | 197.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0310_true-unreach-call.c_3.smt2 |    5.246s | 173.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0250b_true-unreach-call.c_4.smt2 |    5.640s | 294.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0320_true-unreach-call.c_7.smt2 |    5.722s | 367.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c.p+cfa-reducer.c_2.smt2 |    6.487s | 391.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0330a_true-unreach-call.c_6.smt2 |    6.916s | 486.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Newton_pseudoconstant_true-unreach-call.c_1.smt2 |    7.011s | 418.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0320_true-unreach-call.c_5.smt2 |    7.799s | 486.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0873a_true-unreach-call.c_3.smt2 |    8.346s | 359.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0470_true-unreach-call.c_12.smt2 |    8.658s | 389.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c.p+cfa-reducer.c_1.smt2 |    9.062s | 392.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0870b.c_1.smt2 |    9.295s | 208.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0260_true-unreach-call.c_1.smt2 |   10.477s | 676.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0490a_true-unreach-call.c_0.smt2 |   10.657s | 391.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0490a_true-unreach-call.c_10.smt2 |   10.715s | 443.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0490a_true-unreach-call.c_9.smt2 |   10.725s | 389.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_2.smt2 |   10.891s | 682.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0330b_true-unreach-call.c_10.smt2 |   11.166s | 490.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0460_true-unreach-call.c_2.smt2 |   11.190s | 484.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0870b_true-unreach-call.c_3.smt2 |   11.675s | 230.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c.p+cfa-reducer.c_3.smt2 |   11.981s | 766.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20170501-Heizmann-UltimateAutomizer/image_filter_true-unreach-call.c_2.smt2 |   13.080s | 194.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20170501-Heizmann-UltimateAutomizer/filter2_reinit_true-unreach-call.c_7.smt2 |   13.306s | 170.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0320_true-unreach-call.c_6.smt2 |   15.853s | 185.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/Rump_double_true-unreach-call_true-termination.c_0.smt2 |   16.542s | 2579.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/cos_polynomial_true-unreach-call_true-termination.c_0.smt2 |   19.442s | 521.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20230321-UltimateAutomizerSvcomp2023/cos_polynomial.c_0.smt2 |   20.046s | 457.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0874_true-unreach-call.c_3.smt2 |   20.058s | 220.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_11.smt2 |   20.139s | 370.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0240a_true-unreach-call.c_6.smt2 |   20.145s | 348.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0550b_true-unreach-call.c_9.smt2 |   20.151s | 420.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0490a_true-unreach-call.c_2.smt2 |   20.173s | 462.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20170501-Heizmann-UltimateAutomizer/cos_polynomial_true-unreach-call.c_9.smt2 |   20.180s | 508.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_4.smt2 |   20.323s | 1083.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_21.smt2 |   20.336s | 1138.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0260_true-unreach-call.c_3.smt2 |   20.336s | 1077.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0250a.c_1.smt2 |   20.340s | 1079.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_19.smt2 |   20.349s | 1250.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0490a_true-unreach-call.c_3.smt2 |   20.400s | 1611.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0490a.c_4.smt2 |   20.405s | 1624.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0460_true-unreach-call.c_3.smt2 |   20.407s | 1612.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/lnLaw.smt2            |   20.410s | 1900.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/expLaw.smt2           |   20.415s | 1913.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propLnExp1.smt2       |   20.416s | 1903.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propLnExp0.smt2       |   20.417s | 1903.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propExpLn3.smt2       |   20.425s | 1903.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/expInUnit.smt2        |   20.427s | 1900.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propExpLn1.smt2       |   20.428s | 1899.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propLnExp3.smt2       |   20.428s | 1897.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propExpLn2.smt2       |   20.429s | 1897.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propLnExp2.smt2       |   20.431s | 1888.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propExpLn0.smt2       |   20.435s | 2146.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/maxReward.smt2        |   20.931s | 12.826GiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/expInUnit2.smt2       |   20.953s | 13.041GiB| timeout | 0 |  |  |
