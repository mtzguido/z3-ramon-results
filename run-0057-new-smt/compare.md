Comparing data and data


# SUMMARY
- LHS tests = 1341
- RHS tests = 1341
- LHS success = 709  (52.87099179716629%)
- RHS success = 709  (52.87099179716629%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: new-smt
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 6f37da5a0797278590f082aa22024f281dece8e0
Z3 branch: sls
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" sat.smt=true model_validate=true"
Z3 inputs: inputs/QF_NIA_SAT
Z3 commit message: validate sls-arith lemmas

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: new-smt
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 6f37da5a0797278590f082aa22024f281dece8e0
Z3 branch: sls
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" sat.smt=true model_validate=true"
Z3 inputs: inputs/QF_NIA_SAT
Z3 commit message: validate sls-arith lemmas

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1010.smt2                                                                                   |   6.185s  |   6.185s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.232s  |   1.232s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   1.250s  |   1.250s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   2.265s  |   2.265s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   3.812s  |   3.812s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   5.955s  |   5.955s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   6.475s  |   6.475s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   1.937s  |   1.937s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   1.729s  |   1.729s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   7.868s  |   7.868s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   3.637s  |   3.637s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   1.011s  |   1.011s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1010.smt2                                                                                   |   6.185s  |   6.185s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.232s  |   1.232s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   1.250s  |   1.250s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   2.265s  |   2.265s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   3.812s  |   3.812s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   5.955s  |   5.955s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   6.475s  |   6.475s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   1.937s  |   1.937s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   1.729s  |   1.729s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   7.868s  |   7.868s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   3.637s  |   3.637s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   1.011s  |   1.011s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1010.smt2                                                                                   |   6.185s  |   6.185s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.232s  |   1.232s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   1.250s  |   1.250s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   2.265s  |   2.265s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   3.812s  |   3.812s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   5.955s  |   5.955s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   6.475s  |   6.475s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   1.937s  |   1.937s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   1.729s  |   1.729s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   7.868s  |   7.868s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   3.637s  |   3.637s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   1.011s  |   1.011s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1010.smt2                                                                                   |   6.185s  |   6.185s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.232s  |   1.232s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   1.250s  |   1.250s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   2.265s  |   2.265s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   3.812s  |   3.812s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   5.955s  |   5.955s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   6.475s  |   6.475s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   1.937s  |   1.937s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   1.729s  |   1.729s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   7.868s  |   7.868s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   3.637s  |   3.637s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   1.011s  |   1.011s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|177.smt2                                                                                   |  19.890s |88.196MiB|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                |  19.889s |456.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2            |  19.875s |258.0MiB|
|aproveSMT5598217329789101375.smt2                                                          |  19.855s |228.0MiB|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                            |  19.851s |386.0MiB|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                    |  19.826s |132.0MiB|
|aproveSMT4408268044216253595.smt2                                                          |  19.822s |190.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  19.770s |228.0MiB|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2            |  19.768s |86.276MiB|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                             |  19.764s |154.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2            |  19.763s |203.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                       |  19.751s |385.0MiB|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                 |  19.740s |288.0MiB|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                    |  19.728s |241.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2               |  19.721s |315.0MiB|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                     |  19.718s |82.316MiB|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                               |  19.702s |293.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                   |  19.692s |321.0MiB|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                |  19.677s |265.0MiB|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                     |  19.673s |227.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|177.smt2                                                                                   |  19.890s |88.196MiB|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                |  19.889s |456.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2            |  19.875s |258.0MiB|
|aproveSMT5598217329789101375.smt2                                                          |  19.855s |228.0MiB|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                            |  19.851s |386.0MiB|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                    |  19.826s |132.0MiB|
|aproveSMT4408268044216253595.smt2                                                          |  19.822s |190.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  19.770s |228.0MiB|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2            |  19.768s |86.276MiB|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                             |  19.764s |154.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2            |  19.763s |203.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                       |  19.751s |385.0MiB|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                 |  19.740s |288.0MiB|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                    |  19.728s |241.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2               |  19.721s |315.0MiB|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                     |  19.718s |82.316MiB|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                               |  19.702s |293.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                   |  19.692s |321.0MiB|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                |  19.677s |265.0MiB|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                     |  19.673s |227.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1010.smt2                                                                                   |132.0MiB|132.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |30.548MiB|30.548MiB|0B| 0.0%|
|1021.smt2                                                                                   |30.788MiB|30.788MiB|0B| 0.0%|
|1034.smt2                                                                                   |34.408MiB|34.408MiB|0B| 0.0%|
|1063.smt2                                                                                   |52.788MiB|52.788MiB|0B| 0.0%|
|107.smt2                                                                                    |28.588MiB|28.588MiB|0B| 0.0%|
|1082.smt2                                                                                   |111.0MiB|111.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |33.424MiB|33.424MiB|0B| 0.0%|
|1090.smt2                                                                                   |32.56MiB|32.56MiB|0B| 0.0%|
|1092.smt2                                                                                   |33.868MiB|33.868MiB|0B| 0.0%|
|1104.smt2                                                                                   |34.928MiB|34.928MiB|0B| 0.0%|
|1112.smt2                                                                                   |34.624MiB|34.624MiB|0B| 0.0%|
|1113.smt2                                                                                   |37.924MiB|37.924MiB|0B| 0.0%|
|1126.smt2                                                                                   |40.352MiB|40.352MiB|0B| 0.0%|
|1132.smt2                                                                                   |37.644MiB|37.644MiB|0B| 0.0%|
|1148.smt2                                                                                   |38.856MiB|38.856MiB|0B| 0.0%|
|1152.smt2                                                                                   |49.764MiB|49.764MiB|0B| 0.0%|
|1176.smt2                                                                                   |56.128MiB|56.128MiB|0B| 0.0%|
|1190.smt2                                                                                   |64.368MiB|64.368MiB|0B| 0.0%|
|1192.smt2                                                                                   |61.528MiB|61.528MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1010.smt2                                                                                   |132.0MiB|132.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |30.548MiB|30.548MiB|0B| 0.0%|
|1021.smt2                                                                                   |30.788MiB|30.788MiB|0B| 0.0%|
|1034.smt2                                                                                   |34.408MiB|34.408MiB|0B| 0.0%|
|1063.smt2                                                                                   |52.788MiB|52.788MiB|0B| 0.0%|
|107.smt2                                                                                    |28.588MiB|28.588MiB|0B| 0.0%|
|1082.smt2                                                                                   |111.0MiB|111.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |33.424MiB|33.424MiB|0B| 0.0%|
|1090.smt2                                                                                   |32.56MiB|32.56MiB|0B| 0.0%|
|1092.smt2                                                                                   |33.868MiB|33.868MiB|0B| 0.0%|
|1104.smt2                                                                                   |34.928MiB|34.928MiB|0B| 0.0%|
|1112.smt2                                                                                   |34.624MiB|34.624MiB|0B| 0.0%|
|1113.smt2                                                                                   |37.924MiB|37.924MiB|0B| 0.0%|
|1126.smt2                                                                                   |40.352MiB|40.352MiB|0B| 0.0%|
|1132.smt2                                                                                   |37.644MiB|37.644MiB|0B| 0.0%|
|1148.smt2                                                                                   |38.856MiB|38.856MiB|0B| 0.0%|
|1152.smt2                                                                                   |49.764MiB|49.764MiB|0B| 0.0%|
|1176.smt2                                                                                   |56.128MiB|56.128MiB|0B| 0.0%|
|1190.smt2                                                                                   |64.368MiB|64.368MiB|0B| 0.0%|
|1192.smt2                                                                                   |61.528MiB|61.528MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1010.smt2                                                                                   |132.0MiB|132.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |30.548MiB|30.548MiB|0B| 0.0%|
|1021.smt2                                                                                   |30.788MiB|30.788MiB|0B| 0.0%|
|1034.smt2                                                                                   |34.408MiB|34.408MiB|0B| 0.0%|
|1063.smt2                                                                                   |52.788MiB|52.788MiB|0B| 0.0%|
|107.smt2                                                                                    |28.588MiB|28.588MiB|0B| 0.0%|
|1082.smt2                                                                                   |111.0MiB|111.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |33.424MiB|33.424MiB|0B| 0.0%|
|1090.smt2                                                                                   |32.56MiB|32.56MiB|0B| 0.0%|
|1092.smt2                                                                                   |33.868MiB|33.868MiB|0B| 0.0%|
|1104.smt2                                                                                   |34.928MiB|34.928MiB|0B| 0.0%|
|1112.smt2                                                                                   |34.624MiB|34.624MiB|0B| 0.0%|
|1113.smt2                                                                                   |37.924MiB|37.924MiB|0B| 0.0%|
|1126.smt2                                                                                   |40.352MiB|40.352MiB|0B| 0.0%|
|1132.smt2                                                                                   |37.644MiB|37.644MiB|0B| 0.0%|
|1148.smt2                                                                                   |38.856MiB|38.856MiB|0B| 0.0%|
|1152.smt2                                                                                   |49.764MiB|49.764MiB|0B| 0.0%|
|1176.smt2                                                                                   |56.128MiB|56.128MiB|0B| 0.0%|
|1190.smt2                                                                                   |64.368MiB|64.368MiB|0B| 0.0%|
|1192.smt2                                                                                   |61.528MiB|61.528MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1010.smt2                                                                                   |132.0MiB|132.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |30.548MiB|30.548MiB|0B| 0.0%|
|1021.smt2                                                                                   |30.788MiB|30.788MiB|0B| 0.0%|
|1034.smt2                                                                                   |34.408MiB|34.408MiB|0B| 0.0%|
|1063.smt2                                                                                   |52.788MiB|52.788MiB|0B| 0.0%|
|107.smt2                                                                                    |28.588MiB|28.588MiB|0B| 0.0%|
|1082.smt2                                                                                   |111.0MiB|111.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |33.424MiB|33.424MiB|0B| 0.0%|
|1090.smt2                                                                                   |32.56MiB|32.56MiB|0B| 0.0%|
|1092.smt2                                                                                   |33.868MiB|33.868MiB|0B| 0.0%|
|1104.smt2                                                                                   |34.928MiB|34.928MiB|0B| 0.0%|
|1112.smt2                                                                                   |34.624MiB|34.624MiB|0B| 0.0%|
|1113.smt2                                                                                   |37.924MiB|37.924MiB|0B| 0.0%|
|1126.smt2                                                                                   |40.352MiB|40.352MiB|0B| 0.0%|
|1132.smt2                                                                                   |37.644MiB|37.644MiB|0B| 0.0%|
|1148.smt2                                                                                   |38.856MiB|38.856MiB|0B| 0.0%|
|1152.smt2                                                                                   |49.764MiB|49.764MiB|0B| 0.0%|
|1176.smt2                                                                                   |56.128MiB|56.128MiB|0B| 0.0%|
|1190.smt2                                                                                   |64.368MiB|64.368MiB|0B| 0.0%|
|1192.smt2                                                                                   |61.528MiB|61.528MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                |  19.889s |456.0MiB|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                            |  19.851s |386.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                       |  19.751s |385.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                             |  13.699s |382.0MiB|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                         |  12.102s |375.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          |  16.774s |352.0MiB|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                              |  19.334s |347.0MiB|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                          |  16.086s |339.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                   |  19.692s |321.0MiB|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                            |  10.967s |317.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2               |  19.721s |315.0MiB|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                               |  19.702s |293.0MiB|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                 |  19.625s |291.0MiB|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                 |  19.740s |288.0MiB|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                    |  11.764s |284.0MiB|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                |  19.677s |265.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2               |  19.551s |263.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2            |  19.875s |258.0MiB|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                 |   9.499s |258.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  19.502s |256.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                |  19.889s |456.0MiB|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                            |  19.851s |386.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                       |  19.751s |385.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                             |  13.699s |382.0MiB|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                         |  12.102s |375.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          |  16.774s |352.0MiB|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                              |  19.334s |347.0MiB|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                          |  16.086s |339.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                   |  19.692s |321.0MiB|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                            |  10.967s |317.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2               |  19.721s |315.0MiB|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                               |  19.702s |293.0MiB|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                 |  19.625s |291.0MiB|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                 |  19.740s |288.0MiB|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                    |  11.764s |284.0MiB|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                |  19.677s |265.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2               |  19.551s |263.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2            |  19.875s |258.0MiB|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                 |   9.499s |258.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  19.502s |256.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1010.smt2                                                                                   |   6.185s  |   6.185s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.232s  |   1.232s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   1.250s  |   1.250s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   2.265s  |   2.265s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   3.812s  |   3.812s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   5.955s  |   5.955s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   6.475s  |   6.475s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   1.937s  |   1.937s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   1.729s  |   1.729s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   7.868s  |   7.868s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   3.637s  |   3.637s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   1.011s  |   1.011s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   1.627s  |   1.627s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   6.930s  |   6.930s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   4.416s  |   4.416s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.734s  |   0.734s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   1.079s  |   1.079s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.620s  |   0.620s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   2.431s  |   2.431s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   1.280s  |   1.280s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.976s  |   0.976s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |  10.763s  |  10.763s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.676s  |   0.676s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   0.867s  |   0.867s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.642s  |   0.642s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   1.436s  |   1.436s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   1.524s  |   1.524s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   1.110s  |   1.110s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.639s  |   0.639s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   4.119s  |   4.119s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |  19.890s  |  19.890s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   1.473s  |   1.473s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   3.281s  |   3.281s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.593s  |   0.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   2.143s  |   2.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 |  11.337s  |  11.337s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   2.802s  |   2.802s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |   4.218s  |   4.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               |  19.432s  |  19.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   2.474s  |   2.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |  19.443s  |  19.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |   4.722s  |   4.722s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          |  19.639s  |  19.639s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   0.798s  |   0.798s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |   0.603s  |   0.603s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |  19.446s  |  19.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |  19.768s  |  19.768s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |  19.526s  |  19.526s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   0.731s  |   0.731s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   4.259s  |   4.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |   2.694s  |   2.694s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   1.635s  |   1.635s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   3.171s  |   3.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |  11.764s  |  11.764s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |  19.826s  |  19.826s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   1.764s  |   1.764s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     |   1.737s  |   1.737s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |   2.137s  |   2.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   1.715s  |   1.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   1.185s  |   1.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   2.131s  |   2.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |   2.107s  |   2.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |  10.513s  |  10.513s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |  19.875s  |  19.875s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |   1.582s  |   1.582s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.478s  |   0.478s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |  19.763s  |  19.763s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |  19.450s  |  19.450s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |   1.382s  |   1.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   0.606s  |   0.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   3.466s  |   3.466s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   1.926s  |   1.926s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.778s  |   0.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   2.557s  |   2.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |   1.111s  |   1.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   0.591s  |   0.591s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |   5.553s  |   5.553s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   6.551s  |   6.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.732s  |   0.732s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  19.377s  |  19.377s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |  19.728s  |  19.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   1.467s  |   1.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   1.210s  |   1.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |   4.215s  |   4.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   6.413s  |   6.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   1.568s  |   1.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |   2.787s  |   2.787s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   9.689s  |   9.689s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |   1.497s  |   1.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |  19.605s  |  19.605s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   1.659s  |   1.659s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |   1.170s  |   1.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |   3.903s  |   3.903s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   1.968s  |   1.968s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   0.764s  |   0.764s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   1.022s  |   1.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  19.551s  |  19.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   2.587s  |   2.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |   2.878s  |   2.878s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |   1.980s  |   1.980s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   1.137s  |   1.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   0.626s  |   0.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   5.377s  |   5.377s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   1.024s  |   1.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   1.104s  |   1.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   1.216s  |   1.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   2.066s  |   2.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   1.626s  |   1.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   0.742s  |   0.742s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |   1.197s  |   1.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   0.736s  |   0.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   1.194s  |   1.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |   1.024s  |   1.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  19.721s  |  19.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  19.511s  |  19.511s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   0.945s  |   0.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   1.019s  |   1.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   4.231s  |   4.231s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   1.417s  |   1.417s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   1.713s  |   1.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |   0.876s  |   0.876s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   1.460s  |   1.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |   1.539s  |   1.539s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |  19.556s  |  19.556s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   1.080s  |   1.080s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  19.334s  |  19.334s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |   3.908s  |   3.908s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  19.764s  |  19.764s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  19.677s  |  19.677s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |  19.718s  |  19.718s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            |  19.442s  |  19.442s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 |  19.889s  |  19.889s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   1.451s  |   1.451s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |   1.795s  |   1.795s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       |   2.036s  |   2.036s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   1.355s  |   1.355s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |  19.651s  |  19.651s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   0.565s  |   0.565s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   9.523s  |   9.523s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   1.044s  |   1.044s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |  19.428s  |  19.428s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |  19.487s  |  19.487s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  |  19.625s  |  19.625s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 |  19.502s  |  19.502s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |   1.815s  |   1.815s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        |  19.751s  |  19.751s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    |  19.692s  |  19.692s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |  19.587s  |  19.587s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   1.538s  |   1.538s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |  19.317s  |  19.317s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             |  10.967s  |  10.967s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             |  19.851s  |  19.851s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   3.705s  |   3.705s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   3.573s  |   3.573s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               |  19.770s  |  19.770s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |   2.230s  |   2.230s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   1.397s  |   1.397s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   1.052s  |   1.052s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   0.781s  |   0.781s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |  19.348s  |  19.348s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   1.361s  |   1.361s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |  12.102s  |  12.102s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |   5.537s  |   5.537s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |   1.123s  |   1.123s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |  19.643s  |  19.643s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |   1.202s  |   1.202s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |   3.050s  |   3.050s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   0.545s  |   0.545s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |   0.848s  |   0.848s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |  19.647s  |  19.647s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |   2.470s  |   2.470s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   5.605s  |   5.605s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  19.740s  |  19.740s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   0.557s  |   0.557s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   4.464s  |   4.464s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   3.424s  |   3.424s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           |   3.498s  |   3.498s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   0.803s  |   0.803s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   0.867s  |   0.867s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |  19.702s  |  19.702s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |   5.867s  |   5.867s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  19.672s  |  19.672s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |  19.661s  |  19.661s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   0.510s  |   0.510s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |   4.164s  |   4.164s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |   0.652s  |   0.652s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   2.190s  |   2.190s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  19.416s  |  19.416s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |   1.738s  |   1.738s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           |  19.567s  |  19.567s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   3.946s  |   3.946s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   1.395s  |   1.395s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |  19.822s  |  19.822s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.474s  |   0.474s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   0.844s  |   0.844s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   2.294s  |   2.294s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |  19.616s  |  19.616s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |  19.855s  |  19.855s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   1.925s  |   1.925s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |   3.161s  |   3.161s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |  19.623s  |  19.623s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   0.946s  |   0.946s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   0.619s  |   0.619s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   0.945s  |   0.945s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   1.462s  |   1.462s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   1.037s  |   1.037s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            |  19.443s  |  19.443s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.029s  |   0.029s  |   0.000s  | 0.0%|
</details>
