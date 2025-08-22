# .

* SAT 9
* UNSAT 31
* TIMEOUT 35
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfaufbv-threads-4-cube-shareconflicts
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 47ce383ab5ffb3930ebc99a3d81d5b4e7b62f521
Z3 branch: 
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.never_cube=false smt_parallel.frugal_cube_only=false smt_parallel.share_conflicts=true smt_parallel.share_units=false"
Z3 inputs: inputs/QF_AUFBV
Z3 commit message: Merge branch 'Z3Prover:master' into parallel-solving

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add1.short.smt2 |    0.085s | 88.708MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2/gzip/250_gzip.smt2                  |    0.108s | 92.444MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner13.short.smt2  |    0.108s | 98.076MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner23.short.smt2  |    0.120s | 111.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner12.short.smt2  |    0.129s | 99.0MiB| sat | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal.smt2 |    0.133s | 90.86MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div10.short.smt2   |    0.138s | 122.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner4.short.smt2  |    0.139s | 112.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init1.short.smt2 |    0.142s | 120.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init2.short.smt2 |    0.144s | 121.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init.short.smt2 |    0.145s | 121.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal.smt2 |    0.147s | 91.952MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner22.short.smt2  |    0.152s | 115.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add4.short.smt2 |    0.154s | 127.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner3.short.smt2  |    0.158s | 118.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add2.short.smt2 |    0.161s | 118.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add3.short.smt2 |    0.174s | 137.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2/gzip/272_gzip.smt2                  |    0.215s | 97.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/322_gzip.smt2    |    0.281s | 97.604MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash5.short.smt2   |    0.311s | 177.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash3.short.smt2   |    0.318s | 184.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash4.short.smt2   |    0.325s | 182.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/332_gzip.smt2    |    0.355s | 98.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux1.short.smt2 |    0.405s | 249.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux11.short.smt2 |    0.409s | 249.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux12.short.smt2 |    0.439s | 249.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div12.short.smt2   |    0.510s | 134.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div14.short.smt2   |    0.549s | 135.0MiB| unsat | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2               |    0.658s | 135.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux2.short.smt2 |    0.696s | 178.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux4.short.smt2 |    0.728s | 178.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux3.short.smt2 |    0.732s | 178.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2/ph7/708_ph7.smt2                    |    2.131s | 565.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.group_red1.short.smt2  |    2.378s | 159.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal_no_rewrite.smt2 |    3.481s | 230.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div1.short.smt2    |    4.364s | 138.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2-partial-undef/sqlite3/891_sqlite3.smt2 |    6.753s | 262.0MiB| sat | 0 |  |  |
|QF_AUFBV/20210301-Alive2-partial-undef/gcc/204_gcc.smt2      |   13.207s | 152.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.verifySignature.short.smt2 |   17.325s | 259.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub2.short.smt2 |   20.418s | 223.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub3.short.smt2 |   30.033s | 235.0MiB| timeout | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub1.short.smt2 |   30.043s | 287.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20210301-Alive2/sqlite3/906_sqlite3.smt2            |   30.057s | 424.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2               |   30.059s | 309.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2 |   30.069s | 314.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2 |   30.076s | 380.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20210301-Alive2/gcc/033_gcc.smt2                    |   30.080s | 685.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2 |   30.093s | 619.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAY_QF_AUFBV_NONINCR.smt2 |   30.093s | 613.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2 |   30.096s | 690.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2 |   30.106s | 768.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2 |   30.109s | 668.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2 |   30.113s | 571.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCY_QF_AUFBV_NONINCR.smt2 |   30.116s | 684.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2 |   30.123s | 559.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2 |   30.126s | 413.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2 |   30.135s | 771.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2 |   30.157s | 621.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2            |   30.168s | 1336.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2         |   30.200s | 1828.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2         |   30.221s | 1866.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2         |   30.222s | 1950.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2         |   30.233s | 1882.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2         |   30.331s | 2963.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |   30.356s | 2835.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                    |   30.369s | 3131.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |   30.391s | 3322.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |   30.407s | 3435.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2 |   30.567s | 4973.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2 |   30.636s | 4611.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2 |   30.649s | 4977.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2               |   30.746s | 7236.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2               |   30.852s | 7707.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2 |   31.022s | 9102.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2 |   31.061s | 9571.0MiB| timeout | 0 |  |  |
