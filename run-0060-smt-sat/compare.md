Comparing data and data


# SUMMARY
- LHS tests = 1341
- RHS tests = 1341
- LHS success = 1339  (99.85085756897837%)
- RHS success = 1339  (99.85085756897837%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: aa67c3655ffdf89c7ebcc21ed9c236949a6a35b4
Z3 branch: sls
Z3 options: "-T:20 -v:2 smt.sls.enable=false sat.smt=true -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_SAT
Z3 commit message: bugfixes

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: aa67c3655ffdf89c7ebcc21ed9c236949a6a35b4
Z3 branch: sls
Z3 options: "-T:20 -v:2 smt.sls.enable=false sat.smt=true -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_SAT
Z3 commit message: bugfixes

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   1.451s  |   1.451s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   5.799s  |   5.799s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   1.247s  |   1.247s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   2.148s  |   2.148s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   3.549s  |   3.549s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   6.010s  |   6.010s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   6.502s  |   6.502s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   1.967s  |   1.967s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   1.548s  |   1.548s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   7.964s  |   7.964s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   3.825s  |   3.825s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   1.451s  |   1.451s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   5.799s  |   5.799s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   1.247s  |   1.247s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   2.148s  |   2.148s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   3.549s  |   3.549s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   6.010s  |   6.010s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   6.502s  |   6.502s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   1.967s  |   1.967s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   1.548s  |   1.548s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   7.964s  |   7.964s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   3.825s  |   3.825s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   1.451s  |   1.451s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   5.799s  |   5.799s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   1.247s  |   1.247s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   2.148s  |   2.148s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   3.549s  |   3.549s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   6.010s  |   6.010s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   6.502s  |   6.502s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   1.967s  |   1.967s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   1.548s  |   1.548s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   7.964s  |   7.964s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   3.825s  |   3.825s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   1.451s  |   1.451s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   5.799s  |   5.799s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   1.247s  |   1.247s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   2.148s  |   2.148s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   3.549s  |   3.549s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   6.010s  |   6.010s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   6.502s  |   6.502s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   1.967s  |   1.967s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   1.548s  |   1.548s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   7.964s  |   7.964s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   3.825s  |   3.825s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                             |  20.037s |497.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          |  20.034s |401.0MiB|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                              |  20.033s |483.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              |  20.025s |586.0MiB|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                            |  20.020s |388.0MiB|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                          |  20.020s |491.0MiB|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                          |  20.020s |439.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                      |  20.020s |490.0MiB|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                |  20.019s |263.0MiB|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                 |  20.018s |395.0MiB|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                |  20.018s |209.0MiB|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                |  20.016s |336.0MiB|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                            |  20.016s |350.0MiB|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                 |  20.016s |330.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                        |  20.015s |353.0MiB|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                |  20.015s |341.0MiB|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                |  20.015s |384.0MiB|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                           |  20.014s |265.0MiB|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                |  20.014s |298.0MiB|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                   |  20.014s |303.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                             |  20.037s |497.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          |  20.034s |401.0MiB|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                              |  20.033s |483.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              |  20.025s |586.0MiB|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                            |  20.020s |388.0MiB|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                          |  20.020s |491.0MiB|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                          |  20.020s |439.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                      |  20.020s |490.0MiB|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                |  20.019s |263.0MiB|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                 |  20.018s |395.0MiB|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                |  20.018s |209.0MiB|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                |  20.016s |336.0MiB|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                            |  20.016s |350.0MiB|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                 |  20.016s |330.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                        |  20.015s |353.0MiB|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                |  20.015s |341.0MiB|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                |  20.015s |384.0MiB|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                           |  20.014s |265.0MiB|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                |  20.014s |298.0MiB|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                   |  20.014s |303.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |92.44MiB|92.44MiB|0B| 0.0%|
|1010.smt2                                                                                   |136.0MiB|136.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |30.736MiB|30.736MiB|0B| 0.0%|
|1021.smt2                                                                                   |30.768MiB|30.768MiB|0B| 0.0%|
|1034.smt2                                                                                   |34.288MiB|34.288MiB|0B| 0.0%|
|1063.smt2                                                                                   |52.82MiB|52.82MiB|0B| 0.0%|
|107.smt2                                                                                    |28.248MiB|28.248MiB|0B| 0.0%|
|1082.smt2                                                                                   |111.0MiB|111.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |33.596MiB|33.596MiB|0B| 0.0%|
|1090.smt2                                                                                   |32.6MiB|32.6MiB|0B| 0.0%|
|1092.smt2                                                                                   |33.704MiB|33.704MiB|0B| 0.0%|
|1104.smt2                                                                                   |35.244MiB|35.244MiB|0B| 0.0%|
|1112.smt2                                                                                   |34.608MiB|34.608MiB|0B| 0.0%|
|1113.smt2                                                                                   |37.948MiB|37.948MiB|0B| 0.0%|
|1126.smt2                                                                                   |40.376MiB|40.376MiB|0B| 0.0%|
|1132.smt2                                                                                   |37.6MiB|37.6MiB|0B| 0.0%|
|1148.smt2                                                                                   |38.888MiB|38.888MiB|0B| 0.0%|
|1152.smt2                                                                                   |49.564MiB|49.564MiB|0B| 0.0%|
|1176.smt2                                                                                   |55.788MiB|55.788MiB|0B| 0.0%|
|1188.smt2                                                                                   |65.116MiB|65.116MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |92.44MiB|92.44MiB|0B| 0.0%|
|1010.smt2                                                                                   |136.0MiB|136.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |30.736MiB|30.736MiB|0B| 0.0%|
|1021.smt2                                                                                   |30.768MiB|30.768MiB|0B| 0.0%|
|1034.smt2                                                                                   |34.288MiB|34.288MiB|0B| 0.0%|
|1063.smt2                                                                                   |52.82MiB|52.82MiB|0B| 0.0%|
|107.smt2                                                                                    |28.248MiB|28.248MiB|0B| 0.0%|
|1082.smt2                                                                                   |111.0MiB|111.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |33.596MiB|33.596MiB|0B| 0.0%|
|1090.smt2                                                                                   |32.6MiB|32.6MiB|0B| 0.0%|
|1092.smt2                                                                                   |33.704MiB|33.704MiB|0B| 0.0%|
|1104.smt2                                                                                   |35.244MiB|35.244MiB|0B| 0.0%|
|1112.smt2                                                                                   |34.608MiB|34.608MiB|0B| 0.0%|
|1113.smt2                                                                                   |37.948MiB|37.948MiB|0B| 0.0%|
|1126.smt2                                                                                   |40.376MiB|40.376MiB|0B| 0.0%|
|1132.smt2                                                                                   |37.6MiB|37.6MiB|0B| 0.0%|
|1148.smt2                                                                                   |38.888MiB|38.888MiB|0B| 0.0%|
|1152.smt2                                                                                   |49.564MiB|49.564MiB|0B| 0.0%|
|1176.smt2                                                                                   |55.788MiB|55.788MiB|0B| 0.0%|
|1188.smt2                                                                                   |65.116MiB|65.116MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |92.44MiB|92.44MiB|0B| 0.0%|
|1010.smt2                                                                                   |136.0MiB|136.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |30.736MiB|30.736MiB|0B| 0.0%|
|1021.smt2                                                                                   |30.768MiB|30.768MiB|0B| 0.0%|
|1034.smt2                                                                                   |34.288MiB|34.288MiB|0B| 0.0%|
|1063.smt2                                                                                   |52.82MiB|52.82MiB|0B| 0.0%|
|107.smt2                                                                                    |28.248MiB|28.248MiB|0B| 0.0%|
|1082.smt2                                                                                   |111.0MiB|111.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |33.596MiB|33.596MiB|0B| 0.0%|
|1090.smt2                                                                                   |32.6MiB|32.6MiB|0B| 0.0%|
|1092.smt2                                                                                   |33.704MiB|33.704MiB|0B| 0.0%|
|1104.smt2                                                                                   |35.244MiB|35.244MiB|0B| 0.0%|
|1112.smt2                                                                                   |34.608MiB|34.608MiB|0B| 0.0%|
|1113.smt2                                                                                   |37.948MiB|37.948MiB|0B| 0.0%|
|1126.smt2                                                                                   |40.376MiB|40.376MiB|0B| 0.0%|
|1132.smt2                                                                                   |37.6MiB|37.6MiB|0B| 0.0%|
|1148.smt2                                                                                   |38.888MiB|38.888MiB|0B| 0.0%|
|1152.smt2                                                                                   |49.564MiB|49.564MiB|0B| 0.0%|
|1176.smt2                                                                                   |55.788MiB|55.788MiB|0B| 0.0%|
|1188.smt2                                                                                   |65.116MiB|65.116MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |92.44MiB|92.44MiB|0B| 0.0%|
|1010.smt2                                                                                   |136.0MiB|136.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |30.736MiB|30.736MiB|0B| 0.0%|
|1021.smt2                                                                                   |30.768MiB|30.768MiB|0B| 0.0%|
|1034.smt2                                                                                   |34.288MiB|34.288MiB|0B| 0.0%|
|1063.smt2                                                                                   |52.82MiB|52.82MiB|0B| 0.0%|
|107.smt2                                                                                    |28.248MiB|28.248MiB|0B| 0.0%|
|1082.smt2                                                                                   |111.0MiB|111.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |33.596MiB|33.596MiB|0B| 0.0%|
|1090.smt2                                                                                   |32.6MiB|32.6MiB|0B| 0.0%|
|1092.smt2                                                                                   |33.704MiB|33.704MiB|0B| 0.0%|
|1104.smt2                                                                                   |35.244MiB|35.244MiB|0B| 0.0%|
|1112.smt2                                                                                   |34.608MiB|34.608MiB|0B| 0.0%|
|1113.smt2                                                                                   |37.948MiB|37.948MiB|0B| 0.0%|
|1126.smt2                                                                                   |40.376MiB|40.376MiB|0B| 0.0%|
|1132.smt2                                                                                   |37.6MiB|37.6MiB|0B| 0.0%|
|1148.smt2                                                                                   |38.888MiB|38.888MiB|0B| 0.0%|
|1152.smt2                                                                                   |49.564MiB|49.564MiB|0B| 0.0%|
|1176.smt2                                                                                   |55.788MiB|55.788MiB|0B| 0.0%|
|1188.smt2                                                                                   |65.116MiB|65.116MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  19.964s |668.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              |  20.025s |586.0MiB|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                              |  20.002s |566.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                      |  19.873s |513.0MiB|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                            |  19.968s |503.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                             |  20.037s |497.0MiB|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                          |  20.020s |491.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                      |  20.020s |490.0MiB|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                              |  20.033s |483.0MiB|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                         |  19.995s |482.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2               |  19.937s |482.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                          |  20.011s |451.0MiB|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                |  19.670s |451.0MiB|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                          |  20.020s |439.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      |  19.874s |434.0MiB|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                    |  19.980s |433.0MiB|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                             |  19.919s |430.0MiB|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                |  19.982s |427.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              |  20.013s |420.0MiB|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                             |  19.999s |416.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  19.964s |668.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              |  20.025s |586.0MiB|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                              |  20.002s |566.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                      |  19.873s |513.0MiB|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                            |  19.968s |503.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                             |  20.037s |497.0MiB|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                          |  20.020s |491.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                      |  20.020s |490.0MiB|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                              |  20.033s |483.0MiB|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                         |  19.995s |482.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2               |  19.937s |482.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                          |  20.011s |451.0MiB|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                |  19.670s |451.0MiB|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                          |  20.020s |439.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      |  19.874s |434.0MiB|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                    |  19.980s |433.0MiB|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                             |  19.919s |430.0MiB|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                |  19.982s |427.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              |  20.013s |420.0MiB|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                             |  19.999s |416.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1008.smt2                                                                                   |   1.451s  |   1.451s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   5.799s  |   5.799s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   1.247s  |   1.247s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   2.148s  |   2.148s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   3.549s  |   3.549s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   6.010s  |   6.010s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   6.502s  |   6.502s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   1.967s  |   1.967s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   1.548s  |   1.548s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   7.964s  |   7.964s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   3.825s  |   3.825s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   3.395s  |   3.395s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   1.026s  |   1.026s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   1.552s  |   1.552s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   6.485s  |   6.485s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   4.349s  |   4.349s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   2.966s  |   2.966s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.739s  |   0.739s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   1.010s  |   1.010s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   2.435s  |   2.435s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   1.343s  |   1.343s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.912s  |   0.912s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |  10.381s  |  10.381s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   1.094s  |   1.094s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   0.908s  |   0.908s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   3.302s  |   3.302s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   1.593s  |   1.593s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.656s  |   0.656s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.655s  |   0.655s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.624s  |   0.624s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   1.474s  |   1.474s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   1.135s  |   1.135s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.655s  |   0.655s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   4.190s  |   4.190s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |  19.917s  |  19.917s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.769s  |   0.769s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   1.369s  |   1.369s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   0.559s  |   0.559s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   0.695s  |   0.695s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   3.186s  |   3.186s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   1.538s  |   1.538s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       |  19.830s  |  19.830s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  19.854s  |  19.854s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   2.264s  |   2.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |   8.445s  |   8.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         |  19.883s  |  19.883s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 |  11.062s  |  11.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   2.493s  |   2.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   1.932s  |   1.932s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |  19.929s  |  19.929s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |   3.794s  |   3.794s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               |  19.915s  |  19.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   2.807s  |   2.807s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |  13.547s  |  13.547s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |   3.748s  |   3.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   1.159s  |   1.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         |  19.915s  |  19.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |  19.876s  |  19.876s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           |  19.834s  |  19.834s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   2.325s  |   2.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |   0.723s  |   0.723s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |  19.860s  |  19.860s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |  11.905s  |  11.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   |  19.691s  |  19.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   |  19.872s  |  19.872s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |   4.517s  |   4.517s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   3.772s  |   3.772s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   4.096s  |   4.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  19.888s  |  19.888s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          |  19.877s  |  19.877s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          |  19.325s  |  19.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |   4.296s  |   4.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   0.760s  |   0.760s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   5.036s  |   5.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    |  19.805s  |  19.805s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   8.282s  |   8.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |  19.900s  |  19.900s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |  12.735s  |  12.735s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        |  19.878s  |  19.878s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |   5.683s  |   5.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        |   6.049s  |   6.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                |  19.929s  |  19.929s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |  19.891s  |  19.891s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      |  19.905s  |  19.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |  19.925s  |  19.925s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  19.649s  |  19.649s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |  19.460s  |  19.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |   7.566s  |   7.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |  19.963s  |  19.963s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   1.917s  |   1.917s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |  14.871s  |  14.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   4.311s  |   4.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   1.302s  |   1.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   2.294s  |   2.294s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |   8.213s  |   8.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   0.669s  |   0.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   5.670s  |   5.670s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |  11.675s  |  11.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |  19.916s  |  19.916s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   9.506s  |   9.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |  11.906s  |  11.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   2.330s  |   2.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |   2.473s  |   2.473s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   4.052s  |   4.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |   3.055s  |   3.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |   2.790s  |   2.790s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |  16.099s  |  16.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |   3.172s  |   3.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |   0.663s  |   0.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           |   2.858s  |   2.858s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   4.076s  |   4.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |  13.131s  |  13.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   3.507s  |   3.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  16.442s  |  16.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   1.542s  |   1.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |  11.296s  |  11.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   1.054s  |   1.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |   8.830s  |   8.830s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  19.898s  |  19.898s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   1.691s  |   1.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   7.801s  |   7.801s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |   4.736s  |   4.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   2.833s  |   2.833s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |   2.183s  |   2.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |  11.617s  |  11.617s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   5.024s  |   5.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |   7.336s  |   7.336s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.728s  |   0.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |  19.920s  |  19.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   2.919s  |   2.919s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |   2.042s  |   2.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   5.837s  |   5.837s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |  12.506s  |  12.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |   2.781s  |   2.781s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               |  19.815s  |  19.815s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |   3.353s  |   3.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   2.564s  |   2.564s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |  13.139s  |  13.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |   1.861s  |   1.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   1.816s  |   1.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |  10.482s  |  10.482s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   7.049s  |   7.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |   1.883s  |   1.883s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     |   1.804s  |   1.804s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |  12.900s  |  12.900s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   8.266s  |   8.266s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |   2.522s  |   2.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |   0.606s  |   0.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   7.615s  |   7.615s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |   1.874s  |   1.874s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |  17.338s  |  17.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   1.246s  |   1.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               |   1.289s  |   1.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   6.271s  |   6.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |   4.550s  |   4.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   1.641s  |   1.641s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   1.165s  |   1.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   1.856s  |   1.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   2.466s  |   2.466s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   1.908s  |   1.908s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |   6.359s  |   6.359s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |   2.120s  |   2.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |  10.691s  |  10.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   0.767s  |   0.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |  10.381s  |  10.381s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |   4.297s  |   4.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   9.508s  |   9.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |  19.927s  |  19.927s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |   3.323s  |   3.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |   1.622s  |   1.622s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   0.841s  |   0.841s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.480s  |   0.480s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |  11.809s  |  11.809s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |  19.897s  |  19.897s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |  12.994s  |  12.994s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   4.447s  |   4.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |  17.782s  |  17.782s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   2.717s  |   2.717s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |   4.631s  |   4.631s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |   8.455s  |   8.455s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               |  11.896s  |  11.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |   2.671s  |   2.671s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |   2.606s  |   2.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |  10.290s  |  10.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |   1.520s  |   1.520s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |   1.375s  |   1.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   5.803s  |   5.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |  19.741s  |  19.741s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |   2.288s  |   2.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  19.948s  |  19.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |  19.786s  |  19.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |  16.959s  |  16.959s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |  11.085s  |  11.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |  11.493s  |  11.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |  15.112s  |  15.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   3.480s  |   3.480s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   2.367s  |   2.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |   0.566s  |   0.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   1.926s  |   1.926s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   3.518s  |   3.518s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |  11.246s  |  11.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   1.152s  |   1.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   2.025s  |   2.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  19.944s  |  19.944s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |  15.187s  |  15.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   7.058s  |   7.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   3.300s  |   3.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |  19.157s  |  19.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   6.023s  |   6.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   8.574s  |   8.574s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   2.279s  |   2.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |   0.692s  |   0.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |   3.812s  |   3.812s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |   5.856s  |   5.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |   5.073s  |   5.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |   2.735s  |   2.735s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |   1.097s  |   1.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |  10.376s  |  10.376s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |   5.245s  |   5.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   6.555s  |   6.555s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |  19.888s  |  19.888s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   6.555s  |   6.555s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   0.752s  |   0.752s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |  12.459s  |  12.459s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |   2.703s  |   2.703s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |   5.167s  |   5.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |  14.665s  |  14.665s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |  12.995s  |  12.995s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |   0.801s  |   0.801s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |   0.863s  |   0.863s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |   1.778s  |   1.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |   5.292s  |   5.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |   6.273s  |   6.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |  13.187s  |  13.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   2.083s  |   2.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   0.959s  |   0.959s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   1.894s  |   1.894s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   2.068s  |   2.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |   1.261s  |   1.261s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     |   7.554s  |   7.554s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |  11.741s  |  11.741s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   0.973s  |   0.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |   3.955s  |   3.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |  19.916s  |  19.916s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   5.047s  |   5.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |  10.113s  |  10.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   3.402s  |   3.402s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |   3.469s  |   3.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |   7.586s  |   7.586s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  15.522s  |  15.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |   5.415s  |   5.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |   4.094s  |   4.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |   6.577s  |   6.577s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   1.184s  |   1.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |  15.338s  |  15.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |   4.365s  |   4.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   0.979s  |   0.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |   5.292s  |   5.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            |  19.922s  |  19.922s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   6.399s  |   6.399s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   1.422s  |   1.422s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   2.248s  |   2.248s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   0.864s  |   0.864s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |   2.654s  |   2.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |  15.232s  |  15.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   9.245s  |   9.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |   1.373s  |   1.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   1.864s  |   1.864s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |   4.067s  |   4.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |   1.197s  |   1.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |   3.703s  |   3.703s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   1.784s  |   1.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  19.903s  |  19.903s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   2.363s  |   2.363s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |   2.809s  |   2.809s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |   1.973s  |   1.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   1.716s  |   1.716s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |   3.478s  |   3.478s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |   4.115s  |   4.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   1.072s  |   1.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   0.650s  |   0.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   1.344s  |   1.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   8.894s  |   8.894s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   4.770s  |   4.770s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   1.052s  |   1.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   1.083s  |   1.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   1.137s  |   1.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   1.113s  |   1.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |  19.262s  |  19.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   2.095s  |   2.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  19.917s  |  19.917s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   0.748s  |   0.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   1.545s  |   1.545s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |   1.680s  |   1.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   2.071s  |   2.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   0.813s  |   0.813s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |   7.305s  |   7.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |   1.168s  |   1.168s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   1.424s  |   1.424s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |   8.460s  |   8.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |   1.040s  |   1.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   1.084s  |   1.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   4.500s  |   4.500s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  19.914s  |  19.914s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   1.130s  |   1.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   4.695s  |   4.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   0.915s  |   0.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   1.005s  |   1.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                |  19.879s  |  19.879s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |   2.242s  |   2.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |   3.760s  |   3.760s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |   5.692s  |   5.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  19.922s  |  19.922s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   3.942s  |   3.942s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   3.419s  |   3.419s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   0.824s  |   0.824s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |   6.855s  |   6.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   1.283s  |   1.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |   1.050s  |   1.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   1.612s  |   1.612s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |   3.759s  |   3.759s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   2.182s  |   2.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   0.989s  |   0.989s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   1.414s  |   1.414s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |   1.679s  |   1.679s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   2.691s  |   2.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   0.680s  |   0.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |   1.588s  |   1.588s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |  19.762s  |  19.762s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   8.816s  |   8.816s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |  19.933s  |  19.933s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |   1.354s  |   1.354s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   1.014s  |   1.014s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |   2.799s  |   2.799s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    |  19.850s  |  19.850s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |   4.134s  |   4.134s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |  19.626s  |  19.626s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |  19.836s  |  19.836s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  16.044s  |  16.044s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |  19.805s  |  19.805s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |  10.145s  |  10.145s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |  19.926s  |  19.926s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |   2.093s  |   2.093s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |   2.496s  |   2.496s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |   1.777s  |   1.777s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |   1.225s  |   1.225s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   0.861s  |   0.861s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |   0.852s  |   0.852s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |  19.815s  |  19.815s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   1.302s  |   1.302s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |   1.687s  |   1.687s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       |   2.003s  |   2.003s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |   2.369s  |   2.369s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   1.330s  |   1.330s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   1.115s  |   1.115s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   2.406s  |   2.406s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |  19.849s  |  19.849s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |  19.869s  |  19.869s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |  19.705s  |  19.705s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   9.275s  |   9.275s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |   2.394s  |   2.394s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   0.981s  |   0.981s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |  19.888s  |  19.888s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |  19.799s  |  19.799s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |  13.242s  |  13.242s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   0.888s  |   0.888s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   0.783s  |   0.783s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |  19.826s  |  19.826s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |  13.034s  |  13.034s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |  19.920s  |  19.920s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        |  19.926s  |  19.926s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   0.669s  |   0.669s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |   1.122s  |   1.122s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         |  19.599s  |  19.599s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  |  19.870s  |  19.870s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |   5.529s  |   5.529s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |   1.302s  |   1.302s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            |  19.801s  |  19.801s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  18.610s  |  18.610s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 |  19.670s  |  19.670s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 |  19.949s  |  19.949s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  19.056s  |  19.056s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |   1.696s  |   1.696s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           |  19.916s  |  19.916s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 |  19.880s  |  19.880s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 |  19.895s  |  19.895s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  19.918s  |  19.918s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 |  19.931s  |  19.931s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   1.817s  |   1.817s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |   1.429s  |   1.429s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |   2.714s  |   2.714s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |  19.916s  |  19.916s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 |  19.877s  |  19.877s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |  19.898s  |  19.898s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |   3.218s  |   3.218s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        |  19.927s  |  19.927s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        |   5.936s  |   5.936s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        |  19.924s  |  19.924s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        |  19.870s  |  19.870s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        |  19.919s  |  19.919s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  19.464s  |  19.464s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   1.449s  |   1.449s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   1.163s  |   1.163s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |   1.573s  |   1.573s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             |  19.879s  |  19.879s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   4.455s  |   4.455s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   3.071s  |   3.071s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |  14.187s  |  14.187s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             |  11.496s  |  11.496s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   2.083s  |   2.083s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   3.437s  |   3.437s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   7.161s  |   7.161s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  19.788s  |  19.788s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   3.439s  |   3.439s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  |  19.663s  |  19.663s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   3.978s  |   3.978s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            |  19.896s  |  19.896s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  19.888s  |  19.888s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           |  19.897s  |  19.897s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |   3.518s  |   3.518s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               |  19.944s  |  19.944s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |   0.886s  |   0.886s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |   2.519s  |   2.519s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   3.490s  |   3.490s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  13.614s  |  13.614s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |   2.358s  |   2.358s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        |  19.915s  |  19.915s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   1.339s  |   1.339s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            |   4.172s  |   4.172s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |   0.851s  |   0.851s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              |  19.948s  |  19.948s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       |  19.949s  |  19.949s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   1.579s  |   1.579s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         |   3.434s  |   3.434s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   8.603s  |   8.603s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   1.304s  |   1.304s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |   7.629s  |   7.629s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          |  13.418s  |  13.418s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   0.802s  |   0.802s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |  19.871s  |  19.871s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                |   2.251s  |   2.251s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |  19.926s  |  19.926s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |   7.533s  |   7.533s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |   2.024s  |   2.024s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |  19.633s  |  19.633s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   0.712s  |   0.712s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   1.247s  |   1.247s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |  10.667s  |  10.667s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |   0.765s  |   0.765s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |   5.111s  |   5.111s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |   1.099s  |   1.099s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |   3.539s  |   3.539s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |   5.849s  |   5.849s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |   2.228s  |   2.228s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |   1.777s  |   1.777s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |   6.015s  |   6.015s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |   7.947s  |   7.947s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   5.059s  |   5.059s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |   1.157s  |   1.157s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |   3.163s  |   3.163s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |   0.979s  |   0.979s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |   4.442s  |   4.442s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   4.943s  |   4.943s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              |   4.711s  |   4.711s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |  12.842s  |  12.842s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |   2.395s  |   2.395s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |  19.919s  |  19.919s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   4.984s  |   4.984s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   4.602s  |   4.602s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   7.248s  |   7.248s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   1.018s  |   1.018s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   0.510s  |   0.510s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         |  19.849s  |  19.849s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   1.291s  |   1.291s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         |  15.483s  |  15.483s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |  19.680s  |  19.680s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |  16.818s  |  16.818s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   4.098s  |   4.098s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   3.150s  |   3.150s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   3.329s  |   3.329s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   3.974s  |   3.974s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           |   5.611s  |   5.611s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           |   3.295s  |   3.295s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   0.798s  |   0.798s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |  19.908s  |  19.908s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   1.263s  |   1.263s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |   1.389s  |   1.389s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  19.865s  |  19.865s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       |  19.874s  |  19.874s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       |  19.873s  |  19.873s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   8.600s  |   8.600s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             |  19.816s  |  19.816s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |   6.803s  |   6.803s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |   7.887s  |   7.887s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           |  19.743s  |  19.743s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 |  19.840s  |  19.840s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   2.985s  |   2.985s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                |  19.848s  |  19.848s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                |  19.859s  |  19.859s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |   8.451s  |   8.451s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |   5.401s  |   5.401s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |   8.449s  |   8.449s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  19.911s  |  19.911s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   3.854s  |   3.854s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            |  12.448s  |  12.448s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |  15.302s  |  15.302s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      |  19.798s  |  19.798s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  19.791s  |  19.791s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |  18.994s  |  18.994s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  19.941s  |  19.941s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |  19.676s  |  19.676s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |   3.930s  |   3.930s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |  19.833s  |  19.833s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |   0.624s  |   0.624s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |   1.496s  |   1.496s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  19.919s  |  19.919s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |  12.022s  |  12.022s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  19.341s  |  19.341s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |  19.896s  |  19.896s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |  19.906s  |  19.906s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   2.090s  |   2.090s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  19.943s  |  19.943s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |  19.921s  |  19.921s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |   4.657s  |   4.657s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |   1.410s  |   1.410s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |   2.469s  |   2.469s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           |  19.929s  |  19.929s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   2.231s  |   2.231s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   1.393s  |   1.393s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   3.400s  |   3.400s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           |   1.575s  |   1.575s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           |  19.870s  |  19.870s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   1.311s  |   1.311s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   1.763s  |   1.763s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   3.842s  |   3.842s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   1.483s  |   1.483s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   0.876s  |   0.876s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           |   3.187s  |   3.187s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |  13.685s  |  13.685s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   7.281s  |   7.281s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |  19.936s  |  19.936s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   0.811s  |   0.811s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   2.198s  |   2.198s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  19.888s  |  19.888s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   1.086s  |   1.086s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   7.000s  |   7.000s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   1.817s  |   1.817s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  19.854s  |  19.854s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |   3.024s  |   3.024s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |  19.906s  |  19.906s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   0.971s  |   0.971s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   0.921s  |   0.921s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   1.057s  |   1.057s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   2.035s  |   2.035s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           |  19.919s  |  19.919s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   2.110s  |   2.110s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   0.865s  |   0.865s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   0.934s  |   0.934s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   1.362s  |   1.362s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   1.012s  |   1.012s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   4.849s  |   4.849s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |   5.675s  |   5.675s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |  19.847s  |  19.847s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   9.509s  |   9.509s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            |  19.859s  |  19.859s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            |   5.269s  |   5.269s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
</details>
