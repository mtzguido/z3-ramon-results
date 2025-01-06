Comparing data and data


# SUMMARY
- LHS tests = 2000
- RHS tests = 2000
- LHS success = 795  (39.75%)
- RHS success = 795  (39.75%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-top-level-assertions
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: a8b88b185090896d0f56ead0b11ca74efdf787b7
Z3 branch: master
Z3 options: "-T:20 -v:2  sls.bv_use_top_level_assertions=true -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true "
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: fish for nyi

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-top-level-assertions
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: a8b88b185090896d0f56ead0b11ca74efdf787b7
Z3 branch: master
Z3 options: "-T:20 -v:2  sls.bv_use_top_level_assertions=true -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true "
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: fish for nyi

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|100.smt2                                                                                    |  19.739s  |  19.739s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.516s  |  19.516s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.488s  |  19.488s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.571s  |  19.571s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  19.822s  |  19.822s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.688s  |  19.688s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  19.588s  |  19.588s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  19.439s  |  19.439s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  19.455s  |  19.455s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                       |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.4.prop1_cc_ref_max.smt2                                       |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_schedule_world.1.prop1_cc_ref_max.smt2                                         |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_swap_three_cc_ref_max.smt2                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                        |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_swap_two_cc_ref_max.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_synabs_cc_ref_max.smt2                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_BV_counter_v_cc_ref_max.smt2                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_protocols.1.prop1_cc_ref_max.smt2                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|100.smt2                                                                                    |  19.739s  |  19.739s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.516s  |  19.516s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.488s  |  19.488s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.571s  |  19.571s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  19.822s  |  19.822s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.688s  |  19.688s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  19.588s  |  19.588s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  19.439s  |  19.439s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  19.455s  |  19.455s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                       |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.4.prop1_cc_ref_max.smt2                                       |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_schedule_world.1.prop1_cc_ref_max.smt2                                         |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_swap_three_cc_ref_max.smt2                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                        |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_swap_two_cc_ref_max.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_synabs_cc_ref_max.smt2                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_BV_counter_v_cc_ref_max.smt2                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_protocols.1.prop1_cc_ref_max.smt2                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|100.smt2                                                                                    |  19.739s  |  19.739s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.516s  |  19.516s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.488s  |  19.488s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.571s  |  19.571s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  19.822s  |  19.822s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.688s  |  19.688s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  19.588s  |  19.588s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  19.439s  |  19.439s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  19.455s  |  19.455s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                       |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.4.prop1_cc_ref_max.smt2                                       |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_schedule_world.1.prop1_cc_ref_max.smt2                                         |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_swap_three_cc_ref_max.smt2                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                        |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_swap_two_cc_ref_max.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_synabs_cc_ref_max.smt2                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_BV_counter_v_cc_ref_max.smt2                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_protocols.1.prop1_cc_ref_max.smt2                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|100.smt2                                                                                    |  19.739s  |  19.739s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.516s  |  19.516s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.488s  |  19.488s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.571s  |  19.571s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  19.822s  |  19.822s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.688s  |  19.688s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  19.588s  |  19.588s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  19.439s  |  19.439s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  19.455s  |  19.455s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                       |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.4.prop1_cc_ref_max.smt2                                       |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_schedule_world.1.prop1_cc_ref_max.smt2                                         |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_swap_three_cc_ref_max.smt2                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                        |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_swap_two_cc_ref_max.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_synabs_cc_ref_max.smt2                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_BV_counter_v_cc_ref_max.smt2                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_protocols.1.prop1_cc_ref_max.smt2                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|sort.smt2                                                                                  |  19.940s |97.356MiB|
|fig5.phx.smt2                                                                              |  19.933s |61.564MiB|
|94.smt2                                                                                    |  19.928s |25.452MiB|
|bench_2737.smt2                                                                            |  19.863s |18.752MiB|
|bench_1013.smt2                                                                            |  19.857s |65.588MiB|
|26.smt2                                                                                    |  19.822s |23.2MiB|
|bench_13147.smt2                                                                           |  19.802s |23.656MiB|
|bench_353.smt2                                                                             |  19.774s |21.18MiB|
|100.smt2                                                                                   |  19.739s |24.328MiB|
|VS3-benchmark-S1.smt2                                                                      |  19.699s |20.22MiB|
|bench_4261.smt2                                                                            |  19.690s |38.268MiB|
|41.smt2                                                                                    |  19.688s |22.412MiB|
|bench_489.smt2                                                                             |  19.627s |20.184MiB|
|bench_6898.smt2                                                                            |  19.601s |18.768MiB|
|matrixsqrt.smt2                                                                            |  19.600s |18.284MiB|
|bench_10306.smt2                                                                           |  19.591s |19.016MiB|
|64.smt2                                                                                    |  19.588s |25.42MiB|
|20.smt2                                                                                    |  19.571s |24.296MiB|
|rand_65_500_1235857888_0_k-6_sat.gph.smt2                                                  |  19.533s |25.028MiB|
|102.smt2                                                                                   |  19.516s |25.436MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|sort.smt2                                                                                  |  19.940s |97.356MiB|
|fig5.phx.smt2                                                                              |  19.933s |61.564MiB|
|94.smt2                                                                                    |  19.928s |25.452MiB|
|bench_2737.smt2                                                                            |  19.863s |18.752MiB|
|bench_1013.smt2                                                                            |  19.857s |65.588MiB|
|26.smt2                                                                                    |  19.822s |23.2MiB|
|bench_13147.smt2                                                                           |  19.802s |23.656MiB|
|bench_353.smt2                                                                             |  19.774s |21.18MiB|
|100.smt2                                                                                   |  19.739s |24.328MiB|
|VS3-benchmark-S1.smt2                                                                      |  19.699s |20.22MiB|
|bench_4261.smt2                                                                            |  19.690s |38.268MiB|
|41.smt2                                                                                    |  19.688s |22.412MiB|
|bench_489.smt2                                                                             |  19.627s |20.184MiB|
|bench_6898.smt2                                                                            |  19.601s |18.768MiB|
|matrixsqrt.smt2                                                                            |  19.600s |18.284MiB|
|bench_10306.smt2                                                                           |  19.591s |19.016MiB|
|64.smt2                                                                                    |  19.588s |25.42MiB|
|20.smt2                                                                                    |  19.571s |24.296MiB|
|rand_65_500_1235857888_0_k-6_sat.gph.smt2                                                  |  19.533s |25.028MiB|
|102.smt2                                                                                   |  19.516s |25.436MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|100.smt2                                                                                    |24.328MiB|24.328MiB|0B| 0.0%|
|102.smt2                                                                                    |25.436MiB|25.436MiB|0B| 0.0%|
|108.smt2                                                                                    |37.392MiB|37.392MiB|0B| 0.0%|
|20.smt2                                                                                     |24.296MiB|24.296MiB|0B| 0.0%|
|26.smt2                                                                                     |23.2MiB|23.2MiB|0B| 0.0%|
|41.smt2                                                                                     |22.412MiB|22.412MiB|0B| 0.0%|
|64.smt2                                                                                     |25.42MiB|25.42MiB|0B| 0.0%|
|80.smt2                                                                                     |25.44MiB|25.44MiB|0B| 0.0%|
|90.smt2                                                                                     |25.552MiB|25.552MiB|0B| 0.0%|
|94.smt2                                                                                     |25.452MiB|25.452MiB|0B| 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                       |19.232MiB|19.232MiB|0B| 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.4.prop1_cc_ref_max.smt2                                       |20.548MiB|20.548MiB|0B| 0.0%|
|QF_BV_bv8_bv_schedule_world.1.prop1_cc_ref_max.smt2                                         |19.016MiB|19.016MiB|0B| 0.0%|
|QF_BV_bv8_bv_swap_three_cc_ref_max.smt2                                                     |18.508MiB|18.508MiB|0B| 0.0%|
|QF_BV_bv_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                        |18.9MiB|18.9MiB|0B| 0.0%|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                              |18.764MiB|18.764MiB|0B| 0.0%|
|QF_BV_bv_bv_swap_two_cc_ref_max.smt2                                                        |18.252MiB|18.252MiB|0B| 0.0%|
|QF_BV_bv_bv_synabs_cc_ref_max.smt2                                                          |18.508MiB|18.508MiB|0B| 0.0%|
|QF_BV_counter_v_cc_ref_max.smt2                                                             |18.256MiB|18.256MiB|0B| 0.0%|
|QF_BV_protocols.1.prop1_cc_ref_max.smt2                                                     |18.76MiB|18.76MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|100.smt2                                                                                    |24.328MiB|24.328MiB|0B| 0.0%|
|102.smt2                                                                                    |25.436MiB|25.436MiB|0B| 0.0%|
|108.smt2                                                                                    |37.392MiB|37.392MiB|0B| 0.0%|
|20.smt2                                                                                     |24.296MiB|24.296MiB|0B| 0.0%|
|26.smt2                                                                                     |23.2MiB|23.2MiB|0B| 0.0%|
|41.smt2                                                                                     |22.412MiB|22.412MiB|0B| 0.0%|
|64.smt2                                                                                     |25.42MiB|25.42MiB|0B| 0.0%|
|80.smt2                                                                                     |25.44MiB|25.44MiB|0B| 0.0%|
|90.smt2                                                                                     |25.552MiB|25.552MiB|0B| 0.0%|
|94.smt2                                                                                     |25.452MiB|25.452MiB|0B| 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                       |19.232MiB|19.232MiB|0B| 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.4.prop1_cc_ref_max.smt2                                       |20.548MiB|20.548MiB|0B| 0.0%|
|QF_BV_bv8_bv_schedule_world.1.prop1_cc_ref_max.smt2                                         |19.016MiB|19.016MiB|0B| 0.0%|
|QF_BV_bv8_bv_swap_three_cc_ref_max.smt2                                                     |18.508MiB|18.508MiB|0B| 0.0%|
|QF_BV_bv_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                        |18.9MiB|18.9MiB|0B| 0.0%|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                              |18.764MiB|18.764MiB|0B| 0.0%|
|QF_BV_bv_bv_swap_two_cc_ref_max.smt2                                                        |18.252MiB|18.252MiB|0B| 0.0%|
|QF_BV_bv_bv_synabs_cc_ref_max.smt2                                                          |18.508MiB|18.508MiB|0B| 0.0%|
|QF_BV_counter_v_cc_ref_max.smt2                                                             |18.256MiB|18.256MiB|0B| 0.0%|
|QF_BV_protocols.1.prop1_cc_ref_max.smt2                                                     |18.76MiB|18.76MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|100.smt2                                                                                    |24.328MiB|24.328MiB|0B| 0.0%|
|102.smt2                                                                                    |25.436MiB|25.436MiB|0B| 0.0%|
|108.smt2                                                                                    |37.392MiB|37.392MiB|0B| 0.0%|
|20.smt2                                                                                     |24.296MiB|24.296MiB|0B| 0.0%|
|26.smt2                                                                                     |23.2MiB|23.2MiB|0B| 0.0%|
|41.smt2                                                                                     |22.412MiB|22.412MiB|0B| 0.0%|
|64.smt2                                                                                     |25.42MiB|25.42MiB|0B| 0.0%|
|80.smt2                                                                                     |25.44MiB|25.44MiB|0B| 0.0%|
|90.smt2                                                                                     |25.552MiB|25.552MiB|0B| 0.0%|
|94.smt2                                                                                     |25.452MiB|25.452MiB|0B| 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                       |19.232MiB|19.232MiB|0B| 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.4.prop1_cc_ref_max.smt2                                       |20.548MiB|20.548MiB|0B| 0.0%|
|QF_BV_bv8_bv_schedule_world.1.prop1_cc_ref_max.smt2                                         |19.016MiB|19.016MiB|0B| 0.0%|
|QF_BV_bv8_bv_swap_three_cc_ref_max.smt2                                                     |18.508MiB|18.508MiB|0B| 0.0%|
|QF_BV_bv_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                        |18.9MiB|18.9MiB|0B| 0.0%|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                              |18.764MiB|18.764MiB|0B| 0.0%|
|QF_BV_bv_bv_swap_two_cc_ref_max.smt2                                                        |18.252MiB|18.252MiB|0B| 0.0%|
|QF_BV_bv_bv_synabs_cc_ref_max.smt2                                                          |18.508MiB|18.508MiB|0B| 0.0%|
|QF_BV_counter_v_cc_ref_max.smt2                                                             |18.256MiB|18.256MiB|0B| 0.0%|
|QF_BV_protocols.1.prop1_cc_ref_max.smt2                                                     |18.76MiB|18.76MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|100.smt2                                                                                    |24.328MiB|24.328MiB|0B| 0.0%|
|102.smt2                                                                                    |25.436MiB|25.436MiB|0B| 0.0%|
|108.smt2                                                                                    |37.392MiB|37.392MiB|0B| 0.0%|
|20.smt2                                                                                     |24.296MiB|24.296MiB|0B| 0.0%|
|26.smt2                                                                                     |23.2MiB|23.2MiB|0B| 0.0%|
|41.smt2                                                                                     |22.412MiB|22.412MiB|0B| 0.0%|
|64.smt2                                                                                     |25.42MiB|25.42MiB|0B| 0.0%|
|80.smt2                                                                                     |25.44MiB|25.44MiB|0B| 0.0%|
|90.smt2                                                                                     |25.552MiB|25.552MiB|0B| 0.0%|
|94.smt2                                                                                     |25.452MiB|25.452MiB|0B| 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                       |19.232MiB|19.232MiB|0B| 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.4.prop1_cc_ref_max.smt2                                       |20.548MiB|20.548MiB|0B| 0.0%|
|QF_BV_bv8_bv_schedule_world.1.prop1_cc_ref_max.smt2                                         |19.016MiB|19.016MiB|0B| 0.0%|
|QF_BV_bv8_bv_swap_three_cc_ref_max.smt2                                                     |18.508MiB|18.508MiB|0B| 0.0%|
|QF_BV_bv_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                        |18.9MiB|18.9MiB|0B| 0.0%|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                              |18.764MiB|18.764MiB|0B| 0.0%|
|QF_BV_bv_bv_swap_two_cc_ref_max.smt2                                                        |18.252MiB|18.252MiB|0B| 0.0%|
|QF_BV_bv_bv_synabs_cc_ref_max.smt2                                                          |18.508MiB|18.508MiB|0B| 0.0%|
|QF_BV_counter_v_cc_ref_max.smt2                                                             |18.256MiB|18.256MiB|0B| 0.0%|
|QF_BV_protocols.1.prop1_cc_ref_max.smt2                                                     |18.76MiB|18.76MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|servers_slapd_a_vc149789.smt2                                                              |   2.742s |175.0MiB|
|sort.smt2                                                                                  |  19.940s |97.356MiB|
|smulov4bw1024.smt2                                                                         |   1.306s |88.32MiB|
|servers_slapd_a_vc149572.smt2                                                              |   1.364s |75.908MiB|
|ndist.b.28982.smt2                                                                         |   1.922s |72.956MiB|
|ndist.b.27984.smt2                                                                         |   1.974s |69.2MiB|
|bench_15547.smt2                                                                           |  19.420s |66.14MiB|
|bench_1013.smt2                                                                            |  19.857s |65.588MiB|
|fig5.phx.smt2                                                                              |  19.933s |61.564MiB|
|ndist.b.21996.smt2                                                                         |   1.150s |50.14MiB|
|bench_4261.smt2                                                                            |  19.690s |38.268MiB|
|111.smt2                                                                                   |   1.550s |37.472MiB|
|108.smt2                                                                                   |  19.488s |37.392MiB|
|run_00012.trace.cond_057573_0x16388_00.smt2                                                |   0.028s |35.324MiB|
|170.smt2                                                                                   |   0.524s |31.892MiB|
|162.smt2                                                                                   |   0.521s |31.76MiB|
|gryzzles.22.lp.smt2                                                                        |   0.106s |29.684MiB|
|bench_3945.smt2                                                                            |   0.099s |29.1MiB|
|knightTour.in01.smt2                                                                       |   0.098s |28.932MiB|
|gryzzles.8.lp.smt2                                                                         |   0.088s |28.3MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|servers_slapd_a_vc149789.smt2                                                              |   2.742s |175.0MiB|
|sort.smt2                                                                                  |  19.940s |97.356MiB|
|smulov4bw1024.smt2                                                                         |   1.306s |88.32MiB|
|servers_slapd_a_vc149572.smt2                                                              |   1.364s |75.908MiB|
|ndist.b.28982.smt2                                                                         |   1.922s |72.956MiB|
|ndist.b.27984.smt2                                                                         |   1.974s |69.2MiB|
|bench_15547.smt2                                                                           |  19.420s |66.14MiB|
|bench_1013.smt2                                                                            |  19.857s |65.588MiB|
|fig5.phx.smt2                                                                              |  19.933s |61.564MiB|
|ndist.b.21996.smt2                                                                         |   1.150s |50.14MiB|
|bench_4261.smt2                                                                            |  19.690s |38.268MiB|
|111.smt2                                                                                   |   1.550s |37.472MiB|
|108.smt2                                                                                   |  19.488s |37.392MiB|
|run_00012.trace.cond_057573_0x16388_00.smt2                                                |   0.028s |35.324MiB|
|170.smt2                                                                                   |   0.524s |31.892MiB|
|162.smt2                                                                                   |   0.521s |31.76MiB|
|gryzzles.22.lp.smt2                                                                        |   0.106s |29.684MiB|
|bench_3945.smt2                                                                            |   0.099s |29.1MiB|
|knightTour.in01.smt2                                                                       |   0.098s |28.932MiB|
|gryzzles.8.lp.smt2                                                                         |   0.088s |28.3MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|100.smt2                                                                                    |  19.739s  |  19.739s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.516s  |  19.516s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.488s  |  19.488s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.571s  |  19.571s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  19.822s  |  19.822s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.688s  |  19.688s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  19.588s  |  19.588s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  19.439s  |  19.439s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  19.455s  |  19.455s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                       |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.4.prop1_cc_ref_max.smt2                                       |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_schedule_world.1.prop1_cc_ref_max.smt2                                         |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_swap_three_cc_ref_max.smt2                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                        |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_swap_two_cc_ref_max.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_synabs_cc_ref_max.smt2                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_BV_counter_v_cc_ref_max.smt2                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_protocols.1.prop1_cc_ref_max.smt2                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|VS3-benchmark-S1.smt2                                                                       |  19.699s  |  19.699s  |   0.000s  | 0.0%|
|a128test0016.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a167test0001.smt2                                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|a185test0001.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a208test0005.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a213test0012.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a214test0017.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a217test0011.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a324test0010.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a330test0007.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a331test0008.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a333test0009.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a335test0041.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a392test0051.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a393test0014.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a397test0029.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a402test0032.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|a406test0030.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a407test0024.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a409test0002.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a421test0007.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a423test0008.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a430test0028.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a434test0027.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a448test0003.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a479test0010.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a494test0007.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a497test0020.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a55test0003.smt2                                                                            |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a58test0007.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a600test0040.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a60test0004.smt2                                                                            |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a614test0091.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a623test0035.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a631test0073.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a653test0023.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a657test0107.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a658test0026.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a663test0096.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a683test0094.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a97test0001.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|adpcm.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|b188test0002.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|b265test0001.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1013.smt2                                                                             |  19.857s  |  19.857s  |   0.000s  | 0.0%|
|bench_1017.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_10306.smt2                                                                            |  19.591s  |  19.591s  |   0.000s  | 0.0%|
|bench_1041.smt2                                                                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|bench_1053.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1055.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1059.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1094.smt2                                                                             |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|bench_1123.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_1143.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_11736.smt2                                                                            |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench_1187.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_119.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_11971.smt2                                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|bench_120.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1201.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1233.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_1253.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1280.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1283.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1285.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_129.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_13147.smt2                                                                            |  19.802s  |  19.802s  |   0.000s  | 0.0%|
|bench_1323.smt2                                                                             |   9.999s  |   9.999s  |   0.000s  | 0.0%|
|bench_13284.smt2                                                                            |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|bench_1329.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_1338.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1367.smt2                                                                             |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|bench_1386.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1391.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1405.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_14358.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1442.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1453.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1455.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_14595.smt2                                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1470.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_14885.smt2                                                                            |   7.630s  |   7.630s  |   0.000s  | 0.0%|
|bench_1495.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_15.smt2                                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_15547.smt2                                                                            |  19.420s  |  19.420s  |   0.000s  | 0.0%|
|bench_160.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1629.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_163.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1630.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_165.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1665.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_168.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1697.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_1720.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1739.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1748.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1756.smt2                                                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|bench_1757.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1759.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_1770.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1778.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_179.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1811.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_1858.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_1863.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1864.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1869.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1873.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1882.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1888.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1900.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1904.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1905.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1946.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_1957.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1963.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1976.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_1996.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_200.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2021.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_204.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2044.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2067.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2070.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2072.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2075.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2108.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2113.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_2117.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2129.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_214.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2148.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2149.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2150.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2175.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2188.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2192.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2264.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2291.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2293.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_2295.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_2304.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_2308.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2309.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_2312.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2326.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_2327.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_234.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2351.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2358.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_238.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2384.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2386.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2400.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2406.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2420.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_243.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2431.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2432.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2435.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2493.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2517.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2521.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2524.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2548.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2550.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2551.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2552.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2558.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_259.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2612.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2635.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2645.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2650.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2671.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2676.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2688.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2701.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2704.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2710.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2717.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2727.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2729.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2737.smt2                                                                             |  19.863s  |  19.863s  |   0.000s  | 0.0%|
|bench_2750.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2755.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2779.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2811.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2839.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_285.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_288.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_290.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_295.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_296.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2983.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_301.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3018.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_302.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_303.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3048.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_306.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3062.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_3068.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3087.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3094.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3103.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_317.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3206.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3268.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3308.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3329.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3333.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3335.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_3338.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3339.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3352.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3358.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3394.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3416.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3421.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3431.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3446.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_3476.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_348.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3489.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3509.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3516.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_353.smt2                                                                              |  19.774s  |  19.774s  |   0.000s  | 0.0%|
|bench_3539.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3551.smt2                                                                             |  19.383s  |  19.383s  |   0.000s  | 0.0%|
|bench_3558.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3578.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3623.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3636.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3672.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_3681.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3688.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3689.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3697.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3707.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3715.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3719.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3721.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_375.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3750.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3754.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3755.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3757.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_3765.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3787.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3799.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3813.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3818.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3832.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3838.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3846.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3866.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3879.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3881.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3882.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3886.smt2                                                                             |  19.414s  |  19.414s  |   0.000s  | 0.0%|
|bench_3888.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3890.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3894.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3915.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3926.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3936.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3937.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3945.smt2                                                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|bench_3951.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3963.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3964.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3992.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3995.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3997.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4010.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4019.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4021.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4023.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4031.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4040.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4051.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4058.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4069.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4097.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4099.smt2                                                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|bench_4112.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4115.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4137.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4141.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4143.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4154.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4156.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4157.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4160.smt2                                                                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|bench_4164.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4170.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4175.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4192.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4208.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4219.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4220.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4231.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4233.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4261.smt2                                                                             |  19.690s  |  19.690s  |   0.000s  | 0.0%|
|bench_4273.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4275.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4279.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4304.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4312.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4313.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4319.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4321.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4340.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4346.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4350.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4352.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4356.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4359.smt2                                                                             |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|bench_436.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4368.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4375.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4387.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4390.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4397.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4412.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4444.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4447.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4472.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4477.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4494.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4505.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4508.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4516.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4518.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4520.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4522.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4526.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4553.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4555.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_456.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4560.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4565.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4568.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_457.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4576.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4580.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4581.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4583.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4605.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4607.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4617.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4635.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4642.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4644.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4650.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4654.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4662.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4669.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_4689.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4692.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4696.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4706.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4725.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_4728.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4738.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4740.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4753.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4755.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4768.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_4775.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4788.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4813.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_4818.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4820.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4822.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4834.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4838.smt2                                                                             |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|bench_4839.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4840.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4879.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_489.smt2                                                                              |  19.627s  |  19.627s  |   0.000s  | 0.0%|
|bench_4890.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4900.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4906.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4908.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_4920.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4921.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4954.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4964.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4965.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4968.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_497.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4971.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4985.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4990.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5.smt2                                                                                |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_500.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5005.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5030.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5034.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5037.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5041.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5084.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5086.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5123.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5127.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5131.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5139.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_5150.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5153.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_5154.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5155.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5159.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5165.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5170.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5183.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5187.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5188.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_5190.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5192.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5209.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5210.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5218.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5222.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5234.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5236.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5238.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5257.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5261.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_527.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5309.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5326.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5332.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_535.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_536.smt2                                                                              |  19.472s  |  19.472s  |   0.000s  | 0.0%|
|bench_5360.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5392.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5408.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5417.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5432.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5440.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5449.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5459.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5536.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5543.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5613.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5623.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5636.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5645.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5649.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_565.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5658.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5662.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5666.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_5674.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5744.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5752.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5765.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_631.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_639.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6560.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_6699.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6713.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6731.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_6734.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_6742.smt2                                                                             |  14.641s  |  14.641s  |   0.000s  | 0.0%|
|bench_6756.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6765.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6813.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_6826.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6828.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6830.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6837.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6843.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6848.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_685.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6854.smt2                                                                             |   2.585s  |   2.585s  |   0.000s  | 0.0%|
|bench_6857.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_6861.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_6866.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6867.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_6882.smt2                                                                             |  10.943s  |  10.943s  |   0.000s  | 0.0%|
|bench_6886.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6898.smt2                                                                             |  19.601s  |  19.601s  |   0.000s  | 0.0%|
|bench_6901.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_6902.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6906.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_6908.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_6911.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_6917.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_6923.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6924.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_6929.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6938.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_6943.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6953.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6954.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6966.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6973.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6986.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6987.smt2                                                                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|bench_6998.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_702.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7021.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7033.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_706.smt2                                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_7082.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7083.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7086.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7088.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7095.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_710.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7119.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7127.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_7138.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7139.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7140.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7142.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7146.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7166.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7182.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7185.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7188.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7219.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7229.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7233.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7242.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7270.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7274.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7278.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7304.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7310.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7314.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_7319.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7329.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7331.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7339.smt2                                                                             |   0.916s  |   0.916s  |   0.000s  | 0.0%|
|bench_7357.smt2                                                                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|bench_7375.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7382.smt2                                                                             |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|bench_7383.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_7388.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7406.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7412.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7415.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7421.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7438.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7454.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7465.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_748.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7489.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7494.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7495.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7496.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7498.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7517.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7523.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7528.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_753.smt2                                                                              |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|bench_7532.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7534.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7537.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7539.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7550.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7552.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7556.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7563.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7565.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7573.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7575.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_76.smt2                                                                               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7601.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7612.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7627.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7633.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7636.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7641.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7642.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7655.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7663.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7670.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7671.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7673.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7686.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7696.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7705.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7708.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7714.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7729.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_7736.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7749.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7754.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7758.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7765.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_78.smt2                                                                               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7800.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7807.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7811.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7819.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_7823.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7826.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7828.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7832.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7834.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7863.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7867.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_787.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7872.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7878.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7881.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_789.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7943.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_796.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7973.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8019.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8030.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8042.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8049.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8051.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_8053.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8054.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8055.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8070.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8073.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_808.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8082.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_8084.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8088.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8093.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8103.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8110.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8116.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8117.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8165.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8170.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_820.smt2                                                                              |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_8200.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8228.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8234.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8245.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8260.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_8271.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8282.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8283.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8289.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8296.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8298.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8306.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8309.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_831.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8315.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8320.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8357.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_8379.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_838.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8393.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_8394.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8487.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8492.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8507.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_864.smt2                                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_868.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_881.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_883.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_900.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_91.smt2                                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_919.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_92.smt2                                                                               |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_926.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_938.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_941.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_944.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_954.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_957.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_961.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_965.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_975.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_98.smt2                                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_988.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_991.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_993.smt2                                                                              |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|bgpd_bgpd_vc76751.smt2                                                                      |   1.121s  |   1.121s  |   0.000s  | 0.0%|
|bgpd_bgpd_vc76752.smt2                                                                      |   0.515s  |   0.515s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331044.smt2                                                               |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331082.smt2                                                               |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225324.smt2                                                                 |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232137.smt2                                                                 |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232138.smt2                                                                 |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5285.smt2                                                            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|bvsdiv.smt2                                                                                 |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|fig5.phx.smt2                                                                               |  19.933s  |  19.933s  |   0.000s  | 0.0%|
|inf1.smt2                                                                                   |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|matrixsqrt.smt2                                                                             |  19.600s  |  19.600s  |   0.000s  | 0.0%|
|ndist.b.21996.smt2                                                                          |   1.150s  |   1.150s  |   0.000s  | 0.0%|
|ndist.b.27984.smt2                                                                          |   1.974s  |   1.974s  |   0.000s  | 0.0%|
|ndist.b.28982.smt2                                                                          |   1.922s  |   1.922s  |   0.000s  | 0.0%|
|predicate_1245.smt2                                                                         |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|predicate_2801.smt2                                                                         |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|problem_9.smt2                                                                              |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|rand_65_500_1235857888_0_k-6_sat.gph.smt2                                                   |  19.533s  |  19.533s  |   0.000s  | 0.0%|
|rand_80_500_1235848939_0_k-9_sat.gph.smt2                                                   |  19.492s  |  19.492s  |   0.000s  | 0.0%|
|rfunit_flat-64.smt2                                                                         |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__011273.smt2                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__018344.smt2                                                     |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__019220.smt2                                                     |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__020079.smt2                                                     |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|run_00000.trace.cond_016653_0x95026e6_00.smt2                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|run_00000.trace.cond_017116_0x950130a_00.smt2                                               |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|run_00000.trace.cond_017924_0x950130a_00.smt2                                               |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|run_00000.trace.cond_018783_0x950130a_00.smt2                                               |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|run_00000.trace.cond_019196_0x95026e6_00.smt2                                               |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|run_00000.trace.cond_019659_0x950130a_00.smt2                                               |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|run_00000.trace.cond_020055_0x95026e6_00.smt2                                               |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|run_00000.trace.cond_285172_0xe7af40_00.smt2                                                |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|run_00000.trace.cond_285198_0xe7af87_00.smt2                                                |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|run_00000.trace.cond_455476_0xe7af69_00.smt2                                                |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|run_00012.trace.cond_057573_0x16388_00.smt2                                                 |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|run_03230.trace.cond_000028_0x40201f_00.smt2                                                |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|run_03230.trace.cond_000032_0x40248d_00.smt2                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011742_0x4066e2_00.smt2                                                |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025442_0x41821d_00.smt2                                                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025506_0x41821d_00.smt2                                                |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025570_0x41821d_00.smt2                                                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025600_0x41821d_00.smt2                                                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|sort.smt2                                                                                   |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|src_wget_vc18169.smt2                                                                       |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|try3_noof_functions_dwp_stty.visible.il.dwp.smt2                                            |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|try3_noof_functions_dwp_touch.yyerror.il.dwp.smt2                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_cut.hash_int.il.dwp.smt2                                      |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_expr.nomoreargs.il.dwp.smt2                                   |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_stty.visible.il.dwp.smt2                                      |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_cat.quoting_options_from_style.il.flanagansaxe.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_chgrp.quoting_options_from_style.il.flanagansaxe.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_cut.hash_int.il.flanagansaxe.smt2                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_echo.quoting_options_from_style.il.flanagansaxe.smt2  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_env.quoting_options_from_style.il.flanagansaxe.smt2  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_fold.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_hostid.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_kill.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_link.quoting_options_from_style.il.flanagansaxe.smt2  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_mkfifo.quoting_options_from_style.il.flanagansaxe.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_nice.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_nl.quoting_options_from_style.il.flanagansaxe.smt2   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_pinky.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_ptx.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_seq.quoting_options_from_style.il.flanagansaxe.smt2  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_sleep.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_sum.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tac.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_test.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_touch.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_true.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tsort.quoting_options_from_style.il.flanagansaxe.smt2  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tty.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_unexpand.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_users.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_vdir.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_wc.quoting_options_from_style.il.flanagansaxe.smt2   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_noof_functions_fse-bfs_shuf.input_numbers_option_used.il.fse-bfs.smt2            |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_true_functions_dwp_stty.visible.il.dwp.smt2                                      |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_true_functions_dwp_yes.close_stdout_set_file_name.il.dwp.smt2                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_chgrp.i_ring_init.il.flanagansaxe.smt2               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_join.initseq.il.flanagansaxe.smt2                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_md5sum.md5_init_ctx.il.flanagansaxe.smt2             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_sha1sum.sha1_read_ctx.il.flanagansaxe.smt2           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_stty.visible.il.flanagansaxe.smt2                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_tac.rpl_re_set_syntax.il.flanagansaxe.smt2           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_vdir.hash_get_n_entries.il.flanagansaxe.smt2         |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_vdir.unsigned_file_size.il.flanagansaxe.smt2         |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_true_functions_fse-bfs_stty.visible.il.fse-bfs.smt2                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|unconstrained04.smt2                                                                        |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|unconstrained07.smt2                                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|unconstrained08.smt2                                                                        |   0.009s  |   0.009s  |   0.000s  | 0.0%|
</details>
