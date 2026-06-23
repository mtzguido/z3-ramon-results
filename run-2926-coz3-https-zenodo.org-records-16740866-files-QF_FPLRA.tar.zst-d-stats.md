# .

* SAT 31
* UNSAT 2
* TIMEOUT 26
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_FPLRA.tar.zst?download=1 | Source list: benchmarks-qf.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_FPLRA.tar.zst-d
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2081918cea27e604b9077a6c36acb2ac28aa5b78
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_FPLRA.tar.zst?download=1
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
|non-incremental/QF_FPLRA/schanda/spark/zeros_consistent_1.smt2 |    0.022s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/Double_div_bad_false-unreach-call.i_1.smt2 |    0.044s | 20.452MiB| unsat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c_3.smt2 |    1.329s | 331.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/Double_div_bad_false-unreach-call.i_0.smt2 |    1.982s | 161.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c.p+cfa-reducer.c_4.smt2 |    2.179s | 265.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0520_true-unreach-call.c_0.smt2 |    2.929s | 197.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0310_true-unreach-call.c_3.smt2 |    3.828s | 173.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0250b_true-unreach-call.c_4.smt2 |    3.979s | 295.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0320_true-unreach-call.c_7.smt2 |    4.412s | 368.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c.p+cfa-reducer.c_2.smt2 |    5.183s | 392.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0330a_true-unreach-call.c_6.smt2 |    5.241s | 487.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Newton_pseudoconstant_true-unreach-call.c_1.smt2 |    5.700s | 419.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0320_true-unreach-call.c_5.smt2 |    5.918s | 486.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0873a_true-unreach-call.c_3.smt2 |    6.192s | 360.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0470_true-unreach-call.c_12.smt2 |    6.793s | 390.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c.p+cfa-reducer.c_1.smt2 |    6.989s | 392.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0870b.c_1.smt2 |    7.275s | 209.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0490a_true-unreach-call.c_0.smt2 |    8.497s | 392.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_2.smt2 |    8.655s | 683.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0490a_true-unreach-call.c_10.smt2 |    8.694s | 444.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0330b_true-unreach-call.c_10.smt2 |    8.700s | 490.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0460_true-unreach-call.c_2.smt2 |    8.715s | 485.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0490a_true-unreach-call.c_9.smt2 |    8.911s | 390.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0260_true-unreach-call.c_1.smt2 |    9.015s | 676.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0870b_true-unreach-call.c_3.smt2 |    9.463s | 230.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/sqrt_Householder_constant_true-unreach-call.c.p+cfa-reducer.c_3.smt2 |    9.871s | 766.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20170501-Heizmann-UltimateAutomizer/filter2_reinit_true-unreach-call.c_7.smt2 |   10.785s | 170.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20170501-Heizmann-UltimateAutomizer/image_filter_true-unreach-call.c_2.smt2 |   11.082s | 194.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0320_true-unreach-call.c_6.smt2 |   13.013s | 185.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/Rump_double_true-unreach-call_true-termination.c_0.smt2 |   15.411s | 2580.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/cos_polynomial_true-unreach-call_true-termination.c_0.smt2 |   15.993s | 522.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0240a_true-unreach-call.c_6.smt2 |   17.197s | 387.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_19.smt2 |   18.289s | 1342.0MiB| sat | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0874_true-unreach-call.c_3.smt2 |   20.063s | 221.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0550b_true-unreach-call.c_9.smt2 |   20.074s | 420.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_11.smt2 |   20.077s | 410.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20230321-UltimateAutomizerSvcomp2023/cos_polynomial.c_0.smt2 |   20.080s | 457.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20170501-Heizmann-UltimateAutomizer/cos_polynomial_true-unreach-call.c_9.smt2 |   20.106s | 508.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0490a_true-unreach-call.c_2.smt2 |   20.109s | 488.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0260_true-unreach-call.c_3.smt2 |   20.147s | 1077.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_21.smt2 |   20.182s | 1139.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0270a_true-unreach-call.c_4.smt2 |   20.190s | 1084.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0460_true-unreach-call.c_3.smt2 |   20.195s | 1613.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0250a.c_1.smt2 |   20.199s | 1079.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propLnExp0.smt2       |   20.206s | 1904.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propLnExp1.smt2       |   20.207s | 1903.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/lnLaw.smt2            |   20.209s | 1900.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propLnExp3.smt2       |   20.213s | 1898.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/expLaw.smt2           |   20.215s | 1914.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propExpLn2.smt2       |   20.228s | 2046.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0490a_true-unreach-call.c_3.smt2 |   20.232s | 1611.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propExpLn3.smt2       |   20.235s | 1904.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/expInUnit.smt2        |   20.254s | 1900.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0490a.c_4.smt2 |   20.254s | 1626.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propLnExp2.smt2       |   20.255s | 1888.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propExpLn0.smt2       |   20.383s | 3682.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/propExpLn1.smt2       |   20.443s | 3696.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/maxReward.smt2        |   20.894s | 9513.0MiB| timeout | 0 |  |  |
|non-incremental/QF_FPLRA/2019-Gudemann/expInUnit2.smt2       |   21.061s | 10.443GiB| timeout | 0 |  |  |
