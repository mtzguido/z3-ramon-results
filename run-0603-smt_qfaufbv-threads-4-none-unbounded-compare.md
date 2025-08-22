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
Job tag: smt_qfaufbv-threads-4-none-unbounded
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 47ce383ab5ffb3930ebc99a3d81d5b4e7b62f521
Z3 branch: 
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.never_cube=true smt_parallel.share_conflicts=false smt_parallel.share_units=false smt.threads.max_conflicts=4294967295"
Z3 inputs: inputs/QF_AUFBV
Z3 commit message: Merge branch 'Z3Prover:master' into parallel-solving

</pre>
# RHS
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
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.371s  |  30.371s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.827s  |  30.827s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.768s  |  30.768s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.205s  |  30.205s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.233s  |  30.233s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.220s  |  30.220s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.111s  |  30.111s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  22.522s  |  22.522s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.534s  |  30.534s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.562s  |  30.562s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.623s  |  30.623s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.107s  |  30.107s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.371s  |  30.371s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.827s  |  30.827s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.768s  |  30.768s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.205s  |  30.205s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.233s  |  30.233s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.220s  |  30.220s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.111s  |  30.111s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  22.522s  |  22.522s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.534s  |  30.534s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.562s  |  30.562s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.623s  |  30.623s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.107s  |  30.107s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.371s  |  30.371s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.827s  |  30.827s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.768s  |  30.768s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.205s  |  30.205s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.233s  |  30.233s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.220s  |  30.220s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.111s  |  30.111s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  22.522s  |  22.522s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.534s  |  30.534s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.562s  |  30.562s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.623s  |  30.623s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.107s  |  30.107s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.371s  |  30.371s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.827s  |  30.827s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.768s  |  30.768s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.205s  |  30.205s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.233s  |  30.233s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.220s  |  30.220s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.111s  |  30.111s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  22.522s  |  22.522s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.534s  |  30.534s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.562s  |  30.562s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.623s  |  30.623s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.107s  |  30.107s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  30.928s |9541.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.879s |8591.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.827s |7410.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.768s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.623s |4634.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.562s |4880.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.534s |4928.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.432s |3334.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.394s |2854.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.375s |3193.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.371s |2963.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.338s |3126.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.233s |1863.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.222s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.220s |1865.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.205s |1828.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.158s |1371.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.132s |777.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                          |  30.123s |562.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAY_QF_AUFBV_NONINCR.smt2                      |  30.115s |620.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  30.928s |9541.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.879s |8591.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.827s |7410.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.768s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.623s |4634.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.562s |4880.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.534s |4928.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.432s |3334.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.394s |2854.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.375s |3193.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.371s |2963.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.338s |3126.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.233s |1863.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.222s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.220s |1865.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.205s |1828.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.158s |1371.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.132s |777.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                          |  30.123s |562.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAY_QF_AUFBV_NONINCR.smt2                      |  30.115s |620.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7410.0MiB|7410.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |330.0MiB|330.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |136.0MiB|136.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1828.0MiB|1828.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1863.0MiB|1863.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1865.0MiB|1865.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |326.0MiB|326.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |386.0MiB|386.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |630.0MiB|630.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |563.0MiB|563.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |422.0MiB|422.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4928.0MiB|4928.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |4880.0MiB|4880.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |562.0MiB|562.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4634.0MiB|4634.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |615.0MiB|615.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |665.0MiB|665.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7410.0MiB|7410.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |330.0MiB|330.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |136.0MiB|136.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1828.0MiB|1828.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1863.0MiB|1863.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1865.0MiB|1865.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |326.0MiB|326.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |386.0MiB|386.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |630.0MiB|630.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |563.0MiB|563.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |422.0MiB|422.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4928.0MiB|4928.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |4880.0MiB|4880.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |562.0MiB|562.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4634.0MiB|4634.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |615.0MiB|615.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |665.0MiB|665.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7410.0MiB|7410.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |330.0MiB|330.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |136.0MiB|136.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1828.0MiB|1828.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1863.0MiB|1863.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1865.0MiB|1865.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |326.0MiB|326.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |386.0MiB|386.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |630.0MiB|630.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |563.0MiB|563.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |422.0MiB|422.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4928.0MiB|4928.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |4880.0MiB|4880.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |562.0MiB|562.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4634.0MiB|4634.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |615.0MiB|615.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |665.0MiB|665.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7410.0MiB|7410.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |330.0MiB|330.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |136.0MiB|136.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1828.0MiB|1828.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1863.0MiB|1863.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1865.0MiB|1865.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |326.0MiB|326.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |386.0MiB|386.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |630.0MiB|630.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |563.0MiB|563.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |422.0MiB|422.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4928.0MiB|4928.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |4880.0MiB|4880.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |562.0MiB|562.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4634.0MiB|4634.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |615.0MiB|615.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |665.0MiB|665.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  30.928s |9541.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.879s |8591.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.827s |7410.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.768s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.534s |4928.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.562s |4880.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.623s |4634.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.432s |3334.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.375s |3193.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.338s |3126.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.371s |2963.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.394s |2854.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.222s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.220s |1865.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.233s |1863.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.205s |1828.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.158s |1371.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.132s |777.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                      |  30.102s |770.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2                      |  30.098s |686.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  30.928s |9541.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.879s |8591.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.827s |7410.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.768s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.534s |4928.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.562s |4880.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.623s |4634.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.432s |3334.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.375s |3193.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.338s |3126.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.371s |2963.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.394s |2854.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.222s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.220s |1865.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.233s |1863.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.205s |1828.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.158s |1371.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.132s |777.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                      |  30.102s |770.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2                      |  30.098s |686.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.371s  |  30.371s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.827s  |  30.827s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.768s  |  30.768s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.205s  |  30.205s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.233s  |  30.233s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.220s  |  30.220s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.111s  |  30.111s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  22.522s  |  22.522s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.534s  |  30.534s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.562s  |  30.562s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.623s  |  30.623s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.107s  |  30.107s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAY_QF_AUFBV_NONINCR.smt2                       |  30.115s  |  30.115s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                       |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2                       |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                       |  30.102s  |  30.102s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCY_QF_AUFBV_NONINCR.smt2                       |  30.108s  |  30.108s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gcc/204_gcc.smt2                                     |   2.898s  |   2.898s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/322_gzip.smt2                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/332_gzip.smt2                                   |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/sqlite3/891_sqlite3.smt2                             |   6.702s  |   6.702s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gcc/033_gcc.smt2                                                   |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                   |  30.338s  |  30.338s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gzip/250_gzip.smt2                                                 |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gzip/272_gzip.smt2                                                 |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/ph7/708_ph7.smt2                                                   |   2.221s  |   2.221s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                           |  30.158s  |  30.158s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/sqlite3/906_sqlite3.smt2                                           |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2        |  30.879s  |  30.879s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2  |  30.432s  |  30.432s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal.smt2             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal_no_rewrite.smt2  |   5.139s  |   5.139s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2   |  30.928s  |  30.928s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2  |  30.394s  |  30.394s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal.smt2        |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2  |  30.375s  |  30.375s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add1.short.smt2                               |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add2.short.smt2                               |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add3.short.smt2                               |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add4.short.smt2                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub1.short.smt2                               |  16.262s  |  16.262s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub2.short.smt2                               |  14.551s  |  14.551s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub3.short.smt2                               |  16.957s  |  16.957s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux2.short.smt2                                |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux3.short.smt2                                |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux4.short.smt2                                |   0.713s  |   0.713s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux1.short.smt2                           |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux11.short.smt2                          |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux12.short.smt2                          |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init.short.smt2                           |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init1.short.smt2                          |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init2.short.smt2                          |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.group_red1.short.smt2                                 |   1.564s  |   1.564s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div1.short.smt2                                   |   0.823s  |   0.823s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div10.short.smt2                                  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div12.short.smt2                                  |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div14.short.smt2                                  |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner3.short.smt2                                 |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner4.short.smt2                                 |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash3.short.smt2                                  |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash4.short.smt2                                  |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash5.short.smt2                                  |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner12.short.smt2                                 |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner13.short.smt2                                 |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner22.short.smt2                                 |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner23.short.smt2                                 |   0.136s  |   0.136s  |   0.000s  | 0.0%|
</details>
