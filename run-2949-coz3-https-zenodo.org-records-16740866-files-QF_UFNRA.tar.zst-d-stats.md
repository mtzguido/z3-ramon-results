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
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFNRA.tar.zst?download=1 | Source list: benchmarks-qf.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFNRA.tar.zst-d
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2081918cea27e604b9077a6c36acb2ac28aa5b78
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFNRA.tar.zst?download=1
Z3 commit message: cmake: skip std::atomic link check for Emscripten and single-threaded builds (#9932)

The "Python bindings (Pyodide)" CI job fails at CMake configure time
because Emscripten's cross-compiler cannot pass the `std::atomic` link
tests in `check_link_atomic.cmake`, resulting in a fatal error even
though Pyodide builds are single-threaded and never need `libatomic`.

## Change

- **`cmake/check_link_atomic.cmake`**: guard the entire atomic check
behind `if (NOT (EMSCRIPTEN OR Z3_SINGLE_THREADED))`. Emscripten sets
`EMSCRIPTEN` automatically via `emcmake`; Pyodide builds also pass
`-DZ3_SINGLE_THREADED=TRUE`, so either condition is sufficient to bypass
the check safely.

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_UFNRA/20190906-CLEARSY/0004/00003.smt2    |    0.022s | 20.108MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modSimpleTest.smt2 |    0.026s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvInitial.smt2 |    0.030s | 20.7MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/z3.641736.smt2                  |    0.031s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631113.smt2              |    0.041s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.640350.smt2              |    0.041s | 19.576MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.630867.smt2              |    0.041s | 20.068MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631277.smt2              |    0.042s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.630949.smt2              |    0.045s | 20.06MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/l40f.smt2                       |    0.046s | 21.288MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.630785.smt2              |    0.046s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631031.smt2              |    0.048s | 20.036MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631195.smt2              |    0.050s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/z3.630166.smt2                  |    0.050s | 20.076MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvVar1.smt2 |    0.062s | 20.62MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvStep.smt2 |    0.064s | 20.92MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStepFinala.smt2 |    0.068s | 20.908MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/l40m.smt2                       |    0.069s | 21.172MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStepFinal.smt2 |    0.091s | 20.916MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/m40.easy.smt2                   |    0.178s | 28.288MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/c40s.smt2                       |    0.227s | 29.492MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s50.smt2                      |    0.236s | 30.544MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/c40f.smt2                       |    0.265s | 31.288MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep2.smt2 |    0.436s | 21.176MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/c40m.smt2                       |    0.467s | 33.168MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/l40s.smt2                       |    0.475s | 40.748MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m25.smt2                      |    0.480s | 37.404MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f25.smt2                      |    0.573s | 34.64MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m50.smt2                      |    0.633s | 35.7MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep2a.smt2 |    0.723s | 21.28MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f10.smt2                      |    0.790s | 38.228MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep4a.smt2 |    0.790s | 21.392MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m99.smt2                      |    0.919s | 36.124MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s10.smt2                      |    1.005s | 39.744MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s25.smt2                      |    1.034s | 39.452MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep1.smt2 |    1.169s | 21.46MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f50.smt2                      |    1.171s | 35.696MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/20u10.09.smt2                   |    1.194s | 31.26MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep3a.smt2 |    1.231s | 21.508MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s99.smt2                      |    1.368s | 40.308MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m10.smt2                      |    1.534s | 41.176MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f99.smt2                      |    1.802s | 36.564MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep3.smt2 |    1.830s | 21.584MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep6.smt2 |    2.155s | 21.636MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep4.smt2 |    2.209s | 21.532MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep5.smt2 |    2.389s | 21.888MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/s40.smt2                        |    4.954s | 37.696MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep1a.smt2 |    5.311s | 21.556MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep6a.smt2 |    6.360s | 22.012MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep5a.smt2 |    7.512s | 22.552MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/20revert.u.smt2                 |    7.526s | 33.484MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/10u05.04.smt2                   |    9.053s | 25.652MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40u20.19.smt2                   |    9.383s | 56.364MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/m40.smt2                        |   13.385s | 56.876MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep7.smt2 |   14.794s | 23.312MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep7a.smt2 |   20.009s | 22.564MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/30u15.14.smt2                   |   20.011s | 40.768MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvFull.smt2 |   20.130s | 939.0MiB| timeout | 0 |  |  |
