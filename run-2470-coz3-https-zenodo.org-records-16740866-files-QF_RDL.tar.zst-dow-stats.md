# .

* SAT 94
* UNSAT 96
* TIMEOUT 65
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_RDL.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_RDL.tar.zst-dow
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_RDL.tar.zst?download=1
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
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-1.smt2 |    0.018s | 19.552MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-1.smt2             |    0.020s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-1.smt2             |    0.020s | 19.56MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking01.smt2 |    0.022s | 19.764MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-1.smt2             |    0.022s | 19.912MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-4.smt2             |    0.022s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-2.smt2             |    0.023s | 20.008MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-3.smt2             |    0.024s | 19.808MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-2.smt2             |    0.025s | 20.44MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking02.smt2 |    0.027s | 20.008MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-5.smt2             |    0.027s | 20.348MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-3.smt2             |    0.027s | 20.412MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-2.smt2             |    0.027s | 19.688MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking03.smt2 |    0.029s | 20.064MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-6.smt2             |    0.030s | 20.304MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_250.smt2             |    0.034s | 21.58MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-4.smt2             |    0.034s | 20.568MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-04.smt2 |    0.035s | 20.556MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-5.smt2             |    0.035s | 20.972MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-3.smt2             |    0.035s | 20.76MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/check/bignum_rdl1.smt2                |    0.036s | 19.92MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-2.smt2 |    0.036s | 20.48MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-03.smt2 |    0.036s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-2.smt2 |    0.037s | 20.644MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking05.smt2 |    0.037s | 20.476MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/check/bignum_rdl2.smt2                |    0.039s | 19.716MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-7.smt2             |    0.039s | 20.568MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-4.smt2             |    0.040s | 21.184MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking06.smt2 |    0.041s | 20.772MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-8.smt2             |    0.046s | 20.756MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_330.smt2             |    0.047s | 22.428MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking07.smt2 |    0.047s | 20.9MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-matrix1x1.pddl.smt2 |    0.047s | 19.488MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-6.smt2             |    0.048s | 21.304MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-06.smt2 |    0.050s | 20.924MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking08.smt2 |    0.051s | 21.072MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-5.smt2             |    0.051s | 21.828MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_700.smt2             |    0.055s | 21.984MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-08.smt2 |    0.058s | 21.392MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking10.smt2 |    0.062s | 21.424MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking04.smt2 |    0.063s | 20.488MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking11.smt2 |    0.065s | 21.716MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_800.smt2              |    0.067s | 22.78MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_700.smt2             |    0.067s | 22.796MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-05.smt2 |    0.069s | 21.052MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-10.smt2 |    0.070s | 21.672MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1000.smt2             |    0.072s | 22.832MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-9.smt2             |    0.073s | 21.064MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-6.smt2             |    0.075s | 22.24MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_850.smt2             |    0.076s | 23.208MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking09.smt2 |    0.080s | 21.18MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking13.smt2 |    0.080s | 21.86MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-07.smt2 |    0.083s | 21.356MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking14.smt2 |    0.085s | 21.984MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking15.smt2 |    0.090s | 22.124MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking16.smt2 |    0.090s | 22.436MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-7.smt2             |    0.090s | 21.476MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking12.smt2 |    0.091s | 21.648MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-09.smt2 |    0.092s | 21.828MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking17.smt2 |    0.102s | 22.436MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking18.smt2 |    0.104s | 22.64MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-3.smt2 |    0.104s | 22.648MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking20.smt2 |    0.110s | 22.972MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-10.smt2            |    0.110s | 21.436MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking19.smt2 |    0.119s | 22.792MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking21.smt2 |    0.122s | 23.348MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking22.smt2 |    0.123s | 23.256MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_800.smt2             |    0.127s | 23.236MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_800.smt2             |    0.130s | 23.12MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_700.smt2             |    0.131s | 23.124MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_800.smt2             |    0.132s | 23.164MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1400.smt2             |    0.136s | 23.612MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-8.smt2             |    0.159s | 22.12MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_1100.smt2             |    0.189s | 23.852MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-11.smt2            |    0.207s | 21.768MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-20.smt2 |    0.208s | 23.648MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-7.smt2             |    0.208s | 23.112MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_550.smt2             |    0.209s | 24.24MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_1000.smt2            |    0.226s | 23.768MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa/skdmxa-3x3-5.smt2              |    0.237s | 33.9MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-12.smt2            |    0.239s | 21.86MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_1000.smt2            |    0.260s | 24.164MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-13.smt2            |    0.263s | 21.944MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-8.smt2             |    0.309s | 23.736MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_1100.smt2            |    0.314s | 24.38MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-9.smt2             |    0.352s | 23.06MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_900.smt2             |    0.374s | 23.512MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_1000.smt2             |    0.378s | 24.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_900.smt2              |    0.396s | 23.756MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_800.smt2             |    0.407s | 23.764MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-16.smt2            |    0.407s | 22.732MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-14.smt2            |    0.417s | 22.604MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_1200.smt2            |    0.440s | 24.4MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-5.base.cvc.smt2    |    0.440s | 49.624MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_850.smt2             |    0.448s | 23.596MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-15.smt2            |    0.491s | 22.748MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-30.smt2 |    0.511s | 26.128MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_830.smt2             |    0.514s | 23.884MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_950.smt2             |    0.545s | 24.036MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-6.base.cvc.smt2    |    0.557s | 55.436MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1300.smt2             |    0.632s | 24.24MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-17.smt2            |    0.739s | 23.428MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-3.smt2 |    0.740s | 24.136MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_900.smt2             |    0.771s | 24.4MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_900.smt2             |    0.776s | 23.972MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-40.smt2 |    0.787s | 27.74MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-18.smt2            |    0.799s | 23.792MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-5.induction.cvc.smt2 |    0.855s | 66.04MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_943.smt2              |    0.858s | 23.956MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-10.smt2            |    0.863s | 23.896MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_1200.smt2            |    0.881s | 24.884MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-7.base.cvc.smt2    |    0.918s | 59.568MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_1100.smt2            |    0.926s | 25.076MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-11.smt2            |    0.960s | 24.632MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-19.smt2            |    0.973s | 24.188MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_1100.smt2            |    1.002s | 24.832MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-9.smt2             |    1.029s | 24.748MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-12.smt2            |    1.080s | 24.312MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-20.smt2            |    1.271s | 24.68MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_430.smt2             |    1.354s | 24.812MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-9.base.cvc.smt2    |    1.391s | 87.052MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_1000.smt2            |    1.420s | 24.916MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-13.smt2            |    1.431s | 25.436MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-6.induction.cvc.smt2 |    1.469s | 83.688MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_1200.smt2            |    1.549s | 25.54MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_1000.smt2            |    1.561s | 25.24MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_1200.smt2            |    1.568s | 25.56MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa/skdmxa-3x3-10.smt2             |    1.609s | 59.524MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-7.induction.cvc.smt2 |    1.627s | 87.392MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_750.smt2               |    1.642s | 65.768MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-8.base.cvc.smt2    |    1.649s | 83.332MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_750.smt2               |    1.678s | 64.816MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-4.smt2 |    1.737s | 27.328MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_900.smt2             |    1.758s | 24.352MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-9.induction.cvc.smt2 |    2.100s | 124.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_750.smt2               |    2.287s | 65.036MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-8.induction.cvc.smt2 |    2.359s | 106.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-10.smt2            |    2.599s | 27.248MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-11.smt2            |    2.749s | 26.868MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_1100.smt2            |    2.822s | 25.68MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-60.smt2 |    3.011s | 48.392MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-10.induction.cvc.smt2 |    3.090s | 127.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_500.smt2              |    3.131s | 48.912MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-11.induction.cvc.smt2 |    3.216s | 151.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_900.smt2             |    3.257s | 25.128MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-14.smt2            |    3.298s | 27.056MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-16.smt2            |    3.616s | 26.856MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_934.smt2             |    3.631s | 25.764MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_888.smt2             |    3.663s | 25.644MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1200.smt2             |    3.708s | 25.144MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-12.induction.cvc.smt2 |    3.877s | 153.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-10.base.cvc.smt2   |    4.027s | 97.708MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-13.induction.cvc.smt2 |    4.131s | 184.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-80.smt2 |    4.152s | 44.404MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-14.induction.cvc.smt2 |    4.819s | 184.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_1000.smt2            |    5.047s | 25.544MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_1100.smt2            |    5.055s | 26.412MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-70.smt2 |    5.251s | 43.176MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-15.smt2            |    5.267s | 27.52MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-12.smt2            |    5.315s | 28.384MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-18.smt2            |    5.576s | 29.6MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_397.smt2             |    5.647s | 25.92MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-16.induction.cvc.smt2 |    5.847s | 238.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_900.smt2             |    5.900s | 26.252MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-11.base.cvc.smt2   |    6.260s | 103.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-17.smt2            |    6.365s | 28.812MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_944.smt2             |    6.862s | 26.212MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_1005.smt2            |    6.891s | 26.528MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-15.induction.cvc.smt2 |    6.926s | 223.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_930.smt2             |    7.470s | 26.532MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_950.smt2             |    7.480s | 26.156MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-17.induction.cvc.smt2 |    8.386s | 250.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-19.smt2            |    8.496s | 30.172MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-13.base.cvc.smt2   |    8.529s | 117.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_1100.smt2            |    8.864s | 27.12MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-18.induction.cvc.smt2 |    8.978s | 274.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-14.smt2            |    9.022s | 30.48MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-90.smt2 |    9.076s | 46.932MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_888.smt2             |   10.346s | 27.148MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-19.induction.cvc.smt2 |   10.349s | 299.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-13.smt2            |   11.397s | 31.572MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1234.smt2             |   13.244s | 27.596MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_887.smt2             |   13.263s | 27.34MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-20.smt2            |   14.118s | 31.548MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-12.base.cvc.smt2   |   14.583s | 111.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-20.induction.cvc.smt2 |   16.652s | 370.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-5.smt2 |   17.993s | 47.144MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-16.smt2            |   18.434s | 35.924MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa/skdmxa-3x3-15.smt2             |   18.440s | 98.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-14.base.cvc.smt2   |   19.514s | 124.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-18.smt2            |   20.007s | 36.408MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-20.smt2            |   20.007s | 36.908MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-15.smt2            |   20.007s | 34.204MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_1010.smt2            |   20.008s | 28.256MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-4.smt2 |   20.008s | 46.22MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-7.smt2 |   20.009s | 88.528MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-6.smt2 |   20.009s | 56.044MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-17.smt2            |   20.009s | 36.524MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-19.smt2            |   20.010s | 36.748MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-5.smt2 |   20.011s | 79.984MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_828.smt2               |   20.012s | 79.26MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_1000.smt2            |   20.013s | 27.968MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_910.smt2               |   20.013s | 85.384MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_860.smt2               |   20.013s | 82.732MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-matrix2x2.pddl.smt2 |   20.013s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_827.smt2               |   20.015s | 79.128MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-6.smt2 |   20.015s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_1000.smt2            |   20.016s | 28.428MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_2900.smt2            |   20.019s | 197.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv13_3200.smt2            |   20.020s | 204.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_969.smt2               |   20.020s | 86.588MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_919.smt2               |   20.020s | 83.396MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_2972.smt2            |   20.020s | 199.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_887.smt2               |   20.021s | 82.208MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_691.smt2              |   20.021s | 70.264MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_850.smt2               |   20.021s | 76.468MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_950.smt2               |   20.023s | 87.704MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_670.smt2              |   20.028s | 69.684MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa/skdmxa-3x3-20.smt2             |   20.029s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_950.smt2               |   20.030s | 87.16MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_700.smt2              |   20.031s | 69.892MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_890.smt2               |   20.031s | 85.68MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_950.smt2               |   20.032s | 85.536MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-17.base.cvc.smt2   |   20.032s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-20.base.cvc.smt2   |   20.034s | 226.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_600.smt2              |   20.035s | 64.212MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_862.smt2               |   20.035s | 82.04MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-15.base.cvc.smt2   |   20.035s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_1059.smt2            |   20.037s | 28.58MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-16.base.cvc.smt2   |   20.038s | 175.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_3050.smt2            |   20.040s | 193.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_2895.smt2            |   20.040s | 190.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-18.base.cvc.smt2   |   20.040s | 192.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_1005.smt2            |   20.041s | 28.052MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_3050.smt2            |   20.043s | 209.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_894.smt2               |   20.044s | 84.464MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-19.base.cvc.smt2   |   20.046s | 226.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_950.smt2               |   20.048s | 85.82MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_667.smt2              |   20.048s | 69.16MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv13_3150.smt2            |   20.048s | 203.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_2990.smt2            |   20.050s | 207.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_2988.smt2            |   20.050s | 194.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_850.smt2               |   20.052s | 80.368MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_800.smt2              |   20.054s | 73.736MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_1000.smt2              |   20.056s | 88.548MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_2900.smt2            |   20.057s | 192.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_2800.smt2            |   20.057s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_3004.smt2            |   20.058s | 194.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_3000.smt2            |   20.058s | 196.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_2885.smt2            |   20.058s | 191.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_2905.smt2            |   20.059s | 195.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_2992.smt2            |   20.059s | 193.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_2983.smt2            |   20.063s | 190.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv13_3000.smt2            |   20.063s | 195.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv13_3104.smt2            |   20.065s | 199.0MiB| timeout | 0 |  |  |
