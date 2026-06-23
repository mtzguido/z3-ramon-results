# .

* SAT 93
* UNSAT 96
* TIMEOUT 66
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_RDL.tar.zst?download=1 | Source list: benchmarks-qf.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_RDL.tar.zst-dow
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2081918cea27e604b9077a6c36acb2ac28aa5b78
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_RDL.tar.zst?download=1
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
|non-incremental/QF_RDL/sal/fischer6-mutex-1.smt2             |    0.034s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-03.smt2 |    0.038s | 21.068MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-2.smt2 |    0.040s | 21.04MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-4.smt2             |    0.057s | 20.848MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking03.smt2 |    0.059s | 21.112MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-2.smt2             |    0.060s | 20.92MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-4.smt2             |    0.073s | 22.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking01.smt2 |    0.074s | 20.368MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-1.smt2 |    0.077s | 20.14MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking04.smt2 |    0.078s | 20.876MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking10.smt2 |    0.080s | 22.208MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking05.smt2 |    0.080s | 21.024MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_700.smt2             |    0.083s | 22.416MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_250.smt2             |    0.086s | 22.152MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-1.smt2             |    0.087s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-7.smt2             |    0.087s | 21.216MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking02.smt2 |    0.090s | 20.888MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-matrix1x1.pddl.smt2 |    0.090s | 20.136MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking09.smt2 |    0.093s | 21.636MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-5.smt2             |    0.093s | 20.768MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-2.smt2             |    0.095s | 20.74MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-5.smt2             |    0.096s | 21.528MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1000.smt2             |    0.097s | 23.396MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking06.smt2 |    0.100s | 21.196MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/check/bignum_rdl1.smt2                |    0.101s | 19.852MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-04.smt2 |    0.102s | 21.1MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-1.smt2             |    0.102s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking08.smt2 |    0.103s | 21.416MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-08.smt2 |    0.104s | 21.764MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-3.smt2             |    0.105s | 20.896MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_700.smt2             |    0.109s | 23.44MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking11.smt2 |    0.110s | 22.084MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-06.smt2 |    0.110s | 21.46MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-3.smt2             |    0.111s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking07.smt2 |    0.112s | 21.316MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_330.smt2             |    0.113s | 22.92MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-2.smt2 |    0.113s | 21.14MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-05.smt2 |    0.113s | 21.52MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-07.smt2 |    0.114s | 21.776MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking13.smt2 |    0.116s | 22.296MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-6.smt2             |    0.121s | 21.76MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-4.smt2             |    0.125s | 21.508MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-09.smt2 |    0.128s | 22.604MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-10.smt2 |    0.129s | 22.416MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking16.smt2 |    0.130s | 22.86MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking14.smt2 |    0.134s | 22.508MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-3.smt2             |    0.134s | 21.268MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/check/bignum_rdl2.smt2                |    0.136s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_850.smt2             |    0.138s | 23.928MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking12.smt2 |    0.139s | 22.244MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking15.smt2 |    0.142s | 22.896MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-5.smt2             |    0.142s | 22.688MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-8.smt2             |    0.143s | 21.184MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-2.smt2             |    0.147s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking22.smt2 |    0.148s | 23.992MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking18.smt2 |    0.151s | 23.216MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking17.smt2 |    0.151s | 23.228MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-7.smt2             |    0.158s | 22.18MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_800.smt2             |    0.159s | 23.748MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-6.smt2             |    0.159s | 20.908MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-3.smt2 |    0.160s | 23.18MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking20.smt2 |    0.161s | 23.564MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking21.smt2 |    0.171s | 23.692MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-8.smt2             |    0.171s | 22.588MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-9.smt2             |    0.179s | 21.7MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_1100.smt2             |    0.180s | 24.256MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/cooking19.smt2 |    0.181s | 23.528MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_800.smt2             |    0.188s | 23.824MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-6.smt2             |    0.190s | 22.768MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1400.smt2             |    0.192s | 24.188MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_800.smt2              |    0.196s | 23.796MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-11.smt2            |    0.210s | 22.28MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-20.smt2 |    0.231s | 24.228MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-12.smt2            |    0.250s | 22.328MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_700.smt2             |    0.259s | 23.688MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_800.smt2             |    0.262s | 23.788MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-10.smt2            |    0.274s | 21.988MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_1000.smt2            |    0.282s | 24.712MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-7.smt2             |    0.290s | 23.592MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_900.smt2             |    0.322s | 24.204MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_1100.smt2            |    0.369s | 24.996MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_1000.smt2            |    0.382s | 24.444MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-8.smt2             |    0.394s | 24.232MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa/skdmxa-3x3-5.smt2              |    0.396s | 34.512MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_550.smt2             |    0.422s | 24.716MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_800.smt2             |    0.437s | 24.176MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-13.smt2            |    0.445s | 22.684MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_1200.smt2            |    0.482s | 24.964MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_1000.smt2             |    0.486s | 24.54MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_950.smt2             |    0.514s | 24.716MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-30.smt2 |    0.582s | 26.864MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-15.smt2            |    0.592s | 23.46MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-9.smt2             |    0.609s | 23.416MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-14.smt2            |    0.613s | 23.164MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_900.smt2              |    0.625s | 24.132MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-5.base.cvc.smt2    |    0.625s | 50.068MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_830.smt2             |    0.674s | 24.464MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-16.smt2            |    0.713s | 23.304MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_900.smt2             |    0.739s | 24.696MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-3.smt2 |    0.766s | 24.516MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_850.smt2             |    0.779s | 24.204MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-40.smt2 |    0.803s | 28.284MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-7.base.cvc.smt2    |    0.879s | 60.204MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_1200.smt2            |    0.911s | 25.512MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-17.smt2            |    0.913s | 24.024MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-6.base.cvc.smt2    |    0.936s | 56.16MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz6_943.smt2              |    0.937s | 24.712MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-10.smt2            |    0.951s | 24.396MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-5.induction.cvc.smt2 |    0.951s | 66.7MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-18.smt2            |    0.980s | 24.504MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1300.smt2             |    0.985s | 24.916MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_1100.smt2            |    1.046s | 25.32MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-11.smt2            |    1.089s | 25.368MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_900.smt2             |    1.161s | 25.084MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-9.smt2             |    1.249s | 25.38MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-19.smt2            |    1.252s | 24.784MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-12.smt2            |    1.279s | 24.908MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_430.smt2             |    1.340s | 25.532MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_1000.smt2            |    1.378s | 25.736MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_1100.smt2            |    1.461s | 25.58MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_1000.smt2            |    1.526s | 25.78MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_750.smt2               |    1.551s | 66.244MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-13.smt2            |    1.593s | 25.916MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_1200.smt2            |    1.624s | 25.996MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer3-mutex-20.smt2            |    1.693s | 25.448MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_1200.smt2            |    1.731s | 26.036MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-4.smt2 |    1.774s | 28.032MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-9.base.cvc.smt2    |    1.841s | 87.66MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_900.smt2             |    1.857s | 24.72MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-6.induction.cvc.smt2 |    2.113s | 84.456MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-8.base.cvc.smt2    |    2.194s | 83.772MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-7.induction.cvc.smt2 |    2.194s | 87.808MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-8.induction.cvc.smt2 |    2.413s | 107.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa/skdmxa-3x3-10.smt2             |    2.454s | 60.436MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_750.smt2               |    2.491s | 65.38MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_1100.smt2            |    2.894s | 26.296MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-11.smt2            |    2.966s | 27.528MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_500.smt2              |    2.990s | 49.448MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_750.smt2               |    2.995s | 65.676MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-10.smt2            |    3.006s | 27.672MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_900.smt2             |    3.034s | 25.824MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-9.induction.cvc.smt2 |    3.046s | 124.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-10.induction.cvc.smt2 |    3.079s | 127.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-11.induction.cvc.smt2 |    3.291s | 152.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-60.smt2 |    3.388s | 49.02MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb09_934.smt2             |    3.437s | 26.252MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-14.smt2            |    3.916s | 27.364MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1200.smt2             |    3.948s | 25.692MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-10.base.cvc.smt2   |    4.103s | 98.308MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-16.smt2            |    4.133s | 27.492MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb02_888.smt2             |    4.206s | 26.388MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-12.induction.cvc.smt2 |    4.277s | 154.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-13.induction.cvc.smt2 |    4.299s | 184.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-14.induction.cvc.smt2 |    4.474s | 184.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_1100.smt2            |    4.572s | 26.924MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_1000.smt2            |    4.791s | 26.608MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-80.smt2 |    4.940s | 44.896MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb07_397.smt2             |    5.329s | 26.5MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-16.induction.cvc.smt2 |    5.629s | 238.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_900.smt2             |    5.878s | 26.792MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-15.smt2            |    6.162s | 28.076MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb10_944.smt2             |    6.206s | 26.664MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb04_1005.smt2            |    6.207s | 27.024MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-12.smt2            |    6.319s | 28.944MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-11.base.cvc.smt2   |    6.448s | 104.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-18.smt2            |    6.477s | 29.924MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-70.smt2 |    6.478s | 43.812MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-15.induction.cvc.smt2 |    6.743s | 223.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_950.smt2             |    6.902s | 26.724MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_930.smt2             |    6.967s | 27.008MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-17.smt2            |    7.276s | 29.296MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-17.induction.cvc.smt2 |    7.675s | 250.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_1100.smt2            |    8.356s | 27.532MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb08_888.smt2             |    8.915s | 27.564MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-18.induction.cvc.smt2 |    9.307s | 275.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-13.base.cvc.smt2   |    9.860s | 117.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-19.induction.cvc.smt2 |   10.380s | 299.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-19.smt2            |   10.713s | 30.56MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tms-2-3-light-90.smt2 |   10.916s | 47.644MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-14.smt2            |   11.233s | 31.156MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb05_887.smt2             |   11.459s | 28.132MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-12.base.cvc.smt2   |   11.564s | 112.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz5_1234.smt2             |   11.641s | 28.172MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-20.induction.cvc.smt2 |   13.523s | 371.0MiB| sat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-13.smt2            |   14.081s | 32.252MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa/skdmxa-3x3-15.smt2             |   14.311s | 98.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer6-mutex-20.smt2            |   16.594s | 32.376MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-14.base.cvc.smt2   |   16.939s | 125.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-15.base.cvc.smt2   |   18.886s | 140.0MiB| unsat | 0 |  |  |
|non-incremental/QF_RDL/skdmxa/skdmxa-3x3-20.smt2             |   20.023s | 125.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_2992.smt2            |   20.028s | 207.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_827.smt2               |   20.030s | 80.46MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-18.base.cvc.smt2   |   20.039s | 193.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_828.smt2               |   20.043s | 81.264MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_950.smt2               |   20.045s | 88.824MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_1000.smt2            |   20.050s | 29.528MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_862.smt2               |   20.052s | 84.72MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb06_1010.smt2            |   20.058s | 29.368MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_2885.smt2            |   20.059s | 204.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-15.smt2            |   20.059s | 34.22MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_2905.smt2            |   20.062s | 211.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-5.smt2 |   20.062s | 46.576MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-6.smt2 |   20.064s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-20.smt2            |   20.064s | 36.972MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_670.smt2              |   20.066s | 71.988MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_2983.smt2            |   20.070s | 202.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_950.smt2               |   20.072s | 91.652MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_2988.smt2            |   20.072s | 215.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv13_3104.smt2            |   20.072s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_887.smt2               |   20.073s | 85.172MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_1059.smt2            |   20.073s | 29.372MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_2972.smt2            |   20.073s | 213.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_950.smt2               |   20.075s | 90.54MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_919.smt2               |   20.076s | 86.6MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-6.smt2 |   20.076s | 56.152MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-depth-7.smt2 |   20.077s | 89.08MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-19.smt2            |   20.077s | 35.868MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-17.base.cvc.smt2   |   20.077s | 191.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_890.smt2               |   20.078s | 88.692MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb03_1005.smt2            |   20.078s | 28.988MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-5.smt2 |   20.078s | 80.044MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/orb01_1000.smt2            |   20.080s | 28.972MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_600.smt2              |   20.080s | 66.624MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-width-4.smt2 |   20.080s | 46.156MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-17.smt2            |   20.080s | 36.076MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_667.smt2              |   20.081s | 71.876MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-18.smt2            |   20.081s | 36.696MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn2_910.smt2               |   20.082s | 88.1MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_700.smt2              |   20.082s | 72.948MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_894.smt2               |   20.083s | 86.796MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_850.smt2               |   20.085s | 82.608MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_2900.smt2            |   20.085s | 209.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_3050.smt2            |   20.086s | 223.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn3_860.smt2               |   20.087s | 85.476MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn1_950.smt2               |   20.087s | 90.448MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv13_3150.smt2            |   20.087s | 217.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_3004.smt2            |   20.088s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_969.smt2               |   20.088s | 89.644MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_2900.smt2            |   20.088s | 208.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/SMT-Temporal-Planning-Benchmarks/tempo-matrix2x2.pddl.smt2 |   20.088s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-20.base.cvc.smt2   |   20.089s | 224.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv11_3050.smt2            |   20.094s | 203.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_2895.smt2            |   20.094s | 204.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-16.base.cvc.smt2   |   20.095s | 177.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv13_3000.smt2            |   20.096s | 214.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_3000.smt2            |   20.100s | 207.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv14_2800.smt2            |   20.100s | 202.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv12_2990.smt2            |   20.101s | 220.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/swv13_3200.smt2            |   20.103s | 216.0MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_800.smt2              |   20.116s | 75.632MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/sal/fischer9-mutex-16.smt2            |   20.117s | 35.616MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/abz7_691.smt2              |   20.120s | 73.204MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_850.smt2               |   20.120s | 77.968MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/scheduling/yn4_1000.smt2              |   20.122s | 93.22MiB| timeout | 0 |  |  |
|non-incremental/QF_RDL/skdmxa2/skdmxa-3x3-19.base.cvc.smt2   |   20.135s | 228.0MiB| timeout | 0 |  |  |
