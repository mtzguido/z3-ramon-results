Comparing data and data


# SUMMARY
- LHS tests = 75
- RHS tests = 75
- LHS success = 75  (100.0%)
- RHS success = 75  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfaufbv-threads-4-cube-frugal-shareconflicts
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 47ce383ab5ffb3930ebc99a3d81d5b4e7b62f521
Z3 branch: 
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.never_cube=false smt_parallel.frugal_cube_only=true smt_parallel.share_conflicts=true smt_parallel.share_units=false"
Z3 inputs: inputs/QF_AUFBV
Z3 commit message: Merge branch 'Z3Prover:master' into parallel-solving

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfaufbv-threads-4-cube-frugal-shareconflicts
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 47ce383ab5ffb3930ebc99a3d81d5b4e7b62f521
Z3 branch: 
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.never_cube=false smt_parallel.frugal_cube_only=true smt_parallel.share_conflicts=true smt_parallel.share_units=false"
Z3 inputs: inputs/QF_AUFBV
Z3 commit message: Merge branch 'Z3Prover:master' into parallel-solving

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.351s  |  30.351s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.831s  |  30.831s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.763s  |  30.763s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.200s  |  30.200s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.208s  |  30.208s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.538s  |  30.538s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.540s  |  30.540s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.632s  |  30.632s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.112s  |  30.112s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.351s  |  30.351s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.831s  |  30.831s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.763s  |  30.763s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.200s  |  30.200s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.208s  |  30.208s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.538s  |  30.538s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.540s  |  30.540s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.632s  |  30.632s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.112s  |  30.112s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.351s  |  30.351s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.831s  |  30.831s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.763s  |  30.763s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.200s  |  30.200s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.208s  |  30.208s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.538s  |  30.538s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.540s  |  30.540s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.632s  |  30.632s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.112s  |  30.112s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.351s  |  30.351s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.831s  |  30.831s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.763s  |  30.763s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.200s  |  30.200s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.208s  |  30.208s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.538s  |  30.538s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.540s  |  30.540s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.632s  |  30.632s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.112s  |  30.112s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  31.096s |10.188GiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.997s |9119.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.831s |7449.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.763s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.632s |4596.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.540s |5025.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.538s |4877.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.403s |3351.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.397s |3428.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.367s |3127.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.351s |2963.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.308s |2853.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.222s |1880.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.210s |1843.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.208s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.200s |1830.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.171s |1329.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                           |  30.137s |564.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                            |  30.131s |620.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.129s |771.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  31.096s |10.188GiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.997s |9119.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.831s |7449.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.763s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.632s |4596.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.540s |5025.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.538s |4877.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.403s |3351.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.397s |3428.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.367s |3127.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.351s |2963.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.308s |2853.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.222s |1880.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.210s |1843.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.208s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.200s |1830.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.171s |1329.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                           |  30.137s |564.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                            |  30.131s |620.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.129s |771.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7449.0MiB|7449.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |304.0MiB|304.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |134.0MiB|134.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1830.0MiB|1830.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1880.0MiB|1880.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1843.0MiB|1843.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |313.0MiB|313.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |379.0MiB|379.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |619.0MiB|619.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |564.0MiB|564.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |405.0MiB|405.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4877.0MiB|4877.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |5025.0MiB|5025.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |566.0MiB|566.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4596.0MiB|4596.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |620.0MiB|620.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |662.0MiB|662.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7449.0MiB|7449.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |304.0MiB|304.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |134.0MiB|134.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1830.0MiB|1830.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1880.0MiB|1880.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1843.0MiB|1843.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |313.0MiB|313.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |379.0MiB|379.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |619.0MiB|619.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |564.0MiB|564.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |405.0MiB|405.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4877.0MiB|4877.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |5025.0MiB|5025.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |566.0MiB|566.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4596.0MiB|4596.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |620.0MiB|620.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |662.0MiB|662.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7449.0MiB|7449.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |304.0MiB|304.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |134.0MiB|134.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1830.0MiB|1830.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1880.0MiB|1880.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1843.0MiB|1843.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |313.0MiB|313.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |379.0MiB|379.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |619.0MiB|619.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |564.0MiB|564.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |405.0MiB|405.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4877.0MiB|4877.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |5025.0MiB|5025.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |566.0MiB|566.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4596.0MiB|4596.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |620.0MiB|620.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |662.0MiB|662.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7449.0MiB|7449.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |304.0MiB|304.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |134.0MiB|134.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1830.0MiB|1830.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1880.0MiB|1880.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1843.0MiB|1843.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |313.0MiB|313.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |379.0MiB|379.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |619.0MiB|619.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |564.0MiB|564.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |405.0MiB|405.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4877.0MiB|4877.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |5025.0MiB|5025.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |566.0MiB|566.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4596.0MiB|4596.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |620.0MiB|620.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |662.0MiB|662.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  31.096s |10.188GiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.997s |9119.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.831s |7449.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.763s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.540s |5025.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.538s |4877.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.632s |4596.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.397s |3428.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.403s |3351.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.367s |3127.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.351s |2963.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.308s |2853.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.208s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.222s |1880.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.210s |1843.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.200s |1830.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.171s |1329.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.129s |771.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                      |  30.111s |768.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCY_QF_AUFBV_NONINCR.smt2                      |  30.113s |683.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  31.096s |10.188GiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.997s |9119.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.831s |7449.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.763s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.540s |5025.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.538s |4877.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.632s |4596.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.397s |3428.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.403s |3351.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.367s |3127.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.351s |2963.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.308s |2853.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.208s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.222s |1880.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.210s |1843.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.200s |1830.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.171s |1329.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.129s |771.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                      |  30.111s |768.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCY_QF_AUFBV_NONINCR.smt2                      |  30.113s |683.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.351s  |  30.351s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.831s  |  30.831s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.763s  |  30.763s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.200s  |  30.200s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.208s  |  30.208s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.538s  |  30.538s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.540s  |  30.540s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.632s  |  30.632s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.112s  |  30.112s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAY_QF_AUFBV_NONINCR.smt2                       |  30.110s  |  30.110s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                       |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2                       |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                       |  30.111s  |  30.111s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCY_QF_AUFBV_NONINCR.smt2                       |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gcc/204_gcc.smt2                                     |  13.044s  |  13.044s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/322_gzip.smt2                                   |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/332_gzip.smt2                                   |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/sqlite3/891_sqlite3.smt2                             |   7.823s  |   7.823s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gcc/033_gcc.smt2                                                   |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                   |  30.367s  |  30.367s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gzip/250_gzip.smt2                                                 |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gzip/272_gzip.smt2                                                 |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/ph7/708_ph7.smt2                                                   |   2.198s  |   2.198s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                           |  30.171s  |  30.171s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/sqlite3/906_sqlite3.smt2                                           |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2        |  30.997s  |  30.997s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2  |  30.403s  |  30.403s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal.smt2             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal_no_rewrite.smt2  |   3.243s  |   3.243s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2   |  31.096s  |  31.096s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2  |  30.308s  |  30.308s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal.smt2        |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2  |  30.397s  |  30.397s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add1.short.smt2                               |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add2.short.smt2                               |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add3.short.smt2                               |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add4.short.smt2                               |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub1.short.smt2                               |  22.862s  |  22.862s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub2.short.smt2                               |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub3.short.smt2                               |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux2.short.smt2                                |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux3.short.smt2                                |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux4.short.smt2                                |   0.743s  |   0.743s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux1.short.smt2                           |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux11.short.smt2                          |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux12.short.smt2                          |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init.short.smt2                           |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init1.short.smt2                          |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init2.short.smt2                          |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.group_red1.short.smt2                                 |   1.751s  |   1.751s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div1.short.smt2                                   |   0.987s  |   0.987s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div10.short.smt2                                  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div12.short.smt2                                  |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div14.short.smt2                                  |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner3.short.smt2                                 |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner4.short.smt2                                 |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash3.short.smt2                                  |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash4.short.smt2                                  |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash5.short.smt2                                  |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner12.short.smt2                                 |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner13.short.smt2                                 |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner22.short.smt2                                 |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner23.short.smt2                                 |   0.120s  |   0.120s  |   0.000s  | 0.0%|
</details>
