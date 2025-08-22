# .

* SAT 9
* UNSAT 34
* TIMEOUT 32
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfaufbv-threads-4-none-unbounded
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 47ce383ab5ffb3930ebc99a3d81d5b4e7b62f521
Z3 branch: 
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.never_cube=true smt_parallel.share_conflicts=false smt_parallel.share_units=false smt.threads.max_conflicts=4294967295"
Z3 inputs: inputs/QF_AUFBV
Z3 commit message: Merge branch 'Z3Prover:master' into parallel-solving

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|QF_AUFBV/20210301-Alive2/gzip/250_gzip.smt2                  |    0.081s | 92.484MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add1.short.smt2 |    0.084s | 88.856MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner13.short.smt2  |    0.088s | 98.252MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner12.short.smt2  |    0.120s | 100.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add2.short.smt2 |    0.132s | 119.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal.smt2 |    0.133s | 91.44MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div10.short.smt2   |    0.133s | 122.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner4.short.smt2  |    0.134s | 112.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner23.short.smt2  |    0.136s | 111.0MiB| sat | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal.smt2 |    0.139s | 90.908MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/322_gzip.smt2    |    0.139s | 97.592MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner22.short.smt2  |    0.139s | 115.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init.short.smt2 |    0.142s | 121.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init1.short.smt2 |    0.143s | 121.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init2.short.smt2 |    0.145s | 120.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add4.short.smt2 |    0.155s | 126.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner3.short.smt2  |    0.156s | 118.0MiB| sat | 0 |  |  |
|QF_AUFBV/20210301-Alive2/gzip/272_gzip.smt2                  |    0.164s | 97.112MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add3.short.smt2 |    0.179s | 137.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash5.short.smt2   |    0.297s | 177.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash3.short.smt2   |    0.317s | 184.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash4.short.smt2   |    0.326s | 182.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/332_gzip.smt2    |    0.368s | 98.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux12.short.smt2 |    0.402s | 249.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux11.short.smt2 |    0.423s | 249.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux1.short.smt2 |    0.426s | 249.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div12.short.smt2   |    0.475s | 135.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div14.short.smt2   |    0.521s | 135.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux4.short.smt2 |    0.713s | 178.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux2.short.smt2 |    0.714s | 178.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux3.short.smt2 |    0.730s | 178.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div1.short.smt2    |    0.823s | 139.0MiB| unsat | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2               |    1.039s | 136.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.group_red1.short.smt2  |    1.564s | 159.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2/ph7/708_ph7.smt2                    |    2.221s | 562.0MiB| sat | 0 |  |  |
|QF_AUFBV/20210301-Alive2-partial-undef/gcc/204_gcc.smt2      |    2.898s | 142.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal_no_rewrite.smt2 |    5.139s | 230.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2-partial-undef/sqlite3/891_sqlite3.smt2 |    6.702s | 263.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.verifySignature.short.smt2 |   10.081s | 272.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub2.short.smt2 |   14.551s | 468.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub1.short.smt2 |   16.262s | 592.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub3.short.smt2 |   16.957s | 529.0MiB| unsat | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2 |   22.522s | 563.0MiB| unsat | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2               |   30.048s | 330.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20210301-Alive2/sqlite3/906_sqlite3.smt2            |   30.056s | 371.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2 |   30.075s | 386.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2 |   30.088s | 422.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2 |   30.091s | 615.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2 |   30.092s | 630.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20210301-Alive2/gcc/033_gcc.smt2                    |   30.093s | 578.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2 |   30.098s | 686.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2 |   30.102s | 770.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2 |   30.107s | 665.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCY_QF_AUFBV_NONINCR.smt2 |   30.108s | 684.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2 |   30.111s | 326.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAY_QF_AUFBV_NONINCR.smt2 |   30.115s | 620.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2 |   30.123s | 562.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2 |   30.132s | 777.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2            |   30.158s | 1371.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2         |   30.205s | 1828.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2         |   30.220s | 1865.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2         |   30.222s | 1950.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2         |   30.233s | 1863.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                    |   30.338s | 3126.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2         |   30.371s | 2963.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |   30.375s | 3193.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |   30.394s | 2854.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |   30.432s | 3334.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2 |   30.534s | 4928.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2 |   30.562s | 4880.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2 |   30.623s | 4634.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2               |   30.768s | 7236.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2               |   30.827s | 7410.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2 |   30.879s | 8591.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2 |   30.928s | 9541.0MiB| timeout | 0 |  |  |
