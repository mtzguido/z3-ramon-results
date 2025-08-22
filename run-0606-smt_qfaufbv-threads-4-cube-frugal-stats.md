# .

* SAT 9
* UNSAT 30
* TIMEOUT 36
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfaufbv-threads-4-cube-frugal
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 47ce383ab5ffb3930ebc99a3d81d5b4e7b62f521
Z3 branch: 
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.never_cube=false smt_parallel.frugal_cube_only=true smt_parallel.share_conflicts=false smt_parallel.share_units=false"
Z3 inputs: inputs/QF_AUFBV
Z3 commit message: Merge branch 'Z3Prover:master' into parallel-solving

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|QF_AUFBV/20210301-Alive2/gzip/250_gzip.smt2                  |    0.084s | 92.676MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add1.short.smt2 |    0.084s | 88.608MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner13.short.smt2  |    0.084s | 97.92MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner12.short.smt2  |    0.103s | 100.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner4.short.smt2  |    0.120s | 112.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner23.short.smt2  |    0.124s | 111.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div10.short.smt2   |    0.141s | 122.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner22.short.smt2  |    0.141s | 115.0MiB| sat | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal.smt2 |    0.144s | 91.696MiB| unsat | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal.smt2 |    0.145s | 91.416MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init2.short.smt2 |    0.145s | 121.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add4.short.smt2 |    0.154s | 125.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner3.short.smt2  |    0.155s | 118.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init1.short.smt2 |    0.156s | 121.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add2.short.smt2 |    0.157s | 118.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init.short.smt2 |    0.162s | 121.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add3.short.smt2 |    0.176s | 136.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2/gzip/272_gzip.smt2                  |    0.183s | 97.352MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/322_gzip.smt2    |    0.242s | 98.136MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/332_gzip.smt2    |    0.306s | 98.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash5.short.smt2   |    0.307s | 177.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash3.short.smt2   |    0.317s | 184.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash4.short.smt2   |    0.324s | 182.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux1.short.smt2 |    0.404s | 249.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux11.short.smt2 |    0.411s | 249.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux12.short.smt2 |    0.429s | 249.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div12.short.smt2   |    0.510s | 135.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div14.short.smt2   |    0.525s | 135.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux2.short.smt2 |    0.705s | 178.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux4.short.smt2 |    0.721s | 178.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux3.short.smt2 |    0.721s | 178.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div1.short.smt2    |    0.833s | 137.0MiB| unsat | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2               |    0.914s | 136.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.group_red1.short.smt2  |    1.841s | 158.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2/ph7/708_ph7.smt2                    |    2.310s | 563.0MiB| sat | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal_no_rewrite.smt2 |    3.201s | 230.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2-partial-undef/sqlite3/891_sqlite3.smt2 |    7.590s | 266.0MiB| sat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.verifySignature.short.smt2 |   10.799s | 253.0MiB| unsat | 0 |  |  |
|QF_AUFBV/20210301-Alive2-partial-undef/gcc/204_gcc.smt2      |   15.836s | 151.0MiB| unsat | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub1.short.smt2 |   30.039s | 281.0MiB| timeout | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub2.short.smt2 |   30.050s | 221.0MiB| timeout | 0 |  |  |
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub3.short.smt2 |   30.063s | 282.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20210301-Alive2/sqlite3/906_sqlite3.smt2            |   30.068s | 398.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2               |   30.069s | 304.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20210301-Alive2/gcc/033_gcc.smt2                    |   30.071s | 577.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2 |   30.082s | 381.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAY_QF_AUFBV_NONINCR.smt2 |   30.090s | 621.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2 |   30.094s | 406.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2 |   30.097s | 696.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2 |   30.098s | 621.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2 |   30.101s | 763.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2 |   30.104s | 314.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2 |   30.109s | 661.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2 |   30.117s | 622.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCY_QF_AUFBV_NONINCR.smt2 |   30.121s | 683.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2 |   30.124s | 565.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2 |   30.129s | 561.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2 |   30.144s | 776.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2            |   30.168s | 1341.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2         |   30.206s | 1843.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2         |   30.209s | 1950.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2         |   30.210s | 1829.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2         |   30.223s | 1880.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |   30.291s | 2887.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2         |   30.328s | 2963.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |   30.368s | 3389.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |   30.370s | 3470.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                    |   30.387s | 3158.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2 |   30.535s | 4944.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2 |   30.570s | 4589.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2 |   30.635s | 5001.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2               |   30.718s | 7236.0MiB| timeout | 0 |  |  |
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2               |   30.849s | 7561.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2 |   30.968s | 9115.0MiB| timeout | 0 |  |  |
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2 |   31.199s | 11.189GiB| timeout | 0 |  |  |
