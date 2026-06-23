# .

* SAT 5
* UNSAT 12
* TIMEOUT 0
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_AUFNIA.tar.zst?download=1 | Source list: benchmarks-qf.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_AUFNIA.tar.zst-
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2081918cea27e604b9077a6c36acb2ac28aa5b78
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_AUFNIA.tar.zst?download=1
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
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_clnt.blast.03_false-unreach-call.i.cil.c_71.smt2 |    0.046s | 22.664MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.07_false-unreach-call.i.cil.c_0.smt2 |    0.048s | 23.12MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.10_true-unreach-call.i.cil.c_0.smt2 |    0.060s | 24.096MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.08_true-unreach-call.i.cil.c_1140.smt2 |    0.065s | 25.416MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_clnt.blast.02_false-unreach-call.i.cil.c_71.smt2 |    0.066s | 22.408MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_clnt.blast.01_false-unreach-call.i.cil.c_57.smt2 |    0.068s | 23.144MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.15_true-unreach-call.i.cil.c_1173.smt2 |    0.079s | 26.584MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.16_true-unreach-call.i.cil.c_2036.smt2 |    0.093s | 27.4MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.12_true-unreach-call.i.cil.c_0.smt2 |    0.097s | 26.816MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.14_true-unreach-call.i.cil.c_959.smt2 |    0.102s | 26.628MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.06_true-unreach-call.i.cil.c_2803.smt2 |    0.102s | 28.512MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.06_true-unreach-call.i.cil.c.smt2 |    0.114s | 29.828MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.01_false-unreach-call.i.cil.c_0.smt2 |    0.444s | 27.728MiB| sat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.02_false-unreach-call.i.cil.c_0.smt2 |    0.467s | 26.76MiB| sat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.04_false-unreach-call.i.cil.c_0.smt2 |    0.470s | 26.504MiB| sat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.11_false-unreach-call.i.cil.c_0.smt2 |    1.669s | 35.128MiB| sat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_clnt.blast.01_false-unreach-call.i.cil.c_0.smt2 |   14.622s | 51.768MiB| sat | 0 |  |  |
