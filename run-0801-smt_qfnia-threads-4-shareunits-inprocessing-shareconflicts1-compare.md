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
Job tag: smt_qfnia-threads-4-shareunits-inprocessing-shareconflicts1
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 26119a88154a77e05984d35baabd0a52992c356f
Z3 branch: parallel-lockdebug1
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.share_units=true smt_parallel.inprocessing=true smt_parallel.share_conflicts=true"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfnia-threads-4-shareunits-inprocessing-shareconflicts1
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 26119a88154a77e05984d35baabd0a52992c356f
Z3 branch: parallel-lockdebug1
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.share_units=true smt_parallel.inprocessing=true smt_parallel.share_conflicts=true"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: clean up code

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
|aproveSMT8204649684904954337.smt2                                                          |   0.031s |1560.0KiB|
|1785.smt2                                                                                  |   0.031s |1792.0KiB|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                     |   0.030s |1560.0KiB|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                               |   0.030s |1560.0KiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                   |   0.030s |1776.0KiB|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                      |   0.030s |1560.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2              |   0.029s |1788.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2               |   0.029s |1788.0KiB|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                       |   0.029s |1788.0KiB|
|aproveSMT6030602863271290399.smt2                                                          |   0.029s |1560.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                 |   0.029s |1780.0KiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                      |   0.027s |1788.0KiB|
|aproveSMT578728211229400351.smt2                                                           |   0.027s |1560.0KiB|
|1244.smt2                                                                                  |   0.027s |1788.0KiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                      |   0.027s |1552.0KiB|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                  |   0.027s |1560.0KiB|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                     |   0.026s |1560.0KiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |   0.025s |1560.0KiB|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                |   0.025s |1788.0KiB|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.025s |1560.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|aproveSMT8204649684904954337.smt2                                                          |   0.031s |1560.0KiB|
|1785.smt2                                                                                  |   0.031s |1792.0KiB|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                     |   0.030s |1560.0KiB|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                               |   0.030s |1560.0KiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                   |   0.030s |1776.0KiB|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                      |   0.030s |1560.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2              |   0.029s |1788.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2               |   0.029s |1788.0KiB|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                       |   0.029s |1788.0KiB|
|aproveSMT6030602863271290399.smt2                                                          |   0.029s |1560.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                 |   0.029s |1780.0KiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                      |   0.027s |1788.0KiB|
|aproveSMT578728211229400351.smt2                                                           |   0.027s |1560.0KiB|
|1244.smt2                                                                                  |   0.027s |1788.0KiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                      |   0.027s |1552.0KiB|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                  |   0.027s |1560.0KiB|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                     |   0.026s |1560.0KiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |   0.025s |1560.0KiB|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                |   0.025s |1788.0KiB|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.025s |1560.0KiB|
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
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                    |   0.023s |1836.0KiB|
|aproveSMT4817399800518468578.smt2                                                          |   0.004s |1828.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2              |   0.004s |1804.0KiB|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                     |   0.004s |1796.0KiB|
|1785.smt2                                                                                  |   0.031s |1792.0KiB|
|aproveSMT4790304217385820014.smt2                                                          |   0.023s |1792.0KiB|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                 |   0.005s |1792.0KiB|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                            |   0.004s |1792.0KiB|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                       |   0.004s |1792.0KiB|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2              |   0.004s |1792.0KiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                   |   0.004s |1792.0KiB|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                     |   0.003s |1792.0KiB|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                |   0.003s |1792.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2              |   0.029s |1788.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2               |   0.029s |1788.0KiB|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                       |   0.029s |1788.0KiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                      |   0.027s |1788.0KiB|
|1244.smt2                                                                                  |   0.027s |1788.0KiB|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                |   0.025s |1788.0KiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                          |   0.024s |1788.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                    |   0.023s |1836.0KiB|
|aproveSMT4817399800518468578.smt2                                                          |   0.004s |1828.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2              |   0.004s |1804.0KiB|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                     |   0.004s |1796.0KiB|
|1785.smt2                                                                                  |   0.031s |1792.0KiB|
|aproveSMT4790304217385820014.smt2                                                          |   0.023s |1792.0KiB|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                 |   0.005s |1792.0KiB|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                            |   0.004s |1792.0KiB|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                       |   0.004s |1792.0KiB|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2              |   0.004s |1792.0KiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                   |   0.004s |1792.0KiB|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                     |   0.003s |1792.0KiB|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                |   0.003s |1792.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2              |   0.029s |1788.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2               |   0.029s |1788.0KiB|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                       |   0.029s |1788.0KiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                      |   0.027s |1788.0KiB|
|1244.smt2                                                                                  |   0.027s |1788.0KiB|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                |   0.025s |1788.0KiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                          |   0.024s |1788.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
