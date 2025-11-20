Comparing data and data


# SUMMARY
- LHS tests = 2313
- RHS tests = 2313
- LHS success = 1747  (75.52961521833117%)
- RHS success = 1747  (75.52961521833117%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: nia-poly
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: b3f7d1660608e8cfa145e1b086fe1a6f57b11910
Z3 branch: arie
Z3 options: "-T:30 tactic.default_tactic=smt smt.arith.nl.nra.poly=true"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: fix memory leaks and handling of non-integer term coefficients

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: nia-poly
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: b3f7d1660608e8cfa145e1b086fe1a6f57b11910
Z3 branch: arie
Z3 options: "-T:30 tactic.default_tactic=smt smt.arith.nl.nra.poly=true"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: fix memory leaks and handling of non-integer term coefficients

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  30.408s |1917.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  30.265s |2057.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  30.240s |949.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.193s |980.0MiB|
|185.smt2                                                                                   |  30.163s |901.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  30.124s |538.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           |  30.123s |487.0MiB|
|182.smt2                                                                                   |  30.121s |400.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  30.118s |469.0MiB|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                       |  30.114s |275.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  30.113s |486.0MiB|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                            |  30.110s |295.0MiB|
|From_T2__foo.t2__terminationS_12_0.smt2                                                    |  30.108s |514.0MiB|
|aproveSMT3334656614075774306.smt2                                                          |  30.105s |348.0MiB|
|183.smt2                                                                                   |  30.105s |400.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  30.100s |506.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  30.099s |481.0MiB|
|aproveSMT6744625072979146355.smt2                                                          |  30.095s |306.0MiB|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                       |  30.094s |233.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                        |  30.093s |233.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  30.408s |1917.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  30.265s |2057.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  30.240s |949.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.193s |980.0MiB|
|185.smt2                                                                                   |  30.163s |901.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  30.124s |538.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           |  30.123s |487.0MiB|
|182.smt2                                                                                   |  30.121s |400.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  30.118s |469.0MiB|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                       |  30.114s |275.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  30.113s |486.0MiB|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                            |  30.110s |295.0MiB|
|From_T2__foo.t2__terminationS_12_0.smt2                                                    |  30.108s |514.0MiB|
|aproveSMT3334656614075774306.smt2                                                          |  30.105s |348.0MiB|
|183.smt2                                                                                   |  30.105s |400.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  30.100s |506.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  30.099s |481.0MiB|
|aproveSMT6744625072979146355.smt2                                                          |  30.095s |306.0MiB|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                       |  30.094s |233.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                        |  30.093s |233.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |59.996MiB|59.996MiB|0B| 0.0%|
|04.smt2                                                                                     |48.716MiB|48.716MiB|0B| 0.0%|
|1.smt2                                                                                      |26.912MiB|26.912MiB|0B| 0.0%|
|1008.smt2                                                                                   |29.496MiB|29.496MiB|0B| 0.0%|
|1010.smt2                                                                                   |29.712MiB|29.712MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.368MiB|23.368MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.436MiB|23.436MiB|0B| 0.0%|
|1034.smt2                                                                                   |23.616MiB|23.616MiB|0B| 0.0%|
|1063.smt2                                                                                   |23.592MiB|23.592MiB|0B| 0.0%|
|107.smt2                                                                                    |21.652MiB|21.652MiB|0B| 0.0%|
|1082.smt2                                                                                   |26.324MiB|26.324MiB|0B| 0.0%|
|1085.smt2                                                                                   |21.532MiB|21.532MiB|0B| 0.0%|
|1089.smt2                                                                                   |21.916MiB|21.916MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.872MiB|23.872MiB|0B| 0.0%|
|1092.smt2                                                                                   |22.468MiB|22.468MiB|0B| 0.0%|
|11.smt2                                                                                     |45.76MiB|45.76MiB|0B| 0.0%|
|1104.smt2                                                                                   |22.252MiB|22.252MiB|0B| 0.0%|
|1112.smt2                                                                                   |22.312MiB|22.312MiB|0B| 0.0%|
|1113.smt2                                                                                   |22.8MiB|22.8MiB|0B| 0.0%|
|1126.smt2                                                                                   |22.912MiB|22.912MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |59.996MiB|59.996MiB|0B| 0.0%|
|04.smt2                                                                                     |48.716MiB|48.716MiB|0B| 0.0%|
|1.smt2                                                                                      |26.912MiB|26.912MiB|0B| 0.0%|
|1008.smt2                                                                                   |29.496MiB|29.496MiB|0B| 0.0%|
|1010.smt2                                                                                   |29.712MiB|29.712MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.368MiB|23.368MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.436MiB|23.436MiB|0B| 0.0%|
|1034.smt2                                                                                   |23.616MiB|23.616MiB|0B| 0.0%|
|1063.smt2                                                                                   |23.592MiB|23.592MiB|0B| 0.0%|
|107.smt2                                                                                    |21.652MiB|21.652MiB|0B| 0.0%|
|1082.smt2                                                                                   |26.324MiB|26.324MiB|0B| 0.0%|
|1085.smt2                                                                                   |21.532MiB|21.532MiB|0B| 0.0%|
|1089.smt2                                                                                   |21.916MiB|21.916MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.872MiB|23.872MiB|0B| 0.0%|
|1092.smt2                                                                                   |22.468MiB|22.468MiB|0B| 0.0%|
|11.smt2                                                                                     |45.76MiB|45.76MiB|0B| 0.0%|
|1104.smt2                                                                                   |22.252MiB|22.252MiB|0B| 0.0%|
|1112.smt2                                                                                   |22.312MiB|22.312MiB|0B| 0.0%|
|1113.smt2                                                                                   |22.8MiB|22.8MiB|0B| 0.0%|
|1126.smt2                                                                                   |22.912MiB|22.912MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |59.996MiB|59.996MiB|0B| 0.0%|
|04.smt2                                                                                     |48.716MiB|48.716MiB|0B| 0.0%|
|1.smt2                                                                                      |26.912MiB|26.912MiB|0B| 0.0%|
|1008.smt2                                                                                   |29.496MiB|29.496MiB|0B| 0.0%|
|1010.smt2                                                                                   |29.712MiB|29.712MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.368MiB|23.368MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.436MiB|23.436MiB|0B| 0.0%|
|1034.smt2                                                                                   |23.616MiB|23.616MiB|0B| 0.0%|
|1063.smt2                                                                                   |23.592MiB|23.592MiB|0B| 0.0%|
|107.smt2                                                                                    |21.652MiB|21.652MiB|0B| 0.0%|
|1082.smt2                                                                                   |26.324MiB|26.324MiB|0B| 0.0%|
|1085.smt2                                                                                   |21.532MiB|21.532MiB|0B| 0.0%|
|1089.smt2                                                                                   |21.916MiB|21.916MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.872MiB|23.872MiB|0B| 0.0%|
|1092.smt2                                                                                   |22.468MiB|22.468MiB|0B| 0.0%|
|11.smt2                                                                                     |45.76MiB|45.76MiB|0B| 0.0%|
|1104.smt2                                                                                   |22.252MiB|22.252MiB|0B| 0.0%|
|1112.smt2                                                                                   |22.312MiB|22.312MiB|0B| 0.0%|
|1113.smt2                                                                                   |22.8MiB|22.8MiB|0B| 0.0%|
|1126.smt2                                                                                   |22.912MiB|22.912MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |59.996MiB|59.996MiB|0B| 0.0%|
|04.smt2                                                                                     |48.716MiB|48.716MiB|0B| 0.0%|
|1.smt2                                                                                      |26.912MiB|26.912MiB|0B| 0.0%|
|1008.smt2                                                                                   |29.496MiB|29.496MiB|0B| 0.0%|
|1010.smt2                                                                                   |29.712MiB|29.712MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.368MiB|23.368MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.436MiB|23.436MiB|0B| 0.0%|
|1034.smt2                                                                                   |23.616MiB|23.616MiB|0B| 0.0%|
|1063.smt2                                                                                   |23.592MiB|23.592MiB|0B| 0.0%|
|107.smt2                                                                                    |21.652MiB|21.652MiB|0B| 0.0%|
|1082.smt2                                                                                   |26.324MiB|26.324MiB|0B| 0.0%|
|1085.smt2                                                                                   |21.532MiB|21.532MiB|0B| 0.0%|
|1089.smt2                                                                                   |21.916MiB|21.916MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.872MiB|23.872MiB|0B| 0.0%|
|1092.smt2                                                                                   |22.468MiB|22.468MiB|0B| 0.0%|
|11.smt2                                                                                     |45.76MiB|45.76MiB|0B| 0.0%|
|1104.smt2                                                                                   |22.252MiB|22.252MiB|0B| 0.0%|
|1112.smt2                                                                                   |22.312MiB|22.312MiB|0B| 0.0%|
|1113.smt2                                                                                   |22.8MiB|22.8MiB|0B| 0.0%|
|1126.smt2                                                                                   |22.912MiB|22.912MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  30.265s |2057.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  30.408s |1917.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.193s |980.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  30.240s |949.0MiB|
|185.smt2                                                                                   |  30.163s |901.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  30.124s |538.0MiB|
|From_T2__foo.t2__terminationS_12_0.smt2                                                    |  30.108s |514.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  30.100s |506.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           |  30.123s |487.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  30.113s |486.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  30.099s |481.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  30.118s |469.0MiB|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                |  30.080s |462.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       |  30.086s |428.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                      |  30.078s |417.0MiB|
|aproveSMT629665582926508878.smt2                                                           |  30.071s |406.0MiB|
|182.smt2                                                                                   |  30.121s |400.0MiB|
|183.smt2                                                                                   |  30.105s |400.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              |  30.052s |370.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   |  30.067s |356.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  30.265s |2057.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  30.408s |1917.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.193s |980.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  30.240s |949.0MiB|
|185.smt2                                                                                   |  30.163s |901.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  30.124s |538.0MiB|
|From_T2__foo.t2__terminationS_12_0.smt2                                                    |  30.108s |514.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  30.100s |506.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           |  30.123s |487.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  30.113s |486.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  30.099s |481.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  30.118s |469.0MiB|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                |  30.080s |462.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       |  30.086s |428.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                      |  30.078s |417.0MiB|
|aproveSMT629665582926508878.smt2                                                           |  30.071s |406.0MiB|
|182.smt2                                                                                   |  30.121s |400.0MiB|
|183.smt2                                                                                   |  30.105s |400.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              |  30.052s |370.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   |  30.067s |356.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.572s  |   0.572s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  30.121s  |  30.121s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  30.105s  |  30.105s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  30.163s  |  30.163s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   1.082s  |   1.082s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|966.smt2                                                                                    |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|99.smt2                                                                                     |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   1.009s  |   1.009s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |  14.544s  |  14.544s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |   8.065s  |   8.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          |  29.730s  |  29.730s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   2.697s  |   2.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       |  30.024s  |  30.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  30.023s  |  30.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |   2.257s  |   2.257s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   8.294s  |   8.294s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  15.900s  |  15.900s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   1.052s  |   1.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |  10.980s  |  10.980s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         |  30.030s  |  30.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             |  30.110s  |  30.110s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |   2.611s  |   2.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |   3.010s  |   3.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |  10.374s  |  10.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          |  30.023s  |  30.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          |   2.806s  |   2.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |   1.240s  |   1.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               |  30.081s  |  30.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |   6.833s  |   6.833s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |   2.518s  |   2.518s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               |   5.136s  |   5.136s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             |  30.081s  |  30.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |   9.842s  |   9.842s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |  14.358s  |  14.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  23.358s  |  23.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               |  30.029s  |  30.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   1.687s  |   1.687s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |   4.483s  |   4.483s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  15.687s  |  15.687s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          |  30.029s  |  30.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  19.437s  |  19.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |   8.606s  |   8.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   2.355s  |   2.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   1.997s  |   1.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   1.829s  |   1.829s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  13.081s  |  13.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  20.964s  |  20.964s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  15.937s  |  15.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  |  26.776s  |  26.776s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |  16.317s  |  16.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   1.154s  |   1.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   0.778s  |   0.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |   2.111s  |   2.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |   1.175s  |   1.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |   1.444s  |   1.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   |  30.029s  |  30.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     |  11.925s  |  11.925s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   2.289s  |   2.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   0.731s  |   0.731s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |  11.602s  |  11.602s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |  30.023s  |  30.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                |  28.672s  |  28.672s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   1.272s  |   1.272s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   0.949s  |   0.949s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |   6.759s  |   6.759s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |   4.770s  |   4.770s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |  19.427s  |  19.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          |  30.029s  |  30.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |  12.468s  |  12.468s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            |  30.020s  |  30.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |   0.722s  |   0.722s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   2.890s  |   2.890s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   0.949s  |   0.949s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |   7.022s  |   7.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |  11.636s  |  11.636s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |   4.057s  |   4.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   7.971s  |   7.971s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |  19.757s  |  19.757s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   5.034s  |   5.034s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |   1.726s  |   1.726s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |  13.416s  |  13.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |  26.941s  |  26.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   2.908s  |   2.908s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   0.667s  |   0.667s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   1.672s  |   1.672s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   0.901s  |   0.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   0.655s  |   0.655s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   1.497s  |   1.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   0.968s  |   0.968s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     |  30.029s  |  30.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |  23.074s  |  23.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |   1.380s  |   1.380s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |  27.090s  |  27.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |   8.781s  |   8.781s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |  18.397s  |  18.397s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   1.331s  |   1.331s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   1.714s  |   1.714s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |   8.489s  |   8.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   1.058s  |   1.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               |  30.029s  |  30.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |  13.616s  |  13.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   1.240s  |   1.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |  30.023s  |  30.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   0.765s  |   0.765s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   0.883s  |   0.883s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   2.047s  |   2.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   1.234s  |   1.234s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |  11.425s  |  11.425s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |   3.469s  |   3.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   1.214s  |   1.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |  12.102s  |  12.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   1.213s  |   1.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |  13.207s  |  13.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |  25.997s  |  25.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   1.520s  |   1.520s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   6.907s  |   6.907s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |  19.192s  |  19.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |   1.050s  |   1.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |  29.923s  |  29.923s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |   1.514s  |   1.514s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |   1.291s  |   1.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |   1.157s  |   1.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   0.652s  |   0.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   0.987s  |   0.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   0.846s  |   0.846s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   1.294s  |   1.294s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   0.530s  |   0.530s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   1.560s  |   1.560s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   1.189s  |   1.189s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    |  30.030s  |  30.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   1.952s  |   1.952s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |  12.874s  |  12.874s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |  12.683s  |  12.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   1.050s  |   1.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   1.308s  |   1.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |  14.463s  |  14.463s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          |  30.030s  |  30.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   1.570s  |   1.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |  25.940s  |  25.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   1.297s  |   1.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        |  30.024s  |  30.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |  18.349s  |  18.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |   7.089s  |   7.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |  30.030s  |  30.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   2.245s  |   2.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |  13.506s  |  13.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |   2.004s  |   2.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |  13.047s  |  13.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   2.094s  |   2.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |   8.325s  |   8.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |  28.092s  |  28.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |   0.582s  |   0.582s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |  23.049s  |  23.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   1.996s  |   1.996s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |  21.463s  |  21.463s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   1.364s  |   1.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |   3.598s  |   3.598s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   0.949s  |   0.949s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   1.487s  |   1.487s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   1.506s  |   1.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |  15.752s  |  15.752s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   2.024s  |   2.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |   8.694s  |   8.694s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  15.415s  |  15.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  12.927s  |  12.927s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   0.683s  |   0.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  21.601s  |  21.601s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   1.981s  |   1.981s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   1.087s  |   1.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |   2.554s  |   2.554s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |  19.551s  |  19.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   6.492s  |   6.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   3.877s  |   3.877s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  27.028s  |  27.028s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |   5.173s  |   5.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   5.817s  |   5.817s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   1.733s  |   1.733s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   2.269s  |   2.269s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   2.370s  |   2.370s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   2.886s  |   2.886s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   2.246s  |   2.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   4.864s  |   4.864s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  29.466s  |  29.466s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |   2.444s  |   2.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   1.807s  |   1.807s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   2.338s  |   2.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |   9.990s  |   9.990s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   6.271s  |   6.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   4.156s  |   4.156s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |  19.404s  |  19.404s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   2.216s  |   2.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |   4.333s  |   4.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  16.081s  |  16.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |   8.789s  |   8.789s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   2.012s  |   2.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   3.220s  |   3.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |   2.416s  |   2.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   1.355s  |   1.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |   7.473s  |   7.473s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |   2.117s  |   2.117s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   2.782s  |   2.782s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   1.861s  |   1.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   1.381s  |   1.381s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   3.443s  |   3.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   0.769s  |   0.769s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          |  30.081s  |  30.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   1.400s  |   1.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             |  30.118s  |  30.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   0.939s  |   0.939s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   1.574s  |   1.574s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   2.425s  |   2.425s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      |  30.022s  |  30.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   1.155s  |   1.155s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  27.246s  |  27.246s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         |  30.020s  |  30.020s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   2.409s  |   2.409s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |  12.042s  |  12.042s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  11.353s  |  11.353s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  17.220s  |  17.220s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |   7.225s  |   7.225s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |   2.366s  |   2.366s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              |  30.240s  |  30.240s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |   2.061s  |   2.061s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |   2.219s  |   2.219s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   0.863s  |   0.863s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   0.767s  |   0.767s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 |  30.087s  |  30.087s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |   7.310s  |   7.310s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |   2.567s  |   2.567s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |  30.029s  |  30.029s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   3.094s  |   3.094s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |   9.055s  |   9.055s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |   9.704s  |   9.704s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |   2.187s  |   2.187s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  12.770s  |  12.770s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  24.705s  |  24.705s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  25.590s  |  25.590s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |  30.022s  |  30.022s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             |  30.017s  |  30.017s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   0.743s  |   0.743s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             |  30.030s  |  30.030s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |   2.118s  |   2.118s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |   1.364s  |   1.364s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |   1.785s  |   1.785s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   3.507s  |   3.507s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               |  30.408s  |  30.408s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |   3.933s  |   3.933s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  16.071s  |  16.071s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |   4.082s  |   4.082s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |   8.462s  |   8.462s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |   6.316s  |   6.316s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |   3.245s  |   3.245s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |   5.284s  |   5.284s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  17.644s  |  17.644s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |   4.509s  |   4.509s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  18.335s  |  18.335s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   1.402s  |   1.402s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   1.140s  |   1.140s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       |  30.024s  |  30.024s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   0.606s  |   0.606s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |   2.526s  |   2.526s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |   0.683s  |   0.683s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   2.179s  |   2.179s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   1.311s  |   1.311s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   1.461s  |   1.461s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   5.859s  |   5.859s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   3.435s  |   3.435s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |   4.383s  |   4.383s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |  30.023s  |  30.023s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   1.821s  |   1.821s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      |  30.019s  |  30.019s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |  19.190s  |  19.190s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |   5.426s  |   5.426s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  23.855s  |  23.855s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |   7.680s  |   7.680s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  25.538s  |  25.538s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  12.581s  |  12.581s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     |  30.108s  |  30.108s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |   1.357s  |   1.357s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |   4.809s  |   4.809s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  11.464s  |  11.464s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  14.452s  |  14.452s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   2.899s  |   2.899s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  15.220s  |  15.220s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |   4.522s  |   4.522s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  22.551s  |  22.551s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |  15.731s  |  15.731s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           |   9.008s  |   9.008s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |   3.178s  |   3.178s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  25.279s  |  25.279s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |   9.997s  |   9.997s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 |  30.024s  |  30.024s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 |  30.029s  |  30.029s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  30.024s  |  30.024s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |  16.910s  |  16.910s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |   5.263s  |   5.263s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |   5.150s  |   5.150s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  26.795s  |  26.795s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  14.925s  |  14.925s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |   9.020s  |   9.020s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |   8.142s  |   8.142s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  25.409s  |  25.409s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  30.024s  |  30.024s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |  16.532s  |  16.532s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  19.467s  |  19.467s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  25.162s  |  25.162s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        |  30.114s  |  30.114s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |  30.023s  |  30.023s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |   2.295s  |   2.295s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |   2.955s  |   2.955s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   0.760s  |   0.760s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                |  30.018s  |  30.018s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |   5.346s  |   5.346s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           |  30.030s  |  30.030s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   1.305s  |   1.305s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |  11.127s  |  11.127s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   0.810s  |   0.810s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   0.955s  |   0.955s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            |  30.024s  |  30.024s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |   9.446s  |   9.446s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  |  15.805s  |  15.805s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   0.706s  |   0.706s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   0.815s  |   0.815s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |   3.157s  |   3.157s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |   4.004s  |   4.004s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |   2.405s  |   2.405s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               |   5.306s  |   5.306s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               |  30.030s  |  30.030s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |  13.224s  |  13.224s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   0.860s  |   0.860s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |   1.911s  |   1.911s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |   1.877s  |   1.877s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  11.714s  |  11.714s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  28.410s  |  28.410s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   0.783s  |   0.783s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             |  30.016s  |  30.016s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   0.515s  |   0.515s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |   5.124s  |   5.124s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         |  30.193s  |  30.193s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  10.435s  |  10.435s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  11.674s  |  11.674s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  10.975s  |  10.975s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  11.672s  |  11.672s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  17.733s  |  17.733s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  21.735s  |  21.735s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  16.892s  |  16.892s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   1.541s  |   1.541s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   2.230s  |   2.230s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |   1.291s  |   1.291s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           |  30.017s  |  30.017s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |   1.003s  |   1.003s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |   2.106s  |   2.106s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |   2.099s  |   2.099s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |   5.483s  |   5.483s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   1.629s  |   1.629s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |   2.933s  |   2.933s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |   5.158s  |   5.158s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |   5.785s  |   5.785s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |  28.423s  |  28.423s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                |   6.370s  |   6.370s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |  30.024s  |  30.024s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |   9.312s  |   9.312s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                |  30.020s  |  30.020s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                |  30.024s  |  30.024s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |   0.489s  |   0.489s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   6.794s  |   6.794s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   1.150s  |   1.150s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |  30.018s  |  30.018s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   0.545s  |   0.545s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |  30.030s  |  30.030s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |   9.140s  |   9.140s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |  30.030s  |  30.030s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        |  30.024s  |  30.024s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  30.030s  |  30.030s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  |  30.024s  |  30.024s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  |  30.019s  |  30.019s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |   1.125s  |   1.125s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |   3.515s  |   3.515s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         |  30.030s  |  30.030s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         |  30.030s  |  30.030s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   1.785s  |   1.785s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   3.391s  |   3.391s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |   6.164s  |   6.164s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |  19.180s  |  19.180s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |   2.778s  |   2.778s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |   9.093s  |   9.093s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |   7.297s  |   7.297s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |   3.106s  |   3.106s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |   3.322s  |   3.322s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   3.212s  |   3.212s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  12.061s  |  12.061s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  11.412s  |  11.412s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  11.081s  |  11.081s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  15.293s  |  15.293s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   2.042s  |   2.042s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |   8.146s  |   8.146s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   1.473s  |   1.473s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   1.262s  |   1.262s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   1.654s  |   1.654s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   0.572s  |   0.572s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             |  30.024s  |  30.024s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |  24.970s  |  24.970s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |  27.320s  |  27.320s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |   9.565s  |   9.565s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             |  30.022s  |  30.022s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |  18.884s  |  18.884s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      |  30.024s  |  30.024s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          |  30.265s  |  30.265s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |  12.028s  |  12.028s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  12.912s  |  12.912s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  11.340s  |  11.340s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |   5.200s  |   5.200s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   0.670s  |   0.670s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   2.576s  |   2.576s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  16.000s  |  16.000s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  25.233s  |  25.233s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  15.841s  |  15.841s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |   5.286s  |   5.286s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   0.913s  |   0.913s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |  21.165s  |  21.165s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  10.245s  |  10.245s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |  19.129s  |  19.129s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  28.777s  |  28.777s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |   7.175s  |   7.175s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |   6.247s  |   6.247s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   2.830s  |   2.830s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |   2.436s  |   2.436s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                |  30.023s  |  30.023s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                |  30.022s  |  30.022s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  13.385s  |  13.385s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   1.809s  |   1.809s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |   0.900s  |   0.900s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |  30.030s  |  30.030s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   1.266s  |   1.266s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           |  30.015s  |  30.015s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |   9.767s  |   9.767s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |  30.019s  |  30.019s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |   1.638s  |   1.638s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   0.906s  |   0.906s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |   4.075s  |   4.075s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |   8.538s  |   8.538s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |   2.499s  |   2.499s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |  15.700s  |  15.700s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |  14.984s  |  14.984s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |   0.872s  |   0.872s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   3.655s  |   3.655s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  15.081s  |  15.081s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   4.573s  |   4.573s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   3.513s  |   3.513s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |   2.159s  |   2.159s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.712s  |   0.712s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       |  30.020s  |  30.020s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  30.022s  |  30.022s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   0.954s  |   0.954s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |  14.743s  |  14.743s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  20.297s  |  20.297s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  |  30.020s  |  30.020s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |  30.019s  |  30.019s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |  28.273s  |  28.273s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           |  30.017s  |  30.017s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           |  30.023s  |  30.023s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   9.347s  |   9.347s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           |  30.029s  |  30.029s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   1.310s  |   1.310s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   6.343s  |   6.343s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |   3.641s  |   3.641s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |  30.105s  |  30.105s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |   3.162s  |   3.162s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   2.171s  |   2.171s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   1.372s  |   1.372s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |  30.017s  |  30.017s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |  21.030s  |  21.030s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  30.023s  |  30.023s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   2.619s  |   2.619s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   2.273s  |   2.273s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |  30.095s  |  30.095s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |  21.186s  |  21.186s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |  30.029s  |  30.029s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           |  30.020s  |  30.020s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   2.524s  |   2.524s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   1.228s  |   1.228s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   0.772s  |   0.772s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  13.372s  |  13.372s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |   2.605s  |   2.605s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   0.807s  |   0.807s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.208s  |   1.208s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            |   2.126s  |   2.126s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.591s  |   0.591s  |   0.000s  | 0.0%|
</details>
