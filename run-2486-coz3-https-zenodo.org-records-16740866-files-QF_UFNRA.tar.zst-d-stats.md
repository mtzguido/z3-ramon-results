# .

* SAT 31
* UNSAT 24
* TIMEOUT 3
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFNRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFNRA.tar.zst-d
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFNRA.tar.zst?download=1
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
|non-incremental/QF_UFNRA/FFT/smtlib.631277.smt2              |    0.013s | 19.724MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631195.smt2              |    0.015s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.630867.smt2              |    0.020s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631113.smt2              |    0.022s | 19.308MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/z3.641736.smt2                  |    0.024s | 18.968MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modSimpleTest.smt2 |    0.025s | 19.872MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631031.smt2              |    0.026s | 19.26MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.640350.smt2              |    0.029s | 18.988MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.630785.smt2              |    0.031s | 19.42MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20190906-CLEARSY/0004/00003.smt2    |    0.033s | 19.536MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.630949.smt2              |    0.033s | 19.392MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/z3.630166.smt2                  |    0.033s | 19.308MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvInitial.smt2 |    0.033s | 20.048MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/l40f.smt2                       |    0.045s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvVar1.smt2 |    0.045s | 20.252MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvStep.smt2 |    0.054s | 20.34MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStepFinala.smt2 |    0.058s | 20.428MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/l40m.smt2                       |    0.062s | 20.64MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStepFinal.smt2 |    0.088s | 20.332MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/m40.easy.smt2                   |    0.190s | 27.444MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/c40s.smt2                       |    0.231s | 29.04MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s50.smt2                      |    0.271s | 29.972MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/c40f.smt2                       |    0.273s | 30.86MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep2.smt2 |    0.467s | 20.776MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/c40m.smt2                       |    0.501s | 32.748MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/l40s.smt2                       |    0.512s | 40.348MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m25.smt2                      |    0.532s | 36.968MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f25.smt2                      |    0.624s | 33.908MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m50.smt2                      |    0.683s | 34.928MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep2a.smt2 |    0.802s | 20.716MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f10.smt2                      |    0.886s | 37.572MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep4a.smt2 |    0.886s | 20.752MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m99.smt2                      |    0.993s | 35.464MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s10.smt2                      |    1.074s | 39.18MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s25.smt2                      |    1.142s | 39.096MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f50.smt2                      |    1.212s | 35.268MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep1.smt2 |    1.290s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep3a.smt2 |    1.338s | 20.944MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/20u10.09.smt2                   |    1.399s | 30.74MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s99.smt2                      |    1.454s | 39.788MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m10.smt2                      |    1.643s | 40.536MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f99.smt2                      |    1.795s | 35.896MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep3.smt2 |    1.988s | 20.82MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep6.smt2 |    2.576s | 21.416MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep4.smt2 |    2.590s | 21.032MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep5.smt2 |    2.776s | 21.548MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/s40.smt2                        |    5.518s | 36.94MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep1a.smt2 |    6.274s | 21.028MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep6a.smt2 |    7.699s | 21.296MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/20revert.u.smt2                 |    8.581s | 33.024MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep5a.smt2 |    8.669s | 22.068MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40u20.19.smt2                   |   10.021s | 55.488MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/10u05.04.smt2                   |   11.784s | 24.956MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/m40.smt2                        |   14.362s | 56.324MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep7.smt2 |   18.029s | 22.764MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/30u15.14.smt2                   |   20.008s | 40.128MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep7a.smt2 |   20.025s | 21.772MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvFull.smt2 |   20.065s | 939.0MiB| timeout | 0 |  |  |
