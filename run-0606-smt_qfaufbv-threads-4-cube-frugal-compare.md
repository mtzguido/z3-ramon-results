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
Job tag: smt_qfaufbv-threads-4-cube-frugal
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 47ce383ab5ffb3930ebc99a3d81d5b4e7b62f521
Z3 branch: 
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.never_cube=false smt_parallel.frugal_cube_only=true smt_parallel.share_conflicts=false smt_parallel.share_units=false"
Z3 inputs: inputs/QF_AUFBV
Z3 commit message: Merge branch 'Z3Prover:master' into parallel-solving

</pre>
# RHS
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
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.328s  |  30.328s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.849s  |  30.849s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.718s  |  30.718s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.914s  |   0.914s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.223s  |  30.223s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.209s  |  30.209s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.104s  |  30.104s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.535s  |  30.535s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.635s  |  30.635s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.570s  |  30.570s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.117s  |  30.117s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.109s  |  30.109s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.328s  |  30.328s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.849s  |  30.849s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.718s  |  30.718s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.914s  |   0.914s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.223s  |  30.223s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.209s  |  30.209s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.104s  |  30.104s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.535s  |  30.535s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.635s  |  30.635s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.570s  |  30.570s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.117s  |  30.117s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.109s  |  30.109s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.328s  |  30.328s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.849s  |  30.849s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.718s  |  30.718s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.914s  |   0.914s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.223s  |  30.223s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.209s  |  30.209s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.104s  |  30.104s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.535s  |  30.535s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.635s  |  30.635s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.570s  |  30.570s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.117s  |  30.117s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.109s  |  30.109s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.328s  |  30.328s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.849s  |  30.849s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.718s  |  30.718s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.914s  |   0.914s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.223s  |  30.223s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.209s  |  30.209s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.104s  |  30.104s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.535s  |  30.535s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.635s  |  30.635s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.570s  |  30.570s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.117s  |  30.117s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.109s  |  30.109s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  31.199s |11.189GiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.968s |9115.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.849s |7561.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.718s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.635s |5001.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.570s |4589.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.535s |4944.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.387s |3158.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.370s |3470.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.368s |3389.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.328s |2963.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.291s |2887.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.223s |1880.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.210s |1829.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.209s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.206s |1843.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.168s |1341.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.144s |776.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                           |  30.129s |561.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                          |  30.124s |565.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  31.199s |11.189GiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.968s |9115.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.849s |7561.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.718s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.635s |5001.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.570s |4589.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.535s |4944.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.387s |3158.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.370s |3470.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.368s |3389.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.328s |2963.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.291s |2887.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.223s |1880.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.210s |1829.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.209s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.206s |1843.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.168s |1341.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.144s |776.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                           |  30.129s |561.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                          |  30.124s |565.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7561.0MiB|7561.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |304.0MiB|304.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |136.0MiB|136.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1829.0MiB|1829.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1880.0MiB|1880.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1843.0MiB|1843.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |314.0MiB|314.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |381.0MiB|381.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |621.0MiB|621.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |561.0MiB|561.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |406.0MiB|406.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4944.0MiB|4944.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |5001.0MiB|5001.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |565.0MiB|565.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4589.0MiB|4589.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |622.0MiB|622.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |661.0MiB|661.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7561.0MiB|7561.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |304.0MiB|304.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |136.0MiB|136.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1829.0MiB|1829.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1880.0MiB|1880.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1843.0MiB|1843.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |314.0MiB|314.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |381.0MiB|381.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |621.0MiB|621.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |561.0MiB|561.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |406.0MiB|406.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4944.0MiB|4944.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |5001.0MiB|5001.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |565.0MiB|565.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4589.0MiB|4589.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |622.0MiB|622.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |661.0MiB|661.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7561.0MiB|7561.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |304.0MiB|304.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |136.0MiB|136.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1829.0MiB|1829.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1880.0MiB|1880.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1843.0MiB|1843.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |314.0MiB|314.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |381.0MiB|381.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |621.0MiB|621.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |561.0MiB|561.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |406.0MiB|406.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4944.0MiB|4944.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |5001.0MiB|5001.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |565.0MiB|565.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4589.0MiB|4589.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |622.0MiB|622.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |661.0MiB|661.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7561.0MiB|7561.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |304.0MiB|304.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |136.0MiB|136.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1829.0MiB|1829.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1880.0MiB|1880.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1843.0MiB|1843.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |314.0MiB|314.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |381.0MiB|381.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |621.0MiB|621.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |561.0MiB|561.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |406.0MiB|406.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4944.0MiB|4944.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |5001.0MiB|5001.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |565.0MiB|565.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4589.0MiB|4589.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |622.0MiB|622.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |661.0MiB|661.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  31.199s |11.189GiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.968s |9115.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.849s |7561.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.718s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.635s |5001.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.535s |4944.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.570s |4589.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.370s |3470.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.368s |3389.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.387s |3158.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.328s |2963.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.291s |2887.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.209s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.223s |1880.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.206s |1843.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.210s |1829.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.168s |1341.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.144s |776.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                      |  30.101s |763.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2                      |  30.097s |696.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  31.199s |11.189GiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.968s |9115.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.849s |7561.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.718s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.635s |5001.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.535s |4944.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.570s |4589.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.370s |3470.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.368s |3389.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.387s |3158.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.328s |2963.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.291s |2887.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.209s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.223s |1880.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.206s |1843.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.210s |1829.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.168s |1341.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.144s |776.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                      |  30.101s |763.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2                      |  30.097s |696.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.328s  |  30.328s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.849s  |  30.849s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.718s  |  30.718s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.914s  |   0.914s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.223s  |  30.223s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.209s  |  30.209s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.104s  |  30.104s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.535s  |  30.535s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.635s  |  30.635s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.570s  |  30.570s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.117s  |  30.117s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.109s  |  30.109s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAY_QF_AUFBV_NONINCR.smt2                       |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                       |  30.144s  |  30.144s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2                       |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                       |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCY_QF_AUFBV_NONINCR.smt2                       |  30.121s  |  30.121s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gcc/204_gcc.smt2                                     |  15.836s  |  15.836s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/322_gzip.smt2                                   |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/332_gzip.smt2                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/sqlite3/891_sqlite3.smt2                             |   7.590s  |   7.590s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gcc/033_gcc.smt2                                                   |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                   |  30.387s  |  30.387s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gzip/250_gzip.smt2                                                 |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gzip/272_gzip.smt2                                                 |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/ph7/708_ph7.smt2                                                   |   2.310s  |   2.310s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                           |  30.168s  |  30.168s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/sqlite3/906_sqlite3.smt2                                           |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2        |  30.968s  |  30.968s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2  |  30.368s  |  30.368s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal.smt2             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal_no_rewrite.smt2  |   3.201s  |   3.201s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2   |  31.199s  |  31.199s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2  |  30.291s  |  30.291s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal.smt2        |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2  |  30.370s  |  30.370s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add1.short.smt2                               |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add2.short.smt2                               |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add3.short.smt2                               |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add4.short.smt2                               |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub1.short.smt2                               |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub2.short.smt2                               |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub3.short.smt2                               |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux2.short.smt2                                |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux3.short.smt2                                |   0.721s  |   0.721s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux4.short.smt2                                |   0.721s  |   0.721s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux1.short.smt2                           |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux11.short.smt2                          |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux12.short.smt2                          |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init.short.smt2                           |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init1.short.smt2                          |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init2.short.smt2                          |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.group_red1.short.smt2                                 |   1.841s  |   1.841s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div1.short.smt2                                   |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div10.short.smt2                                  |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div12.short.smt2                                  |   0.510s  |   0.510s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div14.short.smt2                                  |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner3.short.smt2                                 |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner4.short.smt2                                 |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash3.short.smt2                                  |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash4.short.smt2                                  |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash5.short.smt2                                  |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner12.short.smt2                                 |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner13.short.smt2                                 |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner22.short.smt2                                 |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner23.short.smt2                                 |   0.124s  |   0.124s  |   0.000s  | 0.0%|
</details>
