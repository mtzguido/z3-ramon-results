Comparing data and data


# SUMMARY
- LHS tests = 1341
- RHS tests = 1341
- LHS success = 1341  (100.0%)
- RHS success = 1341  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: old-smt
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: f902feb47834dc915f955d85923fded970e5bf86
Z3 branch: sls
Z3 options: "-T:20 -v:2  -st tactic.default_tactic="(then smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_SAT
Z3 commit message: reorder inclusion order to define smt_context before theory_sls

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: old-smt
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: f902feb47834dc915f955d85923fded970e5bf86
Z3 branch: sls
Z3 options: "-T:20 -v:2  -st tactic.default_tactic="(then smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_SAT
Z3 commit message: reorder inclusion order to define smt_context before theory_sls

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.031s  |   0.031s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.031s  |   0.031s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.031s  |   0.031s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.031s  |   0.031s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  20.024s |370.0MiB|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                 |  20.023s |303.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  20.018s |343.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                |  20.014s |275.0MiB|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                |  20.013s |232.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          |  20.012s |268.0MiB|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                            |  20.011s |194.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                          |  20.011s |76.028MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              |  20.011s |258.0MiB|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                            |  20.009s |190.0MiB|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                |  20.009s |119.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                 |  20.008s |123.0MiB|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                 |  20.008s |179.0MiB|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                              |  20.008s |181.0MiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       |  20.007s |175.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                          |  20.007s |99.228MiB|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                              |  20.007s |214.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                   |  20.007s |100.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2               |  20.006s |107.0MiB|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                              |  20.006s |107.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  20.024s |370.0MiB|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                 |  20.023s |303.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  20.018s |343.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                |  20.014s |275.0MiB|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                |  20.013s |232.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          |  20.012s |268.0MiB|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                            |  20.011s |194.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                          |  20.011s |76.028MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              |  20.011s |258.0MiB|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                            |  20.009s |190.0MiB|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                |  20.009s |119.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                 |  20.008s |123.0MiB|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                 |  20.008s |179.0MiB|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                              |  20.008s |181.0MiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       |  20.007s |175.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                          |  20.007s |99.228MiB|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                              |  20.007s |214.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                   |  20.007s |100.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2               |  20.006s |107.0MiB|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                              |  20.006s |107.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |25.96MiB|25.96MiB|0B| 0.0%|
|1010.smt2                                                                                   |29.772MiB|29.772MiB|0B| 0.0%|
|1018.smt2                                                                                   |22.032MiB|22.032MiB|0B| 0.0%|
|1021.smt2                                                                                   |22.652MiB|22.652MiB|0B| 0.0%|
|1034.smt2                                                                                   |22.328MiB|22.328MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.632MiB|24.632MiB|0B| 0.0%|
|107.smt2                                                                                    |21.064MiB|21.064MiB|0B| 0.0%|
|1082.smt2                                                                                   |25.928MiB|25.928MiB|0B| 0.0%|
|1089.smt2                                                                                   |21.58MiB|21.58MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.036MiB|23.036MiB|0B| 0.0%|
|1092.smt2                                                                                   |21.816MiB|21.816MiB|0B| 0.0%|
|1104.smt2                                                                                   |21.572MiB|21.572MiB|0B| 0.0%|
|1112.smt2                                                                                   |21.816MiB|21.816MiB|0B| 0.0%|
|1113.smt2                                                                                   |22.092MiB|22.092MiB|0B| 0.0%|
|1126.smt2                                                                                   |22.352MiB|22.352MiB|0B| 0.0%|
|1132.smt2                                                                                   |25.068MiB|25.068MiB|0B| 0.0%|
|1148.smt2                                                                                   |22.756MiB|22.756MiB|0B| 0.0%|
|1152.smt2                                                                                   |22.352MiB|22.352MiB|0B| 0.0%|
|1176.smt2                                                                                   |22.864MiB|22.864MiB|0B| 0.0%|
|1188.smt2                                                                                   |23.368MiB|23.368MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |25.96MiB|25.96MiB|0B| 0.0%|
|1010.smt2                                                                                   |29.772MiB|29.772MiB|0B| 0.0%|
|1018.smt2                                                                                   |22.032MiB|22.032MiB|0B| 0.0%|
|1021.smt2                                                                                   |22.652MiB|22.652MiB|0B| 0.0%|
|1034.smt2                                                                                   |22.328MiB|22.328MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.632MiB|24.632MiB|0B| 0.0%|
|107.smt2                                                                                    |21.064MiB|21.064MiB|0B| 0.0%|
|1082.smt2                                                                                   |25.928MiB|25.928MiB|0B| 0.0%|
|1089.smt2                                                                                   |21.58MiB|21.58MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.036MiB|23.036MiB|0B| 0.0%|
|1092.smt2                                                                                   |21.816MiB|21.816MiB|0B| 0.0%|
|1104.smt2                                                                                   |21.572MiB|21.572MiB|0B| 0.0%|
|1112.smt2                                                                                   |21.816MiB|21.816MiB|0B| 0.0%|
|1113.smt2                                                                                   |22.092MiB|22.092MiB|0B| 0.0%|
|1126.smt2                                                                                   |22.352MiB|22.352MiB|0B| 0.0%|
|1132.smt2                                                                                   |25.068MiB|25.068MiB|0B| 0.0%|
|1148.smt2                                                                                   |22.756MiB|22.756MiB|0B| 0.0%|
|1152.smt2                                                                                   |22.352MiB|22.352MiB|0B| 0.0%|
|1176.smt2                                                                                   |22.864MiB|22.864MiB|0B| 0.0%|
|1188.smt2                                                                                   |23.368MiB|23.368MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |25.96MiB|25.96MiB|0B| 0.0%|
|1010.smt2                                                                                   |29.772MiB|29.772MiB|0B| 0.0%|
|1018.smt2                                                                                   |22.032MiB|22.032MiB|0B| 0.0%|
|1021.smt2                                                                                   |22.652MiB|22.652MiB|0B| 0.0%|
|1034.smt2                                                                                   |22.328MiB|22.328MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.632MiB|24.632MiB|0B| 0.0%|
|107.smt2                                                                                    |21.064MiB|21.064MiB|0B| 0.0%|
|1082.smt2                                                                                   |25.928MiB|25.928MiB|0B| 0.0%|
|1089.smt2                                                                                   |21.58MiB|21.58MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.036MiB|23.036MiB|0B| 0.0%|
|1092.smt2                                                                                   |21.816MiB|21.816MiB|0B| 0.0%|
|1104.smt2                                                                                   |21.572MiB|21.572MiB|0B| 0.0%|
|1112.smt2                                                                                   |21.816MiB|21.816MiB|0B| 0.0%|
|1113.smt2                                                                                   |22.092MiB|22.092MiB|0B| 0.0%|
|1126.smt2                                                                                   |22.352MiB|22.352MiB|0B| 0.0%|
|1132.smt2                                                                                   |25.068MiB|25.068MiB|0B| 0.0%|
|1148.smt2                                                                                   |22.756MiB|22.756MiB|0B| 0.0%|
|1152.smt2                                                                                   |22.352MiB|22.352MiB|0B| 0.0%|
|1176.smt2                                                                                   |22.864MiB|22.864MiB|0B| 0.0%|
|1188.smt2                                                                                   |23.368MiB|23.368MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |25.96MiB|25.96MiB|0B| 0.0%|
|1010.smt2                                                                                   |29.772MiB|29.772MiB|0B| 0.0%|
|1018.smt2                                                                                   |22.032MiB|22.032MiB|0B| 0.0%|
|1021.smt2                                                                                   |22.652MiB|22.652MiB|0B| 0.0%|
|1034.smt2                                                                                   |22.328MiB|22.328MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.632MiB|24.632MiB|0B| 0.0%|
|107.smt2                                                                                    |21.064MiB|21.064MiB|0B| 0.0%|
|1082.smt2                                                                                   |25.928MiB|25.928MiB|0B| 0.0%|
|1089.smt2                                                                                   |21.58MiB|21.58MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.036MiB|23.036MiB|0B| 0.0%|
|1092.smt2                                                                                   |21.816MiB|21.816MiB|0B| 0.0%|
|1104.smt2                                                                                   |21.572MiB|21.572MiB|0B| 0.0%|
|1112.smt2                                                                                   |21.816MiB|21.816MiB|0B| 0.0%|
|1113.smt2                                                                                   |22.092MiB|22.092MiB|0B| 0.0%|
|1126.smt2                                                                                   |22.352MiB|22.352MiB|0B| 0.0%|
|1132.smt2                                                                                   |25.068MiB|25.068MiB|0B| 0.0%|
|1148.smt2                                                                                   |22.756MiB|22.756MiB|0B| 0.0%|
|1152.smt2                                                                                   |22.352MiB|22.352MiB|0B| 0.0%|
|1176.smt2                                                                                   |22.864MiB|22.864MiB|0B| 0.0%|
|1188.smt2                                                                                   |23.368MiB|23.368MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  19.994s |507.0MiB|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                            |  20.006s |378.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  20.024s |370.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  20.018s |343.0MiB|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                           |  19.955s |313.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                        |  19.982s |304.0MiB|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                 |  20.023s |303.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              |  19.966s |288.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                |  20.014s |275.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          |  20.012s |268.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              |  20.011s |258.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   |  19.968s |249.0MiB|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                |  19.982s |247.0MiB|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                        |  20.004s |243.0MiB|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                |  20.013s |232.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          |  19.989s |231.0MiB|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                 |  20.002s |228.0MiB|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                              |  19.995s |228.0MiB|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                               |  19.973s |225.0MiB|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                           |  19.954s |223.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  19.994s |507.0MiB|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                            |  20.006s |378.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  20.024s |370.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  20.018s |343.0MiB|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                           |  19.955s |313.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                        |  19.982s |304.0MiB|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                 |  20.023s |303.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              |  19.966s |288.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                |  20.014s |275.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          |  20.012s |268.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              |  20.011s |258.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   |  19.968s |249.0MiB|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                |  19.982s |247.0MiB|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                        |  20.004s |243.0MiB|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                |  20.013s |232.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          |  19.989s |231.0MiB|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                 |  20.002s |228.0MiB|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                              |  19.995s |228.0MiB|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                               |  19.973s |225.0MiB|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                           |  19.954s |223.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   1.065s  |   1.065s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   2.706s  |   2.706s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  17.362s  |  17.362s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           |  19.918s  |  19.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |  19.767s  |  19.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |   7.999s  |   7.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         |   7.501s  |   7.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   2.120s  |   2.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              |  19.934s  |  19.934s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |   2.979s  |   2.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |   0.816s  |   0.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   1.454s  |   1.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   2.184s  |   2.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |  12.106s  |  12.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |   1.997s  |   1.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |  14.621s  |  14.621s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   3.436s  |   3.436s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   |  19.719s  |  19.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   0.887s  |   0.887s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |  19.886s  |  19.886s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   1.561s  |   1.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |   5.465s  |   5.465s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          |  15.152s  |  15.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   1.122s  |   1.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    |  19.914s  |  19.914s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |  12.114s  |  12.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |   0.748s  |   0.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |   3.077s  |   3.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        |   3.865s  |   3.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              |  19.811s  |  19.811s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |   5.375s  |   5.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |   1.302s  |   1.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   1.350s  |   1.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |  14.559s  |  14.559s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |  10.903s  |  10.903s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |   7.191s  |   7.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |   5.706s  |   5.706s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   0.558s  |   0.558s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   2.170s  |   2.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |  10.145s  |  10.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   0.802s  |   0.802s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   7.218s  |   7.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   2.581s  |   2.581s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   2.318s  |   2.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |  19.846s  |  19.846s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   2.488s  |   2.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   1.371s  |   1.371s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |   2.005s  |   2.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  10.969s  |  10.969s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |   3.772s  |   3.772s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |  17.089s  |  17.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |  19.889s  |  19.889s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  14.797s  |  14.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   1.129s  |   1.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   1.388s  |   1.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |   2.475s  |   2.475s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   5.542s  |   5.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |   9.988s  |   9.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   6.054s  |   6.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   8.432s  |   8.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |  19.906s  |  19.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |  19.941s  |  19.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   7.127s  |   7.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   5.481s  |   5.481s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   0.950s  |   0.950s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |   0.905s  |   0.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |  19.856s  |  19.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |   1.907s  |   1.907s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   1.906s  |   1.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |   1.853s  |   1.853s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   1.651s  |   1.651s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   2.040s  |   2.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |   1.523s  |   1.523s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     |   3.277s  |   3.277s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |   9.149s  |   9.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |   3.790s  |   3.790s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |   3.902s  |   3.902s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |  19.915s  |  19.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |  19.921s  |  19.921s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |   1.295s  |   1.295s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               |   2.452s  |   2.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   2.446s  |   2.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   1.890s  |   1.890s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   1.407s  |   1.407s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |  19.931s  |  19.931s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |   3.011s  |   3.011s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   0.959s  |   0.959s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   4.979s  |   4.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   6.392s  |   6.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |  19.911s  |  19.911s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |  10.720s  |  10.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |   4.297s  |   4.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |   3.235s  |   3.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |   0.888s  |   0.888s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |   8.326s  |   8.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |   5.680s  |   5.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   3.013s  |   3.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |   4.432s  |   4.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   1.173s  |   1.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   3.725s  |   3.725s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |   1.366s  |   1.366s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |  19.943s  |  19.943s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |   0.949s  |   0.949s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   0.996s  |   0.996s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   9.252s  |   9.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |  19.818s  |  19.818s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |   4.798s  |   4.798s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |   8.008s  |   8.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   2.684s  |   2.684s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |  19.921s  |  19.921s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   1.656s  |   1.656s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   2.401s  |   2.401s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   1.024s  |   1.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |   1.906s  |   1.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |   3.347s  |   3.347s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               |   5.071s  |   5.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   1.020s  |   1.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              |  12.967s  |  12.967s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   1.739s  |   1.739s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   5.747s  |   5.747s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |   0.884s  |   0.884s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |  14.921s  |  14.921s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   3.108s  |   3.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |  11.591s  |  11.591s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |   1.027s  |   1.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   0.869s  |   0.869s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |   7.014s  |   7.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |  19.944s  |  19.944s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |  19.723s  |  19.723s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   5.973s  |   5.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   4.796s  |   4.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |  19.887s  |  19.887s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.562s  |   0.562s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   1.199s  |   1.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |   3.109s  |   3.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |  10.448s  |  10.448s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   1.532s  |   1.532s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |   2.479s  |   2.479s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   1.651s  |   1.651s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   1.089s  |   1.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |   1.387s  |   1.387s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |   7.038s  |   7.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |   1.169s  |   1.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |   3.610s  |   3.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   5.335s  |   5.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   2.311s  |   2.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |   1.091s  |   1.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   3.138s  |   3.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   1.311s  |   1.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   1.724s  |   1.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |   2.640s  |   2.640s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |   1.695s  |   1.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   0.713s  |   0.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   2.822s  |   2.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |   0.695s  |   0.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |   2.442s  |   2.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   1.610s  |   1.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   2.153s  |   2.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   1.607s  |   1.607s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |  19.917s  |  19.917s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |   4.829s  |   4.829s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |   5.947s  |   5.947s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   9.536s  |   9.536s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   9.954s  |   9.954s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   7.291s  |   7.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   6.357s  |   6.357s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   1.272s  |   1.272s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   3.832s  |   3.832s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |   8.951s  |   8.951s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |  19.625s  |  19.625s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |   0.933s  |   0.933s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   5.745s  |   5.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |   2.676s  |   2.676s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   2.396s  |   2.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   1.626s  |   1.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |  13.148s  |  13.148s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |   1.252s  |   1.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  19.883s  |  19.883s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |   1.111s  |   1.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  15.610s  |  15.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   1.268s  |   1.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |   2.824s  |   2.824s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |   2.174s  |   2.174s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |   2.893s  |   2.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |   3.172s  |   3.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |   2.951s  |   2.951s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |   5.725s  |   5.725s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   0.955s  |   0.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   1.168s  |   1.168s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   1.766s  |   1.766s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   1.751s  |   1.751s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |   7.359s  |   7.359s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   2.724s  |   2.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   0.809s  |   0.809s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |   4.310s  |   4.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   0.734s  |   0.734s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   1.512s  |   1.512s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |   3.006s  |   3.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |   1.799s  |   1.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |   1.688s  |   1.688s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   0.947s  |   0.947s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   1.348s  |   1.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  19.884s  |  19.884s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   2.446s  |   2.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |   1.117s  |   1.117s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   0.870s  |   0.870s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  18.638s  |  18.638s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   0.546s  |   0.546s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   0.991s  |   0.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   0.626s  |   0.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |   4.367s  |   4.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   1.697s  |   1.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   1.388s  |   1.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   2.863s  |   2.863s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   1.026s  |   1.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   1.240s  |   1.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   0.984s  |   0.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   1.012s  |   1.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   1.000s  |   1.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   0.954s  |   0.954s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |   8.344s  |   8.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   3.134s  |   3.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   1.521s  |   1.521s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   0.727s  |   0.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |   2.490s  |   2.490s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   1.134s  |   1.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   1.292s  |   1.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  11.728s  |  11.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |   1.205s  |   1.205s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   0.907s  |   0.907s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |   4.568s  |   4.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   0.650s  |   0.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   1.597s  |   1.597s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   1.323s  |   1.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |   1.013s  |   1.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |   1.836s  |   1.836s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   2.060s  |   2.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   2.030s  |   2.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   2.940s  |   2.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                |  18.044s  |  18.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |   1.987s  |   1.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |   7.487s  |   7.487s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   0.634s  |   0.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |   9.747s  |   9.747s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   1.695s  |   1.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   6.342s  |   6.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |   2.504s  |   2.504s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   1.433s  |   1.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |   2.010s  |   2.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   0.802s  |   0.802s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |   0.767s  |   0.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |   2.549s  |   2.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   0.865s  |   0.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   1.956s  |   1.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   1.935s  |   1.935s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   0.843s  |   0.843s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   1.719s  |   1.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |   1.474s  |   1.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   3.542s  |   3.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   8.054s  |   8.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |  15.811s  |  15.811s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   1.453s  |   1.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |  15.991s  |  15.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |   0.919s  |   0.919s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |   6.638s  |   6.638s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |   7.220s  |   7.220s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   1.118s  |   1.118s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  19.895s  |  19.895s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  11.971s  |  11.971s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |   3.494s  |   3.494s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  11.884s  |  11.884s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |  19.831s  |  19.831s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   2.603s  |   2.603s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  13.740s  |  13.740s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |  10.634s  |  10.634s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |   5.832s  |   5.832s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |   1.509s  |   1.509s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |  19.963s  |  19.963s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |  19.921s  |  19.921s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   1.151s  |   1.151s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      |  19.922s  |  19.922s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              |  19.913s  |  19.913s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |  19.893s  |  19.893s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |   1.658s  |   1.658s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |  10.099s  |  10.099s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |  19.929s  |  19.929s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       |  19.902s  |  19.902s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |   1.562s  |   1.562s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   0.825s  |   0.825s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |  10.497s  |  10.497s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   2.098s  |   2.098s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   1.696s  |   1.696s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   8.609s  |   8.609s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   2.043s  |   2.043s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   3.305s  |   3.305s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |   4.248s  |   4.248s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   1.527s  |   1.527s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   6.639s  |   6.639s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   1.632s  |   1.632s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |   0.952s  |   0.952s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |  19.910s  |  19.910s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   2.956s  |   2.956s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   4.781s  |   4.781s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   3.651s  |   3.651s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   0.964s  |   0.964s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |  19.934s  |  19.934s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |   4.393s  |   4.393s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |   3.878s  |   3.878s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   9.063s  |   9.063s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |   3.511s  |   3.511s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |  13.833s  |  13.833s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |   1.516s  |   1.516s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            |  19.915s  |  19.915s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |   2.481s  |   2.481s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 |   7.945s  |   7.945s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |   8.073s  |   8.073s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |   6.292s  |   6.292s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           |  19.933s  |  19.933s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           |  19.922s  |  19.922s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  11.996s  |  11.996s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |   9.485s  |   9.485s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 |  19.931s  |  19.931s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |   7.239s  |   7.239s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |   3.819s  |   3.819s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 |  19.910s  |  19.910s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   0.484s  |   0.484s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |   5.384s  |   5.384s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |  19.917s  |  19.917s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   1.301s  |   1.301s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  12.221s  |  12.221s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |   2.035s  |   2.035s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |  12.508s  |  12.508s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |  19.916s  |  19.916s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |   3.945s  |   3.945s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        |  19.895s  |  19.895s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   1.347s  |   1.347s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        |  19.907s  |  19.907s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |   5.062s  |   5.062s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   2.811s  |   2.811s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   6.471s  |   6.471s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   1.118s  |   1.118s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             |  19.874s  |  19.874s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |  19.762s  |  19.762s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |   6.357s  |   6.357s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   9.866s  |   9.866s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   7.697s  |   7.697s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   3.378s  |   3.378s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   0.790s  |   0.790s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   0.957s  |   0.957s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   1.495s  |   1.495s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |   2.425s  |   2.425s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  14.513s  |  14.513s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  |   2.581s  |   2.581s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   1.396s  |   1.396s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |   6.407s  |   6.407s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               |  19.870s  |  19.870s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  19.947s  |  19.947s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |   1.726s  |   1.726s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   2.478s  |   2.478s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |   2.967s  |   2.967s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |   0.925s  |   0.925s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |   2.864s  |   2.864s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            |  19.915s  |  19.915s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            |   4.533s  |   4.533s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |  13.892s  |  13.892s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            |  19.934s  |  19.934s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  19.857s  |  19.857s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              |   0.927s  |   0.927s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       |  19.948s  |  19.948s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   1.972s  |   1.972s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   4.632s  |   4.632s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         |  19.681s  |  19.681s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |   1.896s  |   1.896s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              |  19.898s  |  19.898s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   2.591s  |   2.591s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |   0.905s  |   0.905s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   0.734s  |   0.734s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   1.414s  |   1.414s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |   0.923s  |   0.923s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |   4.635s  |   4.635s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |   0.891s  |   0.891s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |   6.077s  |   6.077s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |   1.434s  |   1.434s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |   0.756s  |   0.756s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   0.790s  |   0.790s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |   1.635s  |   1.635s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   1.065s  |   1.065s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |   1.546s  |   1.546s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   3.904s  |   3.904s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |   2.597s  |   2.597s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   1.033s  |   1.033s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |   1.474s  |   1.474s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |   6.260s  |   6.260s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   1.080s  |   1.080s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   3.075s  |   3.075s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   0.813s  |   0.813s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |   1.262s  |   1.262s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   0.838s  |   0.838s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |   1.733s  |   1.733s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          |   8.335s  |   8.335s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |  13.486s  |  13.486s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   1.615s  |   1.615s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |   0.900s  |   0.900s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |  19.922s  |  19.922s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   1.094s  |   1.094s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |   7.330s  |   7.330s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |   1.452s  |   1.452s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |   5.256s  |   5.256s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   0.585s  |   0.585s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   0.667s  |   0.667s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   0.848s  |   0.848s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   0.751s  |   0.751s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |   2.453s  |   2.453s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   0.955s  |   0.955s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  17.034s  |  17.034s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |   3.993s  |   3.993s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        |  16.709s  |  16.709s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   0.981s  |   0.981s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |   8.510s  |   8.510s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   2.179s  |   2.179s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |   1.994s  |   1.994s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  19.947s  |  19.947s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   1.352s  |   1.352s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   3.508s  |   3.508s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   1.132s  |   1.132s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |  19.932s  |  19.932s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         |   5.207s  |   5.207s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         |   0.921s  |   0.921s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |   4.875s  |   4.875s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   2.046s  |   2.046s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   0.781s  |   0.781s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           |  19.911s  |  19.911s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           |  19.932s  |  19.932s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   3.750s  |   3.750s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |   5.098s  |   5.098s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                |  19.852s  |  19.852s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |   2.391s  |   2.391s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |   1.500s  |   1.500s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          |  19.872s  |  19.872s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       |  19.929s  |  19.929s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   6.781s  |   6.781s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |   8.179s  |   8.179s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |   4.199s  |   4.199s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 |  19.963s  |  19.963s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   1.615s  |   1.615s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                |  19.927s  |  19.927s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  17.626s  |  17.626s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          |  16.203s  |  16.203s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |   3.061s  |   3.061s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |   6.457s  |   6.457s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   1.503s  |   1.503s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |   7.479s  |   7.479s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   1.054s  |   1.054s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      |  19.861s  |  19.861s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |   5.057s  |   5.057s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |   5.672s  |   5.672s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   0.572s  |   0.572s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |   2.647s  |   2.647s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  11.445s  |  11.445s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |   5.115s  |   5.115s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |   2.368s  |   2.368s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   2.661s  |   2.661s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   1.312s  |   1.312s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |   6.080s  |   6.080s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   3.575s  |   3.575s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   2.730s  |   2.730s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |  19.860s  |  19.860s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |   6.179s  |   6.179s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   1.128s  |   1.128s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |  16.906s  |  16.906s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   2.466s  |   2.466s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |   6.058s  |   6.058s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  19.907s  |  19.907s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  19.824s  |  19.824s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   4.445s  |   4.445s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   2.123s  |   2.123s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  19.849s  |  19.849s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   8.407s  |   8.407s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |  17.648s  |  17.648s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |   2.265s  |   2.265s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   6.193s  |   6.193s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   2.258s  |   2.258s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   2.964s  |   2.964s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           |  19.944s  |  19.944s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   1.799s  |   1.799s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   5.040s  |   5.040s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   4.019s  |   4.019s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   6.056s  |   6.056s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   5.731s  |   5.731s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   1.318s  |   1.318s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |  11.139s  |  11.139s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   2.629s  |   2.629s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |  19.800s  |  19.800s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   3.791s  |   3.791s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |   9.199s  |   9.199s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   3.459s  |   3.459s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   1.786s  |   1.786s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   2.227s  |   2.227s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   7.471s  |   7.471s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   6.965s  |   6.965s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   2.060s  |   2.060s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   1.984s  |   1.984s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   2.149s  |   2.149s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   1.990s  |   1.990s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   0.734s  |   0.734s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |  12.123s  |  12.123s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |  12.960s  |  12.960s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            |  19.852s  |  19.852s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
</details>
