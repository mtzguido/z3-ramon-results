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
Job tag: smt_qfaufbv-threads-4-cube-shareconflicts
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 47ce383ab5ffb3930ebc99a3d81d5b4e7b62f521
Z3 branch: 
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.never_cube=false smt_parallel.frugal_cube_only=false smt_parallel.share_conflicts=true smt_parallel.share_units=false"
Z3 inputs: inputs/QF_AUFBV
Z3 commit message: Merge branch 'Z3Prover:master' into parallel-solving

</pre>
# RHS
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
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.331s  |  30.331s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.852s  |  30.852s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.746s  |  30.746s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.200s  |  30.200s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.233s  |  30.233s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.221s  |  30.221s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.567s  |  30.567s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.649s  |  30.649s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.636s  |  30.636s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.157s  |  30.157s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.109s  |  30.109s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.331s  |  30.331s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.852s  |  30.852s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.746s  |  30.746s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.200s  |  30.200s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.233s  |  30.233s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.221s  |  30.221s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.567s  |  30.567s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.649s  |  30.649s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.636s  |  30.636s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.157s  |  30.157s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.109s  |  30.109s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.331s  |  30.331s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.852s  |  30.852s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.746s  |  30.746s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.200s  |  30.200s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.233s  |  30.233s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.221s  |  30.221s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.567s  |  30.567s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.649s  |  30.649s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.636s  |  30.636s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.157s  |  30.157s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.109s  |  30.109s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.331s  |  30.331s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.852s  |  30.852s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.746s  |  30.746s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.200s  |  30.200s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.233s  |  30.233s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.221s  |  30.221s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.567s  |  30.567s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.649s  |  30.649s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.636s  |  30.636s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.157s  |  30.157s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.109s  |  30.109s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  31.061s |9571.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  31.022s |9102.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.852s |7707.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.746s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.649s |4977.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.636s |4611.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.567s |4973.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.407s |3435.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.391s |3322.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.369s |3131.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.356s |2835.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.331s |2963.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.233s |1882.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.222s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.221s |1866.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.200s |1828.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.168s |1336.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                            |  30.157s |621.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.135s |771.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                          |  30.126s |413.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  31.061s |9571.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  31.022s |9102.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.852s |7707.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.746s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.649s |4977.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.636s |4611.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.567s |4973.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.407s |3435.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.391s |3322.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.369s |3131.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.356s |2835.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.331s |2963.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.233s |1882.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.222s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.221s |1866.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.200s |1828.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.168s |1336.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                            |  30.157s |621.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.135s |771.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                          |  30.126s |413.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7707.0MiB|7707.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |309.0MiB|309.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |135.0MiB|135.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1828.0MiB|1828.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1882.0MiB|1882.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1866.0MiB|1866.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |314.0MiB|314.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |380.0MiB|380.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |619.0MiB|619.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |559.0MiB|559.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |413.0MiB|413.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4973.0MiB|4973.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |4977.0MiB|4977.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |571.0MiB|571.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4611.0MiB|4611.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |621.0MiB|621.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |668.0MiB|668.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7707.0MiB|7707.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |309.0MiB|309.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |135.0MiB|135.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1828.0MiB|1828.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1882.0MiB|1882.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1866.0MiB|1866.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |314.0MiB|314.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |380.0MiB|380.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |619.0MiB|619.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |559.0MiB|559.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |413.0MiB|413.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4973.0MiB|4973.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |4977.0MiB|4977.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |571.0MiB|571.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4611.0MiB|4611.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |621.0MiB|621.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |668.0MiB|668.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7707.0MiB|7707.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |309.0MiB|309.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |135.0MiB|135.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1828.0MiB|1828.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1882.0MiB|1882.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1866.0MiB|1866.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |314.0MiB|314.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |380.0MiB|380.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |619.0MiB|619.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |559.0MiB|559.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |413.0MiB|413.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4973.0MiB|4973.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |4977.0MiB|4977.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |571.0MiB|571.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4611.0MiB|4611.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |621.0MiB|621.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |668.0MiB|668.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7707.0MiB|7707.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |309.0MiB|309.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |135.0MiB|135.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1828.0MiB|1828.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1882.0MiB|1882.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1866.0MiB|1866.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |314.0MiB|314.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |380.0MiB|380.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |619.0MiB|619.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |559.0MiB|559.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |413.0MiB|413.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4973.0MiB|4973.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |4977.0MiB|4977.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |571.0MiB|571.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4611.0MiB|4611.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |621.0MiB|621.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |668.0MiB|668.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  31.061s |9571.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  31.022s |9102.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.852s |7707.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.746s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.649s |4977.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.567s |4973.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.636s |4611.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.407s |3435.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.391s |3322.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.369s |3131.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.331s |2963.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.356s |2835.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.222s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.233s |1882.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.221s |1866.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.200s |1828.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.168s |1336.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.135s |771.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                      |  30.106s |768.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2                      |  30.096s |690.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  31.061s |9571.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  31.022s |9102.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.852s |7707.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.746s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.649s |4977.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.567s |4973.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.636s |4611.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.407s |3435.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.391s |3322.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.369s |3131.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.331s |2963.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.356s |2835.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.222s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.233s |1882.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.221s |1866.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.200s |1828.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.168s |1336.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.135s |771.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                      |  30.106s |768.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2                      |  30.096s |690.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.331s  |  30.331s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.852s  |  30.852s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.746s  |  30.746s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.200s  |  30.200s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.233s  |  30.233s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.221s  |  30.221s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.567s  |  30.567s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.649s  |  30.649s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.636s  |  30.636s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.157s  |  30.157s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.109s  |  30.109s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAY_QF_AUFBV_NONINCR.smt2                       |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                       |  30.135s  |  30.135s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2                       |  30.096s  |  30.096s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                       |  30.106s  |  30.106s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCY_QF_AUFBV_NONINCR.smt2                       |  30.116s  |  30.116s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gcc/204_gcc.smt2                                     |  13.207s  |  13.207s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/322_gzip.smt2                                   |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/332_gzip.smt2                                   |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/sqlite3/891_sqlite3.smt2                             |   6.753s  |   6.753s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gcc/033_gcc.smt2                                                   |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                   |  30.369s  |  30.369s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gzip/250_gzip.smt2                                                 |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gzip/272_gzip.smt2                                                 |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/ph7/708_ph7.smt2                                                   |   2.131s  |   2.131s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                           |  30.168s  |  30.168s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/sqlite3/906_sqlite3.smt2                                           |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2        |  31.022s  |  31.022s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2  |  30.391s  |  30.391s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal.smt2             |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal_no_rewrite.smt2  |   3.481s  |   3.481s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2   |  31.061s  |  31.061s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2  |  30.356s  |  30.356s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal.smt2        |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2  |  30.407s  |  30.407s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add1.short.smt2                               |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add2.short.smt2                               |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add3.short.smt2                               |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add4.short.smt2                               |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub1.short.smt2                               |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub2.short.smt2                               |  20.418s  |  20.418s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub3.short.smt2                               |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux2.short.smt2                                |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux3.short.smt2                                |   0.732s  |   0.732s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux4.short.smt2                                |   0.728s  |   0.728s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux1.short.smt2                           |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux11.short.smt2                          |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux12.short.smt2                          |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init.short.smt2                           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init1.short.smt2                          |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init2.short.smt2                          |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.group_red1.short.smt2                                 |   2.378s  |   2.378s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div1.short.smt2                                   |   4.364s  |   4.364s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div10.short.smt2                                  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div12.short.smt2                                  |   0.510s  |   0.510s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div14.short.smt2                                  |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner3.short.smt2                                 |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner4.short.smt2                                 |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash3.short.smt2                                  |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash4.short.smt2                                  |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash5.short.smt2                                  |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner12.short.smt2                                 |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner13.short.smt2                                 |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner22.short.smt2                                 |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner23.short.smt2                                 |   0.120s  |   0.120s  |   0.000s  | 0.0%|
</details>
