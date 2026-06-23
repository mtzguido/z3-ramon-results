# .

* SAT 9
* UNSAT 34
* TIMEOUT 32
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_AUFBV.tar.zst?download=1 | Source list: benchmarks-qf.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_AUFBV.tar.zst-d
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2081918cea27e604b9077a6c36acb2ac28aa5b78
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_AUFBV.tar.zst?download=1
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
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add1.short.smt2 |    0.025s | 19.928MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2/gzip/250_gzip.smt2  |    0.033s | 21.356MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner22.short.smt2 |    0.033s | 22.196MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.group_red1.short.smt2 |    0.035s | 28.704MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div10.short.smt2 |    0.037s | 19.92MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div1.short.smt2 |    0.038s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init1.short.smt2 |    0.040s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init2.short.smt2 |    0.040s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner12.short.smt2 |    0.044s | 21.6MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init.short.smt2 |    0.046s | 20.376MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner23.short.smt2 |    0.047s | 28.34MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div14.short.smt2 |    0.049s | 21.26MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner13.short.smt2 |    0.051s | 28.3MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner4.short.smt2 |    0.054s | 28.968MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner3.short.smt2 |    0.058s | 22.148MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2/gzip/272_gzip.smt2  |    0.064s | 22.912MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div12.short.smt2 |    0.067s | 22.528MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2-partial-undef/gzip/322_gzip.smt2 |    0.076s | 22.936MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub2.short.smt2 |    0.081s | 33.22MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub1.short.smt2 |    0.084s | 33.18MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add4.short.smt2 |    0.086s | 30.896MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub3.short.smt2 |    0.086s | 33.192MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal.smt2 |    0.090s | 24.14MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add2.short.smt2 |    0.090s | 29.94MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux2.short.smt2 |    0.097s | 32.372MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal.smt2 |    0.106s | 25.548MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2-partial-undef/gzip/332_gzip.smt2 |    0.108s | 22.952MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux3.short.smt2 |    0.109s | 32.364MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux4.short.smt2 |    0.118s | 32.376MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash5.short.smt2 |    0.164s | 63.224MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash4.short.smt2 |    0.175s | 63.204MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash3.short.smt2 |    0.184s | 63.224MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add3.short.smt2 |    0.190s | 45.42MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2 |    0.327s | 44.796MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux1.short.smt2 |    0.394s | 93.612MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux11.short.smt2 |    0.396s | 93.856MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux12.short.smt2 |    0.404s | 93.716MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2 |    0.620s | 46.532MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2 |    0.817s | 73.18MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2/ph7/708_ph7.smt2    |    1.441s | 131.0MiB| sat | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2-partial-undef/gcc/204_gcc.smt2 |    4.367s | 34.96MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/ecc/com.galois.ecc.P384ECC64.verifySignature.short.smt2 |    4.406s | 69.112MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2 |    8.894s | 131.0MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2-partial-undef/sqlite3/891_sqlite3.smt2 |   20.017s | 71.52MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2 |   20.017s | 70.028MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2 |   20.018s | 86.864MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAY_QF_AUFBV_NONINCR.smt2 |   20.022s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2 |   20.023s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2 |   20.023s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2 |   20.023s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2 |   20.026s | 101.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2/sqlite3/906_sqlite3.smt2 |   20.028s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCY_QF_AUFBV_NONINCR.smt2 |   20.033s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2/gcc/033_gcc.smt2    |   20.035s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2 |   20.036s | 161.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2 |   20.038s | 220.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2 |   20.039s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2 |   20.040s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2 |   20.049s | 201.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2 |   20.050s | 280.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2 |   20.050s | 220.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2    |   20.056s | 388.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal_no_rewrite.smt2 |   20.056s | 523.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |   20.057s | 532.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |   20.059s | 528.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2 |   20.114s | 994.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |   20.129s | 1118.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2 |   20.148s | 1162.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2 |   20.177s | 1705.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2 |   20.240s | 1997.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2 |   20.259s | 2524.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2 |   20.303s | 3622.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2 |   20.317s | 3595.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2 |   20.438s | 4684.0MiB| timeout | 0 |  |  |
|non-incremental/QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2 |   20.647s | 6917.0MiB| timeout | 0 |  |  |
