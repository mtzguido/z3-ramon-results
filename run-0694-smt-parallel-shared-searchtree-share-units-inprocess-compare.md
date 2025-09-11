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
Job tag: smt-parallel-shared-searchtree-share-units-inprocess
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: dcd947f5efccc74c5a616d80e3ee4075148304ae
Z3 branch: ilana
Z3 options: "-T:30 tactic.default_tactic=smt smt.threads=4 smt_parallel.searchtree=true smt_parallel.share_conflicts=false smt_parallel.share_units=true smt_parallel.cube_initial_only=true smt_parallel.inprocess=true smt_parallel.inprocess_delay=10"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: work on inprocessing

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-parallel-shared-searchtree-share-units-inprocess
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: dcd947f5efccc74c5a616d80e3ee4075148304ae
Z3 branch: ilana
Z3 options: "-T:30 tactic.default_tactic=smt smt.threads=4 smt_parallel.searchtree=true smt_parallel.share_conflicts=false smt_parallel.share_units=true smt_parallel.cube_initial_only=true smt_parallel.inprocess=true smt_parallel.inprocess_delay=10"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: work on inprocessing

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
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2               |   0.029s |1788.0KiB|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                |   0.029s |1560.0KiB|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                  |   0.028s |1560.0KiB|
|From_T2__p.t2__terminationS_3_0.smt2                                                       |   0.028s |1560.0KiB|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                     |   0.028s |1788.0KiB|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                    |   0.027s |1560.0KiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                             |   0.027s |1560.0KiB|
|problem-000124.cvc.1.smt2                                                                  |   0.026s |1788.0KiB|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                              |   0.026s |1788.0KiB|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                       |   0.026s |1560.0KiB|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                               |   0.025s |1560.0KiB|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                     |   0.025s |1560.0KiB|
|aproveSMT4439607947222714793.smt2                                                          |   0.024s |1776.0KiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2            |   0.024s |1560.0KiB|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                    |   0.024s |1556.0KiB|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                           |   0.024s |1560.0KiB|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                            |   0.024s |1560.0KiB|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                     |   0.024s |1560.0KiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      |   0.023s |1788.0KiB|
|term-fu8ErM.smt2                                                                           |   0.023s |1560.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2               |   0.029s |1788.0KiB|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                |   0.029s |1560.0KiB|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                  |   0.028s |1560.0KiB|
|From_T2__p.t2__terminationS_3_0.smt2                                                       |   0.028s |1560.0KiB|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                     |   0.028s |1788.0KiB|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                    |   0.027s |1560.0KiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                             |   0.027s |1560.0KiB|
|problem-000124.cvc.1.smt2                                                                  |   0.026s |1788.0KiB|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                              |   0.026s |1788.0KiB|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                       |   0.026s |1560.0KiB|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                               |   0.025s |1560.0KiB|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                     |   0.025s |1560.0KiB|
|aproveSMT4439607947222714793.smt2                                                          |   0.024s |1776.0KiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2            |   0.024s |1560.0KiB|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                    |   0.024s |1556.0KiB|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                           |   0.024s |1560.0KiB|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                            |   0.024s |1560.0KiB|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                     |   0.024s |1560.0KiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      |   0.023s |1788.0KiB|
|term-fu8ErM.smt2                                                                           |   0.023s |1560.0KiB|
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
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                    |   0.005s |1816.0KiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                          |   0.004s |1796.0KiB|
|aproveSMT8205772230016192248.smt2                                                          |   0.007s |1792.0KiB|
|problem-006542.cvc.1.smt2                                                                  |   0.007s |1792.0KiB|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                    |   0.007s |1792.0KiB|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                           |   0.004s |1792.0KiB|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                           |   0.004s |1792.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2               |   0.003s |1792.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2               |   0.029s |1788.0KiB|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                     |   0.028s |1788.0KiB|
|problem-000124.cvc.1.smt2                                                                  |   0.026s |1788.0KiB|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                              |   0.026s |1788.0KiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      |   0.023s |1788.0KiB|
|1607.smt2                                                                                  |   0.020s |1788.0KiB|
|1901.smt2                                                                                  |   0.020s |1788.0KiB|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                    |   0.019s |1788.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2              |   0.008s |1788.0KiB|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                    |   0.007s |1788.0KiB|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                |   0.007s |1788.0KiB|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                     |   0.007s |1788.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                    |   0.005s |1816.0KiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                          |   0.004s |1796.0KiB|
|aproveSMT8205772230016192248.smt2                                                          |   0.007s |1792.0KiB|
|problem-006542.cvc.1.smt2                                                                  |   0.007s |1792.0KiB|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                    |   0.007s |1792.0KiB|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                           |   0.004s |1792.0KiB|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                           |   0.004s |1792.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2               |   0.003s |1792.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2               |   0.029s |1788.0KiB|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                     |   0.028s |1788.0KiB|
|problem-000124.cvc.1.smt2                                                                  |   0.026s |1788.0KiB|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                              |   0.026s |1788.0KiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      |   0.023s |1788.0KiB|
|1607.smt2                                                                                  |   0.020s |1788.0KiB|
|1901.smt2                                                                                  |   0.020s |1788.0KiB|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                    |   0.019s |1788.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2              |   0.008s |1788.0KiB|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                    |   0.007s |1788.0KiB|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                |   0.007s |1788.0KiB|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                     |   0.007s |1788.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
