Comparing data and data


# SUMMARY
- LHS tests = 2313
- RHS tests = 2313
- LHS success = 1702  (73.58408992650237%)
- RHS success = 1702  (73.58408992650237%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-reduce-pseudo-linear
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 98a9a34f2bd68adc4616d1bc6c959e35253c33a5
Z3 branch: 
Z3 options: "-T:30 smt.arith.nl.reduce_pseudo_linear=true"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: add option to reduce pseudo-linear monomials

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-reduce-pseudo-linear
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 98a9a34f2bd68adc4616d1bc6c959e35253c33a5
Z3 branch: 
Z3 options: "-T:30 smt.arith.nl.reduce_pseudo_linear=true"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: add option to reduce pseudo-linear monomials

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.061s  |   2.061s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.569s  |   1.569s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.061s  |   2.061s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.569s  |   1.569s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.061s  |   2.061s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.569s  |   1.569s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.061s  |   2.061s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.569s  |   1.569s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  30.334s |2500.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.238s |646.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  30.204s |633.0MiB|
|From_T2__foo.t2__terminationS_12_0.smt2                                                    |  30.179s |642.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  30.175s |636.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  30.168s |547.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  30.158s |550.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  30.147s |468.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2         |  30.137s |326.0MiB|
|182.smt2                                                                                   |  30.135s |411.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  30.135s |475.0MiB|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                |  30.129s |215.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                |  30.126s |257.0MiB|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                            |  30.125s |221.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                 |  30.121s |251.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           |  30.120s |472.0MiB|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                         |  30.119s |153.0MiB|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                |  30.117s |247.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  30.116s |415.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  30.115s |471.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  30.334s |2500.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.238s |646.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  30.204s |633.0MiB|
|From_T2__foo.t2__terminationS_12_0.smt2                                                    |  30.179s |642.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  30.175s |636.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  30.168s |547.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  30.158s |550.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  30.147s |468.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2         |  30.137s |326.0MiB|
|182.smt2                                                                                   |  30.135s |411.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  30.135s |475.0MiB|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                |  30.129s |215.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                |  30.126s |257.0MiB|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                            |  30.125s |221.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                 |  30.121s |251.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           |  30.120s |472.0MiB|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                         |  30.119s |153.0MiB|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                |  30.117s |247.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  30.116s |415.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  30.115s |471.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |58.96MiB|58.96MiB|0B| 0.0%|
|04.smt2                                                                                     |55.912MiB|55.912MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.64MiB|31.64MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.52MiB|30.52MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.604MiB|23.604MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.068MiB|24.068MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.124MiB|24.124MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.792MiB|24.792MiB|0B| 0.0%|
|107.smt2                                                                                    |22.44MiB|22.44MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.26MiB|27.26MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.368MiB|80.368MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.808MiB|22.808MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.864MiB|22.864MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.496MiB|23.496MiB|0B| 0.0%|
|11.smt2                                                                                     |52.46MiB|52.46MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.044MiB|24.044MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.432MiB|23.432MiB|0B| 0.0%|
|1113.smt2                                                                                   |25.1MiB|25.1MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.328MiB|25.328MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |58.96MiB|58.96MiB|0B| 0.0%|
|04.smt2                                                                                     |55.912MiB|55.912MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.64MiB|31.64MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.52MiB|30.52MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.604MiB|23.604MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.068MiB|24.068MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.124MiB|24.124MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.792MiB|24.792MiB|0B| 0.0%|
|107.smt2                                                                                    |22.44MiB|22.44MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.26MiB|27.26MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.368MiB|80.368MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.808MiB|22.808MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.864MiB|22.864MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.496MiB|23.496MiB|0B| 0.0%|
|11.smt2                                                                                     |52.46MiB|52.46MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.044MiB|24.044MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.432MiB|23.432MiB|0B| 0.0%|
|1113.smt2                                                                                   |25.1MiB|25.1MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.328MiB|25.328MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |58.96MiB|58.96MiB|0B| 0.0%|
|04.smt2                                                                                     |55.912MiB|55.912MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.64MiB|31.64MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.52MiB|30.52MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.604MiB|23.604MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.068MiB|24.068MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.124MiB|24.124MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.792MiB|24.792MiB|0B| 0.0%|
|107.smt2                                                                                    |22.44MiB|22.44MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.26MiB|27.26MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.368MiB|80.368MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.808MiB|22.808MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.864MiB|22.864MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.496MiB|23.496MiB|0B| 0.0%|
|11.smt2                                                                                     |52.46MiB|52.46MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.044MiB|24.044MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.432MiB|23.432MiB|0B| 0.0%|
|1113.smt2                                                                                   |25.1MiB|25.1MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.328MiB|25.328MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |58.96MiB|58.96MiB|0B| 0.0%|
|04.smt2                                                                                     |55.912MiB|55.912MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.64MiB|31.64MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.52MiB|30.52MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.604MiB|23.604MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.068MiB|24.068MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.124MiB|24.124MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.792MiB|24.792MiB|0B| 0.0%|
|107.smt2                                                                                    |22.44MiB|22.44MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.26MiB|27.26MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.368MiB|80.368MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.808MiB|22.808MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.864MiB|22.864MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.496MiB|23.496MiB|0B| 0.0%|
|11.smt2                                                                                     |52.46MiB|52.46MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.044MiB|24.044MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.432MiB|23.432MiB|0B| 0.0%|
|1113.smt2                                                                                   |25.1MiB|25.1MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.328MiB|25.328MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  30.334s |2500.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.238s |646.0MiB|
|From_T2__foo.t2__terminationS_12_0.smt2                                                    |  30.179s |642.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  30.175s |636.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  30.204s |633.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  30.158s |550.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  30.168s |547.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  30.135s |475.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           |  30.120s |472.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       |  30.085s |472.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  30.115s |471.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  30.147s |468.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   |  30.092s |458.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          |  30.070s |447.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  30.116s |415.0MiB|
|182.smt2                                                                                   |  30.135s |411.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              |  30.103s |411.0MiB|
|183.smt2                                                                                   |  30.090s |411.0MiB|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                           |  30.076s |378.0MiB|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                |  30.113s |359.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  30.334s |2500.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.238s |646.0MiB|
|From_T2__foo.t2__terminationS_12_0.smt2                                                    |  30.179s |642.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  30.175s |636.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  30.204s |633.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  30.158s |550.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  30.168s |547.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  30.135s |475.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           |  30.120s |472.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       |  30.085s |472.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  30.115s |471.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  30.147s |468.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   |  30.092s |458.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          |  30.070s |447.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  30.116s |415.0MiB|
|182.smt2                                                                                   |  30.135s |411.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              |  30.103s |411.0MiB|
|183.smt2                                                                                   |  30.090s |411.0MiB|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                           |  30.076s |378.0MiB|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                |  30.113s |359.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.061s  |   2.061s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.569s  |   1.569s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   1.182s  |   1.182s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   1.942s  |   1.942s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   5.204s  |   5.204s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   2.811s  |   2.811s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   1.401s  |   1.401s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   1.189s  |   1.189s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   2.332s  |   2.332s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  30.102s  |  30.102s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  30.135s  |  30.135s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  30.107s  |  30.107s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   1.524s  |   1.524s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   1.789s  |   1.789s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   2.034s  |   2.034s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   2.818s  |   2.818s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   6.399s  |   6.399s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   5.786s  |   5.786s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   2.147s  |   2.147s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   2.909s  |   2.909s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   1.084s  |   1.084s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   1.451s  |   1.451s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   1.566s  |   1.566s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   2.364s  |   2.364s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   2.452s  |   2.452s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   1.802s  |   1.802s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   2.813s  |   2.813s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   3.223s  |   3.223s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   1.439s  |   1.439s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   4.830s  |   4.830s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|966.smt2                                                                                    |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|99.smt2                                                                                     |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.461s  |   0.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   3.551s  |   3.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          |  30.095s  |  30.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |   9.663s  |   9.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   1.354s  |   1.354s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |  25.095s  |  25.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |  10.357s  |  10.357s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   2.343s  |   2.343s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            |  30.110s  |  30.110s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   4.652s  |   4.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   4.281s  |   4.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   3.172s  |   3.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   2.626s  |   2.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |   9.216s  |   9.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   1.554s  |   1.554s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   1.176s  |   1.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |  18.020s  |  18.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   6.628s  |   6.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   4.226s  |   4.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |  10.608s  |  10.608s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             |  30.096s  |  30.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |   9.734s  |   9.734s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  13.193s  |  13.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   2.686s  |   2.686s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   7.065s  |   7.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   1.180s  |   1.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   1.249s  |   1.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |  11.471s  |  11.471s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |   2.766s  |   2.766s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   2.211s  |   2.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   3.436s  |   3.436s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   1.562s  |   1.562s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   7.328s  |   7.328s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   1.391s  |   1.391s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   3.507s  |   3.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   3.787s  |   3.787s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |   8.842s  |   8.842s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   4.501s  |   4.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  15.040s  |  15.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |  12.924s  |  12.924s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   3.091s  |   3.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   4.382s  |   4.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |   2.280s  |   2.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   8.643s  |   8.643s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  20.483s  |  20.483s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   1.875s  |   1.875s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |   3.220s  |   3.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  26.531s  |  26.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   4.116s  |   4.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   4.115s  |   4.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   4.052s  |   4.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |  30.079s  |  30.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   4.142s  |   4.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   4.771s  |   4.771s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   3.575s  |   3.575s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   1.738s  |   1.738s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   5.280s  |   5.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   1.295s  |   1.295s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |  21.936s  |  21.936s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   2.117s  |   2.117s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   5.814s  |   5.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   1.855s  |   1.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  13.429s  |  13.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   4.269s  |   4.269s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   4.149s  |   4.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   7.106s  |   7.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   2.355s  |   2.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   2.715s  |   2.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |  23.045s  |  23.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |   8.983s  |   8.983s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   1.208s  |   1.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  30.089s  |  30.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  29.629s  |  29.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  15.996s  |  15.996s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  30.084s  |  30.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |   4.871s  |   4.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  18.671s  |  18.671s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   3.084s  |   3.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |   9.696s  |   9.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   3.925s  |   3.925s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   1.866s  |   1.866s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   3.107s  |   3.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   0.634s  |   0.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   1.531s  |   1.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   2.928s  |   2.928s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |   5.657s  |   5.657s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   6.190s  |   6.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  26.144s  |  26.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |  25.264s  |  25.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   6.422s  |   6.422s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   5.258s  |   5.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   3.046s  |   3.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   5.271s  |   5.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   2.595s  |   2.595s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   5.188s  |   5.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   9.907s  |   9.907s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  28.949s  |  28.949s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |   4.283s  |   4.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |   9.282s  |   9.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |  11.445s  |  11.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   9.544s  |   9.544s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   3.854s  |   3.854s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |  13.867s  |  13.867s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   4.143s  |   4.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |  14.007s  |  14.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   4.255s  |   4.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   2.956s  |   2.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |   5.635s  |   5.635s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   2.888s  |   2.888s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   2.424s  |   2.424s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |  18.645s  |  18.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   2.303s  |   2.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |  11.477s  |  11.477s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   1.203s  |   1.203s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |   7.932s  |   7.932s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   2.183s  |   2.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   1.610s  |   1.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |  14.247s  |  14.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   7.652s  |   7.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |   6.375s  |   6.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |  12.078s  |  12.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  23.537s  |  23.537s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   1.571s  |   1.571s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     |  30.104s  |  30.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   0.831s  |   0.831s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   2.199s  |   2.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |   5.374s  |   5.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |   7.544s  |   7.544s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |  12.183s  |  12.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   7.140s  |   7.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   3.622s  |   3.622s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   3.605s  |   3.605s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   2.585s  |   2.585s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   2.825s  |   2.825s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   3.696s  |   3.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   0.484s  |   0.484s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |  11.655s  |  11.655s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |   1.543s  |   1.543s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   6.466s  |   6.466s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   2.670s  |   2.670s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   2.251s  |   2.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   2.217s  |   2.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   2.917s  |   2.917s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  11.652s  |  11.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   5.818s  |   5.818s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   2.456s  |   2.456s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   6.148s  |   6.148s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |  19.221s  |  19.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   2.968s  |   2.968s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   1.026s  |   1.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   1.115s  |   1.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   1.255s  |   1.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |   2.069s  |   2.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   2.313s  |   2.313s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   3.266s  |   3.266s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   0.827s  |   0.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   2.370s  |   2.370s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   2.876s  |   2.876s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   1.701s  |   1.701s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   1.494s  |   1.494s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   2.643s  |   2.643s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |   6.422s  |   6.422s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |   0.742s  |   0.742s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   4.196s  |   4.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   2.328s  |   2.328s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   0.640s  |   0.640s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   2.404s  |   2.404s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   1.685s  |   1.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   2.173s  |   2.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |   5.908s  |   5.908s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   3.307s  |   3.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |   8.389s  |   8.389s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |  12.338s  |  12.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   2.513s  |   2.513s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   2.326s  |   2.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |   2.407s  |   2.407s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |  30.023s  |  30.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |   6.986s  |   6.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |   9.539s  |   9.539s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   2.271s  |   2.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |  10.752s  |  10.752s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               |  10.237s  |  10.237s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |   7.108s  |   7.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   6.052s  |   6.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   4.711s  |   4.711s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   2.170s  |   2.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |   1.944s  |   1.944s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   2.541s  |   2.541s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   1.539s  |   1.539s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |   8.594s  |   8.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   2.245s  |   2.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   1.524s  |   1.524s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   1.639s  |   1.639s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   2.663s  |   2.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   2.479s  |   2.479s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   2.938s  |   2.938s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   1.239s  |   1.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |  15.207s  |  15.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   2.541s  |   2.541s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   3.635s  |   3.635s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |  13.444s  |  13.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   8.334s  |   8.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   2.485s  |   2.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   2.303s  |   2.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |  27.092s  |  27.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   2.541s  |   2.541s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   2.764s  |   2.764s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.934s  |   0.934s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |   1.746s  |   1.746s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   1.410s  |   1.410s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   2.184s  |   2.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   0.640s  |   0.640s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   8.185s  |   8.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   2.488s  |   2.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |  11.443s  |  11.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |   0.773s  |   0.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |   2.044s  |   2.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |   2.033s  |   2.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |   0.580s  |   0.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |  16.986s  |  16.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |   1.325s  |   1.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |   6.163s  |   6.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |   3.846s  |   3.846s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   2.589s  |   2.589s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |  10.970s  |  10.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |   3.988s  |   3.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   2.447s  |   2.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   2.265s  |   2.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |  12.032s  |  12.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   2.332s  |   2.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   2.333s  |   2.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   1.792s  |   1.792s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |  16.263s  |  16.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |   1.695s  |   1.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |  12.819s  |  12.819s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   3.599s  |   3.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |   3.464s  |   3.464s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |   1.372s  |   1.372s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |  28.429s  |  28.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   1.721s  |   1.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |   6.305s  |   6.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   2.557s  |   2.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   1.964s  |   1.964s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   2.711s  |   2.711s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   0.559s  |   0.559s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |   5.645s  |   5.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   1.352s  |   1.352s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   2.874s  |   2.874s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  30.107s  |  30.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |  15.081s  |  15.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   2.285s  |   2.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |  10.620s  |  10.620s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  30.121s  |  30.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   1.451s  |   1.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  10.616s  |  10.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  30.095s  |  30.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   2.642s  |   2.642s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |  30.081s  |  30.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            |  30.095s  |  30.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   2.523s  |   2.523s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   2.179s  |   2.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   3.378s  |   3.378s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   6.330s  |   6.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   3.468s  |   3.468s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   3.849s  |   3.849s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   1.839s  |   1.839s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   5.433s  |   5.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   2.223s  |   2.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   1.612s  |   1.612s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |   9.838s  |   9.838s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   2.783s  |   2.783s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   7.601s  |   7.601s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   2.280s  |   2.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |   2.544s  |   2.544s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |  13.650s  |  13.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   1.797s  |   1.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   3.073s  |   3.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   3.775s  |   3.775s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   2.684s  |   2.684s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   5.804s  |   5.804s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   9.738s  |   9.738s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |  11.057s  |  11.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   4.187s  |   4.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   2.282s  |   2.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   3.232s  |   3.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   3.570s  |   3.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   2.572s  |   2.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   4.885s  |   4.885s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   1.629s  |   1.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   4.595s  |   4.595s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   7.955s  |   7.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   5.099s  |   5.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   2.791s  |   2.791s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   1.599s  |   1.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   7.955s  |   7.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   3.484s  |   3.484s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   3.148s  |   3.148s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   5.179s  |   5.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   4.632s  |   4.632s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   4.056s  |   4.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   3.674s  |   3.674s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   1.704s  |   1.704s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   1.739s  |   1.739s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   2.217s  |   2.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   3.685s  |   3.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |  18.574s  |  18.574s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   7.709s  |   7.709s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   3.443s  |   3.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |  11.274s  |  11.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |   3.385s  |   3.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   2.295s  |   2.295s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   2.566s  |   2.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   3.680s  |   3.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   3.708s  |   3.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   4.206s  |   4.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   1.844s  |   1.844s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |  11.404s  |  11.404s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   8.643s  |   8.643s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   9.297s  |   9.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   2.550s  |   2.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  14.329s  |  14.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  10.333s  |  10.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   3.701s  |   3.701s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   7.999s  |   7.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   3.501s  |   3.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   7.079s  |   7.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |   7.391s  |   7.391s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   2.857s  |   2.857s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   3.053s  |   3.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   8.599s  |   8.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   2.594s  |   2.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   1.794s  |   1.794s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   2.608s  |   2.608s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   3.217s  |   3.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   3.292s  |   3.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |  13.223s  |  13.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   2.503s  |   2.503s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   2.130s  |   2.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   4.506s  |   4.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   1.899s  |   1.899s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |  13.477s  |  13.477s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   2.815s  |   2.815s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |   7.959s  |   7.959s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   2.950s  |   2.950s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |  10.045s  |  10.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   2.220s  |   2.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   2.177s  |   2.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   7.125s  |   7.125s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   1.771s  |   1.771s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   2.548s  |   2.548s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   1.932s  |   1.932s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   7.001s  |   7.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |   8.036s  |   8.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   2.461s  |   2.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   1.460s  |   1.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   3.482s  |   3.482s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   4.581s  |   4.581s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   4.310s  |   4.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   4.825s  |   4.825s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             |  30.147s  |  30.147s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            |  30.120s  |  30.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            |  30.115s  |  30.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   2.881s  |   2.881s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   2.902s  |   2.902s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   4.329s  |   4.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |   4.848s  |   4.848s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   2.958s  |   2.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   6.209s  |   6.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   5.952s  |   5.952s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   0.936s  |   0.936s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   4.279s  |   4.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   4.783s  |   4.783s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   9.179s  |   9.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   1.128s  |   1.128s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   3.482s  |   3.482s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |  18.388s  |  18.388s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |  14.152s  |  14.152s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |  10.400s  |  10.400s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.984s  |   0.984s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   5.260s  |   5.260s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   1.384s  |   1.384s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   2.281s  |   2.281s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   1.315s  |   1.315s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  23.533s  |  23.533s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |   6.812s  |   6.812s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   9.791s  |   9.791s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |  30.114s  |  30.114s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |  11.513s  |  11.513s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         |  30.158s  |  30.158s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  24.048s  |  24.048s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  13.566s  |  13.566s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  27.699s  |  27.699s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  13.449s  |  13.449s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   1.524s  |   1.524s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              |  30.135s  |  30.135s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  30.079s  |  30.079s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   5.635s  |   5.635s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   6.195s  |   6.195s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |   3.249s  |   3.249s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |  11.907s  |  11.907s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |  12.547s  |  12.547s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   6.563s  |   6.563s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   1.764s  |   1.764s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |   5.669s  |   5.669s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   7.539s  |   7.539s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   2.624s  |   2.624s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  10.953s  |  10.953s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |  10.307s  |  10.307s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   3.389s  |   3.389s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   3.189s  |   3.189s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |   9.162s  |   9.162s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  15.862s  |  15.862s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |   9.556s  |   9.556s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |  21.168s  |  21.168s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  23.761s  |  23.761s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   3.605s  |   3.605s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   3.480s  |   3.480s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   7.623s  |   7.623s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   1.702s  |   1.702s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.897s  |   0.897s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |  11.972s  |  11.972s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   3.862s  |   3.862s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   2.756s  |   2.756s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   5.265s  |   5.265s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |   2.141s  |   2.141s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   3.064s  |   3.064s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |   3.459s  |   3.459s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   2.425s  |   2.425s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   3.789s  |   3.789s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   7.082s  |   7.082s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   3.459s  |   3.459s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   1.089s  |   1.089s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   1.073s  |   1.073s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   2.600s  |   2.600s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   4.466s  |   4.466s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               |  30.168s  |  30.168s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   0.895s  |   0.895s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   1.695s  |   1.695s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 |  30.116s  |  30.116s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |  14.438s  |  14.438s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |  10.283s  |  10.283s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |  11.222s  |  11.222s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |  15.723s  |  15.723s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      |  30.114s  |  30.114s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |  14.272s  |  14.272s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |  11.395s  |  11.395s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |  11.186s  |  11.186s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |   4.736s  |   4.736s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   2.357s  |   2.357s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   3.322s  |   3.322s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   4.417s  |   4.417s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   1.179s  |   1.179s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   0.850s  |   0.850s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   0.868s  |   0.868s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |   7.412s  |   7.412s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   8.469s  |   8.469s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   2.499s  |   2.499s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   0.736s  |   0.736s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   3.946s  |   3.946s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   7.583s  |   7.583s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   2.142s  |   2.142s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   2.108s  |   2.108s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   3.489s  |   3.489s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.674s  |   0.674s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   2.349s  |   2.349s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   0.979s  |   0.979s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |  10.481s  |  10.481s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |   7.985s  |   7.985s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |   3.689s  |   3.689s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   9.483s  |   9.483s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   5.344s  |   5.344s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   1.072s  |   1.072s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   3.285s  |   3.285s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   3.025s  |   3.025s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   4.566s  |   4.566s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   2.572s  |   2.572s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |  17.422s  |  17.422s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   2.137s  |   2.137s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   1.527s  |   1.527s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   1.566s  |   1.566s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   1.371s  |   1.371s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   0.959s  |   0.959s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   2.596s  |   2.596s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   3.955s  |   3.955s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   7.758s  |   7.758s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   2.350s  |   2.350s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   1.874s  |   1.874s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   8.569s  |   8.569s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   5.108s  |   5.108s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   1.871s  |   1.871s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   1.468s  |   1.468s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   2.453s  |   2.453s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   5.314s  |   5.314s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   1.845s  |   1.845s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   4.428s  |   4.428s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   3.447s  |   3.447s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   1.848s  |   1.848s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   1.956s  |   1.956s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   1.953s  |   1.953s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   1.098s  |   1.098s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   2.579s  |   2.579s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   3.428s  |   3.428s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |   6.818s  |   6.818s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   1.545s  |   1.545s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   4.647s  |   4.647s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   7.548s  |   7.548s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   1.736s  |   1.736s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.957s  |   0.957s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   2.308s  |   2.308s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   2.716s  |   2.716s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   4.410s  |   4.410s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   2.596s  |   2.596s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   3.472s  |   3.472s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   4.918s  |   4.918s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   2.850s  |   2.850s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   2.444s  |   2.444s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   2.223s  |   2.223s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   7.061s  |   7.061s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   2.374s  |   2.374s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   1.904s  |   1.904s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   2.310s  |   2.310s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   4.957s  |   4.957s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |  13.469s  |  13.469s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   5.858s  |   5.858s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |  10.685s  |  10.685s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |  13.783s  |  13.783s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  26.997s  |  26.997s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |  15.344s  |  15.344s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  26.567s  |  26.567s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |   9.206s  |   9.206s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  15.582s  |  15.582s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   4.491s  |   4.491s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     |  30.179s  |  30.179s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     |  30.204s  |  30.204s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     |  30.175s  |  30.175s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |   9.888s  |   9.888s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |   5.086s  |   5.086s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     |  30.095s  |  30.095s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  17.381s  |  17.381s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  29.928s  |  29.928s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   4.394s  |   4.394s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   2.234s  |   2.234s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   2.241s  |   2.241s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  16.137s  |  16.137s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |  22.048s  |  22.048s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |  13.829s  |  13.829s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |  23.357s  |  23.357s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   7.280s  |   7.280s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  30.117s  |  30.117s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  16.457s  |  16.457s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   6.373s  |   6.373s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   7.624s  |   7.624s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |   5.786s  |   5.786s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   5.154s  |   5.154s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   8.139s  |   8.139s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |   7.688s  |   7.688s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |   6.419s  |   6.419s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   3.721s  |   3.721s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   5.591s  |   5.591s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   3.085s  |   3.085s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   2.125s  |   2.125s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  15.868s  |  15.868s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 |  30.079s  |  30.079s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  19.673s  |  19.673s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        |  30.112s  |  30.112s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    |  30.096s  |  30.096s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  30.081s  |  30.081s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |   6.784s  |   6.784s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              |  30.112s  |  30.112s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  26.070s  |  26.070s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   4.391s  |   4.391s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |  18.622s  |  18.622s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  22.895s  |  22.895s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  16.457s  |  16.457s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  13.929s  |  13.929s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   4.598s  |   4.598s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   6.669s  |   6.669s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   1.840s  |   1.840s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.913s  |   0.913s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   2.661s  |   2.661s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   5.999s  |   5.999s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  18.438s  |  18.438s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   2.002s  |   2.002s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |  11.154s  |  11.154s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |  10.348s  |  10.348s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   8.023s  |   8.023s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   3.743s  |   3.743s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   6.315s  |   6.315s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |   1.829s  |   1.829s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   2.723s  |   2.723s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |   6.353s  |   6.353s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             |  30.125s  |  30.125s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   2.765s  |   2.765s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   6.800s  |   6.800s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   3.692s  |   3.692s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  |  16.659s  |  16.659s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   0.685s  |   0.685s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   5.204s  |   5.204s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   1.261s  |   1.261s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   3.082s  |   3.082s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   2.629s  |   2.629s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   2.745s  |   2.745s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   4.352s  |   4.352s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |   2.454s  |   2.454s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   2.229s  |   2.229s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   1.915s  |   1.915s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |   5.589s  |   5.589s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   3.763s  |   3.763s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   2.396s  |   2.396s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   3.426s  |   3.426s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   6.823s  |   6.823s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   2.683s  |   2.683s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   3.289s  |   3.289s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   1.628s  |   1.628s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            |  30.084s  |  30.084s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   2.644s  |   2.644s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |  15.350s  |  15.350s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   3.029s  |   3.029s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   2.135s  |   2.135s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |   9.909s  |   9.909s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   3.422s  |   3.422s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |  15.643s  |  15.643s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |   3.418s  |   3.418s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  21.495s  |  21.495s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               |  13.490s  |  13.490s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               |  30.114s  |  30.114s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |  17.742s  |  17.742s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |  19.659s  |  19.659s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  13.134s  |  13.134s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |  15.008s  |  15.008s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   4.168s  |   4.168s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   0.880s  |   0.880s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |   1.667s  |   1.667s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   4.242s  |   4.242s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |   3.192s  |   3.192s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |   3.095s  |   3.095s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   3.861s  |   3.861s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   4.968s  |   4.968s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   7.518s  |   7.518s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   3.085s  |   3.085s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   3.468s  |   3.468s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |   2.887s  |   2.887s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               |  30.103s  |  30.103s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         |  30.238s  |  30.238s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  14.404s  |  14.404s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  22.533s  |  22.533s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  20.168s  |  20.168s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  11.247s  |  11.247s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  21.049s  |  21.049s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        |  30.089s  |  30.089s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   0.743s  |   0.743s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   4.111s  |   4.111s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   3.915s  |   3.915s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   2.919s  |   2.919s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  19.930s  |  19.930s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   1.283s  |   1.283s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  13.895s  |  13.895s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   2.948s  |   2.948s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  13.558s  |  13.558s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   3.880s  |   3.880s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   4.590s  |   4.590s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   3.969s  |   3.969s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   7.326s  |   7.326s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         |  26.545s  |  26.545s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |   5.289s  |   5.289s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   2.000s  |   2.000s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |   2.844s  |   2.844s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |   8.899s  |   8.899s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |   3.146s  |   3.146s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                |  30.095s  |  30.095s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   2.797s  |   2.797s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                |  30.084s  |  30.084s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |   8.776s  |   8.776s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |   1.498s  |   1.498s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          |  30.081s  |  30.081s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |  12.033s  |  12.033s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |   8.676s  |   8.676s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   8.618s  |   8.618s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   3.828s  |   3.828s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   6.810s  |   6.810s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   6.250s  |   6.250s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   4.676s  |   4.676s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   6.525s  |   6.525s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   6.827s  |   6.827s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   6.190s  |   6.190s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   2.908s  |   2.908s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   7.157s  |   7.157s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   6.985s  |   6.985s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |   5.788s  |   5.788s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   7.221s  |   7.221s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   4.778s  |   4.778s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   0.721s  |   0.721s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |   1.530s  |   1.530s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   5.124s  |   5.124s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |   1.730s  |   1.730s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   4.108s  |   4.108s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   7.605s  |   7.605s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   6.281s  |   6.281s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   1.372s  |   1.372s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   7.244s  |   7.244s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   4.885s  |   4.885s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |   6.109s  |   6.109s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |   3.724s  |   3.724s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   8.928s  |   8.928s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   5.129s  |   5.129s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   0.812s  |   0.812s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   5.265s  |   5.265s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |   4.794s  |   4.794s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   6.558s  |   6.558s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |   8.863s  |   8.863s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   3.143s  |   3.143s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |   2.185s  |   2.185s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |   7.170s  |   7.170s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   6.159s  |   6.159s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   4.934s  |   4.934s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   1.173s  |   1.173s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   4.402s  |   4.402s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   2.020s  |   2.020s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   6.708s  |   6.708s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   5.315s  |   5.315s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  10.864s  |  10.864s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.546s  |   0.546s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   5.803s  |   5.803s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |  14.135s  |  14.135s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   1.566s  |   1.566s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   6.665s  |   6.665s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |  23.461s  |  23.461s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   5.486s  |   5.486s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   0.823s  |   0.823s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   7.758s  |   7.758s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   1.601s  |   1.601s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |   2.397s  |   2.397s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |   2.700s  |   2.700s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   2.855s  |   2.855s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   1.942s  |   1.942s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   2.148s  |   2.148s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        |  30.096s  |  30.096s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |   7.187s  |   7.187s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   2.837s  |   2.837s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   3.043s  |   3.043s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   7.061s  |   7.061s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  23.678s  |  23.678s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   3.533s  |   3.533s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |   9.838s  |   9.838s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  13.153s  |  13.153s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |  15.107s  |  15.107s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |  10.036s  |  10.036s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |   2.069s  |   2.069s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   7.073s  |   7.073s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   4.651s  |   4.651s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   4.381s  |   4.381s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  14.001s  |  14.001s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  16.170s  |  16.170s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  12.625s  |  12.625s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  20.086s  |  20.086s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   4.564s  |   4.564s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |   3.135s  |   3.135s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   4.563s  |   4.563s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   4.526s  |   4.526s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   4.376s  |   4.376s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   3.906s  |   3.906s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   3.625s  |   3.625s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   8.672s  |   8.672s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   2.996s  |   2.996s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           |   5.677s  |   5.677s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   1.298s  |   1.298s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   3.150s  |   3.150s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   2.876s  |   2.876s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   1.902s  |   1.902s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   8.951s  |   8.951s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   2.204s  |   2.204s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   3.438s  |   3.438s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   3.177s  |   3.177s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   1.989s  |   1.989s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   5.559s  |   5.559s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   2.704s  |   2.704s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |  21.583s  |  21.583s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   1.286s  |   1.286s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   6.422s  |   6.422s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |   4.029s  |   4.029s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   6.831s  |   6.831s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |  23.079s  |  23.079s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   4.053s  |   4.053s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |  12.859s  |  12.859s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   4.421s  |   4.421s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          |  30.334s  |  30.334s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |  14.871s  |  14.871s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  14.093s  |  14.093s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   2.921s  |   2.921s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   3.662s  |   3.662s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  10.264s  |  10.264s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  16.426s  |  16.426s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  30.089s  |  30.089s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  21.656s  |  21.656s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   5.198s  |   5.198s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |   9.086s  |   9.086s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  19.019s  |  19.019s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  19.748s  |  19.748s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |  30.087s  |  30.087s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  30.081s  |  30.081s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  11.335s  |  11.335s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |  10.513s  |  10.513s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |  12.321s  |  12.321s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                |  30.103s  |  30.103s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  15.017s  |  15.017s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |   8.803s  |   8.803s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  15.080s  |  15.080s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   2.636s  |   2.636s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   1.452s  |   1.452s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   5.497s  |   5.497s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  19.746s  |  19.746s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   3.109s  |   3.109s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |   4.190s  |   4.190s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   1.626s  |   1.626s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   1.513s  |   1.513s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   1.057s  |   1.057s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   1.394s  |   1.394s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   1.042s  |   1.042s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   1.980s  |   1.980s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   2.172s  |   2.172s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  30.081s  |  30.081s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   5.592s  |   5.592s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   1.394s  |   1.394s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |  30.106s  |  30.106s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   4.329s  |   4.329s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   3.696s  |   3.696s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   2.287s  |   2.287s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   1.156s  |   1.156s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   2.249s  |   2.249s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   4.815s  |   4.815s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   3.112s  |   3.112s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   4.950s  |   4.950s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   1.500s  |   1.500s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   2.870s  |   2.870s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   1.299s  |   1.299s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   2.889s  |   2.889s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   7.468s  |   7.468s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   4.314s  |   4.314s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   2.853s  |   2.853s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   1.787s  |   1.787s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   3.483s  |   3.483s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  29.028s  |  29.028s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   2.880s  |   2.880s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   6.815s  |   6.815s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   6.047s  |   6.047s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   2.517s  |   2.517s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   0.678s  |   0.678s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   1.851s  |   1.851s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   0.958s  |   0.958s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |   9.224s  |   9.224s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |  30.115s  |  30.115s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  14.687s  |  14.687s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   5.737s  |   5.737s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  11.275s  |  11.275s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   2.818s  |   2.818s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   4.341s  |   4.341s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   3.992s  |   3.992s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   4.809s  |   4.809s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   8.254s  |   8.254s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   4.344s  |   4.344s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   5.370s  |   5.370s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   1.361s  |   1.361s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   0.883s  |   0.883s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   2.321s  |   2.321s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   3.269s  |   3.269s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |   3.098s  |   3.098s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   4.482s  |   4.482s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   1.448s  |   1.448s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   2.966s  |   2.966s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   8.333s  |   8.333s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   2.175s  |   2.175s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   2.542s  |   2.542s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   3.405s  |   3.405s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   6.325s  |   6.325s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   3.742s  |   3.742s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   4.374s  |   4.374s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   1.102s  |   1.102s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |  10.104s  |  10.104s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   1.219s  |   1.219s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.606s  |   0.606s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   1.697s  |   1.697s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   1.308s  |   1.308s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   5.075s  |   5.075s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   1.114s  |   1.114s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   1.354s  |   1.354s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   3.460s  |   3.460s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   2.682s  |   2.682s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   6.031s  |   6.031s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   1.036s  |   1.036s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |  17.750s  |  17.750s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   4.080s  |   4.080s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   3.934s  |   3.934s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   5.078s  |   5.078s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   2.575s  |   2.575s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   4.137s  |   4.137s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.565s  |   0.565s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   1.761s  |   1.761s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   2.295s  |   2.295s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   1.907s  |   1.907s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   2.663s  |   2.663s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   2.476s  |   2.476s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   3.090s  |   3.090s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   2.836s  |   2.836s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.580s  |   0.580s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   5.160s  |   5.160s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   4.454s  |   4.454s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   3.166s  |   3.166s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   1.710s  |   1.710s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |   3.264s  |   3.264s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   0.995s  |   0.995s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   1.426s  |   1.426s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   3.426s  |   3.426s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |   4.154s  |   4.154s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   2.434s  |   2.434s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   7.752s  |   7.752s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   4.210s  |   4.210s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   1.109s  |   1.109s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   3.640s  |   3.640s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   7.163s  |   7.163s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   1.140s  |   1.140s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   1.478s  |   1.478s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   3.440s  |   3.440s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   2.506s  |   2.506s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   4.048s  |   4.048s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   3.887s  |   3.887s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   2.581s  |   2.581s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   3.872s  |   3.872s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   8.932s  |   8.932s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   4.054s  |   4.054s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   3.254s  |   3.254s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   1.599s  |   1.599s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   5.799s  |   5.799s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   5.062s  |   5.062s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   2.334s  |   2.334s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   4.666s  |   4.666s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   5.018s  |   5.018s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   9.180s  |   9.180s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   6.124s  |   6.124s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   8.234s  |   8.234s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   3.367s  |   3.367s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   3.391s  |   3.391s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   5.432s  |   5.432s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   5.737s  |   5.737s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   2.483s  |   2.483s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   9.221s  |   9.221s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   3.963s  |   3.963s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |   3.513s  |   3.513s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.579s  |   1.579s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   1.674s  |   1.674s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   1.646s  |   1.646s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   1.629s  |   1.629s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   8.943s  |   8.943s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   1.078s  |   1.078s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.261s  |   0.261s  |   0.000s  | 0.0%|
</details>
