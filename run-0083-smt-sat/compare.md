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
Job tag: smt-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: b870ed192ada7f98d3a98c8140a2b1899ef09449
Z3 branch: sls
Z3 options: "-T:20 -v:2 smt.sls.enable=false sat.smt=true -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_SAT
Z3 commit message: include disequality expansion for non-unit case.

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: b870ed192ada7f98d3a98c8140a2b1899ef09449
Z3 branch: sls
Z3 options: "-T:20 -v:2 smt.sls.enable=false sat.smt=true -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_SAT
Z3 commit message: include disequality expansion for non-unit case.

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   1.408s  |   1.408s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   5.820s  |   5.820s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.919s  |   0.919s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   1.408s  |   1.408s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   5.820s  |   5.820s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.919s  |   0.919s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   1.408s  |   1.408s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   5.820s  |   5.820s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.919s  |   0.919s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   1.408s  |   1.408s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   5.820s  |   5.820s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.919s  |   0.919s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2               |  20.052s |674.0MiB|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                           |  20.048s |533.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  20.043s |672.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                             |  20.042s |545.0MiB|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                            |  20.039s |466.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2            |  20.039s |457.0MiB|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                            |  20.034s |533.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2               |  20.032s |491.0MiB|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                               |  20.031s |382.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2              |  20.031s |691.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2            |  20.030s |301.0MiB|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                              |  20.030s |364.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                      |  20.030s |266.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                        |  20.029s |305.0MiB|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                 |  20.029s |411.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              |  20.029s |585.0MiB|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                          |  20.029s |481.0MiB|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                  |  20.029s |368.0MiB|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                |  20.028s |384.0MiB|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                              |  20.028s |341.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2               |  20.052s |674.0MiB|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                           |  20.048s |533.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  20.043s |672.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                             |  20.042s |545.0MiB|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                            |  20.039s |466.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2            |  20.039s |457.0MiB|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                            |  20.034s |533.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2               |  20.032s |491.0MiB|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                               |  20.031s |382.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2              |  20.031s |691.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2            |  20.030s |301.0MiB|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                              |  20.030s |364.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                      |  20.030s |266.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                        |  20.029s |305.0MiB|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                 |  20.029s |411.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              |  20.029s |585.0MiB|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                          |  20.029s |481.0MiB|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                  |  20.029s |368.0MiB|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                |  20.028s |384.0MiB|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                              |  20.028s |341.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |87.712MiB|87.712MiB|0B| 0.0%|
|1010.smt2                                                                                   |127.0MiB|127.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |30.18MiB|30.18MiB|0B| 0.0%|
|1021.smt2                                                                                   |30.392MiB|30.392MiB|0B| 0.0%|
|1034.smt2                                                                                   |33.472MiB|33.472MiB|0B| 0.0%|
|1063.smt2                                                                                   |51.3MiB|51.3MiB|0B| 0.0%|
|107.smt2                                                                                    |26.972MiB|26.972MiB|0B| 0.0%|
|1082.smt2                                                                                   |109.0MiB|109.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |29.04MiB|29.04MiB|0B| 0.0%|
|1090.smt2                                                                                   |28.968MiB|28.968MiB|0B| 0.0%|
|1092.smt2                                                                                   |35.364MiB|35.364MiB|0B| 0.0%|
|1104.smt2                                                                                   |30.408MiB|30.408MiB|0B| 0.0%|
|1112.smt2                                                                                   |31.476MiB|31.476MiB|0B| 0.0%|
|1113.smt2                                                                                   |31.496MiB|31.496MiB|0B| 0.0%|
|1126.smt2                                                                                   |32.46MiB|32.46MiB|0B| 0.0%|
|1132.smt2                                                                                   |33.4MiB|33.4MiB|0B| 0.0%|
|1148.smt2                                                                                   |35.684MiB|35.684MiB|0B| 0.0%|
|1152.smt2                                                                                   |46.804MiB|46.804MiB|0B| 0.0%|
|1176.smt2                                                                                   |48.012MiB|48.012MiB|0B| 0.0%|
|1188.smt2                                                                                   |52.944MiB|52.944MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |87.712MiB|87.712MiB|0B| 0.0%|
|1010.smt2                                                                                   |127.0MiB|127.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |30.18MiB|30.18MiB|0B| 0.0%|
|1021.smt2                                                                                   |30.392MiB|30.392MiB|0B| 0.0%|
|1034.smt2                                                                                   |33.472MiB|33.472MiB|0B| 0.0%|
|1063.smt2                                                                                   |51.3MiB|51.3MiB|0B| 0.0%|
|107.smt2                                                                                    |26.972MiB|26.972MiB|0B| 0.0%|
|1082.smt2                                                                                   |109.0MiB|109.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |29.04MiB|29.04MiB|0B| 0.0%|
|1090.smt2                                                                                   |28.968MiB|28.968MiB|0B| 0.0%|
|1092.smt2                                                                                   |35.364MiB|35.364MiB|0B| 0.0%|
|1104.smt2                                                                                   |30.408MiB|30.408MiB|0B| 0.0%|
|1112.smt2                                                                                   |31.476MiB|31.476MiB|0B| 0.0%|
|1113.smt2                                                                                   |31.496MiB|31.496MiB|0B| 0.0%|
|1126.smt2                                                                                   |32.46MiB|32.46MiB|0B| 0.0%|
|1132.smt2                                                                                   |33.4MiB|33.4MiB|0B| 0.0%|
|1148.smt2                                                                                   |35.684MiB|35.684MiB|0B| 0.0%|
|1152.smt2                                                                                   |46.804MiB|46.804MiB|0B| 0.0%|
|1176.smt2                                                                                   |48.012MiB|48.012MiB|0B| 0.0%|
|1188.smt2                                                                                   |52.944MiB|52.944MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |87.712MiB|87.712MiB|0B| 0.0%|
|1010.smt2                                                                                   |127.0MiB|127.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |30.18MiB|30.18MiB|0B| 0.0%|
|1021.smt2                                                                                   |30.392MiB|30.392MiB|0B| 0.0%|
|1034.smt2                                                                                   |33.472MiB|33.472MiB|0B| 0.0%|
|1063.smt2                                                                                   |51.3MiB|51.3MiB|0B| 0.0%|
|107.smt2                                                                                    |26.972MiB|26.972MiB|0B| 0.0%|
|1082.smt2                                                                                   |109.0MiB|109.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |29.04MiB|29.04MiB|0B| 0.0%|
|1090.smt2                                                                                   |28.968MiB|28.968MiB|0B| 0.0%|
|1092.smt2                                                                                   |35.364MiB|35.364MiB|0B| 0.0%|
|1104.smt2                                                                                   |30.408MiB|30.408MiB|0B| 0.0%|
|1112.smt2                                                                                   |31.476MiB|31.476MiB|0B| 0.0%|
|1113.smt2                                                                                   |31.496MiB|31.496MiB|0B| 0.0%|
|1126.smt2                                                                                   |32.46MiB|32.46MiB|0B| 0.0%|
|1132.smt2                                                                                   |33.4MiB|33.4MiB|0B| 0.0%|
|1148.smt2                                                                                   |35.684MiB|35.684MiB|0B| 0.0%|
|1152.smt2                                                                                   |46.804MiB|46.804MiB|0B| 0.0%|
|1176.smt2                                                                                   |48.012MiB|48.012MiB|0B| 0.0%|
|1188.smt2                                                                                   |52.944MiB|52.944MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |87.712MiB|87.712MiB|0B| 0.0%|
|1010.smt2                                                                                   |127.0MiB|127.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |30.18MiB|30.18MiB|0B| 0.0%|
|1021.smt2                                                                                   |30.392MiB|30.392MiB|0B| 0.0%|
|1034.smt2                                                                                   |33.472MiB|33.472MiB|0B| 0.0%|
|1063.smt2                                                                                   |51.3MiB|51.3MiB|0B| 0.0%|
|107.smt2                                                                                    |26.972MiB|26.972MiB|0B| 0.0%|
|1082.smt2                                                                                   |109.0MiB|109.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |29.04MiB|29.04MiB|0B| 0.0%|
|1090.smt2                                                                                   |28.968MiB|28.968MiB|0B| 0.0%|
|1092.smt2                                                                                   |35.364MiB|35.364MiB|0B| 0.0%|
|1104.smt2                                                                                   |30.408MiB|30.408MiB|0B| 0.0%|
|1112.smt2                                                                                   |31.476MiB|31.476MiB|0B| 0.0%|
|1113.smt2                                                                                   |31.496MiB|31.496MiB|0B| 0.0%|
|1126.smt2                                                                                   |32.46MiB|32.46MiB|0B| 0.0%|
|1132.smt2                                                                                   |33.4MiB|33.4MiB|0B| 0.0%|
|1148.smt2                                                                                   |35.684MiB|35.684MiB|0B| 0.0%|
|1152.smt2                                                                                   |46.804MiB|46.804MiB|0B| 0.0%|
|1176.smt2                                                                                   |48.012MiB|48.012MiB|0B| 0.0%|
|1188.smt2                                                                                   |52.944MiB|52.944MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2               |  19.924s |783.0MiB|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                |  18.547s |768.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2               |  19.985s |735.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2              |  20.031s |691.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2               |  20.052s |674.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  20.043s |672.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              |  20.029s |585.0MiB|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                |  20.016s |582.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                             |  20.042s |545.0MiB|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                           |  20.048s |533.0MiB|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                            |  20.034s |533.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2               |  20.032s |491.0MiB|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                          |  20.029s |481.0MiB|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                            |  20.039s |466.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2            |  20.039s |457.0MiB|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                             |  19.935s |436.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          |  20.011s |422.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2           |  20.013s |418.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              |  20.020s |414.0MiB|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                 |  20.029s |411.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2               |  19.924s |783.0MiB|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                |  18.547s |768.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2               |  19.985s |735.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2              |  20.031s |691.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2               |  20.052s |674.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  20.043s |672.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              |  20.029s |585.0MiB|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                |  20.016s |582.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                             |  20.042s |545.0MiB|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                           |  20.048s |533.0MiB|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                            |  20.034s |533.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2               |  20.032s |491.0MiB|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                          |  20.029s |481.0MiB|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                            |  20.039s |466.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2            |  20.039s |457.0MiB|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                             |  19.935s |436.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          |  20.011s |422.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2           |  20.013s |418.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              |  20.020s |414.0MiB|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                 |  20.029s |411.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   1.408s  |   1.408s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   5.820s  |   5.820s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.919s  |   0.919s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   1.077s  |   1.077s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   1.018s  |   1.018s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.676s  |   0.676s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.712s  |   0.712s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   1.607s  |   1.607s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   0.907s  |   0.907s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   0.834s  |   0.834s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.647s  |   0.647s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   3.029s  |   3.029s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   5.961s  |   5.961s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   1.304s  |   1.304s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   9.256s  |   9.256s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.578s  |   0.578s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   0.975s  |   0.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |  19.077s  |  19.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   7.145s  |   7.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |   1.162s  |   1.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   2.070s  |   2.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |   4.514s  |   4.514s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   6.089s  |   6.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   0.992s  |   0.992s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   3.234s  |   3.234s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |   6.448s  |   6.448s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  18.118s  |  18.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              |   6.407s  |   6.407s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   5.358s  |   5.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          |   4.487s  |   4.487s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   1.258s  |   1.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   6.964s  |   6.964s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |   1.589s  |   1.589s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |   1.253s  |   1.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   1.298s  |   1.298s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |   4.907s  |   4.907s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   0.634s  |   0.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |  19.944s  |  19.944s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |  13.620s  |  13.620s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   0.982s  |   0.982s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   8.720s  |   8.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |  14.968s  |  14.968s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   2.956s  |   2.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   2.017s  |   2.017s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   1.054s  |   1.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   1.090s  |   1.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |   2.035s  |   2.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   9.156s  |   9.156s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   1.217s  |   1.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |   3.443s  |   3.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |  14.828s  |  14.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |  19.571s  |  19.571s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |   1.806s  |   1.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |   1.276s  |   1.276s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |  11.453s  |  11.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |   2.260s  |   2.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |  16.748s  |  16.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |  16.995s  |  16.995s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   1.683s  |   1.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   1.285s  |   1.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   4.953s  |   4.953s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   1.926s  |   1.926s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |   9.528s  |   9.528s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.772s  |   0.772s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  19.711s  |  19.711s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   1.592s  |   1.592s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |   0.756s  |   0.756s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |   6.861s  |   6.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |   8.873s  |   8.873s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   2.829s  |   2.829s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |  17.978s  |  17.978s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |   2.536s  |   2.536s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   6.712s  |   6.712s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |  10.816s  |  10.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |   1.157s  |   1.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   4.451s  |   4.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |   9.194s  |   9.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   0.772s  |   0.772s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |   1.675s  |   1.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   3.849s  |   3.849s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |   0.978s  |   0.978s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   1.378s  |   1.378s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |   5.122s  |   5.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   4.584s  |   4.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |   1.806s  |   1.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     |   9.418s  |   9.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   7.061s  |   7.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   7.906s  |   7.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |   4.176s  |   4.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |   1.663s  |   1.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |   8.245s  |   8.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |   3.580s  |   3.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   3.002s  |   3.002s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |   2.485s  |   2.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   1.945s  |   1.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   0.742s  |   0.742s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |   7.463s  |   7.463s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   1.452s  |   1.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   2.925s  |   2.925s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |  10.262s  |  10.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   2.861s  |   2.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |   2.590s  |   2.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |   3.272s  |   3.272s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |   1.221s  |   1.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |   3.060s  |   3.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   2.299s  |   2.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |  14.230s  |  14.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   7.601s  |   7.601s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |   3.379s  |   3.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |   1.665s  |   1.665s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   0.647s  |   0.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   4.230s  |   4.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   3.552s  |   3.552s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |   3.792s  |   3.792s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |  17.395s  |  17.395s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |   9.821s  |   9.821s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |   1.510s  |   1.510s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   6.579s  |   6.579s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |   7.083s  |   7.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   1.909s  |   1.909s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |   1.623s  |   1.623s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |  11.409s  |  11.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |   2.724s  |   2.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |   0.825s  |   0.825s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              |   4.207s  |   4.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |  12.006s  |  12.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   1.862s  |   1.862s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |   5.485s  |   5.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |  19.070s  |  19.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |  13.130s  |  13.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |   1.058s  |   1.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   8.153s  |   8.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |   2.931s  |   2.931s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   2.432s  |   2.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   1.733s  |   1.733s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |   8.553s  |   8.553s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   1.891s  |   1.891s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |   0.723s  |   0.723s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   1.695s  |   1.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |  18.599s  |  18.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   7.447s  |   7.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   2.184s  |   2.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   1.318s  |   1.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  10.244s  |  10.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |   2.570s  |   2.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |   3.417s  |   3.417s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   3.398s  |   3.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   8.715s  |   8.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |   2.453s  |   2.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   3.386s  |   3.386s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   1.007s  |   1.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   1.311s  |   1.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |   2.422s  |   2.422s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |   1.982s  |   1.982s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |   3.991s  |   3.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |   3.847s  |   3.847s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |   0.837s  |   0.837s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   1.388s  |   1.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |   2.268s  |   2.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   1.134s  |   1.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |   2.036s  |   2.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |   4.556s  |   4.556s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   3.599s  |   3.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   0.608s  |   0.608s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   6.317s  |   6.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |   4.823s  |   4.823s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |   1.753s  |   1.753s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |   2.439s  |   2.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   2.684s  |   2.684s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |   4.421s  |   4.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   3.916s  |   3.916s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |   3.378s  |   3.378s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |   4.921s  |   4.921s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |   5.677s  |   5.677s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |   1.722s  |   1.722s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   2.514s  |   2.514s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   0.489s  |   0.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |  17.990s  |  17.990s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |   4.574s  |   4.574s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   0.779s  |   0.779s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   2.820s  |   2.820s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     |   7.403s  |   7.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |   2.574s  |   2.574s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   6.330s  |   6.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |  11.013s  |  11.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   1.211s  |   1.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   1.089s  |   1.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   6.727s  |   6.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |   1.588s  |   1.588s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |   8.285s  |   8.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   3.359s  |   3.359s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |   1.161s  |   1.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   1.292s  |   1.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |  12.460s  |  12.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   0.772s  |   0.772s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |  14.626s  |  14.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |  18.648s  |  18.648s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  18.229s  |  18.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |   1.891s  |   1.891s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  15.772s  |  15.772s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |   8.144s  |   8.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   3.121s  |   3.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |   3.339s  |   3.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   1.676s  |   1.676s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   2.025s  |   2.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |  15.145s  |  15.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |   3.177s  |   3.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |   1.325s  |   1.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   5.859s  |   5.859s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |   0.989s  |   0.989s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |   1.583s  |   1.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |   1.954s  |   1.954s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   1.162s  |   1.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   2.291s  |   2.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   1.212s  |   1.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |   2.945s  |   2.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   0.734s  |   0.734s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |   8.070s  |   8.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   0.986s  |   0.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   0.652s  |   0.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |   5.918s  |   5.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   1.469s  |   1.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   7.877s  |   7.877s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   1.573s  |   1.573s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   1.597s  |   1.597s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   1.339s  |   1.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   0.765s  |   0.765s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   0.690s  |   0.690s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |   3.116s  |   3.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   1.474s  |   1.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  13.389s  |  13.389s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |   1.102s  |   1.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |   9.506s  |   9.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |   0.976s  |   0.976s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   2.186s  |   2.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |   9.897s  |   9.897s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |   1.837s  |   1.837s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   1.247s  |   1.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  19.924s  |  19.924s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                |   9.934s  |   9.934s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |   1.232s  |   1.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |   4.167s  |   4.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |   7.633s  |   7.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |   3.405s  |   3.405s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   4.727s  |   4.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   1.292s  |   1.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   1.773s  |   1.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |   7.821s  |   7.821s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |   1.370s  |   1.370s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   1.443s  |   1.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |   1.694s  |   1.694s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |   1.113s  |   1.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   1.987s  |   1.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   2.484s  |   2.484s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   2.414s  |   2.414s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   1.489s  |   1.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   1.668s  |   1.668s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   1.044s  |   1.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   0.814s  |   0.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   1.860s  |   1.860s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |  17.534s  |  17.534s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |  12.090s  |  12.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |  19.883s  |  19.883s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |  17.901s  |  17.901s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |   6.359s  |   6.359s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |   0.632s  |   0.632s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   0.626s  |   0.626s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   0.558s  |   0.558s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |   2.063s  |   2.063s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |  19.848s  |  19.848s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |  19.360s  |  19.360s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |   2.308s  |   2.308s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |   3.649s  |   3.649s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  13.368s  |  13.368s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |   1.158s  |   1.158s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |   4.997s  |   4.997s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |   4.674s  |   4.674s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   3.397s  |   3.397s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   2.046s  |   2.046s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |   6.276s  |   6.276s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   4.167s  |   4.167s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   0.920s  |   0.920s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   1.383s  |   1.383s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   0.992s  |   0.992s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |  11.766s  |  11.766s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   3.951s  |   3.951s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   3.814s  |   3.814s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   1.942s  |   1.942s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   6.655s  |   6.655s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   1.748s  |   1.748s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |  11.133s  |  11.133s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   0.809s  |   0.809s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   1.280s  |   1.280s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |   4.536s  |   4.536s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |  18.356s  |  18.356s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |   2.971s  |   2.971s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |   6.641s  |   6.641s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |   3.332s  |   3.332s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |   1.449s  |   1.449s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 |  18.547s  |  18.547s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   4.341s  |   4.341s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |   1.266s  |   1.266s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  17.532s  |  17.532s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   4.078s  |   4.078s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   2.820s  |   2.820s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |   1.880s  |   1.880s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   2.125s  |   2.125s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 |  19.948s  |  19.948s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   6.392s  |   6.392s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |  14.988s  |  14.988s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          |  13.251s  |  13.251s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   0.941s  |   0.941s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        |   3.584s  |   3.584s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        |  11.666s  |  11.666s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        |  14.127s  |  14.127s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |  11.623s  |  11.623s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   2.044s  |   2.044s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |   3.611s  |   3.611s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             |   4.945s  |   4.945s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |  12.666s  |  12.666s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   2.173s  |   2.173s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |  19.931s  |  19.931s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   6.201s  |   6.201s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |  15.833s  |  15.833s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   0.950s  |   0.950s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   3.085s  |   3.085s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |   4.197s  |   4.197s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |   6.400s  |   6.400s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |   0.585s  |   0.585s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |   1.530s  |   1.530s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   8.897s  |   8.897s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |   8.163s  |   8.163s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |   2.047s  |   2.047s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            |   6.658s  |   6.658s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |   1.585s  |   1.585s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |   1.180s  |   1.180s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |  10.676s  |  10.676s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |  12.779s  |  12.779s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   6.804s  |   6.804s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   3.230s  |   3.230s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |   1.721s  |   1.721s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   0.982s  |   0.982s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                |   0.690s  |   0.690s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |   2.193s  |   2.193s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |   0.765s  |   0.765s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |   1.037s  |   1.037s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   0.634s  |   0.634s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   1.539s  |   1.539s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   0.515s  |   0.515s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |   0.850s  |   0.850s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |   1.386s  |   1.386s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   2.166s  |   2.166s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |   0.919s  |   0.919s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   2.064s  |   2.064s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |   2.580s  |   2.580s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          |  11.257s  |  11.257s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |   4.976s  |   4.976s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |   3.299s  |   3.299s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |  12.447s  |  12.447s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |  14.741s  |  14.741s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   0.620s  |   0.620s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |   1.777s  |   1.777s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   0.979s  |   0.979s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |   2.700s  |   2.700s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |   1.278s  |   1.278s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   4.775s  |   4.775s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |   1.901s  |   1.901s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   1.416s  |   1.416s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |  16.649s  |  16.649s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   4.793s  |   4.793s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   8.379s  |   8.379s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   1.748s  |   1.748s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         |   1.034s  |   1.034s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |   2.038s  |   2.038s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         |  16.831s  |  16.831s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   4.330s  |   4.330s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           |   9.361s  |   9.361s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   2.374s  |   2.374s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   1.028s  |   1.028s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   3.514s  |   3.514s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   0.586s  |   0.586s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   6.536s  |   6.536s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |   2.353s  |   2.353s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |   3.060s  |   3.060s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  19.884s  |  19.884s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   8.341s  |   8.341s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |   9.290s  |   9.290s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |   9.305s  |   9.305s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   3.042s  |   3.042s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  19.679s  |  19.679s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  17.055s  |  17.055s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |   3.566s  |   3.566s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   1.971s  |   1.971s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |   8.449s  |   8.449s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   1.121s  |   1.121s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   6.060s  |   6.060s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   5.240s  |   5.240s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |  10.174s  |  10.174s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |   4.669s  |   4.669s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |  12.003s  |  12.003s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |   5.576s  |   5.576s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |   2.875s  |   2.875s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |  12.926s  |  12.926s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   0.557s  |   0.557s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  13.520s  |  13.520s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   6.532s  |   6.532s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   3.111s  |   3.111s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   6.333s  |   6.333s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  19.922s  |  19.922s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   4.339s  |   4.339s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |   2.523s  |   2.523s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   2.040s  |   2.040s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   1.344s  |   1.344s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   3.491s  |   3.491s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           |   1.462s  |   1.462s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   1.303s  |   1.303s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   1.574s  |   1.574s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   3.650s  |   3.650s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   0.557s  |   0.557s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   1.397s  |   1.397s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   0.898s  |   0.898s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           |   3.194s  |   3.194s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   0.764s  |   0.764s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |  13.591s  |  13.591s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   7.011s  |   7.011s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |   1.302s  |   1.302s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   7.189s  |   7.189s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   1.718s  |   1.718s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |   2.879s  |   2.879s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   0.588s  |   0.588s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   1.129s  |   1.129s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   1.986s  |   1.986s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   2.047s  |   2.047s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   0.625s  |   0.625s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   0.881s  |   0.881s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   1.412s  |   1.412s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   0.973s  |   0.973s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   4.969s  |   4.969s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |   5.883s  |   5.883s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |  10.789s  |  10.789s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            |   4.912s  |   4.912s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
</details>
