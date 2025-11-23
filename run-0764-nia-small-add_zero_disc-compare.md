Comparing data and data


# SUMMARY
- LHS tests = 2313
- RHS tests = 2313
- LHS success = 2311  (99.91353220925205%)
- RHS success = 2311  (99.91353220925205%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: nia-small-add_zero_disc
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 3ceb913b6ec94df4a858e49bf4a36a39790a7f5e
Z3 branch: unsound
Z3 options: "-T:600"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: optionally call add_zero_assumption on a vanishing discriminant

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: nia-small-add_zero_disc
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 3ceb913b6ec94df4a858e49bf4a36a39790a7f5e
Z3 branch: unsound
Z3 options: "-T:600"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: optionally call add_zero_assumption on a vanishing discriminant

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.278s  |   1.278s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.285s  |   0.285s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.278s  |   1.278s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.285s  |   0.285s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.278s  |   1.278s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.285s  |   0.285s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.278s  |   1.278s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.285s  |   0.285s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                 | 623.785s |293.0MiB|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                | 615.414s |268.0MiB|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                | 613.721s |249.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          | 610.034s |1471.0MiB|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                               | 607.399s |1075.0MiB|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                         | 606.998s |266.0MiB|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                       | 602.733s |212.0MiB|
|40.smt2                                                                                    | 601.915s |146.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 601.301s |2373.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 601.032s |8073.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 600.716s |2155.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 600.678s |5522.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.669s |2072.0MiB|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                         | 600.645s |1229.0MiB|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                   | 600.636s |2286.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2               | 600.625s |2086.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 600.621s |2077.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                | 600.617s |1785.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.607s |2120.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.592s |4944.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                 | 623.785s |293.0MiB|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                | 615.414s |268.0MiB|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                | 613.721s |249.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          | 610.034s |1471.0MiB|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                               | 607.399s |1075.0MiB|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                         | 606.998s |266.0MiB|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                       | 602.733s |212.0MiB|
|40.smt2                                                                                    | 601.915s |146.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 601.301s |2373.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 601.032s |8073.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 600.716s |2155.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 600.678s |5522.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.669s |2072.0MiB|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                         | 600.645s |1229.0MiB|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                   | 600.636s |2286.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2               | 600.625s |2086.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 600.621s |2077.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                | 600.617s |1785.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.607s |2120.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.592s |4944.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |89.1MiB|89.1MiB|0B| 0.0%|
|04.smt2                                                                                     |76.836MiB|76.836MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.744MiB|31.744MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.784MiB|30.784MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.564MiB|23.564MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.012MiB|24.012MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.72MiB|24.72MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.76MiB|24.76MiB|0B| 0.0%|
|107.smt2                                                                                    |22.38MiB|22.38MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.368MiB|27.368MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.372MiB|80.372MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.028MiB|23.028MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.004MiB|23.004MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.508MiB|23.508MiB|0B| 0.0%|
|11.smt2                                                                                     |68.816MiB|68.816MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.276MiB|24.276MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.544MiB|23.544MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.756MiB|24.756MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.468MiB|25.468MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |89.1MiB|89.1MiB|0B| 0.0%|
|04.smt2                                                                                     |76.836MiB|76.836MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.744MiB|31.744MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.784MiB|30.784MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.564MiB|23.564MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.012MiB|24.012MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.72MiB|24.72MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.76MiB|24.76MiB|0B| 0.0%|
|107.smt2                                                                                    |22.38MiB|22.38MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.368MiB|27.368MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.372MiB|80.372MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.028MiB|23.028MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.004MiB|23.004MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.508MiB|23.508MiB|0B| 0.0%|
|11.smt2                                                                                     |68.816MiB|68.816MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.276MiB|24.276MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.544MiB|23.544MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.756MiB|24.756MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.468MiB|25.468MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |89.1MiB|89.1MiB|0B| 0.0%|
|04.smt2                                                                                     |76.836MiB|76.836MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.744MiB|31.744MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.784MiB|30.784MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.564MiB|23.564MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.012MiB|24.012MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.72MiB|24.72MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.76MiB|24.76MiB|0B| 0.0%|
|107.smt2                                                                                    |22.38MiB|22.38MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.368MiB|27.368MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.372MiB|80.372MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.028MiB|23.028MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.004MiB|23.004MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.508MiB|23.508MiB|0B| 0.0%|
|11.smt2                                                                                     |68.816MiB|68.816MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.276MiB|24.276MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.544MiB|23.544MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.756MiB|24.756MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.468MiB|25.468MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |89.1MiB|89.1MiB|0B| 0.0%|
|04.smt2                                                                                     |76.836MiB|76.836MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.744MiB|31.744MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.784MiB|30.784MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.564MiB|23.564MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.012MiB|24.012MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.72MiB|24.72MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.76MiB|24.76MiB|0B| 0.0%|
|107.smt2                                                                                    |22.38MiB|22.38MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.368MiB|27.368MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.372MiB|80.372MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.028MiB|23.028MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.004MiB|23.004MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.508MiB|23.508MiB|0B| 0.0%|
|11.smt2                                                                                     |68.816MiB|68.816MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.276MiB|24.276MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.544MiB|23.544MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.756MiB|24.756MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.468MiB|25.468MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 601.032s |8073.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 600.678s |5522.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.592s |4944.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              | 600.495s |3101.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 600.547s |2727.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 366.882s |2724.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 311.083s |2599.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 601.301s |2373.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               | 600.481s |2363.0MiB|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                             | 600.381s |2327.0MiB|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                       | 600.573s |2316.0MiB|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                   | 600.636s |2286.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                          | 600.446s |2276.0MiB|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                 | 577.989s |2250.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 600.408s |2219.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                         | 600.589s |2215.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 600.716s |2155.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                         | 600.519s |2152.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 600.560s |2138.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 600.310s |2128.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 601.032s |8073.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 600.678s |5522.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.592s |4944.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              | 600.495s |3101.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 600.547s |2727.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 366.882s |2724.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 311.083s |2599.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 601.301s |2373.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               | 600.481s |2363.0MiB|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                             | 600.381s |2327.0MiB|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                       | 600.573s |2316.0MiB|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                   | 600.636s |2286.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                          | 600.446s |2276.0MiB|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                 | 577.989s |2250.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 600.408s |2219.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                         | 600.589s |2215.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 600.716s |2155.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                         | 600.519s |2152.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 600.560s |2138.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 600.310s |2128.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.278s  |   1.278s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|124.smt2                                                                                    | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   1.077s  |   1.077s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   0.818s  |   0.818s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   1.548s  |   1.548s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|140.smt2                                                                                    | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   1.330s  |   1.330s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   1.471s  |   1.471s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   5.207s  |   5.207s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.802s  |   0.802s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.478s  |   0.478s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.695s  |   0.695s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   2.153s  |   2.153s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   8.185s  |   8.185s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   4.623s  |   4.623s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   1.330s  |   1.330s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|177.smt2                                                                                    | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   0.887s  |   0.887s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   3.243s  |   3.243s  |   0.000s  | 0.0%|
|181.smt2                                                                                    | 600.183s  | 600.183s  |   0.000s  | 0.0%|
|182.smt2                                                                                    | 600.366s  | 600.366s  |   0.000s  | 0.0%|
|183.smt2                                                                                    | 600.343s  | 600.343s  |   0.000s  | 0.0%|
|185.smt2                                                                                    | 600.403s  | 600.403s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   1.922s  |   1.922s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   2.258s  |   2.258s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   2.122s  |   2.122s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   4.414s  |   4.414s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   3.046s  |   3.046s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   5.911s  |   5.911s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   5.423s  |   5.423s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   3.498s  |   3.498s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   2.734s  |   2.734s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   2.030s  |   2.030s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   1.476s  |   1.476s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   2.015s  |   2.015s  |   0.000s  | 0.0%|
|35.smt2                                                                                     | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|40.smt2                                                                                     | 601.915s  | 601.915s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   2.166s  |   2.166s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   1.901s  |   1.901s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|54.smt2                                                                                     | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   1.956s  |   1.956s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   1.835s  |   1.835s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   2.803s  |   2.803s  |   0.000s  | 0.0%|
|58.smt2                                                                                     | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   2.597s  |   2.597s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   6.287s  |   6.287s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   5.408s  |   5.408s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|65.smt2                                                                                     | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   1.207s  |   1.207s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|73.smt2                                                                                     | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.530s  |   0.530s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   5.565s  |   5.565s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   1.692s  |   1.692s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   3.217s  |   3.217s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|966.smt2                                                                                    | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|98.smt2                                                                                     | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|99.smt2                                                                                     | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  | 169.812s  | 169.812s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.814s  |   0.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   3.657s  |   3.657s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          | 600.437s  | 600.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |   3.122s  |   3.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   1.369s  |   1.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |  33.552s  |  33.552s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.560s  |   0.560s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          | 124.902s  | 124.902s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   8.759s  |   8.759s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   3.310s  |   3.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            | 600.408s  | 600.408s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   3.409s  |   3.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   2.715s  |   2.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       | 357.961s  | 357.961s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   8.504s  |   8.504s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  85.228s  |  85.228s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   2.697s  |   2.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |   9.387s  |   9.387s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   1.096s  |   1.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   1.401s  |   1.401s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           | 189.545s  | 189.545s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |  16.681s  |  16.681s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |  13.053s  |  13.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  16.177s  |  16.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   3.940s  |   3.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |   9.359s  |   9.359s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             | 600.452s  | 600.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |   9.469s  |   9.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  13.280s  |  13.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 |  16.761s  |  16.761s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   2.413s  |   2.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   4.128s  |   4.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   9.338s  |   9.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   1.771s  |   1.771s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |  23.022s  |  23.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   1.655s  |   1.655s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |  23.167s  |  23.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               | 600.233s  | 600.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         | 600.233s  | 600.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   8.720s  |   8.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |   2.932s  |   2.932s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |  33.640s  |  33.640s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 | 163.767s  | 163.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      | 600.186s  | 600.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   2.137s  |   2.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   9.609s  |   9.609s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              | 222.094s  | 222.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   2.911s  |   2.911s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   4.393s  |   4.393s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          | 600.338s  | 600.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   1.265s  |   1.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          |  29.364s  |  29.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   3.988s  |   3.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         | 341.995s  | 341.995s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   2.789s  |   2.789s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      | 600.288s  | 600.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |  11.529s  |  11.529s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   4.115s  |   4.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   6.159s  |   6.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               | 600.236s  | 600.236s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  10.678s  |  10.678s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |  12.917s  |  12.917s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |  29.730s  |  29.730s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               |  12.467s  |  12.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   5.142s  |   5.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               |  45.750s  |  45.750s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |  15.255s  |  15.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   4.223s  |   4.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |   8.767s  |   8.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |  56.529s  |  56.529s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   4.426s  |   4.426s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   | 600.315s  | 600.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             | 600.471s  | 600.471s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  29.337s  |  29.337s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   1.567s  |   1.567s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    | 600.267s  | 600.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |   8.853s  |   8.853s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |   6.300s  |   6.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  25.014s  |  25.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     | 600.093s  | 600.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   5.662s  |   5.662s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   6.913s  |   6.913s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   3.788s  |   3.788s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |  30.357s  |  30.357s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               | 600.278s  | 600.278s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   1.240s  |   1.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   4.733s  |   4.733s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   5.505s  |   5.505s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   4.833s  |   4.833s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   1.728s  |   1.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   8.856s  |   8.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                | 600.333s  | 600.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   1.574s  |   1.574s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              | 600.281s  | 600.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |  32.442s  |  32.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   2.116s  |   2.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   9.327s  |   9.327s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  17.845s  |  17.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  94.348s  |  94.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   4.477s  |   4.477s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  11.488s  |  11.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          | 600.233s  | 600.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |  30.670s  |  30.670s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          | 600.645s  | 600.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          | 600.422s  | 600.422s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  37.067s  |  37.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   2.581s  |   2.581s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  14.176s  |  14.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   4.466s  |   4.466s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    | 600.338s  | 600.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   3.852s  |   3.852s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   3.149s  |   3.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    | 600.211s  | 600.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   3.519s  |   3.519s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   3.162s  |   3.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        | 132.612s  | 132.612s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |   8.564s  |   8.564s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   8.709s  |   8.709s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        | 145.009s  | 145.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   1.749s  |   1.749s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  42.647s  |  42.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  41.122s  |  41.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  38.826s  |  38.826s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  27.569s  |  27.569s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  69.385s  |  69.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              | 600.201s  | 600.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  50.585s  |  50.585s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  | 148.813s  | 148.813s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  | 163.200s  | 163.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |   7.532s  |   7.532s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |  91.370s  |  91.370s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   3.163s  |   3.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.762s  |   0.762s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   2.877s  |   2.877s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             | 102.493s  | 102.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |   4.503s  |   4.503s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   2.606s  |   2.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  20.718s  |  20.718s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        | 156.583s  | 156.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.704s  |   0.704s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   2.744s  |   2.744s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |  23.452s  |  23.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |   5.258s  |   5.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.781s  |   0.781s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   | 600.126s  | 600.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   4.427s  |   4.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   3.881s  |   3.881s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   2.226s  |   2.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                |  15.856s  |  15.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   1.847s  |   1.847s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      | 215.572s  | 215.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   4.266s  |   4.266s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      | 600.205s  | 600.205s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   5.883s  |   5.883s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      | 600.093s  | 600.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |   4.849s  |   4.849s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   1.006s  |   1.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   2.464s  |   2.464s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   4.972s  |   4.972s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   4.366s  |   4.366s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |  12.529s  |  12.529s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   4.815s  |   4.815s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |  70.641s  |  70.641s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  40.636s  |  40.636s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             | 528.720s  | 528.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   5.608s  |   5.608s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                |  89.036s  |  89.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |  10.909s  |  10.909s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |  10.447s  |  10.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   2.455s  |   2.455s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   4.173s  |   4.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   3.740s  |   3.740s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   5.418s  |   5.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   0.572s  |   0.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   3.729s  |   3.729s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   5.926s  |   5.926s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |  10.589s  |  10.589s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   2.975s  |   2.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  28.365s  |  28.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          | 606.998s  | 606.998s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |  10.974s  |  10.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          | 600.246s  | 600.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          | 600.202s  | 600.202s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |   8.989s  |   8.989s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          | 600.181s  | 600.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |   9.190s  |   9.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          | 600.353s  | 600.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   5.621s  |   5.621s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            | 600.190s  | 600.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   5.712s  |   5.712s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |  52.000s  |  52.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |  19.626s  |  19.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   7.490s  |   7.490s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |   6.644s  |   6.644s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   2.963s  |   2.963s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   0.731s  |   0.731s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   4.174s  |   4.174s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |  47.640s  |  47.640s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   1.017s  |   1.017s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           | 121.778s  | 121.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |  20.458s  |  20.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |   6.112s  |   6.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   2.751s  |   2.751s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   1.155s  |   1.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           | 600.309s  | 600.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   2.271s  |   2.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   2.635s  |   2.635s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |  11.108s  |  11.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |  73.019s  |  73.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   2.330s  |   2.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   1.237s  |   1.237s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           | 186.574s  | 186.574s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  37.493s  |  37.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |   1.723s  |   1.723s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |  33.583s  |  33.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |  14.689s  |  14.689s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           |  11.259s  |  11.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |  12.813s  |  12.813s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   0.915s  |   0.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |  21.790s  |  21.790s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   2.494s  |   2.494s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  39.388s  |  39.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   2.507s  |   2.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |  17.270s  |  17.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   3.957s  |   3.957s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   6.587s  |   6.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |  39.443s  |  39.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   2.183s  |   2.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |  14.185s  |  14.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  23.031s  |  23.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   2.417s  |   2.417s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     | 600.387s  | 600.387s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   2.167s  |   2.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |   2.118s  |   2.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   1.307s  |   1.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     | 600.171s  | 600.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     | 182.098s  | 182.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   2.364s  |   2.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   8.072s  |   8.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |   6.584s  |   6.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |  10.821s  |  10.821s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   1.654s  |   1.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   8.286s  |   8.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   1.568s  |   1.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   3.289s  |   3.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   2.762s  |   2.762s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   3.064s  |   3.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |  70.026s  |  70.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |  91.578s  |  91.578s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |   9.124s  |   9.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   5.598s  |   5.598s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |  11.360s  |  11.360s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               | 478.228s  | 478.228s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |   6.376s  |   6.376s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   3.647s  |   3.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     | 600.180s  | 600.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |  12.794s  |  12.794s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |  41.800s  |  41.800s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   2.220s  |   2.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |  15.553s  |  15.553s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   3.099s  |   3.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |  15.245s  |  15.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |  15.555s  |  15.555s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     | 600.197s  | 600.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     | 600.141s  | 600.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  14.036s  |  14.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   2.109s  |   2.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |  17.144s  |  17.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   2.043s  |   2.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |  16.245s  |  16.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |   9.533s  |   9.533s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   1.407s  |   1.407s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |   4.673s  |   4.673s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |   5.645s  |   5.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               | 232.789s  | 232.789s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               | 600.204s  | 600.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               | 600.262s  | 600.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |   0.738s  |   0.738s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   6.099s  |   6.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |  10.644s  |  10.644s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  38.172s  |  38.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   1.819s  |   1.819s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               | 600.180s  | 600.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |   8.322s  |   8.322s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |  23.227s  |  23.227s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   0.942s  |   0.942s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   8.220s  |   8.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   0.822s  |   0.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   2.623s  |   2.623s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               | 115.483s  | 115.483s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               | 600.222s  | 600.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   9.657s  |   9.657s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   1.868s  |   1.868s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   0.812s  |   0.812s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   7.195s  |   7.195s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               | 600.271s  | 600.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               | 600.176s  | 600.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   2.687s  |   2.687s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |  10.400s  |  10.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |  13.232s  |  13.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |   2.045s  |   2.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   4.526s  |   4.526s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       | 141.595s  | 141.595s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |   1.875s  |   1.875s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   2.366s  |   2.366s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |  35.165s  |  35.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   1.066s  |   1.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |   7.809s  |   7.809s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   2.295s  |   2.295s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   8.243s  |   8.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   2.245s  |   2.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   2.458s  |   2.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |   0.941s  |   0.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   6.383s  |   6.383s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   6.938s  |   6.938s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |  24.408s  |  24.408s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |  16.144s  |  16.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   0.756s  |   0.756s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   2.398s  |   2.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   2.319s  |   2.319s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             | 600.305s  | 600.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |  15.684s  |  15.684s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |  15.792s  |  15.792s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |   5.710s  |   5.710s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   0.478s  |   0.478s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |   0.900s  |   0.900s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |   1.912s  |   1.912s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   5.758s  |   5.758s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   7.756s  |   7.756s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             | 600.249s  | 600.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |   6.346s  |   6.346s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   8.020s  |   8.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   1.827s  |   1.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             | 600.423s  | 600.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |   3.563s  |   3.563s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |   7.550s  |   7.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |   4.864s  |   4.864s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |   3.586s  |   3.586s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         | 185.632s  | 185.632s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   6.737s  |   6.737s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              | 256.643s  | 256.643s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   4.329s  |   4.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   2.188s  |   2.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |  23.619s  |  23.619s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |  36.930s  |  36.930s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   2.206s  |   2.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   2.458s  |   2.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   1.758s  |   1.758s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    | 475.597s  | 475.597s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   2.310s  |   2.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    | 600.316s  | 600.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   5.515s  |   5.515s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   1.851s  |   1.851s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |  96.419s  |  96.419s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    | 600.194s  | 600.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    | 600.212s  | 600.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   3.664s  |   3.664s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   3.727s  |   3.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |   1.157s  |   1.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   8.154s  |   8.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |   9.549s  |   9.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   0.940s  |   0.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  50.491s  |  50.491s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  77.988s  |  77.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   2.539s  |   2.539s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |  31.688s  |  31.688s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   2.279s  |   2.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   9.634s  |   9.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |  11.174s  |  11.174s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   2.604s  |   2.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   6.203s  |   6.203s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |   6.958s  |   6.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   2.305s  |   2.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   2.434s  |   2.434s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |  24.462s  |  24.462s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   4.102s  |   4.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |  11.362s  |  11.362s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          | 600.298s  | 600.298s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   1.731s  |   1.731s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  26.172s  |  26.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |  14.356s  |  14.356s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          | 600.395s  | 600.395s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |  12.598s  |  12.598s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   8.460s  |   8.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |   9.819s  |   9.819s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   2.058s  |   2.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   2.252s  |   2.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   0.702s  |   0.702s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          | 600.226s  | 600.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |  18.645s  |  18.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   2.532s  |   2.532s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   5.365s  |   5.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   6.351s  |   6.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |  12.812s  |  12.812s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |  16.121s  |  16.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |  66.678s  |  66.678s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        | 124.163s  | 124.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |  52.334s  |  52.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |  17.499s  |  17.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   1.764s  |   1.764s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |  14.159s  |  14.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   1.142s  |   1.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |  61.947s  |  61.947s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |  11.150s  |  11.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |  99.628s  |  99.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.776s  |   0.776s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |  19.619s  |  19.619s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   2.816s  |   2.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |   6.238s  |   6.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   2.945s  |   2.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   2.913s  |   2.913s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        | 600.161s  | 600.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   2.317s  |   2.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |   8.720s  |   8.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |  41.960s  |  41.960s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   2.499s  |   2.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |  24.991s  |  24.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |  12.785s  |  12.785s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        | 600.158s  | 600.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |  14.535s  |  14.535s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |  18.428s  |  18.428s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   4.414s  |   4.414s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |   7.822s  |   7.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |  26.472s  |  26.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |   8.214s  |   8.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   1.499s  |   1.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        | 600.167s  | 600.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   2.126s  |   2.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  | 600.335s  | 600.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   1.507s  |   1.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   7.580s  |   7.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |  48.682s  |  48.682s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |  19.222s  |  19.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |   1.773s  |   1.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   7.591s  |   7.591s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   0.906s  |   0.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.969s  |   0.969s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  11.192s  |  11.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     | 600.190s  | 600.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   2.100s  |   2.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     | 600.170s  | 600.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   8.874s  |   8.874s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |   5.893s  |   5.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |   1.786s  |   1.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       | 293.221s  | 293.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   1.972s  |   1.972s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |  51.617s  |  51.617s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |  12.502s  |  12.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |  84.711s  |  84.711s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   2.959s  |   2.959s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   2.141s  |   2.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   2.227s  |   2.227s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |  56.547s  |  56.547s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 | 169.006s  | 169.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   1.988s  |   1.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   1.280s  |   1.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   2.729s  |   2.729s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       | 600.052s  | 600.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       | 600.550s  | 600.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |   7.570s  |   7.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 | 600.291s  | 600.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            | 100.445s  | 100.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |  39.308s  |  39.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  18.081s  |  18.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   2.440s  |   2.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |  13.714s  |  13.714s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  | 107.629s  | 107.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   1.261s  |   1.261s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  23.965s  |  23.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  38.987s  |  38.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   2.044s  |   2.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |  55.549s  |  55.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  94.973s  |  94.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   2.726s  |   2.726s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |  41.588s  |  41.588s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            | 600.386s  | 600.386s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   1.936s  |   1.936s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   2.796s  |   2.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   5.634s  |   5.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   4.076s  |   4.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   2.648s  |   2.648s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   3.996s  |   3.996s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |  25.408s  |  25.408s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                | 278.796s  | 278.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   2.828s  |   2.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   3.433s  |   3.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   1.890s  |   1.890s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   1.696s  |   1.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |  59.658s  |  59.658s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   3.807s  |   3.807s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   4.983s  |   4.983s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   4.995s  |   4.995s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   7.482s  |   7.482s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |   9.512s  |   9.512s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |  13.335s  |  13.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |  38.312s  |  38.312s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   1.681s  |   1.681s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   2.726s  |   2.726s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   3.196s  |   3.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   4.385s  |   4.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   5.594s  |   5.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  44.109s  |  44.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   8.225s  |   8.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  78.779s  |  78.779s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |   9.557s  |   9.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   3.041s  |   3.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   1.784s  |   1.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  59.045s  |  59.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   4.902s  |   4.902s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |  10.235s  |  10.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   5.260s  |   5.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |  23.986s  |  23.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   5.380s  |   5.380s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   1.490s  |   1.490s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   2.652s  |   2.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   5.951s  |   5.951s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   7.745s  |   7.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |  64.704s  |  64.704s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   1.695s  |   1.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   1.947s  |   1.947s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   9.318s  |   9.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |  10.958s  |  10.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   4.482s  |   4.482s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   5.638s  |   5.638s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   3.854s  |   3.854s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   4.164s  |   4.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   3.526s  |   3.526s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   3.184s  |   3.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   1.907s  |   1.907s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  60.511s  |  60.511s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   2.343s  |   2.343s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   3.769s  |   3.769s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                | 336.784s  | 336.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   6.567s  |   6.567s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |  13.398s  |  13.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   4.292s  |   4.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   2.941s  |   2.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |  10.988s  |  10.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  91.887s  |  91.887s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |  12.370s  |  12.370s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   3.336s  |   3.336s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   1.594s  |   1.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                | 600.256s  | 600.256s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   4.956s  |   4.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   3.138s  |   3.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   6.182s  |   6.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   2.822s  |   2.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |  57.594s  |  57.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   3.264s  |   3.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |  11.572s  |  11.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   9.360s  |   9.360s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  10.262s  |  10.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  12.265s  |  12.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |  18.933s  |  18.933s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   3.863s  |   3.863s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   8.187s  |   8.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   2.999s  |   2.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   3.278s  |   3.278s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   7.128s  |   7.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                | 600.625s  | 600.625s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |   9.444s  |   9.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  29.995s  |  29.995s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   2.465s  |   2.465s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |  50.806s  |  50.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  37.952s  |  37.952s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   3.279s  |   3.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   6.784s  |   6.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   2.305s  |   2.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   2.866s  |   2.866s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   3.755s  |   3.755s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   3.736s  |   3.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  44.292s  |  44.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   4.561s  |   4.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |  14.100s  |  14.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   2.409s  |   2.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   2.939s  |   2.939s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   4.463s  |   4.463s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   1.909s  |   1.909s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |  23.407s  |  23.407s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   2.516s  |   2.516s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |   7.618s  |   7.618s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   2.261s  |   2.261s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   3.406s  |   3.406s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   2.676s  |   2.676s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   3.234s  |   3.234s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   2.942s  |   2.942s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   4.377s  |   4.377s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   3.242s  |   3.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   9.867s  |   9.867s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   3.195s  |   3.195s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   2.945s  |   2.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |  21.103s  |  21.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   2.604s  |   2.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   2.429s  |   2.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   4.786s  |   4.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   4.534s  |   4.534s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          | 130.325s  | 130.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          | 219.950s  | 219.950s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          | 120.526s  | 120.526s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |  15.326s  |  15.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   4.908s  |   4.908s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             | 600.227s  | 600.227s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            | 192.409s  | 192.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            | 306.321s  | 306.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   3.809s  |   3.809s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   3.424s  |   3.424s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   7.658s  |   7.658s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   9.304s  |   9.304s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |   6.613s  |   6.613s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   4.155s  |   4.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |   8.698s  |   8.698s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   4.874s  |   4.874s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   4.657s  |   4.657s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   9.527s  |   9.527s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   1.398s  |   1.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   5.046s  |   5.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |  14.575s  |  14.575s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |  10.579s  |  10.579s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   1.386s  |   1.386s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   1.380s  |   1.380s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   2.812s  |   2.812s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   | 600.154s  | 600.154s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               | 545.879s  | 545.879s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |  72.992s  |  72.992s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |  46.181s  |  46.181s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   1.029s  |   1.029s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               | 600.209s  | 600.209s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               | 600.288s  | 600.288s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   6.217s  |   6.217s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   1.425s  |   1.425s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          | 600.268s  | 600.268s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   1.783s  |   1.783s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   2.289s  |   2.289s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               | 600.269s  | 600.269s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               | 600.367s  | 600.367s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  15.409s  |  15.409s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               | 600.187s  | 600.187s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               | 600.161s  | 600.161s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   2.676s  |   2.676s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         | 600.187s  | 600.187s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         |  53.504s  |  53.504s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               | 600.523s  | 600.523s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               | 600.442s  | 600.442s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  96.326s  |  96.326s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   3.978s  |   3.978s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |   7.498s  |   7.498s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         | 600.376s  | 600.376s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |   8.824s  |   8.824s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         | 600.288s  | 600.288s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  18.578s  |  18.578s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  35.831s  |  35.831s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    | 601.032s  | 601.032s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  22.367s  |  22.367s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    | 600.636s  | 600.636s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  16.250s  |  16.250s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  29.148s  |  29.148s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   1.644s  |   1.644s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              | 600.438s  | 600.438s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  27.348s  |  27.348s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   4.977s  |   4.977s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   5.558s  |   5.558s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  34.303s  |  34.303s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.922s  |   0.922s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |  10.384s  |  10.384s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |  13.553s  |  13.553s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   5.711s  |   5.711s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   1.618s  |   1.618s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |   5.636s  |   5.636s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   6.960s  |   6.960s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   3.032s  |   3.032s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  42.667s  |  42.667s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |  36.766s  |  36.766s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 | 600.304s  | 600.304s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  16.207s  |  16.207s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           | 610.034s  | 610.034s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |  10.252s  |  10.252s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |  62.157s  |  62.157s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              | 600.194s  | 600.194s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |  10.238s  |  10.238s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              | 600.272s  | 600.272s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  18.945s  |  18.945s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              | 600.176s  | 600.176s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |  18.933s  |  18.933s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              | 600.161s  | 600.161s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   3.045s  |   3.045s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |   8.093s  |   8.093s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  18.137s  |  18.137s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |   8.837s  |   8.837s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |  33.347s  |  33.347s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  55.711s  |  55.711s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  68.111s  |  68.111s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  24.496s  |  24.496s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  43.133s  |  43.133s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            | 246.229s  | 246.229s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   6.153s  |   6.153s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   4.959s  |   4.959s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             | 600.174s  | 600.174s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   3.207s  |   3.207s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             | 600.180s  | 600.180s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   3.280s  |   3.280s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |  13.899s  |  13.899s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   3.794s  |   3.794s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             | 600.155s  | 600.155s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   2.589s  |   2.589s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   5.018s  |   5.018s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |   2.023s  |   2.023s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   7.077s  |   7.077s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |  10.441s  |  10.441s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   2.691s  |   2.691s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   4.310s  |   4.310s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   7.680s  |   7.680s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   3.294s  |   3.294s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   1.202s  |   1.202s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   1.266s  |   1.266s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |   8.275s  |   8.275s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   2.273s  |   2.273s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               | 600.669s  | 600.669s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   1.074s  |   1.074s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            | 600.338s  | 600.338s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   1.638s  |   1.638s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 | 600.422s  | 600.422s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |   6.587s  |   6.587s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  24.095s  |  24.095s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |   9.630s  |   9.630s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           | 600.156s  | 600.156s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |  15.958s  |  15.958s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |  12.463s  |  12.463s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 | 600.248s  | 600.248s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      | 358.013s  | 358.013s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |  11.430s  |  11.430s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |  13.731s  |  13.731s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  36.450s  |  36.450s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |  11.605s  |  11.605s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  46.225s  |  46.225s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |   5.528s  |   5.528s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   2.203s  |   2.203s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   6.752s  |   6.752s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      | 419.241s  | 419.241s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              | 600.533s  | 600.533s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   2.939s  |   2.939s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.678s  |   0.678s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       | 600.225s  | 600.225s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |  14.163s  |  14.163s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   1.089s  |   1.089s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       |  82.879s  |  82.879s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |   9.863s  |   9.863s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.559s  |   0.559s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   1.093s  |   1.093s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |  10.321s  |  10.321s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |  17.578s  |  17.578s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |  22.535s  |  22.535s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       | 600.326s  | 600.326s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       | 240.470s  | 240.470s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       | 600.213s  | 600.213s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   9.179s  |   9.179s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   2.750s  |   2.750s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       | 600.137s  | 600.137s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |   4.265s  |   4.265s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   1.017s  |   1.017s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   3.403s  |   3.403s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       |  67.981s  |  67.981s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       |  75.722s  |  75.722s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   2.768s  |   2.768s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   8.225s  |   8.225s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       | 230.733s  | 230.733s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   3.753s  |   3.753s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               | 596.645s  | 596.645s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         | 373.427s  | 373.427s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   3.406s  |   3.406s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.690s  |   0.690s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   1.994s  |   1.994s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   1.280s  |   1.280s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   1.050s  |   1.050s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |  10.917s  |  10.917s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |  10.055s  |  10.055s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |   5.318s  |   5.318s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   3.199s  |   3.199s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   6.185s  |   6.185s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   1.743s  |   1.743s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   6.682s  |   6.682s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                | 607.399s  | 607.399s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   2.311s  |   2.311s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   4.146s  |   4.146s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   3.879s  |   3.879s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   2.592s  |   2.592s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   3.352s  |   3.352s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |  14.979s  |  14.979s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   2.380s  |   2.380s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   2.431s  |   2.431s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   1.576s  |   1.576s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   2.243s  |   2.243s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   2.751s  |   2.751s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   1.998s  |   1.998s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   3.951s  |   3.951s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   3.111s  |   3.111s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   2.079s  |   2.079s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |   9.706s  |   9.706s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   2.895s  |   2.895s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      | 600.175s  | 600.175s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   4.442s  |   4.442s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   3.495s  |   3.495s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   8.403s  |   8.403s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   2.332s  |   2.332s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   1.360s  |   1.360s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   3.785s  |   3.785s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   4.649s  |   4.649s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   8.548s  |   8.548s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   3.166s  |   3.166s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   4.715s  |   4.715s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   1.637s  |   1.637s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      | 125.133s  | 125.133s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   2.026s  |   2.026s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      | 600.164s  | 600.164s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   3.807s  |   3.807s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   3.267s  |   3.267s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   5.785s  |   5.785s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   4.737s  |   4.737s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   5.390s  |   5.390s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   4.316s  |   4.316s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |  19.264s  |  19.264s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   2.602s  |   2.602s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   2.777s  |   2.777s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   1.503s  |   1.503s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   1.546s  |   1.546s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   5.080s  |   5.080s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   5.467s  |   5.467s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |  21.631s  |  21.631s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   1.964s  |   1.964s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   7.099s  |   7.099s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   5.140s  |   5.140s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |   4.893s  |   4.893s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   1.443s  |   1.443s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   5.347s  |   5.347s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   1.900s  |   1.900s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   4.043s  |   4.043s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   2.588s  |   2.588s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   2.497s  |   2.497s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   6.927s  |   6.927s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   7.851s  |   7.851s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   2.370s  |   2.370s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   2.105s  |   2.105s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   2.346s  |   2.346s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   2.540s  |   2.540s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   8.355s  |   8.355s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   5.767s  |   5.767s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   1.949s  |   1.949s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   7.488s  |   7.488s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   3.199s  |   3.199s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   4.388s  |   4.388s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |  10.378s  |  10.378s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   5.935s  |   5.935s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |  13.512s  |  13.512s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |   9.879s  |   9.879s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            | 600.268s  | 600.268s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |   9.496s  |   9.496s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  33.861s  |  33.861s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |  19.052s  |  19.052s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  25.551s  |  25.551s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |  14.695s  |  14.695s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        | 600.481s  | 600.481s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        | 366.882s  | 366.882s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  11.621s  |  11.621s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       | 600.147s  | 600.147s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   6.235s  |   6.235s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   3.849s  |   3.849s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     | 562.779s  | 562.779s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     | 600.284s  | 600.284s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     | 600.287s  | 600.287s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |  12.422s  |  12.422s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         | 600.408s  | 600.408s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         | 600.427s  | 600.427s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               | 600.495s  | 600.495s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   2.150s  |   2.150s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |   4.406s  |   4.406s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               | 600.381s  | 600.381s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  | 600.239s  | 600.239s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |  65.720s  |  65.720s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     | 135.030s  | 135.030s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  22.539s  |  22.539s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  26.010s  |  26.010s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            |  51.516s  |  51.516s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            | 600.311s  | 600.311s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   4.284s  |   4.284s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   2.917s  |   2.917s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                | 600.211s  | 600.211s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   3.592s  |   3.592s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.764s  |   0.764s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  95.977s  |  95.977s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 | 536.197s  | 536.197s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 | 521.764s  | 521.764s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  62.749s  |  62.749s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 | 104.255s  | 104.255s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  20.418s  |  20.418s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |  32.908s  |  32.908s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           | 104.048s  | 104.048s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           | 600.211s  | 600.211s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           | 481.613s  | 481.613s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |  16.274s  |  16.274s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  40.280s  |  40.280s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |  22.428s  |  22.428s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   5.399s  |   5.399s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  79.952s  |  79.952s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 | 600.380s  | 600.380s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  35.738s  |  35.738s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 | 546.994s  | 546.994s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   5.518s  |   5.518s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 | 282.609s  | 282.609s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 | 600.237s  | 600.237s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |  29.644s  |  29.644s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 |  89.481s  |  89.481s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   6.231s  |   6.231s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 |  40.406s  |  40.406s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |  11.306s  |  11.306s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  33.599s  |  33.599s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |  52.085s  |  52.085s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |  21.127s  |  21.127s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |  20.710s  |  20.710s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 | 600.370s  | 600.370s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  41.490s  |  41.490s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |  11.556s  |  11.556s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 | 561.587s  | 561.587s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 | 365.246s  | 365.246s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   6.540s  |   6.540s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |   6.533s  |   6.533s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 | 160.450s  | 160.450s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   3.764s  |   3.764s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |  53.002s  |  53.002s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   4.493s  |   4.493s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |  45.676s  |  45.676s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |  10.958s  |  10.958s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |  13.534s  |  13.534s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   4.840s  |   4.840s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   2.522s  |   2.522s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  21.917s  |  21.917s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 |  83.962s  |  83.962s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  37.557s  |  37.557s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 | 147.719s  | 147.719s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  20.780s  |  20.780s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        | 600.292s  | 600.292s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  48.872s  |  48.872s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  24.528s  |  24.528s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |  89.346s  |  89.346s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           |  94.188s  |  94.188s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    | 600.183s  | 600.183s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       |  89.619s  |  89.619s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       | 227.697s  | 227.697s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  37.049s  |  37.049s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  77.978s  |  77.978s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |  12.675s  |  12.675s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              | 600.246s  | 600.246s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  44.919s  |  44.919s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  14.879s  |  14.879s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  94.676s  |  94.676s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  37.755s  |  37.755s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  45.936s  |  45.936s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     | 100.810s  | 100.810s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  30.391s  |  30.391s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   5.919s  |   5.919s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  63.142s  |  63.142s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     | 144.709s  | 144.709s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  53.083s  |  53.083s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          | 124.385s  | 124.385s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  74.973s  |  74.973s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  70.436s  |  70.436s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  25.852s  |  25.852s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  50.004s  |  50.004s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   4.720s  |   4.720s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   7.098s  |   7.098s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        | 600.347s  | 600.347s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        | 206.731s  | 206.731s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |  24.009s  |  24.009s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        | 600.169s  | 600.169s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        | 600.127s  | 600.127s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        |  40.659s  |  40.659s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        |  21.762s  |  21.762s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        |  79.970s  |  79.970s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   1.368s  |   1.368s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     | 600.214s  | 600.214s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   1.165s  |   1.165s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   2.382s  |   2.382s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   7.197s  |   7.197s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  16.361s  |  16.361s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 | 600.319s  | 600.319s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   2.637s  |   2.637s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 | 600.230s  | 600.230s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |   8.268s  |   8.268s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 | 600.183s  | 600.183s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |  11.411s  |  11.411s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   7.071s  |   7.071s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   3.515s  |   3.515s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   6.057s  |   6.057s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |   3.473s  |   3.473s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             | 600.268s  | 600.268s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   5.589s  |   5.589s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             | 600.432s  | 600.432s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             | 600.220s  | 600.220s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   2.240s  |   2.240s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             | 187.432s  | 187.432s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             | 600.411s  | 600.411s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |   7.517s  |   7.517s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             | 600.440s  | 600.440s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   1.826s  |   1.826s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             | 356.489s  | 356.489s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             | 600.562s  | 600.562s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   6.125s  |   6.125s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   3.713s  |   3.713s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   1.859s  |   1.859s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   4.116s  |   4.116s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   1.011s  |   1.011s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  29.711s  |  29.711s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           | 600.127s  | 600.127s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   2.337s  |   2.337s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 | 600.167s  | 600.167s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 | 615.414s  | 615.414s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   3.397s  |   3.397s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   3.316s  |   3.316s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   5.099s  |   5.099s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 | 600.221s  | 600.221s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 | 600.252s  | 600.252s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  |  56.592s  |  56.592s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |   2.290s  |   2.290s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 | 600.180s  | 600.180s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 | 600.243s  | 600.243s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   2.030s  |   2.030s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   1.250s  |   1.250s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |   6.496s  |   6.496s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   3.352s  |   3.352s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   2.305s  |   2.305s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 | 613.721s  | 613.721s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   5.455s  |   5.455s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   6.605s  |   6.605s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  |  32.047s  |  32.047s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   7.913s  |   7.913s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |  16.214s  |  16.214s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            | 600.268s  | 600.268s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  67.001s  |  67.001s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   3.472s  |   3.472s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   2.550s  |   2.550s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  | 623.785s  | 623.785s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            | 600.258s  | 600.258s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   2.293s  |   2.293s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |  16.069s  |  16.069s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   4.633s  |   4.633s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  | 150.366s  | 150.366s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  | 600.171s  | 600.171s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   2.917s  |   2.917s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   7.401s  |   7.401s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  | 600.137s  | 600.137s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |  13.595s  |  13.595s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   2.720s  |   2.720s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |  27.384s  |  27.384s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   1.087s  |   1.087s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |  15.156s  |  15.156s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           | 600.365s  | 600.365s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           | 600.264s  | 600.264s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  16.994s  |  16.994s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               |  13.326s  |  13.326s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               | 600.493s  | 600.493s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               | 270.645s  | 270.645s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               | 600.398s  | 600.398s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               | 600.514s  | 600.514s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |   2.463s  |   2.463s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |  29.293s  |  29.293s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  38.657s  |  38.657s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |  17.538s  |  17.538s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   5.344s  |   5.344s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   1.465s  |   1.465s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |   8.030s  |   8.030s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   3.949s  |   3.949s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |  11.687s  |  11.687s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |   8.943s  |   8.943s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   3.477s  |   3.477s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   4.794s  |   4.794s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  31.597s  |  31.597s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  12.086s  |  12.086s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    | 600.297s  | 600.297s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   7.047s  |   7.047s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               | 600.245s  | 600.245s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             | 600.220s  | 600.220s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             | 600.292s  | 600.292s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   5.559s  |   5.559s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   5.076s  |   5.076s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  20.806s  |  20.806s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |  58.459s  |  58.459s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               | 357.667s  | 357.667s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         | 600.440s  | 600.440s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  17.540s  |  17.540s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  18.543s  |  18.543s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  23.860s  |  23.860s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  11.410s  |  11.410s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  14.918s  |  14.918s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        | 600.547s  | 600.547s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   0.562s  |   0.562s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            |  33.688s  |  33.688s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            |   3.149s  |   3.149s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   2.902s  |   2.902s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |  27.210s  |  27.210s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   4.090s  |   4.090s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            | 114.365s  | 114.365s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   4.255s  |   4.255s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  24.770s  |  24.770s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  35.706s  |  35.706s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              |  14.426s  |  14.426s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   1.692s  |   1.692s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  46.793s  |  46.793s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          | 600.256s  | 600.256s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   2.589s  |   2.589s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |  20.659s  |  20.659s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  24.835s  |  24.835s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   3.754s  |   3.754s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   5.252s  |   5.252s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   6.228s  |   6.228s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   2.795s  |   2.795s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         |  79.537s  |  79.537s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |  15.369s  |  15.369s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |   8.963s  |   8.963s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              | 600.183s  | 600.183s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   2.895s  |   2.895s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   3.343s  |   3.343s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |   1.876s  |   1.876s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          | 600.495s  | 600.495s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          | 600.519s  | 600.519s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |   9.874s  |   9.874s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          | 600.360s  | 600.360s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          | 600.589s  | 600.589s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |   9.220s  |   9.220s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          | 600.272s  | 600.272s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          | 600.678s  | 600.678s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |   8.579s  |   8.579s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                | 600.247s  | 600.247s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                | 600.481s  | 600.481s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   2.385s  |   2.385s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                | 600.427s  | 600.427s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                | 600.560s  | 600.560s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |  10.743s  |  10.743s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                | 600.339s  | 600.339s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                | 600.716s  | 600.716s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |   9.685s  |   9.685s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                | 600.264s  | 600.264s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                | 600.621s  | 600.621s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          | 600.525s  | 600.525s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |  13.133s  |  13.133s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   8.795s  |   8.795s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |   5.219s  |   5.219s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          | 295.300s  | 295.300s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |  33.052s  |  33.052s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   8.479s  |   8.479s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   3.486s  |   3.486s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |  32.798s  |  32.798s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   6.003s  |   6.003s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   5.081s  |   5.081s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |  23.792s  |  23.792s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                | 600.233s  | 600.233s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   0.701s  |   0.701s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.827s  |   0.827s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                | 600.173s  | 600.173s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                | 600.234s  | 600.234s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   5.014s  |   5.014s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   5.283s  |   5.283s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   5.531s  |   5.531s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   2.006s  |   2.006s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   6.643s  |   6.643s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   4.361s  |   4.361s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                | 499.512s  | 499.512s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   5.391s  |   5.391s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |  23.795s  |  23.795s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   7.043s  |   7.043s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   1.380s  |   1.380s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   0.924s  |   0.924s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |   5.767s  |   5.767s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                | 141.375s  | 141.375s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   6.811s  |   6.811s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   6.635s  |   6.635s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   3.420s  |   3.420s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |  20.593s  |  20.593s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   7.567s  |   7.567s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   1.202s  |   1.202s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   1.253s  |   1.253s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   4.214s  |   4.214s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   8.871s  |   8.871s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   4.959s  |   4.959s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   0.997s  |   0.997s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   5.016s  |   5.016s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   4.271s  |   4.271s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   1.623s  |   1.623s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          | 600.208s  | 600.208s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   8.322s  |   8.322s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |   4.271s  |   4.271s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          | 600.199s  | 600.199s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |   6.340s  |   6.340s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          |  14.898s  |  14.898s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  10.746s  |  10.746s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     | 109.528s  | 109.528s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           | 159.046s  | 159.046s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   3.151s  |   3.151s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  | 177.417s  | 177.417s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   5.173s  |   5.173s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   0.588s  |   0.588s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   4.265s  |   4.265s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |   8.901s  |   8.901s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |   5.429s  |   5.429s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   4.613s  |   4.613s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        | 600.189s  | 600.189s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |  36.784s  |  36.784s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        | 567.587s  | 567.587s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        | 535.419s  | 535.419s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   4.781s  |   4.781s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        | 103.367s  | 103.367s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |   9.266s  |   9.266s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   1.355s  |   1.355s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |  26.524s  |  26.524s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   7.335s  |   7.335s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   7.459s  |   7.459s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   1.122s  |   1.122s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   8.675s  |   8.675s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   4.548s  |   4.548s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   1.649s  |   1.649s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   4.436s  |   4.436s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   8.102s  |   8.102s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  20.399s  |  20.399s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   1.470s  |   1.470s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   4.870s  |   4.870s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   3.854s  |   3.854s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |  70.179s  |  70.179s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        | 296.262s  | 296.262s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |   4.967s  |   4.967s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            | 493.630s  | 493.630s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |  50.737s  |  50.737s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   1.189s  |   1.189s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   1.928s  |   1.928s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   1.443s  |   1.443s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   6.627s  |   6.627s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   3.167s  |   3.167s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.889s  |   0.889s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |  14.760s  |  14.760s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |  14.965s  |  14.965s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   1.130s  |   1.130s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |  34.592s  |  34.592s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                | 600.607s  | 600.607s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  66.242s  |  66.242s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   3.363s  |   3.363s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              | 146.579s  | 146.579s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        | 600.573s  | 600.573s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   | 600.310s  | 600.310s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   1.419s  |   1.419s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   | 600.117s  | 600.117s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |   2.844s  |   2.844s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   | 600.314s  | 600.314s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   | 600.262s  | 600.262s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |   2.066s  |   2.066s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         | 600.227s  | 600.227s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         | 600.171s  | 600.171s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   4.056s  |   4.056s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |  36.665s  |  36.665s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   1.843s  |   1.843s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        | 600.271s  | 600.271s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        | 600.415s  | 600.415s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   7.189s  |   7.189s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        | 600.183s  | 600.183s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        | 600.265s  | 600.265s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |   7.508s  |   7.508s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        | 600.357s  | 600.357s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   1.951s  |   1.951s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   3.812s  |   3.812s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   6.787s  |   6.787s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  21.640s  |  21.640s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   8.785s  |   8.785s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   5.820s  |   5.820s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |  13.996s  |  13.996s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  23.175s  |  23.175s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |  12.447s  |  12.447s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |   3.209s  |   3.209s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            | 600.226s  | 600.226s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            | 600.313s  | 600.313s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |   8.453s  |   8.453s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            | 600.292s  | 600.292s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   8.737s  |   8.737s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            | 600.325s  | 600.325s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   4.865s  |   4.865s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  | 600.237s  | 600.237s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   5.609s  |   5.609s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  15.020s  |  15.020s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  27.576s  |  27.576s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  17.435s  |  17.435s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  12.195s  |  12.195s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   6.210s  |   6.210s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |  83.241s  |  83.241s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         |  14.464s  |  14.464s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   3.484s  |   3.484s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         |  20.935s  |  20.935s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |  14.292s  |  14.292s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |   6.074s  |   6.074s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   4.216s  |   4.216s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         | 119.875s  | 119.875s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   4.479s  |   4.479s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   4.984s  |   4.984s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   6.022s  |   6.022s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   3.782s  |   3.782s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   3.291s  |   3.291s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   2.814s  |   2.814s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   1.516s  |   1.516s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   | 600.188s  | 600.188s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           | 600.206s  | 600.206s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           | 600.242s  | 600.242s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           | 600.268s  | 600.268s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   1.983s  |   1.983s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |  47.129s  |  47.129s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           | 120.689s  | 120.689s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           | 600.154s  | 600.154s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   1.437s  |   1.437s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  | 600.197s  | 600.197s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   3.942s  |   3.942s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        | 602.733s  | 602.733s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   3.175s  |   3.175s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   4.603s  |   4.603s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   3.725s  |   3.725s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   3.316s  |   3.316s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   2.512s  |   2.512s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   2.043s  |   2.043s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   2.863s  |   2.863s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   3.095s  |   3.095s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             | 209.911s  | 209.911s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   1.303s  |   1.303s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |  43.633s  |  43.633s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   4.878s  |   4.878s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |  37.144s  |  37.144s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   6.502s  |   6.502s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |  76.272s  |  76.272s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             | 600.217s  | 600.217s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   2.666s  |   2.666s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |  75.362s  |  75.362s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             | 600.220s  | 600.220s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   7.757s  |   7.757s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |  14.330s  |  14.330s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              | 600.253s  | 600.253s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   4.515s  |   4.515s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                | 600.366s  | 600.366s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                | 600.187s  | 600.187s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |  11.926s  |  11.926s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                | 600.321s  | 600.321s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                | 600.241s  | 600.241s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  18.850s  |  18.850s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                | 600.204s  | 600.204s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                | 600.456s  | 600.456s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  16.963s  |  16.963s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  29.222s  |  29.222s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |  23.005s  |  23.005s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   3.455s  |   3.455s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   3.766s  |   3.766s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              | 600.381s  | 600.381s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       | 601.301s  | 601.301s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       | 600.226s  | 600.226s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  36.115s  |  36.115s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  16.630s  |  16.630s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  40.905s  |  40.905s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  46.499s  |  46.499s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           |  33.144s  |  33.144s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  16.983s  |  16.983s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  24.916s  |  24.916s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   8.702s  |   8.702s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             | 600.185s  | 600.185s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  44.178s  |  44.178s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |  25.127s  |  25.127s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  16.156s  |  16.156s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  33.255s  |  33.255s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  27.097s  |  27.097s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |  22.479s  |  22.479s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  52.536s  |  52.536s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  25.176s  |  25.176s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           | 600.446s  | 600.446s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           | 600.592s  | 600.592s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           | 159.334s  | 159.334s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  14.188s  |  14.188s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 | 600.617s  | 600.617s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 | 600.288s  | 600.288s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   7.940s  |   7.940s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |   3.731s  |   3.731s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                | 600.370s  | 600.370s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                | 600.363s  | 600.363s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  14.783s  |  14.783s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  26.323s  |  26.323s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          | 600.582s  | 600.582s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          | 600.437s  | 600.437s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |  10.586s  |  10.586s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  27.657s  |  27.657s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     | 600.032s  | 600.032s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   4.322s  |   4.322s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                |  51.177s  |  51.177s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                | 600.267s  | 600.267s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   1.627s  |   1.627s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   4.273s  |   4.273s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            | 600.124s  | 600.124s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |  22.633s  |  22.633s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  41.185s  |  41.185s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   2.626s  |   2.626s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |  49.191s  |  49.191s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   2.379s  |   2.379s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   1.472s  |   1.472s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |  28.255s  |  28.255s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      | 179.160s  | 179.160s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   3.720s  |   3.720s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   1.342s  |   1.342s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      | 151.418s  | 151.418s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   3.233s  |   3.233s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   1.353s  |   1.353s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.743s  |   0.743s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   1.691s  |   1.691s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  38.474s  |  38.474s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   3.389s  |   3.389s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  42.160s  |  42.160s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   4.665s  |   4.665s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |  15.639s  |  15.639s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |  16.064s  |  16.064s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   1.785s  |   1.785s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.623s  |   0.623s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           | 600.168s  | 600.168s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   9.953s  |   9.953s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |  12.418s  |  12.418s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  | 175.141s  | 175.141s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      | 600.225s  | 600.225s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   7.023s  |   7.023s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           | 178.368s  | 178.368s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   4.365s  |   4.365s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |  16.322s  |  16.322s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   2.682s  |   2.682s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.864s  |   0.864s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   3.625s  |   3.625s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   6.462s  |   6.462s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   9.975s  |   9.975s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  12.634s  |  12.634s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   4.760s  |   4.760s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        | 600.218s  | 600.218s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   2.855s  |   2.855s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   1.329s  |   1.329s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |  21.634s  |  21.634s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   3.566s  |   3.566s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  | 352.437s  | 352.437s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   5.832s  |   5.832s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   6.195s  |   6.195s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   4.069s  |   4.069s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   3.154s  |   3.154s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   2.755s  |   2.755s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  27.422s  |  27.422s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  | 153.551s  | 153.551s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   2.525s  |   2.525s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  18.010s  |  18.010s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  26.202s  |  26.202s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   4.745s  |   4.745s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            | 600.156s  | 600.156s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   7.938s  |   7.938s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |  13.933s  |  13.933s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                | 600.349s  | 600.349s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   5.032s  |   5.032s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   2.724s  |   2.724s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   7.312s  |   7.312s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   2.119s  |   2.119s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   1.635s  |   1.635s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  12.323s  |  12.323s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        | 129.529s  | 129.529s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  10.977s  |  10.977s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                | 600.196s  | 600.196s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |  40.823s  |  40.823s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   5.706s  |   5.706s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  13.431s  |  13.431s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   2.179s  |   2.179s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   5.914s  |   5.914s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       | 231.972s  | 231.972s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   4.152s  |   4.152s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |  52.435s  |  52.435s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |  11.953s  |  11.953s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   5.349s  |   5.349s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       | 117.025s  | 117.025s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       | 600.262s  | 600.262s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       | 600.176s  | 600.176s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   9.708s  |   9.708s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       | 600.213s  | 600.213s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       | 600.206s  | 600.206s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |  11.161s  |  11.161s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   6.323s  |   6.323s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   5.925s  |   5.925s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   1.706s  |   1.706s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   | 600.093s  | 600.093s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   5.010s  |   5.010s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |  10.306s  |  10.306s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   8.103s  |   8.103s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   8.113s  |   8.113s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |  16.369s  |  16.369s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   4.042s  |   4.042s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    | 600.248s  | 600.248s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   7.049s  |   7.049s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  | 600.126s  | 600.126s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  14.064s  |  14.064s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |  97.842s  |  97.842s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   1.655s  |   1.655s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           | 600.311s  | 600.311s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           |  15.740s  |  15.740s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   1.856s  |   1.856s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   4.161s  |   4.161s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   5.546s  |   5.546s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   4.645s  |   4.645s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   5.619s  |   5.619s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           | 600.201s  | 600.201s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   1.966s  |   1.966s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   1.003s  |   1.003s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           |  21.799s  |  21.799s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   1.073s  |   1.073s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.820s  |   0.820s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           | 359.259s  | 359.259s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   2.480s  |   2.480s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   1.400s  |   1.400s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   3.308s  |   3.308s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   2.650s  |   2.650s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   2.130s  |   2.130s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   3.478s  |   3.478s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   2.334s  |   2.334s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   6.109s  |   6.109s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   1.509s  |   1.509s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |   8.896s  |   8.896s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   5.082s  |   5.082s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   2.744s  |   2.744s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           | 571.227s  | 571.227s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   5.202s  |   5.202s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           | 600.038s  | 600.038s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |  75.883s  |  75.883s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   5.578s  |   5.578s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.635s  |   0.635s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   2.080s  |   2.080s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   2.100s  |   2.100s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |  13.981s  |  13.981s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   1.481s  |   1.481s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           |  89.797s  |  89.797s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   9.049s  |   9.049s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.921s  |   0.921s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   2.977s  |   2.977s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   3.306s  |   3.306s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |  50.734s  |  50.734s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   7.032s  |   7.032s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   3.126s  |   3.126s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   2.617s  |   2.617s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   3.699s  |   3.699s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |  15.147s  |  15.147s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |   2.801s  |   2.801s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   1.190s  |   1.190s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   2.377s  |   2.377s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  24.629s  |  24.629s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   3.551s  |   3.551s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |  54.384s  |  54.384s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   2.654s  |   2.654s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            |  61.746s  |  61.746s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   2.772s  |   2.772s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |   5.052s  |   5.052s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   9.021s  |   9.021s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   4.575s  |   4.575s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   2.024s  |   2.024s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  48.381s  |  48.381s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           | 204.691s  | 204.691s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   4.200s  |   4.200s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   6.048s  |   6.048s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  18.057s  |  18.057s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   2.761s  |   2.761s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   2.005s  |   2.005s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   3.431s  |   3.431s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   3.211s  |   3.211s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   4.177s  |   4.177s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |  66.376s  |  66.376s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   2.798s  |   2.798s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   2.700s  |   2.700s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   4.889s  |   4.889s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   1.208s  |   1.208s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |  10.143s  |  10.143s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   3.294s  |   3.294s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   3.196s  |   3.196s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   0.917s  |   0.917s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   7.204s  |   7.204s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           | 600.206s  | 600.206s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   1.117s  |   1.117s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   1.239s  |   1.239s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   6.924s  |   6.924s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           | 600.183s  | 600.183s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   2.404s  |   2.404s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   5.161s  |   5.161s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   3.012s  |   3.012s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |  11.188s  |  11.188s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   4.662s  |   4.662s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |  10.902s  |  10.902s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   4.406s  |   4.406s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  35.272s  |  35.272s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   2.498s  |   2.498s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   1.398s  |   1.398s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   4.721s  |   4.721s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   5.979s  |   5.979s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   2.664s  |   2.664s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |  11.102s  |  11.102s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   4.104s  |   4.104s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |  33.461s  |  33.461s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |  28.196s  |  28.196s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   1.381s  |   1.381s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.770s  |   1.770s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.484s  |   0.484s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   2.021s  |   2.021s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   2.216s  |   2.216s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   1.943s  |   1.943s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   8.310s  |   8.310s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   1.448s  |   1.448s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            | 600.192s  | 600.192s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |  11.021s  |  11.021s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            | 600.189s  | 600.189s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            | 570.650s  | 570.650s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            |  12.253s  |  12.253s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.281s  |   0.281s  |   0.000s  | 0.0%|
</details>
