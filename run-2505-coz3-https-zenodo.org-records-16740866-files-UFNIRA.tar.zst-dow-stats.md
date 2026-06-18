# .

* SAT 15
* UNSAT 94
* TIMEOUT 151
* UNKNOWN 6

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFNIRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFNIRA.tar.zst-dow
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFNIRA.tar.zst?download=1
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
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U6_sol1.smt2 |    0.013s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C3_sol1.smt2 |    0.014s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U72_sol1.smt2 |    0.014s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U19_sol1.smt2 |    0.014s | 19.536MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U20.smt2 |    0.014s | 20.044MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U8_sol1.smt2 |    0.015s | 19.732MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U48_sol1.smt2 |    0.015s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U49_sol1.smt2 |    0.016s | 19.588MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U46_sol2.smt2 |    0.016s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U72.smt2 |    0.016s | 20.092MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U71.smt2 |    0.016s | 20.152MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U25_sol2.smt2 |    0.017s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U90_sol1.smt2 |    0.018s | 19.404MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U39_sol1.smt2 |    0.018s | 19.464MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U42_sol1.smt2 |    0.018s | 19.432MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U75.smt2 |    0.018s | 20.28MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C1_sol1.smt2 |    0.019s | 19.532MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U23.smt2 |    0.019s | 20.32MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C4_sol1.smt2 |    0.020s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U48.smt2 |    0.020s | 20.048MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U62.smt2 |    0.020s | 20.14MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U82_sol1.smt2 |    0.021s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol3.smt2 |    0.021s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U91_sol1.smt2 |    0.021s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U75_sol2.smt2 |    0.021s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U41.smt2 |    0.021s | 20.016MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C10_sol1.smt2 |    0.022s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U75_sol1.smt2 |    0.022s | 19.376MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U45_sol1.smt2 |    0.022s | 20.032MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U56_sol1.smt2 |    0.023s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U91_sol2.smt2 |    0.023s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol2.smt2 |    0.023s | 19.528MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U26_sol1.smt2 |    0.024s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U1.smt2 |    0.024s | 20.18MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U92_sol1.smt2 |    0.025s | 19.364MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U24_sol1.smt2 |    0.025s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U66.smt2 |    0.025s | 20.18MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U45_sol2.smt2 |    0.026s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U81_sol1.smt2 |    0.027s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U25_sol1.smt2 |    0.028s | 19.772MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U48_sol2.smt2 |    0.029s | 19.576MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C13_sol1.smt2 |    0.029s | 19.748MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U71_sol1.smt2 |    0.029s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U17_sol1.smt2 |    0.029s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U87_sol1.smt2 |    0.029s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U89.smt2 |    0.029s | 20.104MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C6_sol1.smt2 |    0.030s | 19.328MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U27_sol1.smt2 |    0.030s | 19.816MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U61_sol1.smt2 |    0.030s | 20.308MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U62_sol1.smt2 |    0.030s | 19.56MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U89_sol1.smt2 |    0.030s | 19.536MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9a_sol1.smt2 |    0.031s | 19.82MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U2_sol1.smt2 |    0.031s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U46_sol1.smt2 |    0.031s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U56_sol2.smt2 |    0.032s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U87_sol2.smt2 |    0.033s | 19.572MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U51_sol1.smt2 |    0.033s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol3.smt2 |    0.033s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U53_sol1.smt2 |    0.034s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U44_sol1.smt2 |    0.034s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U8_sol2.smt2 |    0.035s | 19.508MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U64_sol1.smt2 |    0.035s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C2_sol1.smt2 |    0.035s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U54_sol2.smt2 |    0.035s | 19.532MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U23_sol1.smt2 |    0.035s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U49_sol2.smt2 |    0.036s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U14_sol1.smt2 |    0.036s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U10_sol1.smt2 |    0.036s | 20.036MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U5_sol1.smt2 |    0.036s | 19.632MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U67_sol1.smt2 |    0.036s | 20.012MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U13_sol1.smt2 |    0.036s | 19.536MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol3.smt2 |    0.037s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol2.smt2 |    0.037s | 19.356MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U11_sol1.smt2 |    0.038s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol1.smt2 |    0.038s | 19.516MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U26_sol2.smt2 |    0.038s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U54_sol1.smt2 |    0.038s | 20.308MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U68.smt2 |    0.038s | 20.068MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U93_sol1.smt2 |    0.039s | 20.036MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U46.smt2 |    0.040s | 20.036MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U51.smt2 |    0.040s | 20.06MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U17.smt2 |    0.041s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U57_sol1.smt2 |    0.042s | 20.044MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol1.smt2 |    0.043s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U76_sol1.smt2 |    0.043s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol2.smt2 |    0.043s | 19.576MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U57.smt2 |    0.043s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U68_sol1.smt2 |    0.044s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U4_sol1.smt2 |    0.044s | 20.304MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C12_sol1.smt2 |    0.045s | 19.576MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9_sol1.smt2 |    0.046s | 19.996MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U3_sol1.smt2 |    0.047s | 19.536MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U72_sol2.smt2 |    0.049s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U81.smt2 |    0.050s | 20.016MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U7_sol1.smt2 |    0.051s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U9_sol1.smt2 |    0.051s | 19.572MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U4.smt2 |    0.054s | 20.816MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C10.smt2 |    0.055s | 19.808MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U11.smt2 |    0.059s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol1.smt2 |    0.062s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U44_sol2.smt2 |    0.066s | 20.292MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U37_sol1.smt2 |    0.079s | 20.764MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C5_sol1.smt2 |    0.079s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U66_sol1.smt2 |    0.089s | 19.412MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U26.smt2 |    0.099s | 21.764MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U79.smt2 |    0.101s | 31.916MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C5.smt2 |    0.174s | 20.552MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U12_sol1.smt2 |    0.185s | 20.304MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U66_sol2.smt2 |    0.337s | 20.02MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U7.smt2 |    4.989s | 26.036MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C6.smt2 |    6.056s | 44.896MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U14.smt2 |    6.260s | 29.9MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U14.smt2 |    9.456s | 28.944MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U16_sol1.smt2 |   10.587s | 32.46MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U17.smt2 |   12.714s | 142.0MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U45.smt2 |   20.007s | 27.768MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol1.smt2 |   20.008s | 30.008MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C7.smt2 |   20.008s | 28.168MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U88.smt2 |   20.010s | 36.22MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U76.smt2 |   20.010s | 27.004MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U53.smt2 |   20.010s | 44.756MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C9a.smt2 |   20.010s | 65.516MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U39.smt2 |   20.011s | 65.74MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U10.smt2 |   20.015s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C8_sol1.smt2 |   20.017s | 34.488MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U12.smt2 |   20.018s | 32.872MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U27.smt2 |   20.021s | 24.568MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U90.smt2 |   20.021s | 96.176MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C7_sol1.smt2 |   20.022s | 31.736MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U11.smt2 |   20.022s | 55.592MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U1_sol1.smt2 |   20.023s | 25.664MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U76.smt2 |   20.023s | 28.588MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U23.smt2 |   20.023s | 56.62MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C5.smt2 |   20.023s | 22.1MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U34.smt2 |   20.023s | 167.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U40_sol1.smt2 |   20.025s | 21.004MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C3.smt2 |   20.026s | 64.908MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U38.smt2 |   20.026s | 38.88MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C9.smt2 |   20.027s | 62.324MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U7.smt2 |   20.029s | 52.044MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C7.smt2 |   20.030s | 28.52MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U27.smt2 |   20.030s | 22.476MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U9.smt2 |   20.031s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U66.smt2 |   20.032s | 30.636MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U93.smt2 |   20.032s | 27.516MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C9a.smt2 |   20.033s | 47.556MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C9.smt2 |   20.033s | 36.132MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U12.smt2 |   20.035s | 28.276MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U93.smt2 |   20.036s | 27.084MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U6.smt2 |   20.039s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U33.smt2 |   20.040s | 185.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U57.smt2 |   20.041s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U81.smt2 |   20.042s | 56.516MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U33_sol1.smt2 |   20.046s | 427.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C3.smt2 |   20.046s | 70.864MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U53.smt2 |   20.048s | 48.008MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C4.smt2 |   20.051s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U30.smt2 |   20.058s | 23.16MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U44.smt2 |   20.061s | 41.54MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C13.smt2 |   20.063s | 266.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U87.smt2 |   20.065s | 66.476MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U90.smt2 |   20.071s | 93.9MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U26.smt2 |   20.075s | 32.52MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U9.smt2 |   20.079s | 191.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U72.smt2 |   20.083s | 301.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U6.smt2 |   20.083s | 191.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U33.smt2 |   20.101s | 171.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U44.smt2 |   20.109s | 414.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C6.smt2 |   20.112s | 308.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U4.smt2 |   20.123s | 377.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U45.smt2 |   20.124s | 221.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C10.smt2 |   20.134s | 283.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U10.smt2 |   20.135s | 261.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C13.smt2 |   20.136s | 239.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C4.smt2 |   20.155s | 260.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U39.smt2 |   20.193s | 334.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U16.smt2 |   20.197s | 266.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U91.smt2 |   20.209s | 551.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U56.smt2 |   20.215s | 3058.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U1.smt2 |   20.217s | 2089.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U28.smt2 |   20.221s | 348.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol2.smt2 |   20.228s | 3173.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U71.smt2 |   20.243s | 617.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U68.smt2 |   20.251s | 380.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U92.smt2 |   20.252s | 1406.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U21.smt2 |   20.254s | 3393.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C2.smt2 |   20.270s | 557.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U41.smt2 |   20.273s | 3964.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U47.smt2 |   20.293s | 641.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U22.smt2 |   20.305s | 3622.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U19.smt2 |   20.361s | 719.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C8.smt2 |   20.384s | 629.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U19.smt2 |   20.413s | 2025.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U5.smt2 |   20.442s | 2044.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U22_sol1.smt2 |   20.447s | 3488.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U87.smt2 |   20.448s | 1796.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U70.smt2 |   20.465s | 2347.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U91.smt2 |   20.495s | 1176.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U61.smt2 |   20.510s | 2622.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C8.smt2 |   20.510s | 1210.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U16.smt2 |   20.518s | 985.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U89.smt2 |   20.537s | 7363.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U51.smt2 |   20.612s | 1398.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U43.smt2 |   20.626s | 2839.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C11_sol1.smt2 |   20.646s | 2927.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U29.smt2 |   20.654s | 2754.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U65.smt2 |   20.755s | 4214.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U50.smt2 |   20.783s | 3444.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U43.smt2 |   20.791s | 1688.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U67.smt2 |   20.800s | 1906.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U37.smt2 |   20.813s | 2252.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U31.smt2 |   20.814s | 3622.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U48.smt2 |   20.831s | 1910.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U21_sol1.smt2 |   20.842s | 3702.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U62.smt2 |   20.843s | 2163.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U46.smt2 |   20.852s | 4527.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U67.smt2 |   20.889s | 2169.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U43_sol1.smt2 |   20.894s | 8028.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U40.smt2 |   20.906s | 4070.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U64.smt2 |   20.914s | 3953.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U37.smt2 |   20.951s | 2144.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U8.smt2 |   20.980s | 3464.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U15.smt2 |   21.027s | 2678.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U29.smt2 |   21.148s | 2754.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U82.smt2 |   21.152s | 2787.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U61.smt2 |   21.152s | 2715.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U73.smt2 |   21.153s | 3594.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U73_sol1.smt2 |   21.156s | 4015.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U20.smt2 |   21.165s | 3405.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U24.smt2 |   21.172s | 4170.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U54.smt2 |   21.202s | 3567.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U75.smt2 |   21.217s | 7972.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U50.smt2 |   21.244s | 3116.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U56.smt2 |   21.249s | 2919.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U54.smt2 |   21.257s | 3080.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U42.smt2 |   21.272s | 4125.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U3.smt2 |   21.287s | 3263.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U15.smt2 |   21.337s | 3392.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U8.smt2 |   21.344s | 3378.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C11.smt2 |   21.360s | 3399.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U40.smt2 |   21.360s | 3437.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C12.smt2 |   21.363s | 4455.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U22.smt2 |   21.369s | 3397.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U21.smt2 |   21.378s | 3393.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U5.smt2 |   21.380s | 4741.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C11.smt2 |   21.393s | 3399.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C1.smt2 |   21.395s | 3844.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U82.smt2 |   21.440s | 3668.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U49.smt2 |   21.449s | 3702.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U2.smt2 |   21.465s | 4296.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U3.smt2 |   21.467s | 4219.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U2.smt2 |   21.481s | 4463.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U24.smt2 |   21.518s | 4235.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U25.smt2 |   21.561s | 4394.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U64.smt2 |   21.567s | 5329.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C12.smt2 |   21.572s | 4529.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U49.smt2 |   21.576s | 4489.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U25.smt2 |   21.597s | 4439.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U13.smt2 |   21.599s | 4555.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U13.smt2 |   21.601s | 4516.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C1.smt2 |   21.706s | 7337.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C2.smt2 |   21.726s | 7960.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U92.smt2 |   21.729s | 8154.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U73.smt2 |   21.839s | 8218.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U42.smt2 |   21.935s | 9180.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U29_sol1.smt2 |   21.939s | 6528.0MiB| timeout | 0 |  |  |
