Comparing data and data


# SUMMARY
- LHS tests = 2313
- RHS tests = 2313
- LHS success = 0  (0.0%)
- RHS success = 0  (0.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: par
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: f86702a49b9757cae6025dab1305579681e83e9c
Z3 branch: par
Z3 options: "-T:30 tactic.default_tactic=smt smt.threads=4 smt_parallel.searchtree=true smt_parallel.share_conflicts=false smt_parallel.share_units=true smt_parallel.cube_initial_only=true smt_parallel.inprocessing=true smt_parallel.inprocessing_delay=0"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: neat

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: par
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: f86702a49b9757cae6025dab1305579681e83e9c
Z3 branch: par
Z3 options: "-T:30 tactic.default_tactic=smt smt.threads=4 smt_parallel.searchtree=true smt_parallel.share_conflicts=false smt_parallel.share_units=true smt_parallel.cube_initial_only=true smt_parallel.inprocessing=true smt_parallel.inprocessing_delay=0"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: neat

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                           |   0.034s |1788.0KiB|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                 |   0.031s |1788.0KiB|
|aproveSMT1256079449125527892.smt2                                                          |   0.031s |1788.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2               |   0.030s |1560.0KiB|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                            |   0.029s |1788.0KiB|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2               |   0.029s |1560.0KiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2            |   0.029s |1560.0KiB|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                     |   0.029s |1560.0KiB|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                       |   0.028s |1788.0KiB|
|aproveSMT1022543817592849705.smt2                                                          |   0.028s |1560.0KiB|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                     |   0.028s |1780.0KiB|
|1361.smt2                                                                                  |   0.027s |1576.0KiB|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                               |   0.027s |1560.0KiB|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                      |   0.027s |1788.0KiB|
|aproveSMT7440630011441673394.smt2                                                          |   0.027s |1560.0KiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2            |   0.027s |1560.0KiB|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                    |   0.027s |1560.0KiB|
|aproveSMT2807471946702649636.smt2                                                          |   0.027s |1564.0KiB|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.027s |1560.0KiB|
|aproveSMT1697563446985587562.smt2                                                          |   0.027s |1560.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                           |   0.034s |1788.0KiB|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                 |   0.031s |1788.0KiB|
|aproveSMT1256079449125527892.smt2                                                          |   0.031s |1788.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2               |   0.030s |1560.0KiB|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                            |   0.029s |1788.0KiB|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2               |   0.029s |1560.0KiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2            |   0.029s |1560.0KiB|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                     |   0.029s |1560.0KiB|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                       |   0.028s |1788.0KiB|
|aproveSMT1022543817592849705.smt2                                                          |   0.028s |1560.0KiB|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                     |   0.028s |1780.0KiB|
|1361.smt2                                                                                  |   0.027s |1576.0KiB|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                               |   0.027s |1560.0KiB|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                      |   0.027s |1788.0KiB|
|aproveSMT7440630011441673394.smt2                                                          |   0.027s |1560.0KiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2            |   0.027s |1560.0KiB|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                    |   0.027s |1560.0KiB|
|aproveSMT2807471946702649636.smt2                                                          |   0.027s |1564.0KiB|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.027s |1560.0KiB|
|aproveSMT1697563446985587562.smt2                                                          |   0.027s |1560.0KiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__s1.t2__p18422_safety_0.smt2                                                       |   0.008s |2008.0KiB|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                 |   0.006s |1844.0KiB|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                       |   0.004s |1832.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2               |   0.004s |1824.0KiB|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                             |   0.004s |1812.0KiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                      |   0.006s |1804.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2               |   0.004s |1804.0KiB|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                        |   0.007s |1792.0KiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                |   0.006s |1792.0KiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                   |   0.006s |1792.0KiB|
|167.smt2                                                                                   |   0.006s |1792.0KiB|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                              |   0.005s |1792.0KiB|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                            |   0.004s |1792.0KiB|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                         |   0.004s |1792.0KiB|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                        |   0.004s |1792.0KiB|
|aproveSMT144364303553946193.smt2                                                           |   0.004s |1792.0KiB|
|192.smt2                                                                                   |   0.004s |1792.0KiB|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2         |   0.004s |1792.0KiB|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                           |   0.034s |1788.0KiB|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                 |   0.031s |1788.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__s1.t2__p18422_safety_0.smt2                                                       |   0.008s |2008.0KiB|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                 |   0.006s |1844.0KiB|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                       |   0.004s |1832.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2               |   0.004s |1824.0KiB|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                             |   0.004s |1812.0KiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                      |   0.006s |1804.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2               |   0.004s |1804.0KiB|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                        |   0.007s |1792.0KiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                |   0.006s |1792.0KiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                   |   0.006s |1792.0KiB|
|167.smt2                                                                                   |   0.006s |1792.0KiB|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                              |   0.005s |1792.0KiB|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                            |   0.004s |1792.0KiB|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                         |   0.004s |1792.0KiB|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                        |   0.004s |1792.0KiB|
|aproveSMT144364303553946193.smt2                                                           |   0.004s |1792.0KiB|
|192.smt2                                                                                   |   0.004s |1792.0KiB|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2         |   0.004s |1792.0KiB|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                           |   0.034s |1788.0KiB|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                 |   0.031s |1788.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
