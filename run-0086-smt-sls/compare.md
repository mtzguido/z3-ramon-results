Comparing data and data


# SUMMARY
- LHS tests = 1341
- RHS tests = 1341
- LHS success = 0  (0.0%)
- RHS success = 0  (0.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fa6f3f2dba89c2c44282f10c468e7482972a9bdd
Z3 branch: sls
Z3 options: "-T:20 -v:2 smt.sls.enable=true smt.sls.parallel=false sat.smt=false -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_SAT
Z3 commit message: fixing prop-queue

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fa6f3f2dba89c2c44282f10c468e7482972a9bdd
Z3 branch: sls
Z3 options: "-T:20 -v:2 smt.sls.enable=true smt.sls.parallel=false sat.smt=false -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_SAT
Z3 commit message: fixing prop-queue

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
|aproveSMT1709482801492808359.smt2                                                          |   0.005s |1092.0KiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                      |   0.005s |944.0KiB|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                    |   0.005s |1076.0KiB|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                     |   0.004s |1096.0KiB|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                        |   0.004s |1120.0KiB|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                            |   0.004s |1136.0KiB|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                         |   0.004s |956.0KiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                   |   0.004s |928.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2              |   0.004s |1096.0KiB|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                     |   0.004s |1108.0KiB|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                             |   0.004s |1072.0KiB|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                     |   0.004s |1096.0KiB|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                |   0.004s |1096.0KiB|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                               |   0.004s |1128.0KiB|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                          |   0.004s |1096.0KiB|
|574.smt2                                                                                   |   0.004s |964.0KiB|
|aproveSMT7377887083439038055.smt2                                                          |   0.004s |1092.0KiB|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                          |   0.003s |1100.0KiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                          |   0.003s |1100.0KiB|
|aproveSMT1261041288686639410.smt2                                                          |   0.003s |1092.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|aproveSMT1709482801492808359.smt2                                                          |   0.005s |1092.0KiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                      |   0.005s |944.0KiB|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                    |   0.005s |1076.0KiB|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                     |   0.004s |1096.0KiB|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                        |   0.004s |1120.0KiB|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                            |   0.004s |1136.0KiB|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                         |   0.004s |956.0KiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                   |   0.004s |928.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2              |   0.004s |1096.0KiB|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                     |   0.004s |1108.0KiB|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                             |   0.004s |1072.0KiB|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                     |   0.004s |1096.0KiB|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                |   0.004s |1096.0KiB|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                               |   0.004s |1128.0KiB|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                          |   0.004s |1096.0KiB|
|574.smt2                                                                                   |   0.004s |964.0KiB|
|aproveSMT7377887083439038055.smt2                                                          |   0.004s |1092.0KiB|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                          |   0.003s |1100.0KiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                          |   0.003s |1100.0KiB|
|aproveSMT1261041288686639410.smt2                                                          |   0.003s |1092.0KiB|
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
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2            |   0.002s |1356.0KiB|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                     |   0.002s |1352.0KiB|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                     |   0.002s |1352.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2               |   0.002s |1352.0KiB|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2              |   0.001s |1352.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2              |   0.001s |1352.0KiB|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                   |   0.002s |1336.0KiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       |   0.001s |1308.0KiB|
|problem-005897.cvc.1.smt2                                                                  |   0.002s |1300.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2              |   0.002s |1296.0KiB|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                    |   0.001s |1268.0KiB|
|From_T2__edn.t2__p19793_safety_0.smt2                                                      |   0.003s |1232.0KiB|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                         |   0.001s |1220.0KiB|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                |   0.002s |1144.0KiB|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                 |   0.002s |1144.0KiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                      |   0.002s |1144.0KiB|
|aproveSMT9190658207098859112.smt2                                                          |   0.002s |1144.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2               |   0.003s |1140.0KiB|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                       |   0.002s |1140.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2               |   0.002s |1140.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2            |   0.002s |1356.0KiB|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                     |   0.002s |1352.0KiB|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                     |   0.002s |1352.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2               |   0.002s |1352.0KiB|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2              |   0.001s |1352.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2              |   0.001s |1352.0KiB|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                   |   0.002s |1336.0KiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       |   0.001s |1308.0KiB|
|problem-005897.cvc.1.smt2                                                                  |   0.002s |1300.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2              |   0.002s |1296.0KiB|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                    |   0.001s |1268.0KiB|
|From_T2__edn.t2__p19793_safety_0.smt2                                                      |   0.003s |1232.0KiB|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                         |   0.001s |1220.0KiB|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                |   0.002s |1144.0KiB|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                 |   0.002s |1144.0KiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                      |   0.002s |1144.0KiB|
|aproveSMT9190658207098859112.smt2                                                          |   0.002s |1144.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2               |   0.003s |1140.0KiB|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                       |   0.002s |1140.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2               |   0.002s |1140.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
