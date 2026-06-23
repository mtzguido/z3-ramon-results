# .

* SAT 55
* UNSAT 2
* TIMEOUT 17
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_ABVFPLRA.tar.zst?download=1 | Source list: benchmarks-qf.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_ABVFPLRA.tar.zs
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2081918cea27e604b9077a6c36acb2ac28aa5b78
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_ABVFPLRA.tar.zst?download=1
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
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_323.smt2 |    0.021s | 19.612MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter_iir_true-unreach-call.c_27.smt2 |    0.021s | 19.864MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0680a_true-unreach-call.c_1.smt2 |    0.022s | 19.612MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_8.smt2 |    0.022s | 19.86MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0876_true-unreach-call.c_5.smt2 |    0.023s | 19.556MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0330a_true-unreach-call.c_2.smt2 |    0.023s | 19.972MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_0.smt2 |    0.023s | 19.86MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_9.smt2 |    0.025s | 20.388MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0662a_true-unreach-call.c_1.smt2 |    0.027s | 19.592MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0330a_true-unreach-call.c_1.smt2 |    0.028s | 20.584MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_1.smt2 |    0.028s | 19.636MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_5.smt2 |    0.028s | 20.12MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0550b_true-unreach-call.c_2.smt2 |    0.029s | 20.648MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_335.smt2 |    0.029s | 20.424MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_182.smt2 |    0.029s | 19.876MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_45.smt2 |    0.029s | 19.564MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter_iir_true-unreach-call.c_34.smt2 |    0.029s | 19.768MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_184.smt2 |    0.029s | 19.852MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0685a_true-unreach-call.c_9.smt2 |    0.030s | 19.872MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0873a_true-unreach-call.c_2.smt2 |    0.030s | 19.6MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_334.smt2 |    0.030s | 20.052MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_320.smt2 |    0.030s | 19.552MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_7.smt2 |    0.031s | 20.1MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_6.smt2 |    0.031s | 20.104MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_72.smt2 |    0.031s | 19.964MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0883_true-unreach-call.c_1.smt2 |    0.032s | 19.508MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_poly2_false-unreach-call.c_0.smt2 |    0.032s | 20.58MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_3.smt2 |    0.032s | 20.144MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_324.smt2 |    0.032s | 19.64MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_56.smt2 |    0.032s | 20.072MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0550b_true-unreach-call.c_5.smt2 |    0.033s | 20.36MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0874_true-unreach-call.c_4.smt2 |    0.034s | 19.844MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_336.smt2 |    0.039s | 19.904MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_0.smt2 |    0.039s | 19.772MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_alt_true-unreach-call.c_8.smt2 |    0.041s | 20.12MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_2.smt2 |    0.042s | 19.604MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0660b_true-unreach-call.c_1.smt2 |    0.042s | 19.64MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0550b_true-unreach-call.c_1.smt2 |    0.042s | 20.244MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0883_true-unreach-call.c_2.smt2 |    0.043s | 19.596MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0870b_true-unreach-call.c_4.smt2 |    0.043s | 19.804MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_10.smt2 |    0.043s | 19.852MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_185.smt2 |    0.043s | 19.624MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_10.smt2 |    0.044s | 20.14MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0872a_true-unreach-call.c_8.smt2 |    0.045s | 20.128MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/sin_interpolated_index_false-unreach-call.c_0.smt2 |    0.047s | 19.864MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_alt_true-unreach-call.c_39.smt2 |    0.048s | 20.12MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_3.smt2 |    0.048s | 19.648MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_186.smt2 |    0.048s | 19.652MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_73.smt2 |    0.049s | 20.144MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/sin_interpolated_bigrange_loose_true-unreach-call.c_0.smt2 |    0.049s | 20.116MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_332.smt2 |    0.049s | 20.072MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0620b_true-unreach-call.c_7.smt2 |    0.056s | 22.928MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0240b_true-unreach-call.c_0.smt2 |    0.069s | 24.452MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0220b_true-unreach-call.c_0.smt2 |    0.070s | 24.456MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/inv_Newton_false-unreach-call.c.p+cfa-reducer.c_AllErrorsAtOnce_Iteration4_TraceCheck_0.smt2 |    8.133s | 98.0MiB| unsat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/interpolation_true-unreach-call.c.p+cfa-reducer.c_1.smt2 |   11.981s | 108.0MiB| sat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/inv_Newton_false-unreach-call.c_AllErrorsAtOnce_Iteration2_TraceCheck_0.smt2 |   18.200s | 101.0MiB| unsat | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/interpolation2_true-unreach-call_true-termination.c_0.smt2 |   20.024s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/sin_interpolated_index_false-unreach-call_true-termination.c_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.027s | 149.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/sin_interpolated_index_true-unreach-call_true-termination.c_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.028s | 149.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/interpolation_true-unreach-call.c.p+cfa-reducer.c_0.smt2 |   20.028s | 116.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_poly2_false-unreach-call.c_AllErrorsAtOnce_Iteration1_TraceCheck_0.smt2 |   20.032s | 241.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter2_alt_true-unreach-call.c_AllErrorsAtOnce_Iteration2_TraceCheck_0.smt2 |   20.036s | 77.924MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/interpolation2_true-unreach-call.c.v+cfa-reducer.c_0.smt2 |   20.048s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_327.smt2 |   20.054s | 421.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_330.smt2 |   20.059s | 418.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/sin_interpolated_smallrange_true-unreach-call.c_AllErrorsAtOnce_Iteration2_TraceCheck_0.smt2 |   20.060s | 233.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_331.smt2 |   20.067s | 418.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_71.smt2 |   20.069s | 417.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_70.smt2 |   20.069s | 418.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/filter_iir_true-unreach-call.c_0.smt2 |   20.070s | 482.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_329.smt2 |   20.071s | 420.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_321.smt2 |   20.073s | 417.0MiB| timeout | 0 |  |  |
|non-incremental/QF_ABVFPLRA/20170501-Heizmann-UltimateAutomizer/filter2_iterated_true-unreach-call.c_322.smt2 |   20.081s | 417.0MiB| timeout | 0 |  |  |
