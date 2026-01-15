Comparing data and data


# SUMMARY
- LHS tests = 2313
- RHS tests = 2313
- LHS success = 353  (15.261565067012539%)
- RHS success = 353  (15.261565067012539%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: benchmark run
Job tag: lws_yes_ignore_cost_witness
Runner: GCR-SANDBOX-011
Z3 repo: Z3Prover/z3
Z3 commit: 57d17638093ceefeba97918c8849c65482f45d26
Z3 branch: lws
Z3 options: "-T:600"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: ignore const non-null witnesses

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: benchmark run
Job tag: lws_yes_ignore_cost_witness
Runner: GCR-SANDBOX-011
Z3 repo: Z3Prover/z3
Z3 commit: 57d17638093ceefeba97918c8849c65482f45d26
Z3 branch: lws
Z3 options: "-T:600"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: ignore const non-null witnesses

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1.smt2                                                                                      |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1.smt2                                                                                      |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1.smt2                                                                                      |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1.smt2                                                                                      |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 600.231s |3676.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.224s |3640.0MiB|
|185.smt2                                                                                   | 600.216s |2148.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 600.195s |2271.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 600.154s |2763.0MiB|
|181.smt2                                                                                   | 600.129s |1523.0MiB|
|183.smt2                                                                                   | 600.128s |1709.0MiB|
|182.smt2                                                                                   | 600.096s |1480.0MiB|
|65.smt2                                                                                    | 600.039s |367.0MiB|
|40.smt2                                                                                    | 600.034s |405.0MiB|
|54.smt2                                                                                    | 600.027s |386.0MiB|
|140.smt2                                                                                   | 600.025s |444.0MiB|
|58.smt2                                                                                    | 600.022s |400.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        | 228.553s |1563.0MiB|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                           | 130.560s |521.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  48.874s |554.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  47.067s |571.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  44.688s |382.0MiB|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                 |  42.606s |303.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                    |  29.491s |378.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 600.231s |3676.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.224s |3640.0MiB|
|185.smt2                                                                                   | 600.216s |2148.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 600.195s |2271.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 600.154s |2763.0MiB|
|181.smt2                                                                                   | 600.129s |1523.0MiB|
|183.smt2                                                                                   | 600.128s |1709.0MiB|
|182.smt2                                                                                   | 600.096s |1480.0MiB|
|65.smt2                                                                                    | 600.039s |367.0MiB|
|40.smt2                                                                                    | 600.034s |405.0MiB|
|54.smt2                                                                                    | 600.027s |386.0MiB|
|140.smt2                                                                                   | 600.025s |444.0MiB|
|58.smt2                                                                                    | 600.022s |400.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        | 228.553s |1563.0MiB|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                           | 130.560s |521.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  48.874s |554.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  47.067s |571.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  44.688s |382.0MiB|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                 |  42.606s |303.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                    |  29.491s |378.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.772MiB|24.772MiB|0B| 0.0%|
|107.smt2                                                                                    |22.316MiB|22.316MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.056MiB|80.056MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.6MiB|22.6MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.608MiB|22.608MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.492MiB|23.492MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.072MiB|23.072MiB|0B| 0.0%|
|1132.smt2                                                                                   |23.712MiB|23.712MiB|0B| 0.0%|
|1148.smt2                                                                                   |23.964MiB|23.964MiB|0B| 0.0%|
|1152.smt2                                                                                   |23.868MiB|23.868MiB|0B| 0.0%|
|1176.smt2                                                                                   |24.552MiB|24.552MiB|0B| 0.0%|
|1188.smt2                                                                                   |24.84MiB|24.84MiB|0B| 0.0%|
|1190.smt2                                                                                   |24.976MiB|24.976MiB|0B| 0.0%|
|1192.smt2                                                                                   |25.176MiB|25.176MiB|0B| 0.0%|
|1198.smt2                                                                                   |24.948MiB|24.948MiB|0B| 0.0%|
|1199.smt2                                                                                   |25.244MiB|25.244MiB|0B| 0.0%|
|1244.smt2                                                                                   |25.68MiB|25.68MiB|0B| 0.0%|
|1268.smt2                                                                                   |21.372MiB|21.372MiB|0B| 0.0%|
|1270.smt2                                                                                   |21.304MiB|21.304MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.772MiB|24.772MiB|0B| 0.0%|
|107.smt2                                                                                    |22.316MiB|22.316MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.056MiB|80.056MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.6MiB|22.6MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.608MiB|22.608MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.492MiB|23.492MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.072MiB|23.072MiB|0B| 0.0%|
|1132.smt2                                                                                   |23.712MiB|23.712MiB|0B| 0.0%|
|1148.smt2                                                                                   |23.964MiB|23.964MiB|0B| 0.0%|
|1152.smt2                                                                                   |23.868MiB|23.868MiB|0B| 0.0%|
|1176.smt2                                                                                   |24.552MiB|24.552MiB|0B| 0.0%|
|1188.smt2                                                                                   |24.84MiB|24.84MiB|0B| 0.0%|
|1190.smt2                                                                                   |24.976MiB|24.976MiB|0B| 0.0%|
|1192.smt2                                                                                   |25.176MiB|25.176MiB|0B| 0.0%|
|1198.smt2                                                                                   |24.948MiB|24.948MiB|0B| 0.0%|
|1199.smt2                                                                                   |25.244MiB|25.244MiB|0B| 0.0%|
|1244.smt2                                                                                   |25.68MiB|25.68MiB|0B| 0.0%|
|1268.smt2                                                                                   |21.372MiB|21.372MiB|0B| 0.0%|
|1270.smt2                                                                                   |21.304MiB|21.304MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.772MiB|24.772MiB|0B| 0.0%|
|107.smt2                                                                                    |22.316MiB|22.316MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.056MiB|80.056MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.6MiB|22.6MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.608MiB|22.608MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.492MiB|23.492MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.072MiB|23.072MiB|0B| 0.0%|
|1132.smt2                                                                                   |23.712MiB|23.712MiB|0B| 0.0%|
|1148.smt2                                                                                   |23.964MiB|23.964MiB|0B| 0.0%|
|1152.smt2                                                                                   |23.868MiB|23.868MiB|0B| 0.0%|
|1176.smt2                                                                                   |24.552MiB|24.552MiB|0B| 0.0%|
|1188.smt2                                                                                   |24.84MiB|24.84MiB|0B| 0.0%|
|1190.smt2                                                                                   |24.976MiB|24.976MiB|0B| 0.0%|
|1192.smt2                                                                                   |25.176MiB|25.176MiB|0B| 0.0%|
|1198.smt2                                                                                   |24.948MiB|24.948MiB|0B| 0.0%|
|1199.smt2                                                                                   |25.244MiB|25.244MiB|0B| 0.0%|
|1244.smt2                                                                                   |25.68MiB|25.68MiB|0B| 0.0%|
|1268.smt2                                                                                   |21.372MiB|21.372MiB|0B| 0.0%|
|1270.smt2                                                                                   |21.304MiB|21.304MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.772MiB|24.772MiB|0B| 0.0%|
|107.smt2                                                                                    |22.316MiB|22.316MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.056MiB|80.056MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.6MiB|22.6MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.608MiB|22.608MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.492MiB|23.492MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.072MiB|23.072MiB|0B| 0.0%|
|1132.smt2                                                                                   |23.712MiB|23.712MiB|0B| 0.0%|
|1148.smt2                                                                                   |23.964MiB|23.964MiB|0B| 0.0%|
|1152.smt2                                                                                   |23.868MiB|23.868MiB|0B| 0.0%|
|1176.smt2                                                                                   |24.552MiB|24.552MiB|0B| 0.0%|
|1188.smt2                                                                                   |24.84MiB|24.84MiB|0B| 0.0%|
|1190.smt2                                                                                   |24.976MiB|24.976MiB|0B| 0.0%|
|1192.smt2                                                                                   |25.176MiB|25.176MiB|0B| 0.0%|
|1198.smt2                                                                                   |24.948MiB|24.948MiB|0B| 0.0%|
|1199.smt2                                                                                   |25.244MiB|25.244MiB|0B| 0.0%|
|1244.smt2                                                                                   |25.68MiB|25.68MiB|0B| 0.0%|
|1268.smt2                                                                                   |21.372MiB|21.372MiB|0B| 0.0%|
|1270.smt2                                                                                   |21.304MiB|21.304MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 600.231s |3676.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.224s |3640.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 600.154s |2763.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 600.195s |2271.0MiB|
|185.smt2                                                                                   | 600.216s |2148.0MiB|
|183.smt2                                                                                   | 600.128s |1709.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        | 228.553s |1563.0MiB|
|181.smt2                                                                                   | 600.129s |1523.0MiB|
|182.smt2                                                                                   | 600.096s |1480.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |   5.108s |601.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |   4.897s |601.0MiB|
|From_T2__foo.t2__terminationS_12_0.smt2                                                    |   4.960s |600.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  47.067s |571.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  48.874s |554.0MiB|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                           | 130.560s |521.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           |  26.516s |514.0MiB|
|140.smt2                                                                                   | 600.025s |444.0MiB|
|40.smt2                                                                                    | 600.034s |405.0MiB|
|58.smt2                                                                                    | 600.022s |400.0MiB|
|54.smt2                                                                                    | 600.027s |386.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 600.231s |3676.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.224s |3640.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 600.154s |2763.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 600.195s |2271.0MiB|
|185.smt2                                                                                   | 600.216s |2148.0MiB|
|183.smt2                                                                                   | 600.128s |1709.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        | 228.553s |1563.0MiB|
|181.smt2                                                                                   | 600.129s |1523.0MiB|
|182.smt2                                                                                   | 600.096s |1480.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |   5.108s |601.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |   4.897s |601.0MiB|
|From_T2__foo.t2__terminationS_12_0.smt2                                                    |   4.960s |600.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  47.067s |571.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  48.874s |554.0MiB|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                           | 130.560s |521.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           |  26.516s |514.0MiB|
|140.smt2                                                                                   | 600.025s |444.0MiB|
|40.smt2                                                                                    | 600.034s |405.0MiB|
|58.smt2                                                                                    | 600.022s |400.0MiB|
|54.smt2                                                                                    | 600.027s |386.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1.smt2                                                                                      |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|140.smt2                                                                                    | 600.025s  | 600.025s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   0.639s  |   0.639s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   1.598s  |   1.598s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   1.029s  |   1.029s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|181.smt2                                                                                    | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|182.smt2                                                                                    | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|183.smt2                                                                                    | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|185.smt2                                                                                    | 600.216s  | 600.216s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   0.861s  |   0.861s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   0.985s  |   0.985s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   0.841s  |   0.841s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|40.smt2                                                                                     | 600.034s  | 600.034s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|54.smt2                                                                                     | 600.027s  | 600.027s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|58.smt2                                                                                     | 600.022s  | 600.022s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|65.smt2                                                                                     | 600.039s  | 600.039s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   1.236s  |   1.236s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   0.848s  |   0.848s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   1.684s  |   1.684s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   1.402s  |   1.402s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   1.391s  |   1.391s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   0.886s  |   0.886s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   1.428s  |   1.428s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         | 228.553s  | 228.553s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              | 600.195s  | 600.195s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   0.903s  |   0.903s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |   1.703s  |   1.703s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   1.003s  |   1.003s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   1.315s  |   1.315s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |   2.131s  |   2.131s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    |   3.639s  |   3.639s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |   2.101s  |   2.101s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  |  14.605s  |  14.605s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            | 130.560s  | 130.560s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         | 600.231s  | 600.231s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   1.583s  |   1.583s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |   1.579s  |   1.579s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |   2.326s  |   2.326s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   0.604s  |   0.604s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          | 600.154s  | 600.154s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   1.795s  |   1.795s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   1.565s  |   1.565s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.087s  |   1.087s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.078s  |   0.078s  |   0.000s  | 0.0%|
</details>
