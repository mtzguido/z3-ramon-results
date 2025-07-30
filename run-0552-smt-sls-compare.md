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
Job description: re-run 2 for Nikolaj
Job tag: smt-sls
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: f77123c13cc8dabe8d1d0217a3312738da834eba
Z3 branch: 
Z3 options: "-T:60 smt.threads=4"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: enable passive, add check for bloom up-to-date

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: re-run 2 for Nikolaj
Job tag: smt-sls
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: f77123c13cc8dabe8d1d0217a3312738da834eba
Z3 branch: 
Z3 options: "-T:60 smt.threads=4"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: enable passive, add check for bloom up-to-date

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  60.175s  |  60.175s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  60.212s  |  60.212s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   3.015s  |   3.015s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.745s  |   1.745s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  60.236s  |  60.236s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.302s  |   0.302s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  60.175s  |  60.175s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  60.212s  |  60.212s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   3.015s  |   3.015s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.745s  |   1.745s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  60.236s  |  60.236s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.302s  |   0.302s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  60.175s  |  60.175s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  60.212s  |  60.212s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   3.015s  |   3.015s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.745s  |   1.745s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  60.236s  |  60.236s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.302s  |   0.302s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  60.175s  |  60.175s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  60.212s  |  60.212s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   3.015s  |   3.015s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.745s  |   1.745s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  60.236s  |  60.236s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.302s  |   0.302s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|185.smt2                                                                                   |  61.169s |3037.0MiB|
|182.smt2                                                                                   |  60.990s |1729.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  60.906s |5619.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  60.884s |2067.0MiB|
|183.smt2                                                                                   |  60.863s |1667.0MiB|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                     |  60.700s |481.0MiB|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                       |  60.663s |236.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  60.662s |1384.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2               |  60.621s |443.0MiB|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                |  60.595s |217.0MiB|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                             |  60.580s |186.0MiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2              |  60.577s |201.0MiB|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                |  60.575s |576.0MiB|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                             |  60.562s |301.0MiB|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                          |  60.560s |208.0MiB|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                          |  60.555s |427.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  60.543s |974.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  60.542s |999.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2         |  60.541s |1061.0MiB|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                      |  60.541s |263.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|185.smt2                                                                                   |  61.169s |3037.0MiB|
|182.smt2                                                                                   |  60.990s |1729.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  60.906s |5619.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  60.884s |2067.0MiB|
|183.smt2                                                                                   |  60.863s |1667.0MiB|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                     |  60.700s |481.0MiB|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                       |  60.663s |236.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  60.662s |1384.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2               |  60.621s |443.0MiB|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                |  60.595s |217.0MiB|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                             |  60.580s |186.0MiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2              |  60.577s |201.0MiB|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                |  60.575s |576.0MiB|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                             |  60.562s |301.0MiB|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                          |  60.560s |208.0MiB|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                          |  60.555s |427.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  60.543s |974.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  60.542s |999.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2         |  60.541s |1061.0MiB|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                      |  60.541s |263.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |188.0MiB|188.0MiB|0B| 0.0%|
|04.smt2                                                                                     |163.0MiB|163.0MiB|0B| 0.0%|
|1.smt2                                                                                      |199.0MiB|199.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.712MiB|31.712MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.596MiB|30.596MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.604MiB|23.604MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.064MiB|24.064MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.272MiB|24.272MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.92MiB|24.92MiB|0B| 0.0%|
|107.smt2                                                                                    |22.332MiB|22.332MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.432MiB|27.432MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.304MiB|80.304MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.744MiB|22.744MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.056MiB|23.056MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.708MiB|23.708MiB|0B| 0.0%|
|11.smt2                                                                                     |156.0MiB|156.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.076MiB|24.076MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.372MiB|23.372MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.772MiB|24.772MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.356MiB|25.356MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |188.0MiB|188.0MiB|0B| 0.0%|
|04.smt2                                                                                     |163.0MiB|163.0MiB|0B| 0.0%|
|1.smt2                                                                                      |199.0MiB|199.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.712MiB|31.712MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.596MiB|30.596MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.604MiB|23.604MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.064MiB|24.064MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.272MiB|24.272MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.92MiB|24.92MiB|0B| 0.0%|
|107.smt2                                                                                    |22.332MiB|22.332MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.432MiB|27.432MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.304MiB|80.304MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.744MiB|22.744MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.056MiB|23.056MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.708MiB|23.708MiB|0B| 0.0%|
|11.smt2                                                                                     |156.0MiB|156.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.076MiB|24.076MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.372MiB|23.372MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.772MiB|24.772MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.356MiB|25.356MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |188.0MiB|188.0MiB|0B| 0.0%|
|04.smt2                                                                                     |163.0MiB|163.0MiB|0B| 0.0%|
|1.smt2                                                                                      |199.0MiB|199.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.712MiB|31.712MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.596MiB|30.596MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.604MiB|23.604MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.064MiB|24.064MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.272MiB|24.272MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.92MiB|24.92MiB|0B| 0.0%|
|107.smt2                                                                                    |22.332MiB|22.332MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.432MiB|27.432MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.304MiB|80.304MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.744MiB|22.744MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.056MiB|23.056MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.708MiB|23.708MiB|0B| 0.0%|
|11.smt2                                                                                     |156.0MiB|156.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.076MiB|24.076MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.372MiB|23.372MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.772MiB|24.772MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.356MiB|25.356MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |188.0MiB|188.0MiB|0B| 0.0%|
|04.smt2                                                                                     |163.0MiB|163.0MiB|0B| 0.0%|
|1.smt2                                                                                      |199.0MiB|199.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.712MiB|31.712MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.596MiB|30.596MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.604MiB|23.604MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.064MiB|24.064MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.272MiB|24.272MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.92MiB|24.92MiB|0B| 0.0%|
|107.smt2                                                                                    |22.332MiB|22.332MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.432MiB|27.432MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.304MiB|80.304MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.744MiB|22.744MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.056MiB|23.056MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.708MiB|23.708MiB|0B| 0.0%|
|11.smt2                                                                                     |156.0MiB|156.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.076MiB|24.076MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.372MiB|23.372MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.772MiB|24.772MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.356MiB|25.356MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  60.906s |5619.0MiB|
|185.smt2                                                                                   |  61.169s |3037.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  60.884s |2067.0MiB|
|182.smt2                                                                                   |  60.990s |1729.0MiB|
|183.smt2                                                                                   |  60.863s |1667.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  60.662s |1384.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   |  60.303s |1262.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  60.221s |1232.0MiB|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                |  60.523s |1219.0MiB|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                 |  60.327s |1148.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2         |  60.459s |1144.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  60.452s |1134.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          |  60.249s |1097.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  60.396s |1077.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2         |  60.541s |1061.0MiB|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                           |  60.357s |1053.0MiB|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                          |  60.280s |1018.0MiB|
|181.smt2                                                                                   |  60.417s |1017.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  60.466s |1016.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  60.542s |999.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  60.906s |5619.0MiB|
|185.smt2                                                                                   |  61.169s |3037.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  60.884s |2067.0MiB|
|182.smt2                                                                                   |  60.990s |1729.0MiB|
|183.smt2                                                                                   |  60.863s |1667.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  60.662s |1384.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   |  60.303s |1262.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  60.221s |1232.0MiB|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                |  60.523s |1219.0MiB|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                 |  60.327s |1148.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2         |  60.459s |1144.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  60.452s |1134.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          |  60.249s |1097.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  60.396s |1077.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2         |  60.541s |1061.0MiB|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                           |  60.357s |1053.0MiB|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                          |  60.280s |1018.0MiB|
|181.smt2                                                                                   |  60.417s |1017.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  60.466s |1016.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  60.542s |999.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  60.175s  |  60.175s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  60.212s  |  60.212s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   3.015s  |   3.015s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.745s  |   1.745s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  60.236s  |  60.236s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.628s  |   0.628s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.632s  |   0.632s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |  60.270s  |  60.270s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |  13.439s  |  13.439s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   2.199s  |   2.199s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.731s  |   0.731s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |  60.266s  |  60.266s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.617s  |   0.617s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   2.794s  |   2.794s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   2.361s  |   2.361s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   1.118s  |   1.118s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   1.908s  |   1.908s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.575s  |   0.575s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   2.258s  |   2.258s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   5.518s  |   5.518s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   3.227s  |   3.227s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   2.462s  |   2.462s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |  60.220s  |  60.220s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   1.281s  |   1.281s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   2.353s  |   2.353s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  60.417s  |  60.417s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  60.990s  |  60.990s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  60.863s  |  60.863s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  61.169s  |  61.169s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.839s  |   0.839s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   1.672s  |   1.672s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   1.403s  |   1.403s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   1.681s  |   1.681s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   3.049s  |   3.049s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   5.643s  |   5.643s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   6.959s  |   6.959s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   9.239s  |   9.239s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   4.452s  |   4.452s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   3.219s  |   3.219s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   1.823s  |   1.823s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   1.461s  |   1.461s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   2.211s  |   2.211s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |  60.151s  |  60.151s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |  60.211s  |  60.211s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   1.663s  |   1.663s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |  60.304s  |  60.304s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   7.924s  |   7.924s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   3.897s  |   3.897s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   2.389s  |   2.389s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |  60.245s  |  60.245s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   2.069s  |   2.069s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   5.781s  |   5.781s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   4.273s  |   4.273s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |  60.341s  |  60.341s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   2.175s  |   2.175s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   5.887s  |   5.887s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |  60.313s  |  60.313s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.613s  |   0.613s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   1.170s  |   1.170s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   3.941s  |   3.941s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   1.916s  |   1.916s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   4.487s  |   4.487s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|966.smt2                                                                                    |   7.630s  |   7.630s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  60.166s  |  60.166s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|99.smt2                                                                                     |  60.095s  |  60.095s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |  60.257s  |  60.257s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   2.989s  |   2.989s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          |  60.248s  |  60.248s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |  51.338s  |  51.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   3.347s  |   3.347s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   1.778s  |   1.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |  60.202s  |  60.202s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          |  60.176s  |  60.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |  16.508s  |  16.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   8.985s  |   8.985s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            |  60.176s  |  60.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   5.730s  |   5.730s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   3.755s  |   3.755s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       |  60.228s  |  60.228s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   2.895s  |   2.895s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  60.221s  |  60.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   7.540s  |   7.540s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |  60.400s  |  60.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   1.922s  |   1.922s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   1.864s  |   1.864s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           |  60.129s  |  60.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           |  60.245s  |  60.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |  60.354s  |  60.354s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   6.417s  |   6.417s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  51.009s  |  51.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   5.708s  |   5.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |  12.032s  |  12.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         |  60.225s  |  60.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             |  60.476s  |  60.476s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |  41.998s  |  41.998s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  60.220s  |  60.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             |  60.163s  |  60.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   1.321s  |   1.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 |  51.494s  |  51.494s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   3.032s  |   3.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   4.872s  |   4.872s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   8.170s  |   8.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   2.422s  |   2.422s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              |   6.607s  |   6.607s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |  11.965s  |  11.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   3.184s  |   3.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |  14.763s  |  14.763s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               |  19.931s  |  19.931s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         |  60.244s  |  60.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   8.403s  |   8.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |   3.973s  |   3.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |  60.282s  |  60.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 |  60.298s  |  60.298s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      |  60.269s  |  60.269s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   4.624s  |   4.624s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   7.685s  |   7.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              |  60.262s  |  60.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   4.215s  |   4.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   6.332s  |   6.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          |  60.251s  |  60.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   1.956s  |   1.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          |  60.198s  |  60.198s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |  22.258s  |  22.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         |  60.210s  |  60.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   3.379s  |   3.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      |  60.408s  |  60.408s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |  26.854s  |  26.854s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   5.783s  |   5.783s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   6.855s  |   6.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         |  60.173s  |  60.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      |  60.363s  |  60.363s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               |  60.281s  |  60.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  60.193s  |  60.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |  60.301s  |  60.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   6.421s  |   6.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           |  60.296s  |  60.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               |  60.177s  |  60.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   2.700s  |   2.700s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               |  60.191s  |  60.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |  14.712s  |  14.712s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   4.992s  |   4.992s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |   9.739s  |   9.739s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |  57.020s  |  57.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |  15.513s  |  15.513s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   |  60.315s  |  60.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   |  60.111s  |  60.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   |  60.337s  |  60.337s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             |  60.302s  |  60.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  14.209s  |  14.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   4.320s  |   4.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    |  60.157s  |  60.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |  39.648s  |  39.648s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        |  60.237s  |  60.237s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  60.356s  |  60.356s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  60.266s  |  60.266s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     |  60.200s  |  60.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               |  60.211s  |  60.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               |  60.249s  |  60.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   7.287s  |   7.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   5.287s  |   5.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   4.536s  |   4.536s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |  60.196s  |  60.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               |  60.246s  |  60.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   1.644s  |   1.644s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |  11.846s  |  11.846s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |  11.638s  |  11.638s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   5.387s  |   5.387s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   2.860s  |   2.860s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   7.731s  |   7.731s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                |  60.201s  |  60.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   2.438s  |   2.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              |  60.562s  |  60.562s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |  60.302s  |  60.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   3.964s  |   3.964s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |  12.221s  |  12.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  60.336s  |  60.336s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  60.580s  |  60.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   5.245s  |   5.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  60.222s  |  60.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          |  60.222s  |  60.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          |  60.162s  |  60.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          |  60.191s  |  60.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |  51.096s  |  51.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          |  60.474s  |  60.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          |  60.291s  |  60.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  60.317s  |  60.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |  11.304s  |  11.304s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  29.449s  |  29.449s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   4.624s  |   4.624s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    |  60.369s  |  60.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   4.198s  |   4.198s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   4.401s  |   4.401s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    |  60.184s  |  60.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   5.776s  |   5.776s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   4.828s  |   4.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |  27.060s  |  27.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |  25.166s  |  25.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        |  60.335s  |  60.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |  60.663s  |  60.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |   4.367s  |   4.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   6.767s  |   6.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        |  60.198s  |  60.198s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   2.036s  |   2.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  60.206s  |  60.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  60.355s  |  60.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  60.290s  |  60.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  57.948s  |  57.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  60.210s  |  60.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              |  60.282s  |  60.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  60.254s  |  60.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  |  60.378s  |  60.378s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  |  60.201s  |  60.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |   6.929s  |   6.929s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |  60.250s  |  60.250s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   3.883s  |   3.883s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   1.438s  |   1.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              |  60.216s  |  60.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   3.567s  |   3.567s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |  60.150s  |  60.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |  15.794s  |  15.794s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   5.580s  |   5.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  60.191s  |  60.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        |  60.451s  |  60.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.614s  |   0.614s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   4.617s  |   4.617s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |  60.159s  |  60.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |  17.590s  |  17.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.872s  |   0.872s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   |  60.210s  |  60.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   |  60.225s  |  60.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     |  60.191s  |  60.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   5.724s  |   5.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   5.048s  |   5.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   3.778s  |   3.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     |  60.364s  |  60.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 |  60.124s  |  60.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                |  60.306s  |  60.306s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   3.976s  |   3.976s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                |  60.379s  |  60.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      |  60.379s  |  60.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |  27.501s  |  27.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      |  60.343s  |  60.343s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      |  60.250s  |  60.250s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   8.015s  |   8.015s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      |  60.170s  |  60.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |  16.314s  |  16.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   2.920s  |   2.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |  13.057s  |  13.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   7.020s  |   7.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   6.464s  |   6.464s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |  14.199s  |  14.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   9.552s  |   9.552s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |  60.349s  |  60.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  56.039s  |  56.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |  60.215s  |  60.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   8.099s  |   8.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          |  60.239s  |  60.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               |  60.210s  |  60.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                |  60.239s  |  60.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |  18.958s  |  18.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |  13.585s  |  13.585s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   3.404s  |   3.404s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   4.281s  |   4.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   3.608s  |   3.608s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |  10.224s  |  10.224s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   2.952s  |   2.952s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              |  60.285s  |  60.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   7.633s  |   7.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   5.790s  |   5.790s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |  11.657s  |  11.657s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   4.637s  |   4.637s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  60.208s  |  60.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          |  60.277s  |  60.277s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |  20.826s  |  20.826s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          |  60.245s  |  60.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          |  60.297s  |  60.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |  24.871s  |  24.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          |  60.387s  |  60.387s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          |  60.182s  |  60.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |  51.448s  |  51.448s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          |  60.226s  |  60.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   7.729s  |   7.729s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            |  60.329s  |  60.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   5.380s  |   5.380s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |  60.401s  |  60.401s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |  33.421s  |  33.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            |  60.216s  |  60.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   1.859s  |   1.859s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |  14.305s  |  14.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |   8.291s  |   8.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   1.037s  |   1.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   9.263s  |   9.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   1.508s  |   1.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |  27.522s  |  27.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |  14.161s  |  14.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   4.400s  |   4.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   1.856s  |   1.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |  10.446s  |  10.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           |  60.234s  |  60.234s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           |  60.176s  |  60.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |   9.052s  |   9.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   3.159s  |   3.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   7.007s  |   7.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           |  60.307s  |  60.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   2.753s  |   2.753s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   2.568s  |   2.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   6.675s  |   6.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |  16.698s  |  16.698s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |  16.293s  |  16.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           |  60.137s  |  60.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   2.573s  |   2.573s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   1.810s  |   1.810s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |  10.496s  |  10.496s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  33.962s  |  33.962s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |  17.094s  |  17.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |  24.262s  |  24.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |  16.303s  |  16.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           |   1.196s  |   1.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |  16.646s  |  16.646s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   2.792s  |   2.792s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |  51.041s  |  51.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   2.482s  |   2.482s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  51.812s  |  51.812s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   2.894s  |   2.894s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   6.872s  |   6.872s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   4.622s  |   4.622s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   9.247s  |   9.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |  32.079s  |  32.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   2.398s  |   2.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |  57.003s  |  57.003s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   2.462s  |   2.462s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           |  60.159s  |  60.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  60.202s  |  60.202s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           |  60.204s  |  60.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   2.647s  |   2.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           |  60.204s  |  60.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     |  60.318s  |  60.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   2.374s  |   2.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   2.595s  |   2.595s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |  10.941s  |  10.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   3.350s  |   3.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |  12.186s  |  12.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |  29.572s  |  29.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   2.338s  |   2.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   6.850s  |   6.850s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     |  60.240s  |  60.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |  20.429s  |  20.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   1.155s  |   1.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |  42.861s  |  42.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |  29.318s  |  29.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |  17.488s  |  17.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   2.775s  |   2.775s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |  14.218s  |  14.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   3.482s  |   3.482s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   3.858s  |   3.858s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   2.726s  |   2.726s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   3.453s  |   3.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   4.131s  |   4.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   1.537s  |   1.537s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     |  60.176s  |  60.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |  60.236s  |  60.236s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |  12.653s  |  12.653s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   1.327s  |   1.327s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |  39.290s  |  39.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |  10.430s  |  10.430s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               |  60.135s  |  60.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |   8.944s  |   8.944s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   5.501s  |   5.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     |  60.278s  |  60.278s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |   8.634s  |   8.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |   5.279s  |   5.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   2.593s  |   2.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |  20.217s  |  20.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |   6.555s  |   6.555s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   2.826s  |   2.826s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   5.190s  |   5.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |  58.587s  |  58.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |  14.309s  |  14.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |  17.124s  |  17.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     |  26.488s  |  26.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     |  60.176s  |  60.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  60.188s  |  60.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   1.847s  |   1.847s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               |  60.236s  |  60.236s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |  10.197s  |  10.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   2.595s  |   2.595s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |   7.430s  |   7.430s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               |  60.260s  |  60.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |  60.329s  |  60.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |  11.677s  |  11.677s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |  12.263s  |  12.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               |  60.188s  |  60.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |  19.128s  |  19.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |  60.173s  |  60.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               |  60.247s  |  60.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               |  60.311s  |  60.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               |  60.140s  |  60.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               |  60.269s  |  60.269s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |  60.171s  |  60.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   3.154s  |   3.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   2.499s  |   2.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  60.292s  |  60.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               |  24.018s  |  24.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   2.180s  |   2.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               |  60.462s  |  60.462s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   7.952s  |   7.952s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   3.346s  |   3.346s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |  24.743s  |  24.743s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               |  60.289s  |  60.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |  39.743s  |  39.743s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   2.677s  |   2.677s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   3.480s  |   3.480s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   1.078s  |   1.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   2.615s  |   2.615s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   5.696s  |   5.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               |  60.253s  |  60.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   6.535s  |   6.535s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   2.600s  |   2.600s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   3.794s  |   3.794s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               |  60.320s  |  60.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   2.119s  |   2.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               |  60.233s  |  60.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               |  60.577s  |  60.577s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |  60.169s  |  60.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |   7.070s  |   7.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |  20.150s  |  20.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |  23.410s  |  23.410s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   5.720s  |   5.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |  23.081s  |  23.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |  60.245s  |  60.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   3.343s  |   3.343s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |  20.776s  |  20.776s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   0.830s  |   0.830s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             |  60.249s  |  60.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |   6.210s  |   6.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   2.662s  |   2.662s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   5.623s  |   5.623s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |  17.467s  |  17.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   2.627s  |   2.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   3.039s  |   3.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |  12.949s  |  12.949s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   8.451s  |   8.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |  13.186s  |  13.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   3.348s  |   3.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             |  60.181s  |  60.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |  60.185s  |  60.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |  17.299s  |  17.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   5.592s  |   5.592s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   1.555s  |   1.555s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   1.618s  |   1.618s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             |  60.118s  |  60.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   2.643s  |   2.643s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             |  60.236s  |  60.236s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |  12.056s  |  12.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |   2.885s  |   2.885s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |  26.035s  |  26.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |  15.860s  |  15.860s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   1.473s  |   1.473s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |  22.505s  |  22.505s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |  16.489s  |  16.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             |  60.283s  |  60.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   5.971s  |   5.971s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   2.626s  |   2.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             |  60.293s  |  60.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |  20.461s  |  20.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             |  60.273s  |  60.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |  37.320s  |  37.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             |  60.287s  |  60.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   1.425s  |   1.425s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             |  60.222s  |  60.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |  18.411s  |  18.411s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |  12.116s  |  12.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               |  60.095s  |  60.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |  16.914s  |  16.914s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |  17.851s  |  17.851s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         |  60.312s  |  60.312s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   7.488s  |   7.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              |  44.877s  |  44.877s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   4.693s  |   4.693s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   2.647s  |   2.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |  12.415s  |  12.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |  15.797s  |  15.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    |  60.166s  |  60.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |   7.838s  |   7.838s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |  27.206s  |  27.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   2.454s  |   2.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   4.029s  |   4.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |  15.652s  |  15.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |  60.290s  |  60.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    |  60.214s  |  60.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   2.392s  |   2.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    |  60.128s  |  60.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   5.802s  |   5.802s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   2.419s  |   2.419s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   2.221s  |   2.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    |  60.214s  |  60.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    |  60.297s  |  60.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    |  60.238s  |  60.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   2.703s  |   2.703s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   3.160s  |   3.160s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |  60.238s  |  60.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |  14.523s  |  14.523s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    |  60.165s  |  60.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |  22.176s  |  22.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    |  60.102s  |  60.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   2.763s  |   2.763s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  60.214s  |  60.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  15.945s  |  15.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |  12.196s  |  12.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   3.037s  |   3.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    |  60.157s  |  60.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |  59.369s  |  59.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |  22.061s  |  22.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   2.549s  |   2.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    |  60.201s  |  60.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   4.258s  |   4.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    |  60.268s  |  60.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |   8.720s  |   8.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   8.384s  |   8.384s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   2.710s  |   2.710s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |  11.878s  |  11.878s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |  11.622s  |  11.622s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   2.721s  |   2.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   2.515s  |   2.515s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |  25.557s  |  25.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   2.543s  |   2.543s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          |  60.139s  |  60.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   3.258s  |   3.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          |  60.159s  |  60.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |  21.093s  |  21.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  17.159s  |  17.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |  11.443s  |  11.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          |  60.235s  |  60.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |  22.004s  |  22.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          |  60.368s  |  60.368s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   1.837s  |   1.837s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          |  60.127s  |  60.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |  22.026s  |  22.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |  16.106s  |  16.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   2.733s  |   2.733s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   2.488s  |   2.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          |  60.219s  |  60.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          |  60.196s  |  60.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   1.618s  |   1.618s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   2.950s  |   2.950s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          |  60.339s  |  60.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   6.494s  |   6.494s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   2.950s  |   2.950s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |  10.557s  |  10.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        |  60.335s  |  60.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |  17.427s  |  17.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        |  60.259s  |  60.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   1.968s  |   1.968s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |  24.171s  |  24.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |  20.410s  |  20.410s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |  15.113s  |  15.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |   7.365s  |   7.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |  11.795s  |  11.795s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |  46.439s  |  46.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   1.859s  |   1.859s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |  17.362s  |  17.362s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   2.475s  |   2.475s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |   9.596s  |   9.596s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   7.188s  |   7.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |  12.668s  |  12.668s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |   4.604s  |   4.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   3.213s  |   3.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   8.645s  |   8.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |   4.512s  |   4.512s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |  20.823s  |  20.823s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   0.925s  |   0.925s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   2.784s  |   2.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        |  60.178s  |  60.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   2.566s  |   2.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |  13.039s  |  13.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |  24.882s  |  24.882s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |  21.448s  |  21.448s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   2.576s  |   2.576s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |  14.593s  |  14.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   2.730s  |   2.730s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        |  60.267s  |  60.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |  60.306s  |  60.306s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        |  60.439s  |  60.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |  15.683s  |  15.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   2.936s  |   2.936s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |  46.550s  |  46.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |  60.425s  |  60.425s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |  40.368s  |  40.368s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |  21.080s  |  21.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        |  60.463s  |  60.463s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   7.443s  |   7.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  |  60.263s  |  60.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   6.128s  |   6.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   2.501s  |   2.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |  27.113s  |  27.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   2.104s  |   2.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |  22.047s  |  22.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |  20.893s  |  20.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   8.856s  |   8.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   2.175s  |   2.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   2.484s  |   2.484s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     |   7.779s  |   7.779s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  39.644s  |  39.644s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   0.765s  |   0.765s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   2.566s  |   2.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   4.161s  |   4.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     |  60.222s  |  60.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     |  60.200s  |  60.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     |  60.326s  |  60.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   3.871s  |   3.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |  46.131s  |  46.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   6.903s  |   6.903s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       |  60.155s  |  60.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |  14.000s  |  14.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |  60.334s  |  60.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   3.328s  |   3.328s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |  36.643s  |  36.643s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |  10.798s  |  10.798s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       |  60.218s  |  60.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   5.250s  |   5.250s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |  41.833s  |  41.833s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       |  60.368s  |  60.368s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   3.033s  |   3.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   3.943s  |   3.943s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   3.074s  |   3.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       |  60.153s  |  60.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   0.746s  |   0.746s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       |  60.265s  |  60.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |  15.614s  |  15.614s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   2.755s  |   2.755s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   1.785s  |   1.785s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   3.303s  |   3.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |  11.460s  |  11.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       |  60.206s  |  60.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       |  60.255s  |  60.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |  38.757s  |  38.757s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 |  60.336s  |  60.336s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  60.289s  |  60.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |  21.845s  |  21.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  60.341s  |  60.341s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   9.443s  |   9.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |  60.435s  |  60.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  24.171s  |  24.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   1.980s  |   1.980s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  47.680s  |  47.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  60.343s  |  60.343s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |  13.153s  |  13.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |  39.114s  |  39.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  60.190s  |  60.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |  10.251s  |  10.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |  60.238s  |  60.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            |  60.361s  |  60.361s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   5.300s  |   5.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   5.116s  |   5.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   4.932s  |   4.932s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   6.791s  |   6.791s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   2.448s  |   2.448s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   3.635s  |   3.635s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |  15.068s  |  15.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |  60.373s  |  60.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |  18.380s  |  18.380s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   6.735s  |   6.735s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   7.265s  |   7.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   4.001s  |   4.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |  25.584s  |  25.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   3.228s  |   3.228s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   5.783s  |   5.783s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   7.159s  |   7.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |  18.218s  |  18.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |  15.380s  |  15.380s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |  31.486s  |  31.486s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |  60.177s  |  60.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |  14.495s  |  14.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |  13.829s  |  13.829s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   3.568s  |   3.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   4.353s  |   4.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   6.358s  |   6.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  60.211s  |  60.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |  22.384s  |  22.384s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  60.505s  |  60.505s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |  23.913s  |  23.913s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |  13.566s  |  13.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |  11.321s  |  11.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  60.214s  |  60.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   4.666s  |   4.666s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   6.628s  |   6.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   3.064s  |   3.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |  60.388s  |  60.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   4.604s  |   4.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |  10.604s  |  10.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   9.831s  |   9.831s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   6.865s  |   6.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |  26.275s  |  26.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |  10.658s  |  10.658s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   2.651s  |   2.651s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   2.599s  |   2.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |  12.826s  |  12.826s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |  15.498s  |  15.498s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |  14.019s  |  14.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   6.163s  |   6.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   4.217s  |   4.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   3.967s  |   3.967s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   3.811s  |   3.811s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |  22.013s  |  22.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |  10.822s  |  10.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  60.389s  |  60.389s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |  23.745s  |  23.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |  18.450s  |  18.450s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  60.295s  |  60.295s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   1.677s  |   1.677s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |  60.363s  |  60.363s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |  14.122s  |  14.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |  16.016s  |  16.016s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |  12.270s  |  12.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  58.432s  |  58.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |  42.201s  |  42.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   6.726s  |   6.726s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   7.594s  |   7.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  60.286s  |  60.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   5.525s  |   5.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   1.896s  |   1.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   5.150s  |   5.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |  11.090s  |  11.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |  41.396s  |  41.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |  14.365s  |  14.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |  11.011s  |  11.011s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   5.684s  |   5.684s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  12.140s  |  12.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  15.503s  |  15.503s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |  18.166s  |  18.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   3.965s  |   3.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |  10.358s  |  10.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   9.633s  |   9.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |  10.151s  |  10.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   1.948s  |   1.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                |  60.252s  |  60.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |  31.927s  |  31.927s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  60.621s  |  60.621s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   3.979s  |   3.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |  60.307s  |  60.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  60.300s  |  60.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   5.104s  |   5.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |  11.673s  |  11.673s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |  19.838s  |  19.838s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |  37.308s  |  37.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   6.645s  |   6.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   8.868s  |   8.868s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  60.247s  |  60.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   3.665s  |   3.665s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |  43.020s  |  43.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   2.762s  |   2.762s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |  11.137s  |  11.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   3.627s  |   3.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |  10.641s  |  10.641s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |  47.710s  |  47.710s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   4.028s  |   4.028s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |  15.403s  |  15.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |  10.811s  |  10.811s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   6.587s  |   6.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   8.937s  |   8.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |  16.446s  |  16.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   8.208s  |   8.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |  11.200s  |  11.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |  14.470s  |  14.470s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |  10.746s  |  10.746s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |  10.281s  |  10.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |  14.068s  |  14.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |  12.855s  |  12.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   6.532s  |   6.532s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |  10.390s  |  10.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   9.286s  |   9.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          |  60.541s  |  60.541s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          |  60.364s  |  60.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          |  60.459s  |  60.459s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   7.140s  |   7.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |  13.270s  |  13.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             |  60.452s  |  60.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            |  60.304s  |  60.304s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            |  60.310s  |  60.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   6.287s  |   6.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   5.515s  |   5.515s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   2.853s  |   2.853s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   5.253s  |   5.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |  45.608s  |  45.608s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   4.895s  |   4.895s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |  60.499s  |  60.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   4.415s  |   4.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      |  60.207s  |  60.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   9.677s  |   9.677s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   6.687s  |   6.687s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   4.910s  |   4.910s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   5.392s  |   5.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       |  60.260s  |  60.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |  14.123s  |  14.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   2.937s  |   2.937s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   0.860s  |   0.860s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   5.098s  |   5.098s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   |  60.359s  |  60.359s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |  33.168s  |  33.168s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |  17.993s  |  17.993s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |  21.312s  |  21.312s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   1.555s  |   1.555s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |  45.160s  |  45.160s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |  38.952s  |  38.952s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |  17.030s  |  17.030s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   4.833s  |   4.833s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          |  60.218s  |  60.218s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          |  60.311s  |  60.311s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   4.181s  |   4.181s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   2.912s  |   2.912s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               |  60.256s  |  60.256s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               |  60.255s  |  60.255s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  60.243s  |  60.243s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               |  60.198s  |  60.198s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               |  60.265s  |  60.265s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |  13.280s  |  13.280s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         |  60.151s  |  60.151s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         |  60.310s  |  60.310s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         |  60.276s  |  60.276s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |  60.249s  |  60.249s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               |  60.497s  |  60.497s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  60.158s  |  60.158s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |  15.449s  |  15.449s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |   6.929s  |   6.929s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         |  60.234s  |  60.234s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |  60.266s  |  60.266s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   2.137s  |   2.137s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         |  60.403s  |  60.403s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  55.446s  |  55.446s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  56.213s  |  56.213s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    |  60.303s  |  60.303s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  60.154s  |  60.154s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    |  60.401s  |  60.401s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  31.640s  |  31.640s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  37.172s  |  37.172s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |  13.451s  |  13.451s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              |  60.221s  |  60.221s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  60.307s  |  60.307s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   7.260s  |   7.260s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   6.235s  |   6.235s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  10.276s  |  10.276s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   1.182s  |   1.182s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |  15.802s  |  15.802s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |  19.406s  |  19.406s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   7.369s  |   7.369s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   3.963s  |   3.963s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |   5.255s  |   5.255s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   8.454s  |   8.454s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.670s  |   0.670s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  |  60.261s  |  60.261s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |  12.771s  |  12.771s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  19.250s  |  19.250s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |  60.351s  |  60.351s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 |  60.523s  |  60.523s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  39.422s  |  39.422s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           |  60.462s  |  60.462s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |  21.481s  |  21.481s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |  24.428s  |  24.428s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              |  60.167s  |  60.167s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              |  60.237s  |  60.237s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              |  60.350s  |  60.350s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  60.269s  |  60.269s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              |  60.409s  |  60.409s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              |  60.120s  |  60.120s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |  60.115s  |  60.115s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              |  60.303s  |  60.303s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              |  60.212s  |  60.212s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   3.311s  |   3.311s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |  60.307s  |  60.307s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  60.237s  |  60.237s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |  27.964s  |  27.964s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |  60.700s  |  60.700s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  60.163s  |  60.163s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  60.367s  |  60.367s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  60.387s  |  60.387s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  60.276s  |  60.276s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            |  60.254s  |  60.254s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   4.238s  |   4.238s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             |  60.153s  |  60.153s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   3.621s  |   3.621s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             |  60.270s  |  60.270s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             |  60.357s  |  60.357s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |  10.587s  |  10.587s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             |  60.206s  |  60.206s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             |  60.223s  |  60.223s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |  11.625s  |  11.625s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 |  60.296s  |  60.296s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   1.788s  |   1.788s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  |  60.248s  |  60.248s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |  60.232s  |  60.232s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   4.408s  |   4.408s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             |  60.214s  |  60.214s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   3.107s  |   3.107s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   8.886s  |   8.886s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |  27.056s  |  27.056s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   3.234s  |   3.234s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |  31.035s  |  31.035s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   4.811s  |   4.811s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             |  60.203s  |  60.203s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   3.103s  |   3.103s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   6.332s  |   6.332s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   4.054s  |   4.054s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   3.209s  |   3.209s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   1.839s  |   1.839s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |  16.949s  |  16.949s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   3.523s  |   3.523s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   5.029s  |   5.029s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               |  60.884s  |  60.884s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   2.896s  |   2.896s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            |  60.365s  |  60.365s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   3.866s  |   3.866s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 |  60.542s  |  60.542s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |  42.825s  |  42.825s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  60.317s  |  60.317s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |  24.930s  |  24.930s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           |  60.310s  |  60.310s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |  31.394s  |  31.394s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |  27.537s  |  27.537s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 |  60.338s  |  60.338s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      |  60.337s  |  60.337s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |  28.505s  |  28.505s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |  26.462s  |  26.462s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           |  60.280s  |  60.280s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  60.266s  |  60.266s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |  24.201s  |  24.201s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  43.020s  |  43.020s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              |  60.197s  |  60.197s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |   5.585s  |   5.585s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   4.674s  |   4.674s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   3.678s  |   3.678s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      |  60.204s  |  60.204s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               |  60.212s  |  60.212s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              |  60.317s  |  60.317s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |  13.007s  |  13.007s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       |  60.270s  |  60.270s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |  10.006s  |  10.006s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   3.567s  |   3.567s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       |  60.258s  |  60.258s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   2.942s  |   2.942s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   1.406s  |   1.406s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       |  60.185s  |  60.185s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |  60.234s  |  60.234s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.958s  |   0.958s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       |  60.342s  |  60.342s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   1.360s  |   1.360s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   3.660s  |   3.660s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |  18.240s  |  18.240s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |  13.361s  |  13.361s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   1.249s  |   1.249s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       |  60.191s  |  60.191s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   1.404s  |   1.404s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |  15.160s  |  15.160s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       |  60.191s  |  60.191s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |  10.283s  |  10.283s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   4.302s  |   4.302s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       |  11.084s  |  11.084s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |  16.611s  |  16.611s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   1.949s  |   1.949s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   4.663s  |   4.663s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       |  60.162s  |  60.162s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       |  60.329s  |  60.329s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |  11.222s  |  11.222s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   1.836s  |   1.836s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       |  60.231s  |  60.231s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   8.856s  |   8.856s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   2.306s  |   2.306s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   1.186s  |   1.186s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               |  60.150s  |  60.150s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         |  60.271s  |  60.271s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |  18.249s  |  18.249s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   1.871s  |   1.871s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |  14.550s  |  14.550s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |  10.476s  |  10.476s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 |  60.265s  |  60.265s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   2.798s  |   2.798s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |  20.855s  |  20.855s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |  21.032s  |  21.032s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |  20.746s  |  20.746s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |  21.742s  |  21.742s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   4.825s  |   4.825s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                |  60.115s  |  60.115s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   2.571s  |   2.571s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   6.042s  |   6.042s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                |  60.171s  |  60.171s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   2.669s  |   2.669s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   8.857s  |   8.857s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   3.006s  |   3.006s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      |  60.164s  |  60.164s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   2.690s  |   2.690s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   2.574s  |   2.574s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |   4.436s  |   4.436s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   7.928s  |   7.928s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   3.876s  |   3.876s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   1.904s  |   1.904s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   1.627s  |   1.627s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   1.420s  |   1.420s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   1.917s  |   1.917s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   3.933s  |   3.933s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   2.488s  |   2.488s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   3.633s  |   3.633s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   2.700s  |   2.700s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |  19.512s  |  19.512s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   4.604s  |   4.604s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      |  60.131s  |  60.131s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   3.086s  |   3.086s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      |  60.179s  |  60.179s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   2.583s  |   2.583s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   8.961s  |   8.961s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   9.674s  |   9.674s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   1.339s  |   1.339s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   2.585s  |   2.585s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   3.838s  |   3.838s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   2.551s  |   2.551s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   3.455s  |   3.455s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   4.745s  |   4.745s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   1.941s  |   1.941s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |  28.599s  |  28.599s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   2.317s  |   2.317s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      |  60.299s  |  60.299s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   8.424s  |   8.424s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   4.317s  |   4.317s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   2.865s  |   2.865s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   8.996s  |   8.996s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   4.170s  |   4.170s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |  10.573s  |  10.573s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   4.047s  |   4.047s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |  60.172s  |  60.172s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   4.082s  |   4.082s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   4.933s  |   4.933s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   3.020s  |   3.020s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      |  60.218s  |  60.218s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   1.603s  |   1.603s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      |  60.184s  |  60.184s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   4.860s  |   4.860s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   4.049s  |   4.049s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |  15.020s  |  15.020s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   3.585s  |   3.585s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      |  60.152s  |  60.152s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   2.961s  |   2.961s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   3.436s  |   3.436s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |   4.695s  |   4.695s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |  60.160s  |  60.160s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   3.781s  |   3.781s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   1.471s  |   1.471s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   1.854s  |   1.854s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   5.568s  |   5.568s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |  11.264s  |  11.264s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   6.648s  |   6.648s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   4.100s  |   4.100s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   2.773s  |   2.773s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |  10.125s  |  10.125s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   5.792s  |   5.792s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   3.631s  |   3.631s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   3.791s  |   3.791s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   3.163s  |   3.163s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   3.398s  |   3.398s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   6.780s  |   6.780s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   3.328s  |   3.328s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   5.774s  |   5.774s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   2.287s  |   2.287s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   4.663s  |   4.663s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |  16.474s  |  16.474s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   9.242s  |   9.242s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   6.835s  |   6.835s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |  38.198s  |  38.198s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            |  60.229s  |  60.229s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |  30.030s  |  30.030s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  60.319s  |  60.319s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |  49.143s  |  49.143s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  60.324s  |  60.324s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |  18.223s  |  18.223s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        |  60.311s  |  60.311s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  60.225s  |  60.225s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       |  60.414s  |  60.414s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   5.770s  |   5.770s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   5.192s  |   5.192s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     |  60.439s  |  60.439s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     |  60.543s  |  60.543s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     |  60.662s  |  60.662s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |  33.603s  |  33.603s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         |  60.219s  |  60.219s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               |  60.093s  |  60.093s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         |  60.301s  |  60.301s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               |  60.289s  |  60.289s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   3.581s  |   3.581s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |  35.743s  |  35.743s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               |  60.154s  |  60.154s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  |  60.284s  |  60.284s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |  60.295s  |  60.295s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     |  60.203s  |  60.203s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  60.326s  |  60.326s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  60.261s  |  60.261s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            |  60.346s  |  60.346s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            |  60.319s  |  60.319s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   4.494s  |   4.494s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   4.387s  |   4.387s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                |  60.150s  |  60.150s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   4.826s  |   4.826s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  60.357s  |  60.357s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 |  60.575s  |  60.575s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 |  60.466s  |  60.466s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  60.372s  |  60.372s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 |  60.325s  |  60.325s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  59.535s  |  59.535s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |  60.275s  |  60.275s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           |  60.363s  |  60.363s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           |  60.251s  |  60.251s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           |  60.555s  |  60.555s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |  60.287s  |  60.287s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  60.209s  |  60.209s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |  60.289s  |  60.289s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   9.590s  |   9.590s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  60.212s  |  60.212s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 |  60.213s  |  60.213s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  60.138s  |  60.138s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 |  60.169s  |  60.169s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   6.654s  |   6.654s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 |  60.476s  |  60.476s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 |  60.264s  |  60.264s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |   6.952s  |   6.952s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  60.147s  |  60.147s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 |  60.152s  |  60.152s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   6.353s  |   6.353s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 |  60.142s  |  60.142s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |  21.916s  |  21.916s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  58.448s  |  58.448s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |  60.210s  |  60.210s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   6.970s  |   6.970s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   9.956s  |   9.956s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 |  60.275s  |  60.275s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  60.179s  |  60.179s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |   8.216s  |   8.216s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 |  60.595s  |  60.595s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 |  60.230s  |  60.230s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   5.485s  |   5.485s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |   6.270s  |   6.270s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 |  60.186s  |  60.186s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   3.988s  |   3.988s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |  60.221s  |  60.221s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   3.590s  |   3.590s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |  60.229s  |  60.229s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |  26.411s  |  26.411s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |  60.221s  |  60.221s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   7.519s  |   7.519s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   3.226s  |   3.226s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              |  60.343s  |  60.343s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  55.315s  |  55.315s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 |  60.207s  |  60.207s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  60.350s  |  60.350s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 |  60.188s  |  60.188s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  47.479s  |  47.479s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        |  60.376s  |  60.376s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  60.215s  |  60.215s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  60.202s  |  60.202s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |  60.314s  |  60.314s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           |  60.306s  |  60.306s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    |  60.326s  |  60.326s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    |  60.336s  |  60.336s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       |  60.255s  |  60.255s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       |  60.174s  |  60.174s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  60.149s  |  60.149s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  60.306s  |  60.306s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |  20.702s  |  20.702s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              |  60.512s  |  60.512s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  60.275s  |  60.275s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  47.402s  |  47.402s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  60.252s  |  60.252s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  60.193s  |  60.193s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  60.237s  |  60.237s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  |  60.327s  |  60.327s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  60.239s  |  60.239s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  60.203s  |  60.203s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   4.761s  |   4.761s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  60.275s  |  60.275s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |  60.200s  |  60.200s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  60.132s  |  60.132s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            |  60.357s  |  60.357s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          |  60.301s  |  60.301s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  60.181s  |  60.181s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  60.187s  |  60.187s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  60.212s  |  60.212s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  60.145s  |  60.145s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   5.207s  |   5.207s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   8.547s  |   8.547s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        |  60.288s  |  60.288s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        |  60.380s  |  60.380s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |  60.156s  |  60.156s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        |  60.189s  |  60.189s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        |  60.242s  |  60.242s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        |  60.253s  |  60.253s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        |  25.738s  |  25.738s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        |  60.259s  |  60.259s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        |  60.195s  |  60.195s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  |  60.163s  |  60.163s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   2.655s  |   2.655s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |  60.313s  |  60.313s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   1.906s  |   1.906s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   2.610s  |   2.610s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   5.981s  |   5.981s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  32.508s  |  32.508s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 |  60.264s  |  60.264s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   4.482s  |   4.482s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 |  60.323s  |  60.323s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 |  60.179s  |  60.179s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |  18.538s  |  18.538s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 |  60.232s  |  60.232s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 |  60.129s  |  60.129s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |  39.810s  |  39.810s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   9.719s  |   9.719s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   4.560s  |   4.560s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |  51.570s  |  51.570s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             |  60.291s  |  60.291s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             |  60.351s  |  60.351s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   7.008s  |   7.008s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             |  60.412s  |  60.412s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             |  60.356s  |  60.356s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |  48.051s  |  48.051s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |  60.277s  |  60.277s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             |  60.253s  |  60.253s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |  39.802s  |  39.802s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             |  60.177s  |  60.177s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             |  60.459s  |  60.459s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |  48.465s  |  48.465s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             |  60.428s  |  60.428s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             |  60.444s  |  60.444s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   5.821s  |   5.821s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   4.289s  |   4.289s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  |  60.229s  |  60.229s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   1.827s  |   1.827s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   3.841s  |   3.841s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                |  60.348s  |  60.348s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   2.030s  |   2.030s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  18.926s  |  18.926s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           |  60.271s  |  60.271s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 |  60.174s  |  60.174s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   4.694s  |   4.694s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 |  60.284s  |  60.284s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 |  60.257s  |  60.257s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   4.199s  |   4.199s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 |  60.289s  |  60.289s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 |  60.172s  |  60.172s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |  13.889s  |  13.889s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           |  60.384s  |  60.384s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |  18.974s  |  18.974s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 |  60.410s  |  60.410s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 |  60.195s  |  60.195s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           |  60.406s  |  60.406s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  |  60.361s  |  60.361s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |  24.797s  |  24.797s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 |  60.281s  |  60.281s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 |  60.220s  |  60.220s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   3.767s  |   3.767s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   3.957s  |   3.957s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |   5.757s  |   5.757s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 |  60.172s  |  60.172s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   4.643s  |   4.643s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 |  60.246s  |  60.246s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 |  60.202s  |  60.202s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   4.237s  |   4.237s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 |  60.185s  |  60.185s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   5.208s  |   5.208s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   7.933s  |   7.933s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  |  60.413s  |  60.413s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |  26.463s  |  26.463s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |  58.681s  |  58.681s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            |  37.073s  |  37.073s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  60.302s  |  60.302s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   3.426s  |   3.426s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  |  60.156s  |  60.156s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   3.933s  |   3.933s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  |  60.226s  |  60.226s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  |  44.409s  |  44.409s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            |  60.309s  |  60.309s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   4.454s  |   4.454s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 |  60.468s  |  60.468s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |  60.153s  |  60.153s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  |  60.304s  |  60.304s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   6.280s  |   6.280s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  |  60.125s  |  60.125s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  |  60.216s  |  60.216s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   5.852s  |   5.852s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  |  60.213s  |  60.213s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  |  60.318s  |  60.318s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |  11.536s  |  11.536s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  |  60.279s  |  60.279s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  |  60.146s  |  60.146s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   2.059s  |   2.059s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |  60.238s  |  60.238s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            |  60.228s  |  60.228s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   5.689s  |   5.689s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |  60.237s  |  60.237s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   2.901s  |   2.901s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |  26.122s  |  26.122s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           |  60.353s  |  60.353s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           |  60.394s  |  60.394s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           |  60.298s  |  60.298s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  60.182s  |  60.182s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               |  60.180s  |  60.180s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               |  60.369s  |  60.369s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               |  60.185s  |  60.185s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               |  60.309s  |  60.309s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               |  60.407s  |  60.407s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |  60.211s  |  60.211s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |  60.236s  |  60.236s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  60.384s  |  60.384s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |  32.817s  |  32.817s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   5.082s  |   5.082s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |  12.179s  |  12.179s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             |  60.213s  |  60.213s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |  24.106s  |  24.106s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   7.359s  |   7.359s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |   8.839s  |   8.839s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |  27.172s  |  27.172s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   3.346s  |   3.346s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   6.012s  |   6.012s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  60.201s  |  60.201s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  60.397s  |  60.397s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            |  60.324s  |  60.324s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    |  60.234s  |  60.234s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |  16.528s  |  16.528s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               |  60.169s  |  60.169s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             |  60.114s  |  60.114s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             |  60.118s  |  60.118s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             |  60.257s  |  60.257s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   5.377s  |   5.377s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             |  60.532s  |  60.532s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             |  60.392s  |  60.392s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   5.128s  |   5.128s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             |  60.150s  |  60.150s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             |  60.305s  |  60.305s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  60.162s  |  60.162s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |  12.549s  |  12.549s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               |  60.285s  |  60.285s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         |  60.396s  |  60.396s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  50.363s  |  50.363s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  51.316s  |  51.316s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  54.885s  |  54.885s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  60.337s  |  60.337s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  60.326s  |  60.326s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        |  60.313s  |  60.313s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   2.940s  |   2.940s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            |  60.180s  |  60.180s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            |  57.869s  |  57.869s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   6.999s  |   6.999s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |  60.245s  |  60.245s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   3.302s  |   3.302s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            |  42.067s  |  42.067s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   3.011s  |   3.011s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  60.099s  |  60.099s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              |  60.283s  |  60.283s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  60.347s  |  60.347s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              |  29.769s  |  29.769s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   4.020s  |   4.020s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  60.253s  |  60.253s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          |  60.238s  |  60.238s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   5.136s  |   5.136s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |  45.452s  |  45.452s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  50.365s  |  50.365s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       |  60.157s  |  60.157s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   5.815s  |   5.815s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       |  60.212s  |  60.212s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   6.007s  |   6.007s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  16.643s  |  16.643s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |  60.256s  |  60.256s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         |  60.336s  |  60.336s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |  38.873s  |  38.873s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           |  60.197s  |  60.197s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |  16.017s  |  16.017s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  |  60.167s  |  60.167s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            |  60.197s  |  60.197s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              |  10.343s  |  10.343s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   4.294s  |   4.294s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   2.832s  |   2.832s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |  31.288s  |  31.288s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          |  60.292s  |  60.292s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          |  60.311s  |  60.311s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |  60.373s  |  60.373s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          |  60.171s  |  60.171s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          |  60.169s  |  60.169s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |  60.226s  |  60.226s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          |  60.173s  |  60.173s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          |  60.113s  |  60.113s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |  60.192s  |  60.192s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                |  60.356s  |  60.356s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                |  60.428s  |  60.428s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |  20.663s  |  20.663s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                |  60.173s  |  60.173s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                |  60.187s  |  60.187s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |  23.582s  |  23.582s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                |  60.281s  |  60.281s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                |  60.459s  |  60.459s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |  38.431s  |  38.431s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                |  60.191s  |  60.191s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                |  60.209s  |  60.209s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          |  60.341s  |  60.341s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |  52.628s  |  52.628s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          |  60.239s  |  60.239s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |  13.495s  |  13.495s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |  60.270s  |  60.270s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          |  60.299s  |  60.299s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |  60.255s  |  60.255s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                |  60.182s  |  60.182s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   5.513s  |   5.513s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   6.719s  |   6.719s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |  17.796s  |  17.796s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |  12.716s  |  12.716s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   6.890s  |   6.890s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |  34.916s  |  34.916s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |  15.349s  |  15.349s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   1.957s  |   1.957s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                |  60.189s  |  60.189s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   1.984s  |   1.984s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |  17.798s  |  17.798s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                |  60.180s  |  60.180s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                |  32.248s  |  32.248s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |  41.452s  |  41.452s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |  24.237s  |  24.237s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |  17.264s  |  17.264s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                |  60.180s  |  60.180s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |  20.185s  |  20.185s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |  18.861s  |  18.861s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   2.691s  |   2.691s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                |  60.305s  |  60.305s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |  12.972s  |  12.972s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |  17.724s  |  17.724s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   3.999s  |   3.999s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |  23.163s  |  23.163s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |  11.908s  |  11.908s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |  33.205s  |  33.205s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |  16.924s  |  16.924s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                |  60.161s  |  60.161s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   6.074s  |   6.074s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   1.883s  |   1.883s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |  25.305s  |  25.305s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                |  60.369s  |  60.369s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                |  60.303s  |  60.303s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |  14.839s  |  14.839s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |  24.809s  |  24.809s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   7.591s  |   7.591s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   2.551s  |   2.551s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |  21.797s  |  21.797s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          |  60.153s  |  60.153s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          |  60.170s  |  60.170s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   1.651s  |   1.651s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   3.682s  |   3.682s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |  14.443s  |  14.443s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |  10.691s  |  10.691s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |  14.458s  |  14.458s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |  60.170s  |  60.170s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   3.294s  |   3.294s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   5.547s  |   5.547s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |  11.340s  |  11.340s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |  10.789s  |  10.789s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          |  60.085s  |  60.085s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |  18.360s  |  18.360s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   3.193s  |   3.193s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   9.595s  |   9.595s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   3.438s  |   3.438s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   3.024s  |   3.024s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |  33.774s  |  33.774s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |  16.833s  |  16.833s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |  15.235s  |  15.235s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          |  60.287s  |  60.287s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          |  60.429s  |  60.429s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          |  60.156s  |  60.156s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          |  60.283s  |  60.283s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |  20.550s  |  20.550s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   2.783s  |   2.783s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          |  10.292s  |  10.292s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  60.371s  |  60.371s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |  60.397s  |  60.397s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |  18.493s  |  18.493s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           |  60.205s  |  60.205s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           |  60.237s  |  60.237s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   5.807s  |   5.807s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |  60.265s  |  60.265s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |  14.572s  |  14.572s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   2.898s  |   2.898s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        |  60.176s  |  60.176s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   5.364s  |   5.364s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |  18.202s  |  18.202s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |   4.811s  |   4.811s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |  13.370s  |  13.370s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |  60.463s  |  60.463s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   3.427s  |   3.427s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |  17.475s  |  17.475s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        |  60.179s  |  60.179s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   1.607s  |   1.607s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |  52.166s  |  52.166s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |  39.059s  |  39.059s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   4.505s  |   4.505s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |  12.336s  |  12.336s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |  22.620s  |  22.620s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   2.638s  |   2.638s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |  28.276s  |  28.276s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |  16.218s  |  16.218s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |  20.294s  |  20.294s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   2.841s  |   2.841s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        |  60.289s  |  60.289s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   3.552s  |   3.552s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   8.540s  |   8.540s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |  18.514s  |  18.514s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |  13.119s  |  13.119s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |  29.723s  |  29.723s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        |  60.212s  |  60.212s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |  14.129s  |  14.129s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        |  60.204s  |  60.204s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  18.822s  |  18.822s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   5.152s  |   5.152s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   2.686s  |   2.686s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |  14.886s  |  14.886s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        |  60.199s  |  60.199s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        |  60.128s  |  60.128s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   5.918s  |   5.918s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |  60.358s  |  60.358s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        |  45.323s  |  45.323s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |  60.209s  |  60.209s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            |  60.331s  |  60.331s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  |  60.206s  |  60.206s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  |  60.180s  |  60.180s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |  15.627s  |  15.627s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  |  60.122s  |  60.122s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  |  60.204s  |  60.204s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   2.959s  |   2.959s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   3.040s  |   3.040s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   2.700s  |   2.700s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   7.994s  |   7.994s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  |  60.321s  |  60.321s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.764s  |   0.764s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   1.411s  |   1.411s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |  14.746s  |  14.746s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   6.269s  |   6.269s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  |  60.392s  |  60.392s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  |  60.271s  |  60.271s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   2.556s  |   2.556s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |  13.041s  |  13.041s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                |  60.222s  |  60.222s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  60.288s  |  60.288s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |  37.233s  |  37.233s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              |  60.224s  |  60.224s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        |  60.304s  |  60.304s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   |  60.154s  |  60.154s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   |  60.147s  |  60.147s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |  18.514s  |  18.514s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   |  60.232s  |  60.232s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   |  60.223s  |  60.223s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |  60.132s  |  60.132s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   |  60.383s  |  60.383s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   |  60.507s  |  60.507s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |  19.908s  |  19.908s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   |  60.298s  |  60.298s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         |  60.297s  |  60.297s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   5.593s  |   5.593s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   4.909s  |   4.909s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |  10.266s  |  10.266s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         |  60.302s  |  60.302s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |  19.541s  |  19.541s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        |  60.156s  |  60.156s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        |  60.485s  |  60.485s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |  54.054s  |  54.054s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        |  60.201s  |  60.201s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        |  60.294s  |  60.294s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |  21.262s  |  21.262s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        |  60.323s  |  60.323s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   8.216s  |   8.216s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   3.530s  |   3.530s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   9.576s  |   9.576s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  60.196s  |  60.196s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   8.260s  |   8.260s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   4.096s  |   4.096s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |  60.246s  |  60.246s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  60.301s  |  60.301s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |  60.275s  |  60.275s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |  20.295s  |  20.295s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            |  60.427s  |  60.427s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            |  60.374s  |  60.374s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |  28.044s  |  28.044s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            |  60.191s  |  60.191s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            |  60.180s  |  60.180s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |  32.348s  |  32.348s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            |  60.186s  |  60.186s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  |  60.267s  |  60.267s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |  15.668s  |  15.668s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  |  60.415s  |  60.415s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   2.761s  |   2.761s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            |  60.265s  |  60.265s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  57.606s  |  57.606s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  60.217s  |  60.217s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  60.255s  |  60.255s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  60.400s  |  60.400s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |  14.203s  |  14.203s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         |  60.336s  |  60.336s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |  60.254s  |  60.254s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         |  60.228s  |  60.228s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   3.773s  |   3.773s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         |  22.722s  |  22.722s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |  14.186s  |  14.186s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |   7.330s  |   7.330s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   7.096s  |   7.096s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   4.644s  |   4.644s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         |  60.348s  |  60.348s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   7.467s  |   7.467s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   6.331s  |   6.331s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   7.016s  |   7.016s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   3.490s  |   3.490s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   4.500s  |   4.500s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   5.203s  |   5.203s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   8.642s  |   8.642s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   7.170s  |   7.170s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   |  60.346s  |  60.346s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           |   5.991s  |   5.991s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           |  60.273s  |  60.273s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           |  60.369s  |  60.369s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   2.352s  |   2.352s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |  60.323s  |  60.323s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           |  15.605s  |  15.605s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           |  60.163s  |  60.163s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           |  60.302s  |  60.302s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  |  60.200s  |  60.200s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   3.400s  |   3.400s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   2.234s  |   2.234s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   3.884s  |   3.884s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   3.284s  |   3.284s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   3.011s  |   3.011s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   5.430s  |   5.430s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             |  60.363s  |  60.363s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   2.820s  |   2.820s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   2.488s  |   2.488s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   5.209s  |   5.209s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   5.904s  |   5.904s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |  60.215s  |  60.215s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             |  60.309s  |  60.309s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   2.001s  |   2.001s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |  60.302s  |  60.302s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   8.868s  |   8.868s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |   4.353s  |   4.353s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             |  60.115s  |  60.115s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   5.431s  |   5.431s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   2.556s  |   2.556s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.580s  |   0.580s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |  60.272s  |  60.272s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             |  60.337s  |  60.337s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   6.393s  |   6.393s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |  60.199s  |  60.199s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             |  60.186s  |  60.186s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   6.098s  |   6.098s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |  22.340s  |  22.340s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              |  60.333s  |  60.333s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      |  60.298s  |  60.298s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   5.868s  |   5.868s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          |  60.906s  |  60.906s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                |  60.521s  |  60.521s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |  60.308s  |  60.308s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |  60.180s  |  60.180s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                |  60.312s  |  60.312s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                |  60.353s  |  60.353s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  60.202s  |  60.202s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                |  60.224s  |  60.224s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                |  60.441s  |  60.441s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  60.236s  |  60.236s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  58.927s  |  58.927s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          |  60.269s  |  60.269s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |  60.521s  |  60.521s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   6.081s  |   6.081s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   4.358s  |   4.358s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              |  60.310s  |  60.310s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       |  60.436s  |  60.436s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       |  60.295s  |  60.295s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  47.925s  |  47.925s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  60.232s  |  60.232s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  60.302s  |  60.302s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  60.367s  |  60.367s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           |  60.281s  |  60.281s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  28.096s  |  28.096s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  11.476s  |  11.476s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   9.106s  |   9.106s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             |  60.532s  |  60.532s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  60.209s  |  60.209s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |  60.211s  |  60.211s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  46.259s  |  46.259s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  60.300s  |  60.300s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  60.237s  |  60.237s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |  60.137s  |  60.137s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  60.188s  |  60.188s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  60.319s  |  60.319s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           |  60.334s  |  60.334s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           |  60.249s  |  60.249s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |  60.172s  |  60.172s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  60.214s  |  60.214s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 |  60.292s  |  60.292s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 |  60.333s  |  60.333s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |  29.308s  |  29.308s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |  60.322s  |  60.322s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                |  60.328s  |  60.328s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                |  60.268s  |  60.268s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  60.290s  |  60.290s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  60.296s  |  60.296s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          |  60.180s  |  60.180s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          |  60.491s  |  60.491s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          |  60.137s  |  60.137s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |  23.542s  |  23.542s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  60.159s  |  60.159s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     |  60.158s  |  60.158s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   2.992s  |   2.992s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                |  60.420s  |  60.420s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                |  60.232s  |  60.232s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   4.095s  |   4.095s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   4.479s  |   4.479s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            |  60.222s  |  60.222s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |  60.153s  |  60.153s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   6.918s  |   6.918s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  51.283s  |  51.283s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |  15.321s  |  15.321s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |   3.228s  |   3.228s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   2.055s  |   2.055s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   1.672s  |   1.672s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |  60.337s  |  60.337s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   1.258s  |   1.258s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            |  60.164s  |  60.164s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      |  60.287s  |  60.287s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   2.537s  |   2.537s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      |  60.144s  |  60.144s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   2.145s  |   2.145s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   2.955s  |   2.955s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   2.835s  |   2.835s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  60.282s  |  60.282s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |  60.350s  |  60.350s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   4.603s  |   4.603s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  60.137s  |  60.137s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   6.088s  |   6.088s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |  45.187s  |  45.187s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |  60.180s  |  60.180s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   2.708s  |   2.708s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.897s  |   0.897s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  60.259s  |  60.259s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  21.022s  |  21.022s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |  19.032s  |  19.032s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  |  60.157s  |  60.157s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |  54.455s  |  54.455s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           |  60.560s  |  60.560s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      |  60.301s  |  60.301s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   4.891s  |   4.891s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      |  60.184s  |  60.184s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           |  60.184s  |  60.184s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           |  60.125s  |  60.125s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        |  60.218s  |  60.218s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |  25.456s  |  25.456s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |  25.766s  |  25.766s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   2.320s  |   2.320s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |  60.132s  |  60.132s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   1.867s  |   1.867s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   2.002s  |   2.002s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   9.626s  |   9.626s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   7.160s  |   7.160s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  22.044s  |  22.044s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   7.336s  |   7.336s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   3.386s  |   3.386s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        |  60.203s  |  60.203s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   2.424s  |   2.424s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   3.123s  |   3.123s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |  60.533s  |  60.533s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   5.013s  |   5.013s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |  60.277s  |  60.277s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |  10.402s  |  10.402s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   5.175s  |   5.175s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   5.931s  |   5.931s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.695s  |   0.695s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.765s  |   0.765s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   6.061s  |   6.061s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   2.895s  |   2.895s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |  60.213s  |  60.213s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  60.166s  |  60.166s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |  12.652s  |  12.652s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  60.195s  |  60.195s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  60.268s  |  60.268s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   6.531s  |   6.531s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |  60.258s  |  60.258s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   8.601s  |   8.601s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |  43.037s  |  43.037s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                |  60.512s  |  60.512s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                |  60.269s  |  60.269s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   1.959s  |   1.959s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          |  60.158s  |  60.158s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   3.843s  |   3.843s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   2.848s  |   2.848s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   2.444s  |   2.444s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   2.049s  |   2.049s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  13.465s  |  13.465s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |  60.345s  |  60.345s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |  60.189s  |  60.189s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  57.994s  |  57.994s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   1.053s  |   1.053s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                |  60.310s  |  60.310s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |   6.524s  |   6.524s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   4.787s  |   4.787s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  27.631s  |  27.631s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   1.541s  |   1.541s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   4.525s  |   4.525s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  60.283s  |  60.283s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   4.169s  |   4.169s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   5.386s  |   5.386s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   8.614s  |   8.614s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   3.749s  |   3.749s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  47.886s  |  47.886s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       |  60.342s  |  60.342s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       |  60.541s  |  60.541s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   5.624s  |   5.624s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       |  60.170s  |  60.170s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       |  60.406s  |  60.406s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       |  60.192s  |  60.192s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       |  60.363s  |  60.363s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |  24.719s  |  24.719s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   1.608s  |   1.608s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   6.966s  |   6.966s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       |  60.181s  |  60.181s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   7.417s  |   7.417s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       |  60.336s  |  60.336s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     |  60.327s  |  60.327s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   3.662s  |   3.662s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  60.392s  |  60.392s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   2.024s  |   2.024s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |  60.169s  |  60.169s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   6.413s  |   6.413s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |  60.228s  |  60.228s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   7.044s  |   7.044s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   7.528s  |   7.528s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   4.401s  |   4.401s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |  17.922s  |  17.922s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |  60.325s  |  60.325s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        |  60.458s  |  60.458s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        |  60.133s  |  60.133s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   2.383s  |   2.383s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  60.368s  |  60.368s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  |  60.153s  |  60.153s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  |  60.337s  |  60.337s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   1.015s  |   1.015s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   1.092s  |   1.092s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  60.239s  |  60.239s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.949s  |   0.949s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |  60.157s  |  60.157s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |  10.034s  |  10.034s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           |  60.162s  |  60.162s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           |  60.284s  |  60.284s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   3.144s  |   3.144s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   4.599s  |   4.599s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   4.659s  |   4.659s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   5.072s  |   5.072s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   4.894s  |   4.894s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   3.053s  |   3.053s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           |  60.308s  |  60.308s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   4.143s  |   4.143s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   1.548s  |   1.548s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           |  60.163s  |  60.163s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   2.016s  |   2.016s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   1.086s  |   1.086s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           |  60.494s  |  60.494s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   2.221s  |   2.221s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   3.427s  |   3.427s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   4.444s  |   4.444s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   2.456s  |   2.456s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   2.729s  |   2.729s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.781s  |   0.781s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   4.134s  |   4.134s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   4.146s  |   4.146s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   6.972s  |   6.972s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   1.224s  |   1.224s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |  60.181s  |  60.181s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   4.010s  |   4.010s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   3.673s  |   3.673s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           |  60.237s  |  60.237s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   4.907s  |   4.907s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           |  60.153s  |  60.153s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   3.522s  |   3.522s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   5.946s  |   5.946s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.923s  |   0.923s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   2.215s  |   2.215s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   2.315s  |   2.315s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |  60.226s  |  60.226s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   2.673s  |   2.673s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           |  60.208s  |  60.208s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   3.084s  |   3.084s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   2.627s  |   2.627s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   6.921s  |   6.921s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.818s  |   0.818s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.848s  |   0.848s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   4.862s  |   4.862s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   3.605s  |   3.605s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |  60.198s  |  60.198s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.880s  |   0.880s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   1.347s  |   1.347s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   5.669s  |   5.669s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   4.915s  |   4.915s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   3.439s  |   3.439s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   3.578s  |   3.578s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |   9.340s  |   9.340s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |   2.986s  |   2.986s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   1.044s  |   1.044s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   2.324s  |   2.324s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  60.403s  |  60.403s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   4.397s  |   4.397s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |   4.493s  |   4.493s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |  21.299s  |  21.299s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.899s  |   0.899s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            |  60.277s  |  60.277s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   2.851s  |   2.851s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |  60.217s  |  60.217s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |  11.059s  |  11.059s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   4.201s  |   4.201s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   1.838s  |   1.838s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  60.263s  |  60.263s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           |  60.155s  |  60.155s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   4.372s  |   4.372s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   6.860s  |   6.860s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  60.349s  |  60.349s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.545s  |   0.545s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   2.810s  |   2.810s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   2.314s  |   2.314s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   4.288s  |   4.288s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.585s  |   0.585s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   3.736s  |   3.736s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   4.792s  |   4.792s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   4.705s  |   4.705s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |  60.189s  |  60.189s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   4.187s  |   4.187s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   3.142s  |   3.142s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   5.272s  |   5.272s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   1.826s  |   1.826s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   8.547s  |   8.547s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   5.129s  |   5.129s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           |  60.172s  |  60.172s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   4.591s  |   4.591s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   1.981s  |   1.981s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   9.612s  |   9.612s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           |  60.272s  |  60.272s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   2.393s  |   2.393s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   7.150s  |   7.150s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           |  60.186s  |  60.186s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   2.800s  |   2.800s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   5.499s  |   5.499s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   6.103s  |   6.103s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |  17.043s  |  17.043s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   5.110s  |   5.110s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   8.588s  |   8.588s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   3.324s  |   3.324s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.913s  |   0.913s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   1.610s  |   1.610s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           |  60.256s  |  60.256s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.756s  |   0.756s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  60.296s  |  60.296s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   4.647s  |   4.647s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   3.535s  |   3.535s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   5.870s  |   5.870s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   5.471s  |   5.471s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   2.602s  |   2.602s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   7.449s  |   7.449s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   5.138s  |   5.138s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |  60.240s  |  60.240s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.718s  |   0.718s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   0.983s  |   0.983s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.814s  |   1.814s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.566s  |   0.566s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   1.681s  |   1.681s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   2.332s  |   2.332s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   9.513s  |   9.513s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.797s  |   0.797s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |  15.756s  |  15.756s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   0.861s  |   0.861s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            |  60.338s  |  60.338s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |  25.733s  |  25.733s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            |  60.181s  |  60.181s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            |  60.200s  |  60.200s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            |  60.460s  |  60.460s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            |  51.613s  |  51.613s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            |  60.481s  |  60.481s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.242s  |   0.242s  |   0.000s  | 0.0%|
</details>
