# .

* SAT 0
* UNSAT 2
* TIMEOUT 1
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_NIRA.tar.zst?download=1 | Source list: benchmarks-qf.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_NIRA.tar.zst-do
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2081918cea27e604b9077a6c36acb2ac28aa5b78
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_NIRA.tar.zst?download=1
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
|non-incremental/QF_NIRA/UltimateAutomizer/test_union_cast-1_true-unreach-call.i.smt2 |    0.025s | 20.576MiB| unsat | 0 |  |  |
|non-incremental/QF_NIRA/LCTES/miniflight.smt2                |    3.088s | 122.0MiB| unsat | 0 |  |  |
|non-incremental/QF_NIRA/LCTES/miniflight.nosummaries.smt2    |   20.065s | 454.0MiB| timeout | 0 |  |  |
