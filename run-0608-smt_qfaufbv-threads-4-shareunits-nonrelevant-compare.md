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
Job tag: smt_qfaufbv-threads-4-shareunits-nonrelevant
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 47ce383ab5ffb3930ebc99a3d81d5b4e7b62f521
Z3 branch: 
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.never_cube=true smt_parallel.share_conflicts=true smt_parallel.share_units=false smt_parallel.relevant_units_only=false"
Z3 inputs: inputs/QF_AUFBV
Z3 commit message: Merge branch 'Z3Prover:master' into parallel-solving

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfaufbv-threads-4-shareunits-nonrelevant
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 47ce383ab5ffb3930ebc99a3d81d5b4e7b62f521
Z3 branch: 
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.never_cube=true smt_parallel.share_conflicts=true smt_parallel.share_units=false smt_parallel.relevant_units_only=false"
Z3 inputs: inputs/QF_AUFBV
Z3 commit message: Merge branch 'Z3Prover:master' into parallel-solving

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.360s  |  30.360s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.841s  |  30.841s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.768s  |  30.768s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.240s  |  30.240s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.227s  |  30.227s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  18.443s  |  18.443s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.537s  |  30.537s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.654s  |  30.654s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  21.874s  |  21.874s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.613s  |  30.613s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.112s  |  30.112s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.360s  |  30.360s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.841s  |  30.841s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.768s  |  30.768s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.240s  |  30.240s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.227s  |  30.227s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  18.443s  |  18.443s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.537s  |  30.537s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.654s  |  30.654s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  21.874s  |  21.874s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.613s  |  30.613s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.112s  |  30.112s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.360s  |  30.360s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.841s  |  30.841s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.768s  |  30.768s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.240s  |  30.240s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.227s  |  30.227s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  18.443s  |  18.443s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.537s  |  30.537s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.654s  |  30.654s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  21.874s  |  21.874s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.613s  |  30.613s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.112s  |  30.112s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.360s  |  30.360s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.841s  |  30.841s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.768s  |  30.768s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.240s  |  30.240s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.227s  |  30.227s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  18.443s  |  18.443s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.537s  |  30.537s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.654s  |  30.654s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  21.874s  |  21.874s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.613s  |  30.613s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.112s  |  30.112s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.965s |8675.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  30.965s |9541.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.841s |7368.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.768s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.654s |4871.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.613s |4614.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.537s |4976.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.410s |3298.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.408s |2852.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.400s |3228.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.375s |3146.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.360s |2963.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.240s |1879.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.227s |1843.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.206s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.206s |1831.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.190s |1434.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.131s |780.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                      |  30.112s |662.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCY_QF_AUFBV_NONINCR.smt2                      |  30.108s |680.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.965s |8675.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  30.965s |9541.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.841s |7368.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.768s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.654s |4871.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.613s |4614.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.537s |4976.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.410s |3298.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.408s |2852.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.400s |3228.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.375s |3146.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.360s |2963.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.240s |1879.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.227s |1843.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.206s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.206s |1831.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.190s |1434.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.131s |780.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                      |  30.112s |662.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCY_QF_AUFBV_NONINCR.smt2                      |  30.108s |680.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7368.0MiB|7368.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |408.0MiB|408.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |135.0MiB|135.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1831.0MiB|1831.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1879.0MiB|1879.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1843.0MiB|1843.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |317.0MiB|317.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |383.0MiB|383.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |633.0MiB|633.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |557.0MiB|557.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |419.0MiB|419.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4976.0MiB|4976.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |4871.0MiB|4871.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |568.0MiB|568.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4614.0MiB|4614.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |627.0MiB|627.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |662.0MiB|662.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7368.0MiB|7368.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |408.0MiB|408.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |135.0MiB|135.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1831.0MiB|1831.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1879.0MiB|1879.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1843.0MiB|1843.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |317.0MiB|317.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |383.0MiB|383.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |633.0MiB|633.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |557.0MiB|557.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |419.0MiB|419.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4976.0MiB|4976.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |4871.0MiB|4871.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |568.0MiB|568.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4614.0MiB|4614.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |627.0MiB|627.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |662.0MiB|662.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7368.0MiB|7368.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |408.0MiB|408.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |135.0MiB|135.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1831.0MiB|1831.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1879.0MiB|1879.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1843.0MiB|1843.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |317.0MiB|317.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |383.0MiB|383.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |633.0MiB|633.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |557.0MiB|557.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |419.0MiB|419.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4976.0MiB|4976.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |4871.0MiB|4871.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |568.0MiB|568.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4614.0MiB|4614.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |627.0MiB|627.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |662.0MiB|662.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |2963.0MiB|2963.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |7368.0MiB|7368.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |7236.0MiB|7236.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |408.0MiB|408.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |135.0MiB|135.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |1831.0MiB|1831.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |1879.0MiB|1879.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |1843.0MiB|1843.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |1950.0MiB|1950.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |317.0MiB|317.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |383.0MiB|383.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |633.0MiB|633.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |557.0MiB|557.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |419.0MiB|419.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |4976.0MiB|4976.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |4871.0MiB|4871.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |568.0MiB|568.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |4614.0MiB|4614.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |627.0MiB|627.0MiB|0B| 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |662.0MiB|662.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  30.965s |9541.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.965s |8675.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.841s |7368.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.768s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.537s |4976.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.654s |4871.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.613s |4614.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.410s |3298.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.400s |3228.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.375s |3146.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.360s |2963.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.408s |2852.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.206s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.240s |1879.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.227s |1843.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.206s |1831.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.190s |1434.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.131s |780.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                      |  30.105s |771.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2                      |  30.102s |691.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2  |  30.965s |9541.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2       |  30.965s |8675.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                             |  30.841s |7368.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                             |  30.768s |7236.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                  |  30.537s |4976.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                |  30.654s |4871.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                           |  30.613s |4614.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.410s |3298.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2 |  30.400s |3228.0MiB|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                  |  30.375s |3146.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                       |  30.360s |2963.0MiB|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2 |  30.408s |2852.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                       |  30.206s |1950.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                       |  30.240s |1879.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                       |  30.227s |1843.0MiB|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                       |  30.206s |1831.0MiB|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                          |  30.190s |1434.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                      |  30.131s |780.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                      |  30.105s |771.0MiB|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2                      |  30.102s |691.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|QF_AUFBV/2019-Gonzalvez/opStructure_C_16_32_2_2.smt2                                        |  30.360s  |  30.360s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_6.smt2                                              |  30.841s  |  30.841s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_MBA_7.smt2                                              |  30.768s  |  30.768s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_1.smt2                                              |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_NPT_2.smt2                                              |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_24_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_16_32_2_2.smt2                                        |  30.240s  |  30.240s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_16_2_2.smt2                                        |  30.227s  |  30.227s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Gonzalvez/opStructure_O_32_32_2_2.smt2                                        |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-15-compact-mem.smt2                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-20-compact-mem.smt2                        |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/VexRiscv-regch0-30-compact-mem.smt2                        |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-check-compact-mem.smt2                            |  18.443s  |  18.443s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/picorv32-pcregs-compact-mem.smt2                           |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-sat-compact-mem.smt2                   |  30.537s  |  30.537s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/ponylink-slaveTXlen-unsat-compact-mem.smt2                 |  30.654s  |  30.654s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-busdelay-compact-mem.smt2                           |  21.874s  |  21.874s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-pfcache-compact-mem.smt2                            |  30.613s  |  30.613s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2018E/zipcpu-zipmmu-compact-mem.smt2                             |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAX_QF_AUFBV_NONINCR.smt2                       |  30.112s  |  30.112s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutAY_QF_AUFBV_NONINCR.smt2                       |  30.096s  |  30.096s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBX_QF_AUFBV_NONINCR.smt2                       |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutBY_QF_AUFBV_NONINCR.smt2                       |  30.102s  |  30.102s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCX_QF_AUFBV_NONINCR.smt2                       |  30.105s  |  30.105s  |   0.000s  | 0.0%|
|QF_AUFBV/2019-Wolf-fmbench/2019A/picorv32_mutCY_QF_AUFBV_NONINCR.smt2                       |  30.108s  |  30.108s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gcc/204_gcc.smt2                                     |   3.116s  |   3.116s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/322_gzip.smt2                                   |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/gzip/332_gzip.smt2                                   |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2-partial-undef/sqlite3/891_sqlite3.smt2                             |   3.749s  |   3.749s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gcc/033_gcc.smt2                                                   |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gcc/073_gcc.smt2                                                   |  30.375s  |  30.375s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gzip/250_gzip.smt2                                                 |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/gzip/272_gzip.smt2                                                 |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/ph7/708_ph7.smt2                                                   |   2.250s  |   2.250s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/sqlite3/823_sqlite3.smt2                                           |  30.190s  |  30.190s  |   0.000s  | 0.0%|
|QF_AUFBV/20210301-Alive2/sqlite3/906_sqlite3.smt2                                           |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariantLoopInductive.smt2        |  30.965s  |  30.965s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_loop_inductive_invariant_no_rewriteLoopInductive.smt2  |  30.410s  |  30.410s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal.smt2             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_armv8_one_block_correct_fn_calls_equal_no_rewrite.smt2  |   5.582s  |   5.582s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariantLoopInductive.smt2   |  30.965s  |  30.965s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_loop_inductive_invariant_no_rewriteLoopInductive.smt2  |  30.408s  |  30.408s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal.smt2        |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|QF_AUFBV/20231002-nysm/sha512_block_data_order_one_block_correct_fn_calls_equal_no_rewrite.smt2  |  30.400s  |  30.400s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add1.short.smt2                               |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add2.short.smt2                               |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add3.short.smt2                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_add4.short.smt2                               |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub1.short.smt2                               |  22.387s  |  22.387s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub2.short.smt2                               |  19.105s  |  19.105s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_full_sub3.short.smt2                               |  14.280s  |  14.280s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux2.short.smt2                                |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux3.short.smt2                                |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_mul_aux4.short.smt2                                |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux1.short.smt2                           |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux11.short.smt2                          |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_aux12.short.smt2                          |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init.short.smt2                           |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init1.short.smt2                          |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.ec_twin_mul_init2.short.smt2                          |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.group_red1.short.smt2                                 |   1.567s  |   1.567s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div1.short.smt2                                   |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div10.short.smt2                                  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div12.short.smt2                                  |   0.480s  |   0.480s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mod_div14.short.smt2                                  |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner3.short.smt2                                 |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.mul_inner4.short.smt2                                 |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash3.short.smt2                                  |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash4.short.smt2                                  |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.signHash5.short.smt2                                  |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner12.short.smt2                                 |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner13.short.smt2                                 |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner22.short.smt2                                 |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|QF_AUFBV/ecc/com.galois.ecc.P384ECC64.sq_inner23.short.smt2                                 |   0.123s  |   0.123s  |   0.000s  | 0.0%|
</details>
