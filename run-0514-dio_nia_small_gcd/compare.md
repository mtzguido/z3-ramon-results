Comparing data and data


# SUMMARY
- LHS tests = 2313
- RHS tests = 2313
- LHS success = 2313  (100.0%)
- RHS success = 2313  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: dio_nia_small_gcd
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 36a0006f595c746a98c133ba38671ab5659dacf6
Z3 branch: 
Z3 options: "-T:600 -st lp.dio=true lp.dio_run_gcd=true"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: remove testing code in is_big_term_on_no_term

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: dio_nia_small_gcd
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 36a0006f595c746a98c133ba38671ab5659dacf6
Z3 branch: 
Z3 options: "-T:600 -st lp.dio=true lp.dio_run_gcd=true"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: remove testing code in is_big_term_on_no_term

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 599.691s  | 599.691s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 599.052s  | 599.052s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.038s  |   2.038s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.386s  |   1.386s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.863s  | 598.863s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 599.691s  | 599.691s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 599.052s  | 599.052s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.038s  |   2.038s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.386s  |   1.386s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.863s  | 598.863s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 599.691s  | 599.691s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 599.052s  | 599.052s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.038s  |   2.038s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.386s  |   1.386s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.863s  | 598.863s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 599.691s  | 599.691s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 599.052s  | 599.052s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.038s  |   2.038s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.386s  |   1.386s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.863s  | 598.863s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 600.106s |1944.0MiB|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                         | 600.054s |1545.0MiB|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                            | 600.026s |1313.0MiB|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                               | 599.947s |1245.0MiB|
|aproveSMT1802082844053698751.smt2                                                          | 599.941s |227.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 599.919s |852.0MiB|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                           | 599.915s |1312.0MiB|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                     | 599.905s |638.0MiB|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                        | 599.904s |1135.0MiB|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                | 599.901s |438.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 599.900s |753.0MiB|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                         | 599.889s |124.0MiB|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                         | 599.885s |903.0MiB|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                  | 599.883s |513.0MiB|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                     | 599.882s |405.0MiB|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                 | 599.855s |250.0MiB|
|98.smt2                                                                                    | 599.855s |187.0MiB|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                 | 599.848s |251.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 599.809s |1342.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                      | 599.799s |93.936MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 600.106s |1944.0MiB|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                         | 600.054s |1545.0MiB|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                            | 600.026s |1313.0MiB|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                               | 599.947s |1245.0MiB|
|aproveSMT1802082844053698751.smt2                                                          | 599.941s |227.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 599.919s |852.0MiB|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                           | 599.915s |1312.0MiB|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                     | 599.905s |638.0MiB|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                        | 599.904s |1135.0MiB|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                | 599.901s |438.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 599.900s |753.0MiB|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                         | 599.889s |124.0MiB|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                         | 599.885s |903.0MiB|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                  | 599.883s |513.0MiB|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                     | 599.882s |405.0MiB|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                 | 599.855s |250.0MiB|
|98.smt2                                                                                    | 599.855s |187.0MiB|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                 | 599.848s |251.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 599.809s |1342.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                      | 599.799s |93.936MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |88.984MiB|88.984MiB|0B| 0.0%|
|04.smt2                                                                                     |70.476MiB|70.476MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |28.436MiB|28.436MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.548MiB|30.548MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.444MiB|23.444MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.536MiB|23.536MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.568MiB|24.568MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.916MiB|24.916MiB|0B| 0.0%|
|107.smt2                                                                                    |22.316MiB|22.316MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.204MiB|27.204MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.228MiB|80.228MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.164MiB|23.164MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.896MiB|22.896MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.988MiB|23.988MiB|0B| 0.0%|
|11.smt2                                                                                     |68.824MiB|68.824MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.952MiB|23.952MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.288MiB|23.288MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.448MiB|23.448MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.62MiB|25.62MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |88.984MiB|88.984MiB|0B| 0.0%|
|04.smt2                                                                                     |70.476MiB|70.476MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |28.436MiB|28.436MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.548MiB|30.548MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.444MiB|23.444MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.536MiB|23.536MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.568MiB|24.568MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.916MiB|24.916MiB|0B| 0.0%|
|107.smt2                                                                                    |22.316MiB|22.316MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.204MiB|27.204MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.228MiB|80.228MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.164MiB|23.164MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.896MiB|22.896MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.988MiB|23.988MiB|0B| 0.0%|
|11.smt2                                                                                     |68.824MiB|68.824MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.952MiB|23.952MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.288MiB|23.288MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.448MiB|23.448MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.62MiB|25.62MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |88.984MiB|88.984MiB|0B| 0.0%|
|04.smt2                                                                                     |70.476MiB|70.476MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |28.436MiB|28.436MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.548MiB|30.548MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.444MiB|23.444MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.536MiB|23.536MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.568MiB|24.568MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.916MiB|24.916MiB|0B| 0.0%|
|107.smt2                                                                                    |22.316MiB|22.316MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.204MiB|27.204MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.228MiB|80.228MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.164MiB|23.164MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.896MiB|22.896MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.988MiB|23.988MiB|0B| 0.0%|
|11.smt2                                                                                     |68.824MiB|68.824MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.952MiB|23.952MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.288MiB|23.288MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.448MiB|23.448MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.62MiB|25.62MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |88.984MiB|88.984MiB|0B| 0.0%|
|04.smt2                                                                                     |70.476MiB|70.476MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |28.436MiB|28.436MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.548MiB|30.548MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.444MiB|23.444MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.536MiB|23.536MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.568MiB|24.568MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.916MiB|24.916MiB|0B| 0.0%|
|107.smt2                                                                                    |22.316MiB|22.316MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.204MiB|27.204MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.228MiB|80.228MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.164MiB|23.164MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.896MiB|22.896MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.988MiB|23.988MiB|0B| 0.0%|
|11.smt2                                                                                     |68.824MiB|68.824MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.952MiB|23.952MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.288MiB|23.288MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.448MiB|23.448MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.62MiB|25.62MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 599.423s |2633.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               | 598.458s |2367.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 599.757s |2250.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 599.591s |2067.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 600.106s |1944.0MiB|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                               | 599.396s |1907.0MiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       | 599.789s |1862.0MiB|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                            | 597.647s |1811.0MiB|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                           | 599.567s |1700.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 599.146s |1623.0MiB|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                               | 599.108s |1598.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 599.360s |1553.0MiB|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                         | 600.054s |1545.0MiB|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                               | 599.143s |1542.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 599.152s |1538.0MiB|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                           | 599.550s |1513.0MiB|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                               | 599.720s |1505.0MiB|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                 | 599.695s |1499.0MiB|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                       | 599.683s |1468.0MiB|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                            | 599.514s |1380.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 599.423s |2633.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               | 598.458s |2367.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 599.757s |2250.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 599.591s |2067.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 600.106s |1944.0MiB|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                               | 599.396s |1907.0MiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       | 599.789s |1862.0MiB|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                            | 597.647s |1811.0MiB|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                           | 599.567s |1700.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 599.146s |1623.0MiB|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                               | 599.108s |1598.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 599.360s |1553.0MiB|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                         | 600.054s |1545.0MiB|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                               | 599.143s |1542.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 599.152s |1538.0MiB|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                           | 599.550s |1513.0MiB|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                               | 599.720s |1505.0MiB|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                 | 599.695s |1499.0MiB|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                       | 599.683s |1468.0MiB|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                            | 599.514s |1380.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 599.691s  | 599.691s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 599.052s  | 599.052s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.038s  |   2.038s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.386s  |   1.386s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.863s  | 598.863s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|124.smt2                                                                                    | 599.151s  | 599.151s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.824s  |   0.824s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   1.219s  |   1.219s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.757s  |   0.757s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|140.smt2                                                                                    | 599.716s  | 599.716s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   1.897s  |   1.897s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   1.208s  |   1.208s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.474s  |   0.474s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   5.824s  |   5.824s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   4.916s  |   4.916s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   4.273s  |   4.273s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   1.234s  |   1.234s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|177.smt2                                                                                    | 598.842s  | 598.842s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   0.831s  |   0.831s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   2.615s  |   2.615s  |   0.000s  | 0.0%|
|181.smt2                                                                                    | 599.362s  | 599.362s  |   0.000s  | 0.0%|
|182.smt2                                                                                    | 599.184s  | 599.184s  |   0.000s  | 0.0%|
|183.smt2                                                                                    | 599.422s  | 599.422s  |   0.000s  | 0.0%|
|185.smt2                                                                                    | 599.343s  | 599.343s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   1.623s  |   1.623s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   1.799s  |   1.799s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   1.276s  |   1.276s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   2.132s  |   2.132s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   4.321s  |   4.321s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   4.921s  |   4.921s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   5.846s  |   5.846s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   2.574s  |   2.574s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   2.676s  |   2.676s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   1.709s  |   1.709s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   1.263s  |   1.263s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   1.330s  |   1.330s  |   0.000s  | 0.0%|
|35.smt2                                                                                     | 599.075s  | 599.075s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|40.smt2                                                                                     | 598.495s  | 598.495s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   2.015s  |   2.015s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   1.058s  |   1.058s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|54.smt2                                                                                     | 599.318s  | 599.318s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   2.513s  |   2.513s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   2.148s  |   2.148s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   2.230s  |   2.230s  |   0.000s  | 0.0%|
|58.smt2                                                                                     | 599.253s  | 599.253s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   2.063s  |   2.063s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   2.401s  |   2.401s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   4.469s  |   4.469s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|65.smt2                                                                                     | 598.947s  | 598.947s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   5.206s  |   5.206s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   5.337s  |   5.337s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|73.smt2                                                                                     | 599.201s  | 599.201s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.939s  |   0.939s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   4.422s  |   4.422s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   1.146s  |   1.146s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   3.158s  |   3.158s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|966.smt2                                                                                    |   3.381s  |   3.381s  |   0.000s  | 0.0%|
|98.smt2                                                                                     | 599.855s  | 599.855s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|99.smt2                                                                                     | 599.433s  | 599.433s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |  61.786s  |  61.786s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   1.064s  |   1.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   4.706s  |   4.706s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          | 599.463s  | 599.463s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |   6.338s  |   6.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   1.171s  |   1.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |  20.997s  |  20.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          | 222.916s  | 222.916s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   9.059s  |   9.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   2.773s  |   2.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            | 599.712s  | 599.712s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   6.037s  |   6.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   3.053s  |   3.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       | 598.728s  | 598.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   2.872s  |   2.872s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          | 101.078s  | 101.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   4.458s  |   4.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |  78.239s  |  78.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   2.646s  |   2.646s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   1.435s  |   1.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           | 599.653s  | 599.653s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           | 587.719s  | 587.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |   3.077s  |   3.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   5.390s  |   5.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  17.160s  |  17.160s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   4.785s  |   4.785s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |   8.593s  |   8.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         | 599.151s  | 599.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             | 584.033s  | 584.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |  50.874s  |  50.874s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  53.819s  |  53.819s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             | 598.942s  | 598.942s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 | 599.231s  | 599.231s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   2.206s  |   2.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   4.434s  |   4.434s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   7.279s  |   7.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   1.570s  |   1.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              |  12.751s  |  12.751s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |  45.184s  |  45.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   1.504s  |   1.504s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |  11.230s  |  11.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               | 599.112s  | 599.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         | 598.839s  | 598.839s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   8.476s  |   8.476s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |  17.096s  |  17.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       | 112.026s  | 112.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 | 323.764s  | 323.764s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      | 598.850s  | 598.850s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   3.079s  |   3.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   3.965s  |   3.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              | 599.318s  | 599.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   4.218s  |   4.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   4.770s  |   4.770s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          | 599.435s  | 599.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   1.034s  |   1.034s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          | 599.089s  | 599.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   4.171s  |   4.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         |  84.438s  |  84.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   2.713s  |   2.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      | 599.521s  | 599.521s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |  12.501s  |  12.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   3.252s  |   3.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   5.992s  |   5.992s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         | 599.070s  | 599.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      | 599.905s  | 599.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               | 598.707s  | 598.707s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  59.072s  |  59.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   | 110.023s  | 110.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |  12.945s  |  12.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           | 598.376s  | 598.376s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               | 447.886s  | 447.886s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   2.178s  |   2.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               |  84.316s  |  84.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |  20.783s  |  20.783s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   4.065s  |   4.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |  13.006s  |  13.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |  27.422s  |  27.422s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   7.763s  |   7.763s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   | 599.278s  | 599.278s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   | 599.297s  | 599.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   | 110.855s  | 110.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             | 599.694s  | 599.694s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  22.233s  |  22.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   1.645s  |   1.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    | 599.068s  | 599.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |  43.416s  |  43.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        | 189.009s  | 189.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  79.316s  |  79.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  94.901s  |  94.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     | 599.501s  | 599.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               | 598.003s  | 598.003s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               | 598.976s  | 598.976s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   4.426s  |   4.426s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   4.393s  |   4.393s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   4.081s  |   4.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |  49.828s  |  49.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               | 599.507s  | 599.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   1.327s  |   1.327s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   4.596s  |   4.596s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   4.940s  |   4.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   3.540s  |   3.540s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   2.235s  |   2.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   8.321s  |   8.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                | 599.037s  | 599.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              | 599.076s  | 599.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              | 119.873s  | 119.873s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   1.782s  |   1.782s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   6.181s  |   6.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  30.768s  |  30.768s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  80.707s  |  80.707s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   2.457s  |   2.457s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  28.154s  |  28.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          | 344.538s  | 344.538s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          | 599.761s  | 599.761s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |   9.524s  |   9.524s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          | 599.299s  | 599.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          | 599.017s  | 599.017s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  46.201s  |  46.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   9.064s  |   9.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  28.937s  |  28.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   4.031s  |   4.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    | 599.147s  | 599.147s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   4.511s  |   4.511s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   3.005s  |   3.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    | 599.342s  | 599.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   4.239s  |   4.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   4.225s  |   4.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |  35.421s  |  35.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |  23.737s  |  23.737s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        | 599.432s  | 599.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |   4.934s  |   4.934s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |  26.063s  |  26.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   7.012s  |   7.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        | 337.156s  | 337.156s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   1.575s  |   1.575s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  46.376s  |  46.376s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  52.778s  |  52.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  46.264s  |  46.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  59.110s  |  59.110s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  88.951s  |  88.951s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              |  37.730s  |  37.730s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  33.822s  |  33.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  | 159.593s  | 159.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  | 157.471s  | 157.471s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |  75.552s  |  75.552s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |  29.154s  |  29.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   2.510s  |   2.510s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              | 599.123s  | 599.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   3.175s  |   3.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |  64.934s  |  64.934s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |  10.400s  |  10.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   4.470s  |   4.470s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  20.795s  |  20.795s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        | 190.943s  | 190.943s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   2.433s  |   2.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |  23.652s  |  23.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |   3.872s  |   3.872s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   | 599.285s  | 599.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   | 599.314s  | 599.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     | 599.268s  | 599.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   5.123s  |   5.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   2.298s  |   2.298s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     | 597.983s  | 597.983s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 | 598.998s  | 598.998s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                |  49.770s  |  49.770s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   2.204s  |   2.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                | 599.590s  | 599.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      | 598.885s  | 598.885s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   9.513s  |   9.513s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      | 598.730s  | 598.730s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      | 599.204s  | 599.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   7.492s  |   7.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      | 599.618s  | 599.618s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |  12.694s  |  12.694s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   1.245s  |   1.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   2.066s  |   2.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   5.194s  |   5.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   3.249s  |   3.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |  18.297s  |  18.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   5.013s  |   5.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   | 210.838s  | 210.838s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  13.916s  |  13.916s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             | 523.252s  | 523.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   5.542s  |   5.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          | 598.755s  | 598.755s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               | 594.904s  | 594.904s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                | 232.673s  | 232.673s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   6.345s  |   6.345s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |  12.149s  |  12.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   1.869s  |   1.869s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   4.000s  |   4.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   4.005s  |   4.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   8.895s  |   8.895s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   1.365s  |   1.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              | 599.323s  | 599.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   8.717s  |   8.717s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   3.066s  |   3.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   7.633s  |   7.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   4.547s  |   4.547s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  59.038s  |  59.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          | 599.048s  | 599.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |   5.179s  |   5.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          | 599.143s  | 599.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          | 599.885s  | 599.885s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |  13.703s  |  13.703s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          | 599.398s  | 599.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          | 598.945s  | 598.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |  15.268s  |  15.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          | 599.547s  | 599.547s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   6.010s  |   6.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            | 599.403s  | 599.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   3.889s  |   3.889s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |   8.033s  |   8.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |  14.984s  |  14.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            | 599.415s  | 599.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   7.567s  |   7.567s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           | 599.457s  | 599.457s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   2.271s  |   2.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   3.452s  |   3.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   0.944s  |   0.944s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   3.200s  |   3.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |   6.400s  |   6.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   3.142s  |   3.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   2.751s  |   2.751s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           | 421.283s  | 421.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           | 599.589s  | 599.589s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           | 599.792s  | 599.792s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           | 599.416s  | 599.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   2.749s  |   2.749s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   1.655s  |   1.655s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           | 599.124s  | 599.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   2.507s  |   2.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   2.314s  |   2.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |  72.573s  |  72.573s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |  11.142s  |  11.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   1.231s  |   1.231s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           | 599.498s  | 599.498s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   2.247s  |   2.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   1.462s  |   1.462s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |  32.493s  |  32.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  30.267s  |  30.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           | 599.409s  | 599.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |  99.421s  |  99.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |  10.202s  |  10.202s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           | 598.692s  | 598.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |   1.744s  |   1.744s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   2.736s  |   2.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |  13.925s  |  13.925s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   2.224s  |   2.224s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           | 598.186s  | 598.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   2.302s  |   2.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   6.412s  |   6.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   3.251s  |   3.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |  50.478s  |  50.478s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   2.119s  |   2.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           | 158.157s  | 158.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   2.207s  |   2.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           | 599.199s  | 599.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  22.948s  |  22.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           | 598.827s  | 598.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   2.264s  |   2.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           | 599.748s  | 599.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     | 599.099s  | 599.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   2.088s  |   2.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   2.157s  |   2.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     | 599.200s  | 599.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   2.611s  |   2.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |   7.587s  |   7.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     | 123.824s  | 123.824s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   2.183s  |   2.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |  25.495s  |  25.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     | 599.493s  | 599.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     | 599.418s  | 599.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |  22.925s  |  22.925s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |   8.582s  |   8.582s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   1.288s  |   1.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   1.298s  |   1.298s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   6.140s  |   6.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   2.752s  |   2.752s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   3.282s  |   3.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   2.395s  |   2.395s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   2.598s  |   2.598s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   5.349s  |   5.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   5.510s  |   5.510s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     | 599.572s  | 599.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |   4.838s  |   4.838s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |  12.192s  |  12.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   1.696s  |   1.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   3.162s  |   3.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |   1.635s  |   1.635s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               | 598.332s  | 598.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     | 599.406s  | 599.406s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   2.695s  |   2.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     | 599.420s  | 599.420s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |   6.700s  |   6.700s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |   3.906s  |   3.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   2.265s  |   2.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |  54.685s  |  54.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |  28.935s  |  28.935s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   2.231s  |   2.231s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |  18.065s  |  18.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   8.136s  |   8.136s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |   9.012s  |   9.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     | 599.403s  | 599.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     | 598.801s  | 598.801s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  21.270s  |  21.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   6.090s  |   6.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               | 599.197s  | 599.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   1.174s  |   1.174s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   1.782s  |   1.782s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               | 599.374s  | 599.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               | 599.531s  | 599.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |  17.529s  |  17.529s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   7.307s  |   7.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |   4.254s  |   4.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               | 599.236s  | 599.236s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               | 599.080s  | 599.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |  62.140s  |  62.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               | 599.437s  | 599.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               | 599.183s  | 599.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               | 598.037s  | 598.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               | 599.180s  | 599.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               | 142.356s  | 142.356s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   2.662s  |   2.662s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   2.133s  |   2.133s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  44.953s  |  44.953s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               | 599.498s  | 599.498s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   1.971s  |   1.971s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               | 598.716s  | 598.716s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   6.467s  |   6.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |  10.744s  |  10.744s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               | 599.444s  | 599.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               | 189.783s  | 189.783s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   1.427s  |   1.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   2.961s  |   2.961s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   6.275s  |   6.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   1.374s  |   1.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   0.965s  |   0.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               | 599.263s  | 599.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               | 596.869s  | 596.869s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   2.172s  |   2.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   3.396s  |   3.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               | 599.008s  | 599.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   8.181s  |   8.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               | 597.720s  | 597.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               | 599.344s  | 599.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   2.505s  |   2.505s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               | 597.940s  | 597.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               | 115.714s  | 115.714s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |   7.266s  |   7.266s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   5.241s  |   5.241s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |   9.570s  |   9.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             | 598.828s  | 598.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   0.685s  |   0.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |  12.514s  |  12.514s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             | 598.822s  | 598.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |   7.032s  |   7.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   2.257s  |   2.257s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   5.751s  |   5.751s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   6.111s  |   6.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   2.166s  |   2.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   2.293s  |   2.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |  15.052s  |  15.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   1.721s  |   1.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |  14.627s  |  14.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   2.858s  |   2.858s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             | 599.634s  | 599.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |  21.447s  |  21.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |   1.988s  |   1.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   5.273s  |   5.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   2.418s  |   2.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             | 599.537s  | 599.537s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   2.229s  |   2.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             | 599.006s  | 599.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |  39.605s  |  39.605s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |   2.359s  |   2.359s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |  14.152s  |  14.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |  39.063s  |  39.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   1.298s  |   1.298s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |   6.644s  |   6.644s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |  10.896s  |  10.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             | 598.593s  | 598.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   5.405s  |   5.405s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             | 598.901s  | 598.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             | 228.472s  | 228.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             | 598.920s  | 598.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   1.022s  |   1.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             | 599.486s  | 599.486s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   1.035s  |   1.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             | 599.406s  | 599.406s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               | 139.853s  | 139.853s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |  55.600s  |  55.600s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               | 594.964s  | 594.964s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |  10.071s  |  10.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |   7.872s  |   7.872s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         | 152.983s  | 152.983s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        | 263.094s  | 263.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              |  60.924s  |  60.924s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   1.247s  |   1.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   2.421s  |   2.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |   0.865s  |   0.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   1.549s  |   1.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    | 599.214s  | 599.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |  73.353s  |  73.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |   9.111s  |   9.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   2.019s  |   2.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   2.381s  |   2.381s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   8.869s  |   8.869s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |  91.709s  |  91.709s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    | 599.303s  | 599.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   2.164s  |   2.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    | 599.772s  | 599.772s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   5.300s  |   5.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   2.225s  |   2.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   2.523s  |   2.523s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    | 599.061s  | 599.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    | 599.433s  | 599.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    | 599.686s  | 599.686s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   2.319s  |   2.319s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   2.557s  |   2.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    | 555.243s  | 555.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   1.606s  |   1.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    | 599.738s  | 599.738s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |  35.968s  |  35.968s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    | 597.626s  | 597.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   1.123s  |   1.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  13.292s  |  13.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  58.480s  |  58.480s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |  53.888s  |  53.888s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   2.357s  |   2.357s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    | 599.488s  | 599.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |  64.219s  |  64.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |  25.219s  |  25.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   2.215s  |   2.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    | 599.245s  | 599.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   3.477s  |   3.477s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    | 598.891s  | 598.891s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    | 598.807s  | 598.807s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   7.886s  |   7.886s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   2.325s  |   2.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   6.799s  |   6.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |  13.584s  |  13.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   1.127s  |   1.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   2.190s  |   2.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |   9.364s  |   9.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   2.388s  |   2.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          | 596.732s  | 596.732s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   2.749s  |   2.749s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          | 598.745s  | 598.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   8.109s  |   8.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  12.469s  |  12.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |  32.613s  |  32.613s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          | 598.387s  | 598.387s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |  16.972s  |  16.972s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          | 599.107s  | 599.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   7.436s  |   7.436s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          | 597.570s  | 597.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   6.252s  |   6.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |   7.245s  |   7.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   2.360s  |   2.360s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   2.160s  |   2.160s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          | 599.341s  | 599.341s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          | 599.046s  | 599.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   1.426s  |   1.426s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   1.690s  |   1.690s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          | 599.499s  | 599.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   5.245s  |   5.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   2.302s  |   2.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   5.669s  |   5.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        | 599.360s  | 599.360s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   8.525s  |   8.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        | 599.608s  | 599.608s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   1.815s  |   1.815s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |   7.107s  |   7.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |  17.059s  |  17.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |  13.922s  |  13.922s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |   1.306s  |   1.306s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |  14.536s  |  14.536s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |  19.518s  |  19.518s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   2.243s  |   2.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |  10.908s  |  10.908s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   1.207s  |   1.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        | 598.946s  | 598.946s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   1.943s  |   1.943s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |   7.230s  |   7.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |   3.527s  |   3.527s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   2.514s  |   2.514s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   6.950s  |   6.950s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |   1.672s  |   1.672s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   2.370s  |   2.370s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        | 599.542s  | 599.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   2.134s  |   2.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |   1.784s  |   1.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        | 598.907s  | 598.907s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        | 133.859s  | 133.859s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   2.328s  |   2.328s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |  15.790s  |  15.790s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   2.221s  |   2.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        | 598.961s  | 598.961s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        | 599.706s  | 599.706s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        | 598.272s  | 598.272s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |   6.119s  |   6.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   2.374s  |   2.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |  60.184s  |  60.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |  11.703s  |  11.703s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        | 599.254s  | 599.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   8.069s  |   8.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        | 598.029s  | 598.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   5.394s  |   5.394s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  | 598.502s  | 598.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   2.181s  |   2.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   6.232s  |   6.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   5.880s  |   5.880s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |  14.134s  |  14.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |  48.638s  |  48.638s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   8.283s  |   8.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |  30.516s  |  30.516s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   1.044s  |   1.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     | 598.988s  | 598.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |   9.149s  |   9.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   2.172s  |   2.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   3.348s  |   3.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     | 599.548s  | 599.548s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     | 599.753s  | 599.753s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     | 598.916s  | 598.916s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   3.061s  |   3.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   6.290s  |   6.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       | 599.666s  | 599.666s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |   7.225s  |   7.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |   9.393s  |   9.393s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   2.853s  |   2.853s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       | 131.418s  | 131.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |  18.449s  |  18.449s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       | 598.888s  | 598.888s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   4.191s  |   4.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       | 173.066s  | 173.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       | 599.002s  | 599.002s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   2.418s  |   2.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   3.108s  |   3.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   2.118s  |   2.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   2.697s  |   2.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       | 599.799s  | 599.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       | 599.555s  | 599.555s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 | 219.515s  | 219.515s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   2.393s  |   2.393s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   1.848s  |   1.848s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   2.645s  |   2.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       | 599.630s  | 599.630s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       | 599.421s  | 599.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |  25.720s  |  25.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 | 599.024s  | 599.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  92.205s  |  92.205s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |  25.865s  |  25.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  42.186s  |  42.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   3.158s  |   3.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |  11.530s  |  11.530s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  16.898s  |  16.898s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   1.162s  |   1.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            | 598.717s  | 598.717s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  81.123s  |  81.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |  11.127s  |  11.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            | 599.252s  | 599.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  18.516s  |  18.516s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   1.561s  |   1.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  | 599.561s  | 599.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            | 425.097s  | 425.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   3.642s  |   3.642s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   3.187s  |   3.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   4.632s  |   4.632s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   5.218s  |   5.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   2.822s  |   2.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   3.015s  |   3.015s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   3.164s  |   3.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |  16.176s  |  16.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   2.958s  |   2.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   5.979s  |   5.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   3.209s  |   3.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   1.870s  |   1.870s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |  10.311s  |  10.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   3.041s  |   3.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   5.669s  |   5.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   4.940s  |   4.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   8.986s  |   8.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |  14.255s  |  14.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |  15.983s  |  15.983s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |  37.255s  |  37.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   1.310s  |   1.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   2.436s  |   2.436s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   4.347s  |   4.347s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   3.817s  |   3.817s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   5.349s  |   5.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  16.798s  |  16.798s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   8.082s  |   8.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  41.602s  |  41.602s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |   7.771s  |   7.771s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   3.960s  |   3.960s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |  17.435s  |  17.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  41.737s  |  41.737s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   4.026s  |   4.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   1.833s  |   1.833s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   3.556s  |   3.556s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |  39.624s  |  39.624s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   4.071s  |   4.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   3.290s  |   3.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   1.698s  |   1.698s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   4.909s  |   4.909s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   3.383s  |   3.383s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |  10.645s  |  10.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   1.306s  |   1.306s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   2.144s  |   2.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   3.727s  |   3.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   2.313s  |   2.313s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   3.732s  |   3.732s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   3.840s  |   3.840s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   3.279s  |   3.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   4.609s  |   4.609s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   3.635s  |   3.635s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   2.114s  |   2.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   3.205s  |   3.205s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  19.936s  |  19.936s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   3.160s  |   3.160s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   2.873s  |   2.873s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  23.473s  |  23.473s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   0.891s  |   0.891s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |  12.534s  |  12.534s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   1.583s  |   1.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   9.364s  |   9.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   3.112s  |   3.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  13.519s  |  13.519s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |  22.697s  |  22.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   2.381s  |   2.381s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   1.652s  |   1.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  66.314s  |  66.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   3.591s  |   3.591s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   1.803s  |   1.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   5.820s  |   5.820s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   8.401s  |   8.401s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |  15.339s  |  15.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   5.816s  |   5.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |  16.920s  |  16.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   5.047s  |   5.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  22.447s  |  22.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  11.279s  |  11.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   7.545s  |   7.545s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   2.775s  |   2.775s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   8.962s  |   8.962s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   3.153s  |   3.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   9.644s  |   9.644s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   1.665s  |   1.665s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                |  26.340s  |  26.340s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |  12.589s  |  12.589s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  18.180s  |  18.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   1.746s  |   1.746s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |  85.416s  |  85.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  31.494s  |  31.494s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   2.767s  |   2.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   1.520s  |   1.520s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   3.076s  |   3.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   2.431s  |   2.431s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   4.099s  |   4.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   2.216s  |   2.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  45.631s  |  45.631s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   2.891s  |   2.891s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |  12.104s  |  12.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   1.371s  |   1.371s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   2.902s  |   2.902s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   3.201s  |   3.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   2.594s  |   2.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |   2.964s  |   2.964s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   3.754s  |   3.754s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |  14.416s  |  14.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |  10.368s  |  10.368s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   4.531s  |   4.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   2.835s  |   2.835s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |  17.294s  |  17.294s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   2.665s  |   2.665s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   6.135s  |   6.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |  10.663s  |  10.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   2.355s  |   2.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |  11.969s  |  11.969s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |  11.942s  |  11.942s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |  12.745s  |  12.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   7.724s  |   7.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   1.713s  |   1.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   7.734s  |   7.734s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   4.655s  |   4.655s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          | 518.495s  | 518.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          | 488.861s  | 488.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          | 282.301s  | 282.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   6.642s  |   6.642s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   4.966s  |   4.966s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             | 599.002s  | 599.002s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            | 598.793s  | 598.793s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            | 599.586s  | 599.586s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   3.068s  |   3.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   4.363s  |   4.363s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   2.376s  |   2.376s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   4.188s  |   4.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |  20.203s  |  20.203s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   9.294s  |   9.294s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       | 119.625s  | 119.625s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   3.439s  |   3.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      | 599.282s  | 599.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   5.962s  |   5.962s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   5.484s  |   5.484s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   1.827s  |   1.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   4.246s  |   4.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       |  32.663s  |  32.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   3.937s  |   3.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   2.437s  |   2.437s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   0.734s  |   0.734s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   5.156s  |   5.156s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   | 599.459s  | 599.459s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |  12.144s  |  12.144s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               | 343.179s  | 343.179s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |   9.781s  |   9.781s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               | 599.606s  | 599.606s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |  70.007s  |  70.007s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |  12.034s  |  12.034s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   3.970s  |   3.970s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          | 599.613s  | 599.613s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          | 599.304s  | 599.304s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   2.525s  |   2.525s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   1.945s  |   1.945s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               |  38.021s  |  38.021s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               | 599.432s  | 599.432s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  20.781s  |  20.781s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               | 598.242s  | 598.242s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               | 598.601s  | 598.601s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |  10.033s  |  10.033s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         | 599.108s  | 599.108s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         | 599.904s  | 599.904s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         | 260.225s  | 260.225s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |   6.192s  |   6.192s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               | 599.028s  | 599.028s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  76.789s  |  76.789s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   4.120s  |   4.120s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |   7.298s  |   7.298s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         | 599.218s  | 599.218s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |  21.275s  |  21.275s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         | 598.606s  | 598.606s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  21.200s  |  21.200s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  85.685s  |  85.685s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    | 599.919s  | 599.919s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  34.300s  |  34.300s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    | 598.341s  | 598.341s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  21.803s  |  21.803s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |   3.284s  |   3.284s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   2.146s  |   2.146s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              | 599.809s  | 599.809s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   | 204.882s  | 204.882s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   5.896s  |   5.896s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   5.592s  |   5.592s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  32.885s  |  32.885s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.650s  |   0.650s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |   9.183s  |   9.183s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |  10.748s  |  10.748s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   6.142s  |   6.142s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   2.890s  |   2.890s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |   4.659s  |   4.659s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   7.162s  |   7.162s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  | 599.695s  | 599.695s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   4.480s  |   4.480s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  47.958s  |  47.958s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 | 599.185s  | 599.185s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 | 599.173s  | 599.173s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  15.069s  |  15.069s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           | 599.330s  | 599.330s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |   9.930s  |   9.930s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |  68.243s  |  68.243s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              | 599.041s  | 599.041s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   3.448s  |   3.448s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              | 598.561s  | 598.561s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              | 599.207s  | 599.207s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  20.252s  |  20.252s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              | 598.973s  | 598.973s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              | 598.465s  | 598.465s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |  35.585s  |  35.585s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              | 598.892s  | 598.892s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              | 599.634s  | 599.634s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   3.261s  |   3.261s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |  34.167s  |  34.167s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  55.019s  |  55.019s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |  13.073s  |  13.073s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      | 370.993s  | 370.993s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     | 182.817s  | 182.817s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          | 113.287s  | 113.287s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  42.848s  |  42.848s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  65.849s  |  65.849s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            |  58.258s  |  58.258s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   3.329s  |   3.329s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             | 599.734s  | 599.734s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   3.632s  |   3.632s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             | 598.996s  | 598.996s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             | 599.181s  | 599.181s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   1.806s  |   1.806s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             | 599.105s  | 599.105s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             | 599.628s  | 599.628s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   1.705s  |   1.705s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 | 597.286s  | 597.286s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  | 598.382s  | 598.382s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |  13.860s  |  13.860s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   4.568s  |   4.568s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             | 598.566s  | 598.566s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   2.166s  |   2.166s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   6.255s  |   6.255s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |  12.008s  |  12.008s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   2.651s  |   2.651s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |  15.470s  |  15.470s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   3.544s  |   3.544s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             | 598.868s  | 598.868s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   3.109s  |   3.109s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   8.724s  |   8.724s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   3.156s  |   3.156s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   1.900s  |   1.900s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   1.092s  |   1.092s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |   9.849s  |   9.849s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   1.820s  |   1.820s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   4.054s  |   4.054s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               | 599.591s  | 599.591s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   2.685s  |   2.685s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            | 598.425s  | 598.425s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   1.444s  |   1.444s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 | 599.443s  | 599.443s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |  12.006s  |  12.006s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  27.573s  |  27.573s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |  11.049s  |  11.049s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           | 599.369s  | 599.369s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |  11.116s  |  11.116s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |  13.950s  |  13.950s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 | 599.008s  | 599.008s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      | 516.057s  | 516.057s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |  11.678s  |  11.678s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |  16.991s  |  16.991s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           | 598.772s  | 598.772s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  24.987s  |  24.987s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |   5.052s  |   5.052s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  26.727s  |  26.727s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              | 599.631s  | 599.631s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |   3.834s  |   3.834s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   3.684s  |   3.684s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   4.043s  |   4.043s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      | 376.749s  | 376.749s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               | 599.382s  | 599.382s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              | 598.836s  | 598.836s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   2.582s  |   2.582s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       | 599.372s  | 599.372s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   2.716s  |   2.716s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       | 131.165s  | 131.165s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   1.161s  |   1.161s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.827s  |   0.827s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       | 599.704s  | 599.704s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |   3.382s  |   3.382s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.655s  |   0.655s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       | 599.236s  | 599.236s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   1.531s  |   1.531s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   4.508s  |   4.508s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |  12.246s  |  12.246s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |  27.993s  |  27.993s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       | 599.268s  | 599.268s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |  16.667s  |  16.667s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       | 599.221s  | 599.221s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   7.622s  |   7.622s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   2.304s  |   2.304s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       | 158.846s  | 158.846s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |   9.883s  |   9.883s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   1.203s  |   1.203s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   3.135s  |   3.135s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       |  68.287s  |  68.287s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       |  74.180s  |  74.180s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   3.684s  |   3.684s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   1.389s  |   1.389s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       | 179.737s  | 179.737s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   4.086s  |   4.086s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   1.428s  |   1.428s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               | 598.900s  | 598.900s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         | 599.676s  | 599.676s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   3.961s  |   3.961s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.761s  |   0.761s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   7.615s  |   7.615s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   1.158s  |   1.158s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 | 599.648s  | 599.648s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   1.326s  |   1.326s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |  10.412s  |  10.412s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |  38.859s  |  38.859s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |   8.931s  |   8.931s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   2.843s  |   2.843s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   5.730s  |   5.730s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                | 598.824s  | 598.824s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   1.685s  |   1.685s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   5.446s  |   5.446s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                | 599.309s  | 599.309s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   4.250s  |   4.250s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |  16.444s  |  16.444s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   3.359s  |   3.359s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      | 599.882s  | 599.882s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   1.641s  |   1.641s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   3.565s  |   3.565s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |   7.774s  |   7.774s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   9.093s  |   9.093s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |  13.250s  |  13.250s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   1.281s  |   1.281s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   2.090s  |   2.090s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   1.871s  |   1.871s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   1.660s  |   1.660s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      | 291.373s  | 291.373s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   4.805s  |   4.805s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   8.668s  |   8.668s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   1.900s  |   1.900s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |  28.992s  |  28.992s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   2.933s  |   2.933s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      | 599.594s  | 599.594s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   2.119s  |   2.119s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      | 599.620s  | 599.620s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   3.624s  |   3.624s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   7.341s  |   7.341s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   2.933s  |   2.933s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   1.628s  |   1.628s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   3.800s  |   3.800s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   9.961s  |   9.961s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   1.972s  |   1.972s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   5.560s  |   5.560s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   3.554s  |   3.554s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   1.452s  |   1.452s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |   1.928s  |   1.928s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   2.883s  |   2.883s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      | 599.506s  | 599.506s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |  12.428s  |  12.428s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   4.147s  |   4.147s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   3.130s  |   3.130s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   5.832s  |   5.832s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   3.755s  |   3.755s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   2.949s  |   2.949s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   9.629s  |   9.629s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |   3.694s  |   3.694s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   1.642s  |   1.642s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   9.298s  |   9.298s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   1.343s  |   1.343s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      | 598.731s  | 598.731s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   0.958s  |   0.958s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      | 598.907s  | 598.907s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   2.759s  |   2.759s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   5.798s  |   5.798s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |  10.721s  |  10.721s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   1.743s  |   1.743s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      | 598.498s  | 598.498s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   7.218s  |   7.218s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   3.411s  |   3.411s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |  23.188s  |  23.188s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |   3.983s  |   3.983s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   6.446s  |   6.446s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   1.224s  |   1.224s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   5.580s  |   5.580s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   3.635s  |   3.635s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   5.784s  |   5.784s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   2.047s  |   2.047s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   3.413s  |   3.413s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   4.228s  |   4.228s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   7.770s  |   7.770s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   3.470s  |   3.470s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   1.734s  |   1.734s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   2.967s  |   2.967s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   4.065s  |   4.065s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |  10.376s  |  10.376s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   8.623s  |   8.623s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   3.010s  |   3.010s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   9.437s  |   9.437s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   3.221s  |   3.221s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   2.907s  |   2.907s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   6.317s  |   6.317s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |  10.787s  |  10.787s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   6.789s  |   6.789s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |  15.571s  |  15.571s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            | 598.750s  | 598.750s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |  17.175s  |  17.175s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  49.081s  |  49.081s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |  22.953s  |  22.953s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  25.547s  |  25.547s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |  22.050s  |  22.050s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        | 599.789s  | 599.789s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        | 229.512s  | 229.512s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  39.502s  |  39.502s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       |  63.081s  |  63.081s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   5.001s  |   5.001s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   5.880s  |   5.880s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     | 598.498s  | 598.498s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     | 599.157s  | 599.157s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     | 599.638s  | 599.638s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |  13.165s  |  13.165s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         | 599.128s  | 599.128s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               | 599.780s  | 599.780s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         | 599.337s  | 599.337s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               | 599.436s  | 599.436s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   3.113s  |   3.113s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |  17.683s  |  17.683s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               | 599.635s  | 599.635s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  | 599.120s  | 599.120s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  | 111.785s  | 111.785s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     |  84.761s  |  84.761s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  52.130s  |  52.130s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  19.440s  |  19.440s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            | 215.576s  | 215.576s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            | 598.940s  | 598.940s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   3.331s  |   3.331s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   2.442s  |   2.442s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                | 599.577s  | 599.577s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   3.492s  |   3.492s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  71.231s  |  71.231s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 | 193.718s  | 193.718s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 | 599.351s  | 599.351s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  44.464s  |  44.464s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 | 599.550s  | 599.550s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  21.834s  |  21.834s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |  87.059s  |  87.059s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           | 539.186s  | 539.186s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           | 599.752s  | 599.752s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           | 255.518s  | 255.518s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |  14.522s  |  14.522s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  66.876s  |  66.876s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |  99.420s  |  99.420s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   7.622s  |   7.622s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  48.674s  |  48.674s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 | 598.752s  | 598.752s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  42.907s  |  42.907s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 |  90.521s  |  90.521s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   4.503s  |   4.503s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 | 306.194s  | 306.194s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 | 599.222s  | 599.222s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |  35.144s  |  35.144s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  41.622s  |  41.622s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 | 423.163s  | 423.163s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   7.147s  |   7.147s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 | 599.901s  | 599.901s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |  19.705s  |  19.705s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  23.203s  |  23.203s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 | 599.686s  | 599.686s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   4.593s  |   4.593s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   9.555s  |   9.555s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 | 598.802s  | 598.802s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  85.495s  |  85.495s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |  11.794s  |  11.794s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 | 385.087s  | 385.087s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 | 599.262s  | 599.262s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   6.239s  |   6.239s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |   6.029s  |   6.029s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 | 599.491s  | 599.491s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   4.165s  |   4.165s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 | 122.976s  | 122.976s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   2.865s  |   2.865s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 | 365.977s  | 365.977s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |   5.784s  |   5.784s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |  11.045s  |  11.045s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   5.886s  |   5.886s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   2.791s  |   2.791s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              | 599.074s  | 599.074s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  21.822s  |  21.822s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 |  56.895s  |  56.895s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 | 135.962s  | 135.962s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 | 109.139s  | 109.139s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        | 599.664s  | 599.664s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  42.558s  |  42.558s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  30.330s  |  30.330s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |  74.689s  |  74.689s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           | 133.204s  | 133.204s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    | 598.650s  | 598.650s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    | 598.551s  | 598.551s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       |  79.458s  |  79.458s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       |  66.900s  |  66.900s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  42.847s  |  42.847s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  75.097s  |  75.097s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |   9.791s  |   9.791s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              | 598.889s  | 598.889s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  66.947s  |  66.947s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  17.982s  |  17.982s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  52.649s  |  52.649s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  70.307s  |  70.307s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  33.322s  |  33.322s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  | 599.063s  | 599.063s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  46.919s  |  46.919s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  42.026s  |  42.026s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   5.583s  |   5.583s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  57.214s  |  57.214s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |  50.939s  |  50.939s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  46.361s  |  46.361s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            | 599.432s  | 599.432s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          | 154.185s  | 154.185s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  66.128s  |  66.128s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  42.271s  |  42.271s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  57.664s  |  57.664s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  87.398s  |  87.398s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   3.495s  |   3.495s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |  13.038s  |  13.038s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        | 482.028s  | 482.028s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        | 599.685s  | 599.685s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |   5.143s  |   5.143s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        |   3.021s  |   3.021s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        |  15.385s  |  15.385s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        | 269.170s  | 269.170s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        | 599.083s  | 599.083s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        | 598.329s  | 598.329s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        | 598.952s  | 598.952s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  | 599.469s  | 599.469s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   1.836s  |   1.836s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |  17.663s  |  17.663s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.919s  |   0.919s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   2.989s  |   2.989s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   4.962s  |   4.962s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  54.181s  |  54.181s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 | 598.364s  | 598.364s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   4.003s  |   4.003s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 | 599.198s  | 599.198s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 | 599.079s  | 599.079s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |  23.711s  |  23.711s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 | 599.305s  | 599.305s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 | 599.662s  | 599.662s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |   9.739s  |   9.739s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   7.336s  |   7.336s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   3.177s  |   3.177s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |  29.999s  |  29.999s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |  21.915s  |  21.915s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             | 572.598s  | 572.598s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             | 600.026s  | 600.026s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   8.012s  |   8.012s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             | 453.422s  | 453.422s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             | 599.365s  | 599.365s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   8.540s  |   8.540s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             | 227.317s  | 227.317s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             | 599.120s  | 599.120s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |   6.087s  |   6.087s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             | 246.979s  | 246.979s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             | 597.888s  | 597.888s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |  19.655s  |  19.655s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             | 598.516s  | 598.516s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             | 597.647s  | 597.647s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   5.392s  |   5.392s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   3.350s  |   3.350s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  | 212.045s  | 212.045s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   1.109s  |   1.109s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   4.549s  |   4.549s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                | 599.654s  | 599.654s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   1.266s  |   1.266s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  14.090s  |  14.090s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           | 599.415s  | 599.415s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 | 599.142s  | 599.142s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   2.467s  |   2.467s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 | 599.063s  | 599.063s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 | 598.719s  | 598.719s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   2.028s  |   2.028s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 | 598.937s  | 598.937s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 | 599.091s  | 599.091s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   3.161s  |   3.161s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           | 598.270s  | 598.270s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   5.121s  |   5.121s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 | 599.269s  | 599.269s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 | 599.427s  | 599.427s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           | 599.384s  | 599.384s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  | 323.411s  | 323.411s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |  12.011s  |  12.011s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 | 599.641s  | 599.641s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 | 599.549s  | 599.549s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   3.092s  |   3.092s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   2.982s  |   2.982s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |  51.022s  |  51.022s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 | 598.448s  | 598.448s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   4.723s  |   4.723s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 | 599.038s  | 599.038s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 | 598.787s  | 598.787s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   3.299s  |   3.299s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 | 599.562s  | 599.562s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   3.733s  |   3.733s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   5.067s  |   5.067s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  |  12.643s  |  12.643s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   9.844s  |   9.844s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |  12.407s  |  12.407s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            | 377.444s  | 377.444s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            | 115.831s  | 115.831s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   1.836s  |   1.836s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  | 599.584s  | 599.584s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   1.724s  |   1.724s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  | 598.583s  | 598.583s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  |  39.537s  |  39.537s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            | 599.690s  | 599.690s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   2.377s  |   2.377s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 | 599.331s  | 599.331s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |  21.355s  |  21.355s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  | 599.154s  | 599.154s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   2.720s  |   2.720s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  | 599.848s  | 599.848s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  | 599.225s  | 599.225s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   2.935s  |   2.935s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  | 599.601s  | 599.601s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  | 598.394s  | 598.394s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   7.130s  |   7.130s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  | 599.418s  | 599.418s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  | 598.563s  | 598.563s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            | 126.036s  | 126.036s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            | 598.775s  | 598.775s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   3.812s  |   3.812s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |  12.710s  |  12.710s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   1.383s  |   1.383s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |   9.530s  |   9.530s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           | 599.108s  | 599.108s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           | 599.511s  | 599.511s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           | 598.211s  | 598.211s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  68.165s  |  68.165s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               | 156.278s  | 156.278s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               | 599.372s  | 599.372s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               | 312.658s  | 312.658s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               | 598.897s  | 598.897s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               | 599.282s  | 599.282s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |  24.874s  |  24.874s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   | 122.078s  | 122.078s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 | 241.478s  | 241.478s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |   2.894s  |   2.894s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   4.090s  |   4.090s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |  19.781s  |  19.781s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             | 599.289s  | 599.289s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |   4.686s  |   4.686s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   3.521s  |   3.521s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |   8.532s  |   8.532s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |  11.313s  |  11.313s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   3.795s  |   3.795s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   5.220s  |   5.220s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  26.679s  |  26.679s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  25.994s  |  25.994s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            | 599.595s  | 599.595s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    | 599.667s  | 599.667s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   7.245s  |   7.245s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               | 599.667s  | 599.667s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             | 599.514s  | 599.514s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             | 598.753s  | 598.753s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             | 599.756s  | 599.756s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   6.322s  |   6.322s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             | 598.090s  | 598.090s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             | 599.491s  | 599.491s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   6.536s  |   6.536s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             | 599.362s  | 599.362s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             | 599.286s  | 599.286s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  31.192s  |  31.192s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |   8.547s  |   8.547s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               | 393.821s  | 393.821s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         | 599.152s  | 599.152s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  15.164s  |  15.164s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  16.494s  |  16.494s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  14.911s  |  14.911s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  15.389s  |  15.389s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  45.179s  |  45.179s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        | 599.524s  | 599.524s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   1.067s  |   1.067s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            | 403.644s  | 403.644s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            | 549.902s  | 549.902s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   7.974s  |   7.974s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |   5.090s  |   5.090s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   2.568s  |   2.568s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            | 597.814s  | 597.814s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   2.424s  |   2.424s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  19.054s  |  19.054s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              | 598.248s  | 598.248s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  15.417s  |  15.417s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              | 599.279s  | 599.279s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   2.574s  |   2.574s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  18.846s  |  18.846s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          | 598.700s  | 598.700s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   3.789s  |   3.789s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |  33.126s  |  33.126s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  16.775s  |  16.775s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       | 599.156s  | 599.156s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   2.707s  |   2.707s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       | 126.102s  | 126.102s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   5.278s  |   5.278s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   4.405s  |   4.405s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   6.965s  |   6.965s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         | 599.061s  | 599.061s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |  18.029s  |  18.029s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           | 599.629s  | 599.629s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |   9.160s  |   9.160s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  | 599.493s  | 599.493s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            | 598.418s  | 598.418s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              | 204.424s  | 204.424s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   5.447s  |   5.447s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   4.071s  |   4.071s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |   9.691s  |   9.691s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          | 597.962s  | 597.962s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          | 598.876s  | 598.876s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |  71.720s  |  71.720s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          | 599.623s  | 599.623s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          | 599.091s  | 599.091s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |  14.179s  |  14.179s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          | 599.617s  | 599.617s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          | 599.757s  | 599.757s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |  15.987s  |  15.987s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                | 599.143s  | 599.143s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                | 598.458s  | 598.458s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   3.355s  |   3.355s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                | 599.396s  | 599.396s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                | 599.207s  | 599.207s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |  11.602s  |  11.602s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                | 599.720s  | 599.720s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                | 599.360s  | 599.360s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |  37.947s  |  37.947s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                | 599.108s  | 599.108s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                | 599.146s  | 599.146s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          | 599.157s  | 599.157s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |  18.351s  |  18.351s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          | 599.175s  | 599.175s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |  19.939s  |  19.939s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |   4.667s  |   4.667s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          | 599.407s  | 599.407s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |  40.540s  |  40.540s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                | 599.388s  | 599.388s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   9.979s  |   9.979s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   6.947s  |   6.947s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |  11.092s  |  11.092s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   5.248s  |   5.248s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   4.726s  |   4.726s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |  51.533s  |  51.533s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |  24.402s  |  24.402s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   1.018s  |   1.018s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                | 599.365s  | 599.365s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.548s  |   0.548s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |   8.629s  |   8.629s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                | 599.384s  | 599.384s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                |   8.085s  |   8.085s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |   3.398s  |   3.398s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |  78.502s  |  78.502s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   5.587s  |   5.587s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                | 599.512s  | 599.512s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   6.842s  |   6.842s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |  13.442s  |  13.442s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   1.673s  |   1.673s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                | 599.264s  | 599.264s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |  12.036s  |  12.036s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |  26.924s  |  26.924s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   3.116s  |   3.116s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |  11.033s  |  11.033s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   8.718s  |   8.718s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |  11.995s  |  11.995s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   6.354s  |   6.354s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                | 599.437s  | 599.437s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   2.770s  |   2.770s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   0.906s  |   0.906s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |  12.462s  |  12.462s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                | 599.262s  | 599.262s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                | 598.643s  | 598.643s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |  23.644s  |  23.644s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |  17.639s  |  17.639s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   4.818s  |   4.818s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |  10.679s  |  10.679s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          | 597.991s  | 597.991s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          | 599.046s  | 599.046s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   3.089s  |   3.089s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   3.262s  |   3.262s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |   2.094s  |   2.094s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   7.856s  |   7.856s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |   8.516s  |   8.516s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |  19.369s  |  19.369s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   2.780s  |   2.780s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   2.625s  |   2.625s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |  10.700s  |  10.700s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   8.318s  |   8.318s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          | 599.889s  | 599.889s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |  10.811s  |  10.811s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   2.319s  |   2.319s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   7.907s  |   7.907s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |  13.627s  |  13.627s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   2.428s  |   2.428s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |   3.110s  |   3.110s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   9.955s  |   9.955s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |  13.242s  |  13.242s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          | 599.559s  | 599.559s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          | 599.260s  | 599.260s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          | 599.633s  | 599.633s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          | 599.326s  | 599.326s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |  13.296s  |  13.296s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   2.430s  |   2.430s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          | 119.438s  | 119.438s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  54.704s  |  54.704s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     | 188.648s  | 188.648s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |  26.025s  |  26.025s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           | 598.242s  | 598.242s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           | 598.969s  | 598.969s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   2.809s  |   2.809s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |  72.514s  |  72.514s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   5.600s  |   5.600s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   1.841s  |   1.841s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        | 599.284s  | 599.284s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   4.532s  |   4.532s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |   9.710s  |   9.710s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |   1.862s  |   1.862s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   6.700s  |   6.700s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |  34.760s  |  34.760s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   0.908s  |   0.908s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |  12.016s  |  12.016s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        | 599.048s  | 599.048s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   0.796s  |   0.796s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |   9.326s  |   9.326s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |  37.353s  |  37.353s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |  12.616s  |  12.616s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |  21.728s  |  21.728s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |  17.662s  |  17.662s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   2.559s  |   2.559s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |  14.285s  |  14.285s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |  16.011s  |  16.011s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   8.717s  |   8.717s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        | 599.512s  | 599.512s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   3.291s  |   3.291s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   4.349s  |   4.349s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   2.942s  |   2.942s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   9.586s  |   9.586s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |  15.399s  |  15.399s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        | 598.963s  | 598.963s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   6.574s  |   6.574s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        | 599.622s  | 599.622s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  46.090s  |  46.090s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   2.682s  |   2.682s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.749s  |   0.749s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   3.351s  |   3.351s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        | 598.866s  | 598.866s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        | 598.828s  | 598.828s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   4.175s  |   4.175s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |  18.520s  |  18.520s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        |  51.025s  |  51.025s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |  78.243s  |  78.243s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            | 256.853s  | 256.853s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  | 598.786s  | 598.786s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  | 598.972s  | 598.972s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |   8.321s  |   8.321s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  | 599.605s  | 599.605s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  | 595.334s  | 595.334s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   2.725s  |   2.725s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   1.594s  |   1.594s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   2.396s  |   2.396s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   2.459s  |   2.459s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   6.212s  |   6.212s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  | 599.173s  | 599.173s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |  11.146s  |  11.146s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   6.564s  |   6.564s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  | 598.887s  | 598.887s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  | 599.855s  | 599.855s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   3.283s  |   3.283s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |  39.353s  |  39.353s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                | 599.571s  | 599.571s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  55.752s  |  55.752s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   2.641s  |   2.641s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              | 164.524s  | 164.524s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        | 599.134s  | 599.134s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   | 598.343s  | 598.343s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   8.098s  |   8.098s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   | 599.737s  | 599.737s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   | 599.883s  | 599.883s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |  18.069s  |  18.069s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   | 599.339s  | 599.339s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   | 599.063s  | 599.063s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |  21.376s  |  21.376s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   | 599.207s  | 599.207s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         | 460.599s  | 460.599s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   3.679s  |   3.679s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   4.310s  |   4.310s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |   8.321s  |   8.321s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         | 599.180s  | 599.180s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   7.310s  |   7.310s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        | 597.905s  | 597.905s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        | 599.280s  | 599.280s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |  10.102s  |  10.102s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        | 598.014s  | 598.014s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        | 599.683s  | 599.683s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |   8.287s  |   8.287s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        | 599.451s  | 599.451s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   4.147s  |   4.147s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   3.349s  |   3.349s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   2.216s  |   2.216s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  52.065s  |  52.065s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   5.944s  |   5.944s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   3.114s  |   3.114s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |  32.962s  |  32.962s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  36.800s  |  36.800s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      | 113.741s  | 113.741s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |   8.501s  |   8.501s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            | 599.554s  | 599.554s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            | 599.550s  | 599.550s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |  10.145s  |  10.145s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            | 599.915s  | 599.915s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            | 599.567s  | 599.567s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |  10.090s  |  10.090s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            | 598.546s  | 598.546s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  | 598.757s  | 598.757s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   6.839s  |   6.839s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  | 599.371s  | 599.371s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   3.124s  |   3.124s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            | 599.268s  | 599.268s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  28.847s  |  28.847s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  28.009s  |  28.009s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  46.389s  |  46.389s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  60.571s  |  60.571s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |  10.529s  |  10.529s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         | 599.404s  | 599.404s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |  94.759s  |  94.759s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         |  24.900s  |  24.900s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   2.480s  |   2.480s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         | 179.581s  | 179.581s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |  13.128s  |  13.128s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |  32.039s  |  32.039s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   5.438s  |   5.438s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   4.127s  |   4.127s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         | 599.184s  | 599.184s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   5.798s  |   5.798s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   5.521s  |   5.521s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   5.372s  |   5.372s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   3.105s  |   3.105s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   2.947s  |   2.947s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   6.036s  |   6.036s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   9.902s  |   9.902s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   6.240s  |   6.240s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   | 599.018s  | 599.018s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           |   6.169s  |   6.169s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           | 598.920s  | 598.920s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           | 171.127s  | 171.127s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   1.644s  |   1.644s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |  89.074s  |  89.074s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           |  46.887s  |  46.887s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           | 599.546s  | 599.546s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           | 599.034s  | 599.034s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   1.001s  |   1.001s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  | 599.171s  | 599.171s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   2.434s  |   2.434s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   1.487s  |   1.487s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   3.345s  |   3.345s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   4.520s  |   4.520s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   2.189s  |   2.189s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   2.595s  |   2.595s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             | 598.922s  | 598.922s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   2.370s  |   2.370s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   2.947s  |   2.947s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   4.010s  |   4.010s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   3.815s  |   3.815s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |  38.676s  |  38.676s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             | 599.336s  | 599.336s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |  78.908s  |  78.908s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   6.372s  |   6.372s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |   3.960s  |   3.960s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             | 599.710s  | 599.710s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   6.179s  |   6.179s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   0.857s  |   0.857s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |  20.601s  |  20.601s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             | 599.204s  | 599.204s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   2.600s  |   2.600s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |  97.371s  |  97.371s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             | 598.856s  | 598.856s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   6.940s  |   6.940s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |  28.047s  |  28.047s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              | 598.718s  | 598.718s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      | 598.916s  | 598.916s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   2.433s  |   2.433s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          | 599.423s  | 599.423s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                | 598.766s  | 598.766s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |  31.598s  |  31.598s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                | 192.556s  | 192.556s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                | 598.640s  | 598.640s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                | 599.045s  | 599.045s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  28.913s  |  28.913s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                | 599.439s  | 599.439s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                | 599.947s  | 599.947s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  24.684s  |  24.684s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  29.613s  |  29.613s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          | 598.556s  | 598.556s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |  25.024s  |  25.024s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   4.301s  |   4.301s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   3.925s  |   3.925s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              | 599.337s  | 599.337s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       | 599.590s  | 599.590s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       | 598.944s  | 598.944s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  16.846s  |  16.846s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  29.659s  |  29.659s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  56.531s  |  56.531s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  73.088s  |  73.088s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           | 114.819s  | 114.819s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  57.037s  |  57.037s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  12.312s  |  12.312s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   5.250s  |   5.250s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             | 598.819s  | 598.819s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  72.984s  |  72.984s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |  90.104s  |  90.104s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  33.295s  |  33.295s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  46.084s  |  46.084s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  77.707s  |  77.707s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |  58.953s  |  58.953s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  36.333s  |  36.333s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  64.645s  |  64.645s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           | 598.834s  | 598.834s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           | 599.900s  | 599.900s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |  60.021s  |  60.021s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  21.810s  |  21.810s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 | 599.247s  | 599.247s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 | 598.844s  | 598.844s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   9.387s  |   9.387s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |  29.153s  |  29.153s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                | 598.969s  | 598.969s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                | 598.839s  | 598.839s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  12.555s  |  12.555s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          | 117.333s  | 117.333s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          | 599.795s  | 599.795s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          | 599.769s  | 599.769s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          | 284.999s  | 284.999s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |  13.115s  |  13.115s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  21.002s  |  21.002s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     | 257.713s  | 257.713s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   2.007s  |   2.007s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                | 184.590s  | 184.590s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                | 598.427s  | 598.427s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   2.943s  |   2.943s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   4.303s  |   4.303s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            | 598.359s  | 598.359s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |  17.474s  |  17.474s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   5.580s  |   5.580s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  42.191s  |  42.191s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   2.452s  |   2.452s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |   3.071s  |   3.071s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   1.604s  |   1.604s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   1.276s  |   1.276s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |  16.490s  |  16.490s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            | 599.579s  | 599.579s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      | 501.679s  | 501.679s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   2.328s  |   2.328s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      |  56.521s  |  56.521s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   2.318s  |   2.318s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   1.349s  |   1.349s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  39.795s  |  39.795s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |  90.401s  |  90.401s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   2.275s  |   2.275s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  23.522s  |  23.522s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   5.426s  |   5.426s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        | 574.618s  | 574.618s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |  44.171s  |  44.171s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   1.477s  |   1.477s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           | 598.522s  | 598.522s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           | 219.330s  | 219.330s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |  55.405s  |  55.405s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  | 597.748s  | 597.748s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  | 123.607s  | 123.607s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           | 599.045s  | 599.045s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      | 599.310s  | 599.310s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   4.006s  |   4.006s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      | 599.466s  | 599.466s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           | 598.750s  | 598.750s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           | 227.732s  | 227.732s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        | 598.961s  | 598.961s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   2.609s  |   2.609s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   3.286s  |   3.286s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   1.421s  |   1.421s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             | 599.588s  | 599.588s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   1.559s  |   1.559s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   4.541s  |   4.541s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   5.633s  |   5.633s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  18.463s  |  18.463s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   4.740s  |   4.740s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        | 598.689s  | 598.689s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   2.536s  |   2.536s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   1.397s  |   1.397s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |  11.513s  |  11.513s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   3.440s  |   3.440s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  | 119.893s  | 119.893s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |  10.216s  |  10.216s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   5.406s  |   5.406s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   3.219s  |   3.219s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   4.207s  |   4.207s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   1.575s  |   1.575s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           | 599.060s  | 599.060s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  24.889s  |  24.889s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |  10.652s  |  10.652s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   3.078s  |   3.078s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  31.210s  |  31.210s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  31.580s  |  31.580s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   3.424s  |   3.424s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            | 156.019s  | 156.019s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   4.816s  |   4.816s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |  32.210s  |  32.210s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                | 599.142s  | 599.142s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                | 597.840s  | 597.840s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   4.887s  |   4.887s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          | 599.535s  | 599.535s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   2.281s  |   2.281s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   0.944s  |   0.944s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   7.211s  |   7.211s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   1.143s  |   1.143s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  10.874s  |  10.874s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           | 598.832s  | 598.832s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        | 168.823s  | 168.823s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  24.311s  |  24.311s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                | 599.758s  | 599.758s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |  11.508s  |  11.508s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   3.471s  |   3.471s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  28.611s  |  28.611s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   2.093s  |   2.093s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   3.867s  |   3.867s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  30.195s  |  30.195s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   3.414s  |   3.414s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   4.626s  |   4.626s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   6.892s  |   6.892s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   3.322s  |   3.322s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       | 138.148s  | 138.148s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       | 595.126s  | 595.126s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       | 598.757s  | 598.757s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |  13.694s  |  13.694s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       | 599.482s  | 599.482s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       | 598.842s  | 598.842s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       | 599.471s  | 599.471s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       | 599.259s  | 599.259s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |   9.726s  |   9.726s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   4.167s  |   4.167s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       | 598.553s  | 598.553s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   3.611s  |   3.611s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       | 599.629s  | 599.629s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     | 599.481s  | 599.481s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   3.212s  |   3.212s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                | 598.930s  | 598.930s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   1.086s  |   1.086s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   3.461s  |   3.461s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   3.202s  |   3.202s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |  25.820s  |  25.820s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   5.666s  |   5.666s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   2.000s  |   2.000s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   2.448s  |   2.448s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   3.211s  |   3.211s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |  12.496s  |  12.496s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        | 599.264s  | 599.264s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        | 599.641s  | 599.641s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   7.494s  |   7.494s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  39.828s  |  39.828s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  | 598.809s  | 598.809s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  | 599.527s  | 599.527s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  42.528s  |  42.528s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |  26.978s  |  26.978s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   2.243s  |   2.243s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           |  85.452s  |  85.452s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           | 319.947s  | 319.947s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   1.855s  |   1.855s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   3.961s  |   3.961s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   5.275s  |   5.275s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   3.811s  |   3.811s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   5.033s  |   5.033s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           | 599.941s  | 599.941s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   1.807s  |   1.807s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           |  92.104s  |  92.104s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   1.267s  |   1.267s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   1.048s  |   1.048s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           | 599.745s  | 599.745s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   1.866s  |   1.866s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   0.992s  |   0.992s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   4.524s  |   4.524s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   2.427s  |   2.427s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   2.221s  |   2.221s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   3.492s  |   3.492s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   1.699s  |   1.699s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   5.635s  |   5.635s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.837s  |   0.837s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |   6.731s  |   6.731s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   3.442s  |   3.442s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   3.222s  |   3.222s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           | 399.037s  | 399.037s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   5.625s  |   5.625s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           | 389.180s  | 389.180s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   2.746s  |   2.746s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   5.208s  |   5.208s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   1.092s  |   1.092s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   2.271s  |   2.271s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |  84.249s  |  84.249s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   1.443s  |   1.443s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           |  80.868s  |  80.868s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   2.437s  |   2.437s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   2.399s  |   2.399s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   5.268s  |   5.268s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   2.572s  |   2.572s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   4.572s  |   4.572s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |  94.986s  |  94.986s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   4.951s  |   4.951s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   4.139s  |   4.139s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   2.597s  |   2.597s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   3.421s  |   3.421s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |   3.311s  |   3.311s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |   2.409s  |   2.409s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   0.704s  |   0.704s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   2.661s  |   2.661s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  19.535s  |  19.535s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   4.007s  |   4.007s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |   4.471s  |   4.471s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   2.487s  |   2.487s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.895s  |   0.895s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            |  85.879s  |  85.879s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   2.478s  |   2.478s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |   4.389s  |   4.389s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   6.718s  |   6.718s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   4.182s  |   4.182s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   1.794s  |   1.794s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           | 107.361s  | 107.361s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           |  87.968s  |  87.968s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   4.003s  |   4.003s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   5.571s  |   5.571s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  69.232s  |  69.232s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   1.121s  |   1.121s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   2.182s  |   2.182s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   2.862s  |   2.862s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   2.640s  |   2.640s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   1.940s  |   1.940s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   3.880s  |   3.880s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |  90.540s  |  90.540s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   4.424s  |   4.424s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   2.596s  |   2.596s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           | 599.245s  | 599.245s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |  16.103s  |  16.103s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   5.870s  |   5.870s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           | 599.542s  | 599.542s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   3.070s  |   3.070s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   1.378s  |   1.378s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   8.170s  |   8.170s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           | 209.238s  | 209.238s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.667s  |   0.667s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   9.186s  |   9.186s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           |  60.095s  |  60.095s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   2.249s  |   2.249s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   4.470s  |   4.470s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   2.698s  |   2.698s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   9.134s  |   9.134s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   5.903s  |   5.903s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   7.800s  |   7.800s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   1.883s  |   1.883s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           | 598.787s  | 598.787s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  33.314s  |  33.314s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   2.663s  |   2.663s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   1.236s  |   1.236s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   7.128s  |   7.128s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   5.187s  |   5.187s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   2.481s  |   2.481s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   6.939s  |   6.939s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   4.354s  |   4.354s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |  86.341s  |  86.341s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |   3.841s  |   3.841s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   1.037s  |   1.037s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.582s  |   1.582s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   1.314s  |   1.314s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   1.843s  |   1.843s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   7.764s  |   7.764s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            | 363.975s  | 363.975s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |  19.779s  |  19.779s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            | 599.753s  | 599.753s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            | 598.691s  | 598.691s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            | 599.390s  | 599.390s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            | 171.234s  | 171.234s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            | 599.134s  | 599.134s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.089s  |   0.089s  |   0.000s  | 0.0%|
</details>
