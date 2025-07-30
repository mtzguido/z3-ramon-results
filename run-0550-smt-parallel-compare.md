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
Job tag: smt-parallel
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: f77123c13cc8dabe8d1d0217a3312738da834eba
Z3 branch: 
Z3 options: "-T:20 smt.threads=4"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: enable passive, add check for bloom up-to-date

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-parallel
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: f77123c13cc8dabe8d1d0217a3312738da834eba
Z3 branch: 
Z3 options: "-T:20 smt.threads=4"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: enable passive, add check for bloom up-to-date

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  55.617s  |  55.617s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  65.522s  |  65.522s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.555s  |   1.555s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  61.820s  |  61.820s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.177s  |   0.177s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  55.617s  |  55.617s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  65.522s  |  65.522s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.555s  |   1.555s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  61.820s  |  61.820s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.177s  |   0.177s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  55.617s  |  55.617s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  65.522s  |  65.522s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.555s  |   1.555s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  61.820s  |  61.820s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.177s  |   0.177s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  55.617s  |  55.617s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  65.522s  |  65.522s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.555s  |   1.555s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  61.820s  |  61.820s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.177s  |   0.177s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2 |  68.616s |151.0MiB|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                      |  66.815s |236.0MiB|
|04.smt2                                                                                    |  65.522s |215.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                        |  65.366s |1052.0MiB|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                            |  64.482s |253.0MiB|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                 |  64.228s |1031.0MiB|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                            |  64.128s |1140.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                         |  63.889s |211.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  63.773s |1283.0MiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                   |  63.720s |224.0MiB|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                |  63.406s |426.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                      |  63.344s |265.0MiB|
|73.smt2                                                                                    |  63.244s |328.0MiB|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                          |  63.200s |592.0MiB|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                        |  63.184s |309.0MiB|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2               |  63.153s |178.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                       |  62.978s |804.0MiB|
|term-0BB4ks.smt2                                                                           |  62.968s |428.0MiB|
|124.smt2                                                                                   |  62.821s |292.0MiB|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                           |  62.726s |386.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2 |  68.616s |151.0MiB|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                      |  66.815s |236.0MiB|
|04.smt2                                                                                    |  65.522s |215.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                        |  65.366s |1052.0MiB|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                            |  64.482s |253.0MiB|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                 |  64.228s |1031.0MiB|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                            |  64.128s |1140.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                         |  63.889s |211.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  63.773s |1283.0MiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                   |  63.720s |224.0MiB|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                |  63.406s |426.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                      |  63.344s |265.0MiB|
|73.smt2                                                                                    |  63.244s |328.0MiB|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                          |  63.200s |592.0MiB|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                        |  63.184s |309.0MiB|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2               |  63.153s |178.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                       |  62.978s |804.0MiB|
|term-0BB4ks.smt2                                                                           |  62.968s |428.0MiB|
|124.smt2                                                                                   |  62.821s |292.0MiB|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                           |  62.726s |386.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |241.0MiB|241.0MiB|0B| 0.0%|
|04.smt2                                                                                     |215.0MiB|215.0MiB|0B| 0.0%|
|1.smt2                                                                                      |200.0MiB|200.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.648MiB|31.648MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.812MiB|30.812MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.572MiB|23.572MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.552MiB|24.552MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.552MiB|24.552MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.94MiB|24.94MiB|0B| 0.0%|
|107.smt2                                                                                    |22.56MiB|22.56MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.948MiB|27.948MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.376MiB|80.376MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.136MiB|23.136MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.9MiB|22.9MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.692MiB|23.692MiB|0B| 0.0%|
|11.smt2                                                                                     |212.0MiB|212.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.284MiB|24.284MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.908MiB|23.908MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.932MiB|24.932MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.608MiB|25.608MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |241.0MiB|241.0MiB|0B| 0.0%|
|04.smt2                                                                                     |215.0MiB|215.0MiB|0B| 0.0%|
|1.smt2                                                                                      |200.0MiB|200.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.648MiB|31.648MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.812MiB|30.812MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.572MiB|23.572MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.552MiB|24.552MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.552MiB|24.552MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.94MiB|24.94MiB|0B| 0.0%|
|107.smt2                                                                                    |22.56MiB|22.56MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.948MiB|27.948MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.376MiB|80.376MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.136MiB|23.136MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.9MiB|22.9MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.692MiB|23.692MiB|0B| 0.0%|
|11.smt2                                                                                     |212.0MiB|212.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.284MiB|24.284MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.908MiB|23.908MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.932MiB|24.932MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.608MiB|25.608MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |241.0MiB|241.0MiB|0B| 0.0%|
|04.smt2                                                                                     |215.0MiB|215.0MiB|0B| 0.0%|
|1.smt2                                                                                      |200.0MiB|200.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.648MiB|31.648MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.812MiB|30.812MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.572MiB|23.572MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.552MiB|24.552MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.552MiB|24.552MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.94MiB|24.94MiB|0B| 0.0%|
|107.smt2                                                                                    |22.56MiB|22.56MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.948MiB|27.948MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.376MiB|80.376MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.136MiB|23.136MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.9MiB|22.9MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.692MiB|23.692MiB|0B| 0.0%|
|11.smt2                                                                                     |212.0MiB|212.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.284MiB|24.284MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.908MiB|23.908MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.932MiB|24.932MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.608MiB|25.608MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |241.0MiB|241.0MiB|0B| 0.0%|
|04.smt2                                                                                     |215.0MiB|215.0MiB|0B| 0.0%|
|1.smt2                                                                                      |200.0MiB|200.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.648MiB|31.648MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.812MiB|30.812MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.572MiB|23.572MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.552MiB|24.552MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.552MiB|24.552MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.94MiB|24.94MiB|0B| 0.0%|
|107.smt2                                                                                    |22.56MiB|22.56MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.948MiB|27.948MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.376MiB|80.376MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.136MiB|23.136MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.9MiB|22.9MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.692MiB|23.692MiB|0B| 0.0%|
|11.smt2                                                                                     |212.0MiB|212.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.284MiB|24.284MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.908MiB|23.908MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.932MiB|24.932MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.608MiB|25.608MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|185.smt2                                                                                   |  20.370s |3072.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  20.292s |2544.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  20.160s |1296.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  63.773s |1283.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  20.143s |1189.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2         |  36.960s |1166.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           |  20.139s |1153.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  20.131s |1150.0MiB|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                            |  64.128s |1140.0MiB|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                           |  32.477s |1139.0MiB|
|181.smt2                                                                                   |  30.310s |1132.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2         |  21.130s |1118.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2             |  30.923s |1101.0MiB|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                 |  21.181s |1092.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  20.174s |1064.0MiB|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                       |  47.115s |1061.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   |  49.762s |1054.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                        |  65.366s |1052.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2         |  20.163s |1049.0MiB|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                 |  64.228s |1031.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|185.smt2                                                                                   |  20.370s |3072.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  20.292s |2544.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  20.160s |1296.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  63.773s |1283.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  20.143s |1189.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2         |  36.960s |1166.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           |  20.139s |1153.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  20.131s |1150.0MiB|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                            |  64.128s |1140.0MiB|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                           |  32.477s |1139.0MiB|
|181.smt2                                                                                   |  30.310s |1132.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2         |  21.130s |1118.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2             |  30.923s |1101.0MiB|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                 |  21.181s |1092.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  20.174s |1064.0MiB|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                       |  47.115s |1061.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   |  49.762s |1054.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                        |  65.366s |1052.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2         |  20.163s |1049.0MiB|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                 |  64.228s |1031.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  55.617s  |  55.617s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  65.522s  |  65.522s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.555s  |   1.555s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  61.820s  |  61.820s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |  62.821s  |  62.821s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   1.211s  |   1.211s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |  47.202s  |  47.202s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   0.685s  |   0.685s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   2.235s  |   2.235s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   1.192s  |   1.192s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   0.474s  |   0.474s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |  60.253s  |  60.253s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   0.633s  |   0.633s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  30.310s  |  30.310s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  20.370s  |  20.370s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   0.666s  |   0.666s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   0.484s  |   0.484s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   1.116s  |   1.116s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   1.387s  |   1.387s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   1.640s  |   1.640s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   2.038s  |   2.038s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   0.813s  |   0.813s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   1.105s  |   1.105s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |  60.250s  |  60.250s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |  54.487s  |  54.487s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   0.515s  |   0.515s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |  53.098s  |  53.098s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   1.679s  |   1.679s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   1.705s  |   1.705s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   0.983s  |   0.983s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |  61.388s  |  61.388s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   0.701s  |   0.701s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   1.939s  |   1.939s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   1.384s  |   1.384s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |  58.017s  |  58.017s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   1.380s  |   1.380s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |  63.244s  |  63.244s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   1.171s  |   1.171s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   0.905s  |   0.905s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|966.smt2                                                                                    |   2.448s  |   2.448s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  61.558s  |  61.558s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|99.smt2                                                                                     |  51.431s  |  51.431s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |  68.616s  |  68.616s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   1.018s  |   1.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          |  48.153s  |  48.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |   7.134s  |   7.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   2.361s  |   2.361s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |  49.453s  |  49.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          |  29.878s  |  29.878s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   2.514s  |   2.514s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   1.490s  |   1.490s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            |  52.091s  |  52.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   5.163s  |   5.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   1.328s  |   1.328s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       |  54.545s  |  54.545s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   0.975s  |   0.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  53.698s  |  53.698s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   3.894s  |   3.894s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |  34.068s  |  34.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           |  50.847s  |  50.847s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           |  46.803s  |  46.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |  46.508s  |  46.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   3.699s  |   3.699s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  32.677s  |  32.677s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   7.104s  |   7.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |   9.218s  |   9.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         |  36.693s  |  36.693s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             |  64.128s  |  64.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |  41.349s  |  41.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  23.808s  |  23.808s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             |  38.219s  |  38.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.685s  |   0.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 |  41.618s  |  41.618s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   0.979s  |   0.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   2.845s  |   2.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   4.312s  |   4.312s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   1.056s  |   1.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              |   2.604s  |   2.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |   3.422s  |   3.422s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   1.287s  |   1.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |   3.280s  |   3.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               |  14.924s  |  14.924s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         |  45.742s  |  45.742s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   8.684s  |   8.684s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |   1.498s  |   1.498s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |  43.336s  |  43.336s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 |  57.438s  |  57.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      |  58.445s  |  58.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   6.956s  |   6.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   1.444s  |   1.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              |  49.685s  |  49.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   2.418s  |   2.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   5.955s  |   5.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          |  23.057s  |  23.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          |  50.797s  |  50.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |  17.789s  |  17.789s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         |  54.313s  |  54.313s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   1.524s  |   1.524s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      |  53.802s  |  53.802s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |  20.399s  |  20.399s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   1.714s  |   1.714s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   5.401s  |   5.401s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         |  32.791s  |  32.791s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      |  32.690s  |  32.690s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               |  45.270s  |  45.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  36.876s  |  36.876s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |  25.894s  |  25.894s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   2.678s  |   2.678s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           |  47.030s  |  47.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               |  55.300s  |  55.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   0.960s  |   0.960s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               |  44.949s  |  44.949s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |  14.477s  |  14.477s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   1.699s  |   1.699s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |  11.852s  |  11.852s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |  24.011s  |  24.011s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   6.001s  |   6.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   |  36.283s  |  36.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   |  38.496s  |  38.496s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   |  51.111s  |  51.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             |  55.185s  |  55.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  12.421s  |  12.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   3.736s  |   3.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    |  52.356s  |  52.356s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |   6.481s  |   6.481s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        |  55.505s  |  55.505s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  48.501s  |  48.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  51.435s  |  51.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     |  54.944s  |  54.944s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               |  47.459s  |  47.459s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               |  46.907s  |  46.907s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   2.796s  |   2.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   1.839s  |   1.839s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |  33.735s  |  33.735s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |  43.809s  |  43.809s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               |  41.854s  |  41.854s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   3.683s  |   3.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   3.406s  |   3.406s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   2.732s  |   2.732s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   2.440s  |   2.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                |  23.546s  |  23.546s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              |  56.748s  |  56.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |  48.474s  |  48.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   1.969s  |   1.969s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |  12.590s  |  12.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  46.268s  |  46.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  56.931s  |  56.931s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   1.183s  |   1.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  45.435s  |  45.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          |  31.502s  |  31.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          |  50.425s  |  50.425s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          |  50.933s  |  50.933s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |  27.226s  |  27.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          |  35.120s  |  35.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          |  56.920s  |  56.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  55.704s  |  55.704s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   2.314s  |   2.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  17.000s  |  17.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   2.770s  |   2.770s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    |  60.243s  |  60.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   7.223s  |   7.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   1.300s  |   1.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    |  53.550s  |  53.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   7.204s  |   7.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   7.867s  |   7.867s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |  24.642s  |  24.642s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |   7.474s  |   7.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        |  30.525s  |  30.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |   8.857s  |   8.857s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |   1.461s  |   1.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   2.091s  |   2.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        |  37.828s  |  37.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  43.678s  |  43.678s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  44.763s  |  44.763s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  17.178s  |  17.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  22.361s  |  22.361s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  41.566s  |  41.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              |  49.614s  |  49.614s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  53.851s  |  53.851s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  |  41.217s  |  41.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  |  40.005s  |  40.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |   6.318s  |   6.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |   7.981s  |   7.981s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   1.174s  |   1.174s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              |  53.762s  |  53.762s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   5.546s  |   5.546s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |  40.786s  |  40.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |  14.557s  |  14.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   8.485s  |   8.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  41.495s  |  41.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        |  45.461s  |  45.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |  55.905s  |  55.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |  15.619s  |  15.619s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   |  43.408s  |  43.408s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   |  49.441s  |  49.441s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     |  55.706s  |  55.706s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   2.779s  |   2.779s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   1.195s  |   1.195s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   1.842s  |   1.842s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     |  53.902s  |  53.902s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 |  42.403s  |  42.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                |  46.502s  |  46.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   3.203s  |   3.203s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                |  53.468s  |  53.468s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      |  48.178s  |  48.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |  20.433s  |  20.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      |  34.020s  |  34.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      |  34.999s  |  34.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   8.418s  |   8.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      |  39.098s  |  39.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |   4.122s  |   4.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   2.303s  |   2.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   4.800s  |   4.800s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   6.433s  |   6.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   1.938s  |   1.938s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |   3.094s  |   3.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   3.768s  |   3.768s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |  44.979s  |  44.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  33.251s  |  33.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |  34.791s  |  34.791s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   8.568s  |   8.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          |  30.310s  |  30.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               |  24.142s  |  24.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                |  49.302s  |  49.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   5.702s  |   5.702s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |   5.700s  |   5.700s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   0.632s  |   0.632s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   7.022s  |   7.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   7.635s  |   7.635s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   2.513s  |   2.513s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   2.129s  |   2.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              |  52.813s  |  52.813s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   6.143s  |   6.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   1.725s  |   1.725s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   2.820s  |   2.820s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   6.297s  |   6.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  43.339s  |  43.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          |  36.402s  |  36.402s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |  17.557s  |  17.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          |  24.676s  |  24.676s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          |  56.920s  |  56.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |  25.494s  |  25.494s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          |  33.643s  |  33.643s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          |  57.580s  |  57.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |  22.478s  |  22.478s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          |  53.261s  |  53.261s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            |  48.053s  |  48.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   2.508s  |   2.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |   6.093s  |   6.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |  20.749s  |  20.749s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            |  47.730s  |  47.730s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   1.073s  |   1.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   1.645s  |   1.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |  11.962s  |  11.962s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   6.630s  |   6.630s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |   1.489s  |   1.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   4.319s  |   4.319s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   1.356s  |   1.356s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |   5.179s  |   5.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           |  54.713s  |  54.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           |  52.944s  |  52.944s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |   4.280s  |   4.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   5.454s  |   5.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   4.550s  |   4.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           |  60.135s  |  60.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   6.130s  |   6.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   6.413s  |   6.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   4.102s  |   4.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |  16.375s  |  16.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   2.284s  |   2.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           |  56.363s  |  56.363s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   6.595s  |   6.595s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |   5.296s  |   5.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  18.569s  |  18.569s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |  15.217s  |  15.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |  17.212s  |  17.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |   4.284s  |   4.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |  17.239s  |  17.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   3.844s  |   3.844s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |  39.153s  |  39.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   6.793s  |   6.793s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  20.381s  |  20.381s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   3.972s  |   3.972s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |  10.029s  |  10.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   6.669s  |   6.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   2.352s  |   2.352s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |   4.661s  |   4.661s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   2.067s  |   2.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |  29.201s  |  29.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   1.782s  |   1.782s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           |  55.695s  |  55.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  55.747s  |  55.747s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           |  50.359s  |  50.359s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   6.479s  |   6.479s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           |  52.176s  |  52.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     |  27.015s  |  27.015s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   3.358s  |   3.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   5.118s  |   5.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |  11.043s  |  11.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   1.645s  |   1.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |   3.234s  |   3.234s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |  17.061s  |  17.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   5.347s  |   5.347s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   2.552s  |   2.552s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     |  56.403s  |  56.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |   1.279s  |   1.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.703s  |   0.703s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |   6.347s  |   6.347s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |  22.563s  |  22.563s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   3.286s  |   3.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   5.933s  |   5.933s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |  14.508s  |  14.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   7.524s  |   7.524s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   6.853s  |   6.853s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   6.391s  |   6.391s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   5.323s  |   5.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   1.691s  |   1.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   0.876s  |   0.876s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     |  60.449s  |  60.449s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |   5.467s  |   5.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |  15.001s  |  15.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   3.582s  |   3.582s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |  14.374s  |  14.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               |  58.687s  |  58.687s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |  11.611s  |  11.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   2.023s  |   2.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     |  51.817s  |  51.817s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |   1.597s  |   1.597s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |   7.166s  |   7.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   1.853s  |   1.853s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   3.686s  |   3.686s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |   1.549s  |   1.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   7.399s  |   7.399s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   2.408s  |   2.408s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |  24.332s  |  24.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   2.609s  |   2.609s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |  18.938s  |  18.938s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     |  23.716s  |  23.716s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     |  53.155s  |  53.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  46.365s  |  46.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               |  52.592s  |  52.592s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   2.685s  |   2.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   6.513s  |   6.513s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |   1.797s  |   1.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               |  52.866s  |  52.866s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |  32.270s  |  32.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   4.385s  |   4.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |  14.475s  |  14.475s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               |  24.088s  |  24.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |  20.751s  |  20.751s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |  39.540s  |  39.540s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               |  28.896s  |  28.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               |  59.146s  |  59.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               |  49.302s  |  49.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               |  53.637s  |  53.637s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |   3.815s  |   3.815s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   7.541s  |   7.541s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   5.340s  |   5.340s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  19.210s  |  19.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               |   2.257s  |   2.257s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               |  42.997s  |  42.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   1.521s  |   1.521s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   2.752s  |   2.752s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |   2.420s  |   2.420s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               |  57.362s  |  57.362s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |  30.691s  |  30.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   2.728s  |   2.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   7.089s  |   7.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   0.543s  |   0.543s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   4.821s  |   4.821s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   5.210s  |   5.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               |  57.204s  |  57.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   2.219s  |   2.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   6.081s  |   6.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   6.861s  |   6.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               |  52.517s  |  52.517s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   1.375s  |   1.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               |  42.628s  |  42.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               |  56.324s  |  56.324s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   5.126s  |   5.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |  10.691s  |  10.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |   4.981s  |   4.981s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |   2.974s  |   2.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   3.266s  |   3.266s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |   4.198s  |   4.198s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |  26.777s  |  26.777s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   2.937s  |   2.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |   2.461s  |   2.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             |  59.384s  |  59.384s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |  22.199s  |  22.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   6.367s  |   6.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   9.815s  |   9.815s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |  17.501s  |  17.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   6.455s  |   6.455s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   6.402s  |   6.402s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |  13.009s  |  13.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   2.639s  |   2.639s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |  10.288s  |  10.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   7.352s  |   7.352s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             |  53.914s  |  53.914s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |  41.108s  |  41.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |  11.105s  |  11.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   3.777s  |   3.777s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             |  55.738s  |  55.738s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   6.863s  |   6.863s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             |  39.547s  |  39.547s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |   2.057s  |   2.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |   7.056s  |   7.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |   1.772s  |   1.772s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |  23.984s  |  23.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   0.650s  |   0.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |  19.191s  |  19.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |  16.676s  |  16.676s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             |  54.467s  |  54.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   6.047s  |   6.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   5.868s  |   5.868s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             |  45.542s  |  45.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |  12.486s  |  12.486s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             |  55.391s  |  55.391s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   2.228s  |   2.228s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             |  38.580s  |  38.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             |  59.268s  |  59.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |  11.192s  |  11.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |  13.822s  |  13.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               |  14.119s  |  14.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |  16.533s  |  16.533s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |  16.610s  |  16.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         |  53.571s  |  53.571s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   3.060s  |   3.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              |   4.628s  |   4.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   5.630s  |   5.630s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   3.593s  |   3.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |   4.137s  |   4.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |  15.169s  |  15.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    |  24.193s  |  24.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |   3.859s  |   3.859s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |   3.795s  |   3.795s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   3.995s  |   3.995s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   6.149s  |   6.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   5.426s  |   5.426s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |  16.938s  |  16.938s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    |  47.096s  |  47.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   3.577s  |   3.577s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    |  61.069s  |  61.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   2.796s  |   2.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   6.493s  |   6.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   1.338s  |   1.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    |  53.128s  |  53.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    |  51.501s  |  51.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    |  48.089s  |  48.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   6.120s  |   6.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   6.081s  |   6.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |   2.412s  |   2.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |  19.598s  |  19.598s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    |  52.047s  |  52.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |  14.819s  |  14.819s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    |  29.867s  |  29.867s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   4.204s  |   4.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  35.071s  |  35.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  11.703s  |  11.703s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |   4.028s  |   4.028s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   7.625s  |   7.625s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    |  51.644s  |  51.644s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |   3.900s  |   3.900s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |   3.965s  |   3.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   6.516s  |   6.516s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    |  63.720s  |  63.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   5.420s  |   5.420s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    |  35.958s  |  35.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |   1.579s  |   1.579s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   1.588s  |   1.588s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   6.109s  |   6.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   4.551s  |   4.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |   2.148s  |   2.148s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   1.111s  |   1.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   6.146s  |   6.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |  16.574s  |  16.574s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   6.374s  |   6.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          |  57.465s  |  57.465s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   6.191s  |   6.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          |  56.669s  |  56.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |  13.549s  |  13.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  15.186s  |  15.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |   1.082s  |   1.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          |  51.269s  |  51.269s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |   1.881s  |   1.881s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          |  58.642s  |  58.642s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   0.670s  |   0.670s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          |  59.142s  |  59.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   3.441s  |   3.441s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |  16.734s  |  16.734s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   7.089s  |   7.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   7.384s  |   7.384s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          |  58.155s  |  58.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          |  53.451s  |  53.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.823s  |   0.823s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   2.754s  |   2.754s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          |  56.864s  |  56.864s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   6.928s  |   6.928s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   6.703s  |   6.703s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |  12.650s  |  12.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        |  56.663s  |  56.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   2.775s  |   2.775s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        |  55.566s  |  55.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   0.669s  |   0.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |  26.698s  |  26.698s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |   4.086s  |   4.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |   2.226s  |   2.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |   1.075s  |   1.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |   4.358s  |   4.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |  24.389s  |  24.389s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   0.945s  |   0.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |  14.781s  |  14.781s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   2.091s  |   2.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |  11.992s  |  11.992s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   1.997s  |   1.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |  13.990s  |  13.990s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |   6.852s  |   6.852s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   3.384s  |   3.384s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   1.286s  |   1.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |   7.993s  |   7.993s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |  17.171s  |  17.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   3.061s  |   3.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        |  58.288s  |  58.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   6.591s  |   6.591s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |   2.246s  |   2.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |  20.355s  |  20.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |  18.890s  |  18.890s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   5.893s  |   5.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |  11.036s  |  11.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   6.417s  |   6.417s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        |  55.593s  |  55.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |   4.201s  |   4.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        |  49.166s  |  49.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |  14.578s  |  14.578s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   3.843s  |   3.843s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |   1.306s  |   1.306s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |  43.026s  |  43.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |  29.195s  |  29.195s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   5.155s  |   5.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        |  54.381s  |  54.381s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   7.952s  |   7.952s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  |  53.749s  |  53.749s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   1.377s  |   1.377s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   3.484s  |   3.484s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   4.675s  |   4.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   1.275s  |   1.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |   1.748s  |   1.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |   5.624s  |   5.624s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   2.469s  |   2.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   1.214s  |   1.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.810s  |   0.810s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     |   4.549s  |   4.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  23.514s  |  23.514s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   4.325s  |   4.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   7.663s  |   7.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     |  57.195s  |  57.195s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     |  42.667s  |  42.667s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     |  55.466s  |  55.466s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   8.363s  |   8.363s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |  21.666s  |  21.666s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   0.902s  |   0.902s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       |  52.135s  |  52.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |  13.627s  |  13.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |   3.709s  |   3.709s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   7.814s  |   7.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |  22.664s  |  22.664s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |  10.343s  |  10.343s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       |  51.138s  |  51.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   4.254s  |   4.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |  26.385s  |  26.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       |  59.694s  |  59.694s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   4.719s  |   4.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   6.636s  |   6.636s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   1.518s  |   1.518s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   5.335s  |   5.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       |  54.614s  |  54.614s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       |  55.540s  |  55.540s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |  14.267s  |  14.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   4.466s  |   4.466s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   0.667s  |   0.667s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   1.291s  |   1.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   2.622s  |   2.622s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       |  58.893s  |  58.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       |  63.344s  |  63.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |  15.610s  |  15.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 |  49.025s  |  49.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  26.026s  |  26.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |  14.502s  |  14.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  37.229s  |  37.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   2.244s  |   2.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |  34.776s  |  34.776s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  14.453s  |  14.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   0.606s  |   0.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  19.053s  |  19.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  21.493s  |  21.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |  12.043s  |  12.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |  18.662s  |  18.662s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  29.413s  |  29.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   2.135s  |   2.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |  23.118s  |  23.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            |  53.737s  |  53.737s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   3.617s  |   3.617s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   2.134s  |   2.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   0.851s  |   0.851s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   1.500s  |   1.500s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   0.656s  |   0.656s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   1.317s  |   1.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |  41.795s  |  41.795s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   1.375s  |   1.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   2.173s  |   2.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   3.599s  |   3.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   1.927s  |   1.927s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |   4.083s  |   4.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   2.019s  |   2.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   2.721s  |   2.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |  12.584s  |  12.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |  11.598s  |  11.598s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |  16.856s  |  16.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |  19.843s  |  19.843s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   3.323s  |   3.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |  13.108s  |  13.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   0.939s  |   0.939s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   2.260s  |   2.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  38.337s  |  38.337s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   3.249s  |   3.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  33.727s  |  33.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |  12.259s  |  12.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   3.796s  |   3.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   3.685s  |   3.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  38.145s  |  38.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   6.920s  |   6.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   1.019s  |   1.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |  24.906s  |  24.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   1.114s  |   1.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   2.008s  |   2.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   1.825s  |   1.825s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   1.679s  |   1.679s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   3.307s  |   3.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   1.890s  |   1.890s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   0.904s  |   0.904s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   4.386s  |   4.386s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   5.330s  |   5.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   2.294s  |   2.294s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   1.576s  |   1.576s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   1.439s  |   1.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   1.160s  |   1.160s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   1.242s  |   1.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   4.045s  |   4.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   2.539s  |   2.539s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  19.875s  |  19.875s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |  18.917s  |  18.917s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   3.850s  |   3.850s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  33.472s  |  33.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |  11.590s  |  11.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   2.019s  |   2.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |  10.515s  |  10.515s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   3.322s  |   3.322s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  45.758s  |  45.758s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |  12.100s  |  12.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   3.613s  |   3.613s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   1.775s  |   1.775s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  27.092s  |  27.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   1.524s  |   1.524s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   1.471s  |   1.471s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   2.690s  |   2.690s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |  18.706s  |  18.706s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   3.169s  |   3.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   4.919s  |   4.919s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   2.257s  |   2.257s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |   5.626s  |   5.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  11.017s  |  11.017s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   2.061s  |   2.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   1.185s  |   1.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   2.009s  |   2.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   3.747s  |   3.747s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   2.942s  |   2.942s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                |  40.841s  |  40.841s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |  13.230s  |  13.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  35.283s  |  35.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   1.166s  |   1.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |  47.932s  |  47.932s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  42.590s  |  42.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   1.320s  |   1.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   1.627s  |   1.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |  10.844s  |  10.844s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   2.161s  |   2.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   4.685s  |   4.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   2.271s  |   2.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  18.077s  |  18.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   0.997s  |   0.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |  10.073s  |  10.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   0.560s  |   0.560s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   2.561s  |   2.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   1.892s  |   1.892s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |  16.045s  |  16.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   1.588s  |   1.588s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |   5.654s  |   5.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   4.001s  |   4.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   1.753s  |   1.753s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   1.719s  |   1.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   3.265s  |   3.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   1.724s  |   1.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   2.383s  |   2.383s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   2.529s  |   2.529s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   3.497s  |   3.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   3.745s  |   3.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   4.650s  |   4.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |   2.851s  |   2.851s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   2.512s  |   2.512s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   2.557s  |   2.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   5.342s  |   5.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   1.758s  |   1.758s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          |  21.130s  |  21.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          |  36.960s  |  36.960s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          |  20.163s  |  20.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   8.077s  |   8.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   3.212s  |   3.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             |  20.143s  |  20.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            |  20.139s  |  20.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            |  20.131s  |  20.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   2.469s  |   2.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   2.956s  |   2.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   0.938s  |   0.938s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   7.105s  |   7.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |  27.526s  |  27.526s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   1.677s  |   1.677s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |  61.019s  |  61.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   8.382s  |   8.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      |  39.281s  |  39.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   3.012s  |   3.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   8.700s  |   8.700s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   0.461s  |   0.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   6.368s  |   6.368s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   2.452s  |   2.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       |  52.248s  |  52.248s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   5.218s  |   5.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   4.789s  |   4.789s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   1.808s  |   1.808s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   |  34.176s  |  34.176s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |   5.879s  |   5.879s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |  16.614s  |  16.614s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |   5.439s  |   5.439s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |  29.784s  |  29.784s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |  26.978s  |  26.978s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   4.096s  |   4.096s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   6.186s  |   6.186s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          |  56.425s  |  56.425s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          |  50.186s  |  50.186s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   1.237s  |   1.237s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   0.823s  |   0.823s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               |  54.936s  |  54.936s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               |  40.354s  |  40.354s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  45.498s  |  45.498s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               |  25.005s  |  25.005s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               |  61.913s  |  61.913s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   4.579s  |   4.579s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         |  36.767s  |  36.767s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         |  40.090s  |  40.090s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         |  51.741s  |  51.741s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |   5.107s  |   5.107s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               |  48.834s  |  48.834s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  46.729s  |  46.729s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   3.997s  |   3.997s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |  65.366s  |  65.366s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         |  42.077s  |  42.077s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |   1.862s  |   1.862s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  26.495s  |  26.495s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  48.496s  |  48.496s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    |  49.762s  |  49.762s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  44.381s  |  44.381s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    |  53.958s  |  53.958s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  15.466s  |  15.466s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  18.327s  |  18.327s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   3.380s  |   3.380s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  46.772s  |  46.772s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   4.395s  |   4.395s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   4.576s  |   4.576s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  11.052s  |  11.052s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |   2.536s  |   2.536s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |   3.118s  |   3.118s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   4.503s  |   4.503s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   4.945s  |   4.945s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |  64.228s  |  64.228s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   3.595s  |   3.595s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  |  47.701s  |  47.701s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   1.461s  |   1.461s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  11.078s  |  11.078s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |   6.231s  |   6.231s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  17.500s  |  17.500s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           |  41.850s  |  41.850s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |   6.569s  |   6.569s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |  17.739s  |  17.739s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              |  33.374s  |  33.374s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   6.588s  |   6.588s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              |  48.225s  |  48.225s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              |  42.027s  |  42.027s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  48.229s  |  48.229s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              |  36.810s  |  36.810s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              |  42.977s  |  42.977s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |  53.074s  |  53.074s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              |  40.954s  |  40.954s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              |  38.226s  |  38.226s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   0.964s  |   0.964s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |  58.270s  |  58.270s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  59.561s  |  59.561s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |   4.561s  |   4.561s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |  54.203s  |  54.203s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  54.102s  |  54.102s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  48.261s  |  48.261s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  26.139s  |  26.139s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  54.516s  |  54.516s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            |  56.086s  |  56.086s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   7.358s  |   7.358s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             |  27.378s  |  27.378s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   1.518s  |   1.518s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             |  32.970s  |  32.970s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             |  52.573s  |  52.573s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   3.086s  |   3.086s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             |  49.360s  |  49.360s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             |  50.020s  |  50.020s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   1.665s  |   1.665s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 |  39.928s  |  39.928s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   1.385s  |   1.385s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  |  59.745s  |  59.745s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |  31.672s  |  31.672s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   7.927s  |   7.927s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             |  45.553s  |  45.553s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   0.907s  |   0.907s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   2.528s  |   2.528s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |  24.844s  |  24.844s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   1.346s  |   1.346s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |  23.972s  |  23.972s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   1.466s  |   1.466s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             |  24.224s  |  24.224s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   1.186s  |   1.186s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   2.625s  |   2.625s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   1.447s  |   1.447s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   2.547s  |   2.547s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |  15.184s  |  15.184s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   1.088s  |   1.088s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   7.476s  |   7.476s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               |  20.160s  |  20.160s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   5.254s  |   5.254s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            |  53.530s  |  53.530s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   1.653s  |   1.653s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 |  20.174s  |  20.174s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |   5.578s  |   5.578s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  49.148s  |  49.148s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |  14.888s  |  14.888s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           |  51.468s  |  51.468s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |   5.208s  |   5.208s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |   5.912s  |   5.912s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 |  57.320s  |  57.320s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      |  39.718s  |  39.718s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |   4.971s  |   4.971s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |  12.948s  |  12.948s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           |  52.736s  |  52.736s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  36.677s  |  36.677s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |   4.277s  |   4.277s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  27.840s  |  27.840s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              |  56.208s  |  56.208s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |   7.860s  |   7.860s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   3.499s  |   3.499s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   1.027s  |   1.027s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      |  61.076s  |  61.076s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               |  34.335s  |  34.335s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              |  47.399s  |  47.399s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   1.537s  |   1.537s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       |  56.796s  |  56.796s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |   9.355s  |   9.355s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   1.823s  |   1.823s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       |  54.616s  |  54.616s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   1.715s  |   1.715s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       |  25.267s  |  25.267s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |  39.058s  |  39.058s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       |  54.224s  |  54.224s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   0.723s  |   0.723s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   1.782s  |   1.782s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |   2.867s  |   2.867s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |  13.202s  |  13.202s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       |  48.786s  |  48.786s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |   3.837s  |   3.837s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       |  50.993s  |  50.993s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   1.622s  |   1.622s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       |   9.492s  |   9.492s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |  13.376s  |  13.376s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   0.894s  |   0.894s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   2.365s  |   2.365s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       |  25.349s  |  25.349s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       |  56.861s  |  56.861s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   3.956s  |   3.956s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   0.563s  |   0.563s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       |  54.913s  |  54.913s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   3.181s  |   3.181s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   0.927s  |   0.927s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               |  54.344s  |  54.344s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         |  32.015s  |  32.015s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   5.806s  |   5.806s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.617s  |   0.617s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   2.403s  |   2.403s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   2.862s  |   2.862s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 |  54.614s  |  54.614s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |  17.570s  |  17.570s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |  20.150s  |  20.150s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |  16.379s  |  16.379s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   5.471s  |   5.471s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   7.941s  |   7.941s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                |  36.486s  |  36.486s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   2.014s  |   2.014s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   8.249s  |   8.249s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                |  55.088s  |  55.088s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   0.952s  |   0.952s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   2.346s  |   2.346s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      |  53.310s  |  53.310s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   1.140s  |   1.140s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |   1.435s  |   1.435s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   5.692s  |   5.692s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   2.126s  |   2.126s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   2.168s  |   2.168s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   1.091s  |   1.091s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   1.075s  |   1.075s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   0.894s  |   0.894s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |   1.901s  |   1.901s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   1.787s  |   1.787s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      |  27.960s  |  27.960s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      |  51.345s  |  51.345s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   1.218s  |   1.218s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   6.033s  |   6.033s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   4.762s  |   4.762s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   0.766s  |   0.766s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   1.819s  |   1.819s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   0.814s  |   0.814s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   1.996s  |   1.996s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   6.148s  |   6.148s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |  22.428s  |  22.428s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      |  55.561s  |  55.561s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   3.985s  |   3.985s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   5.295s  |   5.295s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   0.983s  |   0.983s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   2.891s  |   2.891s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   2.062s  |   2.062s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |  12.898s  |  12.898s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   1.886s  |   1.886s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |  33.960s  |  33.960s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   0.640s  |   0.640s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   1.309s  |   1.309s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   1.121s  |   1.121s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      |  23.566s  |  23.566s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      |  56.206s  |  56.206s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   2.933s  |   2.933s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   1.439s  |   1.439s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |   3.322s  |   3.322s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   2.830s  |   2.830s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      |  56.298s  |  56.298s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   0.867s  |   0.867s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   1.306s  |   1.306s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |   6.637s  |   6.637s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |   6.357s  |   6.357s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   7.730s  |   7.730s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   6.258s  |   6.258s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   2.615s  |   2.615s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   2.816s  |   2.816s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   0.866s  |   0.866s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   5.792s  |   5.792s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   1.887s  |   1.887s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   0.921s  |   0.921s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   1.850s  |   1.850s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   1.932s  |   1.932s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   0.738s  |   0.738s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   2.717s  |   2.717s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   1.112s  |   1.112s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   4.920s  |   4.920s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   2.429s  |   2.429s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   1.943s  |   1.943s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |  25.636s  |  25.636s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            |  48.897s  |  48.897s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |   6.363s  |   6.363s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  50.791s  |  50.791s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |  29.522s  |  29.522s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  35.703s  |  35.703s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |  17.715s  |  17.715s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        |  46.134s  |  46.134s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        |  35.001s  |  35.001s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  40.779s  |  40.779s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       |  55.433s  |  55.433s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   4.282s  |   4.282s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   4.623s  |   4.623s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     |  20.132s  |  20.132s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     |  20.152s  |  20.152s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     |  20.173s  |  20.173s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |  19.785s  |  19.785s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         |  49.898s  |  49.898s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               |  37.981s  |  37.981s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         |  59.410s  |  59.410s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               |  58.736s  |  58.736s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   6.472s  |   6.472s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |  21.256s  |  21.256s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               |  60.697s  |  60.697s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |  19.160s  |  19.160s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     |  50.739s  |  50.739s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  41.496s  |  41.496s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  23.069s  |  23.069s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            |  51.078s  |  51.078s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            |  59.706s  |  59.706s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   4.092s  |   4.092s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   1.082s  |   1.082s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                |  26.342s  |  26.342s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   1.027s  |   1.027s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 |  35.354s  |  35.354s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 |  43.180s  |  43.180s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  26.988s  |  26.988s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |   3.318s  |   3.318s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           |  51.884s  |  51.884s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           |  56.456s  |  56.456s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           |  55.051s  |  55.051s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |  36.329s  |  36.329s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  58.089s  |  58.089s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |  38.109s  |  38.109s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   2.131s  |   2.131s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  57.343s  |  57.343s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 |  59.178s  |  59.178s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  42.799s  |  42.799s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 |  63.406s  |  63.406s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   2.110s  |   2.110s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 |  53.947s  |  53.947s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |   1.561s  |   1.561s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  44.979s  |  44.979s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 |  58.987s  |  58.987s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   2.359s  |   2.359s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 |  25.330s  |  25.330s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |   2.906s  |   2.906s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |   4.558s  |   4.558s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |  58.408s  |  58.408s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   6.696s  |   6.696s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   8.318s  |   8.318s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 |  56.689s  |  56.689s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  53.333s  |  53.333s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |   8.108s  |   8.108s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 |  51.725s  |  51.725s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 |  57.955s  |  57.955s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   4.195s  |   4.195s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |   9.288s  |   9.288s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 |  51.915s  |  51.915s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   7.493s  |   7.493s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |  53.115s  |  53.115s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |  62.689s  |  62.689s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |   4.692s  |   4.692s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |  30.490s  |  30.490s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   9.121s  |   9.121s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              |  43.762s  |  43.762s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  16.811s  |  16.811s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 |  54.681s  |  54.681s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  55.050s  |  55.050s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 |  56.002s  |  56.002s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  23.715s  |  23.715s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        |  62.978s  |  62.978s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  55.901s  |  55.901s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  51.237s  |  51.237s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |  43.575s  |  43.575s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           |  57.323s  |  57.323s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    |  47.262s  |  47.262s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    |  38.445s  |  38.445s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       |  54.885s  |  54.885s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       |  52.738s  |  52.738s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  29.655s  |  29.655s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  53.174s  |  53.174s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |   2.894s  |   2.894s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              |  30.923s  |  30.923s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  51.200s  |  51.200s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  16.194s  |  16.194s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  45.612s  |  45.612s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  45.117s  |  45.117s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  31.621s  |  31.621s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  |  21.181s  |  21.181s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  59.407s  |  59.407s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  52.585s  |  52.585s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   7.295s  |   7.295s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  58.141s  |  58.141s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |  53.620s  |  53.620s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  55.848s  |  55.848s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            |  32.477s  |  32.477s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          |  56.034s  |  56.034s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  56.714s  |  56.714s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  46.906s  |  46.906s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  44.894s  |  44.894s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  53.576s  |  53.576s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   1.382s  |   1.382s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   2.644s  |   2.644s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        |  37.169s  |  37.169s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        |  42.675s  |  42.675s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |  57.007s  |  57.007s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        |  53.981s  |  53.981s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        |  57.930s  |  57.930s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        |  57.919s  |  57.919s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        |  18.361s  |  18.361s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        |  33.706s  |  33.706s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        |  51.642s  |  51.642s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  |  51.196s  |  51.196s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   1.330s  |   1.330s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |  25.224s  |  25.224s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   1.163s  |   1.163s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   9.325s  |   9.325s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 |  46.748s  |  46.748s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   5.748s  |   5.748s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 |  43.074s  |  43.074s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 |  48.208s  |  48.208s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |  17.824s  |  17.824s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 |  43.696s  |  43.696s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 |  46.608s  |  46.608s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |  51.195s  |  51.195s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   2.991s  |   2.991s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   7.261s  |   7.261s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   7.886s  |   7.886s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |  18.097s  |  18.097s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             |  52.737s  |  52.737s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             |  50.193s  |  50.193s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   9.598s  |   9.598s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             |  45.037s  |  45.037s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             |  53.669s  |  53.669s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |  28.859s  |  28.859s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |  51.662s  |  51.662s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             |  53.399s  |  53.399s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |  10.778s  |  10.778s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             |  57.536s  |  57.536s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             |  57.058s  |  57.058s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   4.939s  |   4.939s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             |  51.837s  |  51.837s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             |  41.933s  |  41.933s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   6.807s  |   6.807s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   7.476s  |   7.476s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  |  36.428s  |  36.428s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   0.870s  |   0.870s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   1.552s  |   1.552s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                |  30.312s  |  30.312s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   1.224s  |   1.224s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  14.739s  |  14.739s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           |  58.909s  |  58.909s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 |  28.096s  |  28.096s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   2.850s  |   2.850s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 |  32.502s  |  32.502s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 |  32.501s  |  32.501s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   3.074s  |   3.074s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 |  50.662s  |  50.662s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 |  23.773s  |  23.773s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   4.808s  |   4.808s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           |  38.631s  |  38.631s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |  18.110s  |  18.110s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 |  31.461s  |  31.461s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 |  42.104s  |  42.104s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           |  57.209s  |  57.209s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  |  43.306s  |  43.306s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |  18.359s  |  18.359s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 |  49.820s  |  49.820s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 |  53.416s  |  53.416s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   1.671s  |   1.671s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   5.264s  |   5.264s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |   8.619s  |   8.619s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 |  33.820s  |  33.820s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   4.715s  |   4.715s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 |  50.097s  |  50.097s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   6.760s  |   6.760s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 |  46.650s  |  46.650s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   7.372s  |   7.372s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   6.023s  |   6.023s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  |  50.766s  |  50.766s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   3.592s  |   3.592s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |   6.388s  |   6.388s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            |  21.016s  |  21.016s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  62.726s  |  62.726s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   1.128s  |   1.128s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  |  24.012s  |  24.012s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   3.999s  |   3.999s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  |  48.668s  |  48.668s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  |  30.614s  |  30.614s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            |  50.704s  |  50.704s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   1.071s  |   1.071s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 |  51.500s  |  51.500s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |  45.791s  |  45.791s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  |  38.759s  |  38.759s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   2.824s  |   2.824s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  |  40.662s  |  40.662s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  |  51.299s  |  51.299s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   6.203s  |   6.203s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  |  43.844s  |  43.844s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  |  46.542s  |  46.542s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |  11.426s  |  11.426s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  |  59.391s  |  59.391s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  |  56.349s  |  56.349s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |  29.630s  |  29.630s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            |  37.583s  |  37.583s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   3.332s  |   3.332s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |  36.775s  |  36.775s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   1.215s  |   1.215s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |  18.474s  |  18.474s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           |  55.604s  |  55.604s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           |  63.200s  |  63.200s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           |  55.561s  |  55.561s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  42.556s  |  42.556s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               |  43.110s  |  43.110s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               |  56.566s  |  56.566s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               |  39.967s  |  39.967s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               |  47.640s  |  47.640s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               |  63.773s  |  63.773s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |  36.497s  |  36.497s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |  48.034s  |  48.034s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  53.752s  |  53.752s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |  21.919s  |  21.919s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   7.888s  |   7.888s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   4.407s  |   4.407s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             |  50.114s  |  50.114s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |  14.512s  |  14.512s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   1.668s  |   1.668s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |   3.416s  |   3.416s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |  16.882s  |  16.882s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   0.897s  |   0.897s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   7.337s  |   7.337s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  55.650s  |  55.650s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  46.445s  |  46.445s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            |  48.271s  |  48.271s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    |  49.826s  |  49.826s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   4.334s  |   4.334s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               |  54.808s  |  54.808s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             |  47.219s  |  47.219s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             |  31.426s  |  31.426s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             |  47.885s  |  47.885s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   6.727s  |   6.727s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             |  54.102s  |  54.102s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             |  59.163s  |  59.163s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   6.375s  |   6.375s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             |  53.929s  |  53.929s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             |  45.748s  |  45.748s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  51.534s  |  51.534s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |   4.364s  |   4.364s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               |  58.700s  |  58.700s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         |  20.150s  |  20.150s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  12.578s  |  12.578s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  14.826s  |  14.826s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  19.010s  |  19.010s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  27.931s  |  27.931s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  48.433s  |  48.433s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        |  53.389s  |  53.389s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   1.148s  |   1.148s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            |  54.019s  |  54.019s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            |  54.805s  |  54.805s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   3.667s  |   3.667s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |  41.791s  |  41.791s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   0.957s  |   0.957s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            |  28.362s  |  28.362s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   0.915s  |   0.915s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  43.240s  |  43.240s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              |  42.039s  |  42.039s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  36.268s  |  36.268s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              |  20.594s  |  20.594s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   2.766s  |   2.766s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  34.890s  |  34.890s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          |  42.957s  |  42.957s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   1.598s  |   1.598s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |  34.325s  |  34.325s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  35.702s  |  35.702s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       |  54.330s  |  54.330s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   1.610s  |   1.610s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       |  56.300s  |  56.300s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   7.381s  |   7.381s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  13.159s  |  13.159s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         |  46.401s  |  46.401s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |  26.461s  |  26.461s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           |  47.213s  |  47.213s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |   7.110s  |   7.110s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  |  29.251s  |  29.251s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            |  36.649s  |  36.649s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              |  12.237s  |  12.237s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   0.933s  |   0.933s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |   6.603s  |   6.603s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          |  50.841s  |  50.841s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          |  41.697s  |  41.697s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |  32.836s  |  32.836s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          |  58.800s  |  58.800s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          |  52.247s  |  52.247s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |  44.144s  |  44.144s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          |  63.889s  |  63.889s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          |  57.719s  |  57.719s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |  31.191s  |  31.191s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                |  47.495s  |  47.495s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                |  62.496s  |  62.496s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   6.841s  |   6.841s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                |  54.992s  |  54.992s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                |  62.276s  |  62.276s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |  19.519s  |  19.519s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                |  57.313s  |  57.313s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                |  61.005s  |  61.005s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |  25.138s  |  25.138s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                |  50.212s  |  50.212s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                |  37.348s  |  37.348s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          |  52.165s  |  52.165s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |  36.448s  |  36.448s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          |  51.535s  |  51.535s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   3.306s  |   3.306s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |   8.843s  |   8.843s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          |  53.492s  |  53.492s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |  38.768s  |  38.768s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                |  52.969s  |  52.969s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   2.064s  |   2.064s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   3.151s  |   3.151s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |  13.189s  |  13.189s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   4.044s  |   4.044s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   3.663s  |   3.663s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |   5.501s  |   5.501s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |  15.094s  |  15.094s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                |  26.185s  |  26.185s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.857s  |   0.857s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |  29.412s  |  29.412s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                |  39.140s  |  39.140s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                |  15.348s  |  15.348s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |   5.385s  |   5.385s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |   4.257s  |   4.257s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   4.681s  |   4.681s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                |  25.449s  |  25.449s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   5.080s  |   5.080s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   4.793s  |   4.793s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   6.618s  |   6.618s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                |  52.227s  |  52.227s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   2.964s  |   2.964s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |  14.603s  |  14.603s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   1.622s  |   1.622s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |  16.511s  |  16.511s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   7.048s  |   7.048s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |  18.421s  |  18.421s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   6.713s  |   6.713s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                |  48.883s  |  48.883s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   6.249s  |   6.249s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   1.424s  |   1.424s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |  16.615s  |  16.615s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                |  53.210s  |  53.210s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                |  58.042s  |  58.042s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |  13.734s  |  13.734s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   6.640s  |   6.640s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   3.095s  |   3.095s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   2.107s  |   2.107s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |   5.789s  |   5.789s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          |  41.617s  |  41.617s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          |  43.023s  |  43.023s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   0.864s  |   0.864s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   1.277s  |   1.277s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |   4.847s  |   4.847s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   2.716s  |   2.716s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |   6.380s  |   6.380s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |  49.362s  |  49.362s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   5.174s  |   5.174s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   4.953s  |   4.953s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   3.305s  |   3.305s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |  11.437s  |  11.437s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   3.497s  |   3.497s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   4.729s  |   4.729s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   6.594s  |   6.594s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   5.886s  |   5.886s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   5.916s  |   5.916s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |  16.940s  |  16.940s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   5.194s  |   5.194s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |  13.228s  |  13.228s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          |  24.721s  |  24.721s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          |  27.721s  |  27.721s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          |  47.918s  |  47.918s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          |  40.921s  |  40.921s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |  17.780s  |  17.780s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   1.546s  |   1.546s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          |  12.102s  |  12.102s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  46.757s  |  46.757s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |  47.409s  |  47.409s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |  14.566s  |  14.566s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           |  46.190s  |  46.190s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           |  58.744s  |  58.744s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   2.018s  |   2.018s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |  55.069s  |  55.069s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   2.256s  |   2.256s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   2.040s  |   2.040s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        |  54.921s  |  54.921s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   1.601s  |   1.601s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |  12.339s  |  12.339s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |   7.135s  |   7.135s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   4.751s  |   4.751s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |   6.533s  |   6.533s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   2.439s  |   2.439s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |  13.560s  |  13.560s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        |  60.017s  |  60.017s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   1.024s  |   1.024s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |  21.908s  |  21.908s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |  21.154s  |  21.154s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   1.494s  |   1.494s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |  12.927s  |  12.927s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |   6.747s  |   6.747s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   3.800s  |   3.800s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |  20.782s  |  20.782s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   4.426s  |   4.426s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   6.095s  |   6.095s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |  15.833s  |  15.833s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        |  45.602s  |  45.602s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   1.371s  |   1.371s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   2.349s  |   2.349s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   4.519s  |   4.519s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   4.822s  |   4.822s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |   2.783s  |   2.783s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        |  41.419s  |  41.419s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   5.236s  |   5.236s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        |  25.155s  |  25.155s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  14.633s  |  14.633s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   6.282s  |   6.282s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   1.230s  |   1.230s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   3.840s  |   3.840s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        |  28.655s  |  28.655s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        |  33.123s  |  33.123s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   1.392s  |   1.392s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |  31.838s  |  31.838s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        |  27.674s  |  27.674s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |  57.247s  |  57.247s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            |  57.396s  |  57.396s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  |  56.714s  |  56.714s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  |  45.640s  |  45.640s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |  14.793s  |  14.793s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  |  43.647s  |  43.647s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  |  26.736s  |  26.736s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   4.097s  |   4.097s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   7.050s  |   7.050s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   5.469s  |   5.469s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   3.321s  |   3.321s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  |  33.856s  |  33.856s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |  13.050s  |  13.050s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   2.321s  |   2.321s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  |  57.838s  |  57.838s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  |  24.724s  |  24.724s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   3.134s  |   3.134s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |  13.533s  |  13.533s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                |  47.720s  |  47.720s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  60.805s  |  60.805s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   6.526s  |   6.526s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              |  58.255s  |  58.255s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        |  47.115s  |  47.115s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   |  43.533s  |  43.533s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   |  55.437s  |  55.437s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   3.222s  |   3.222s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   |  56.669s  |  56.669s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   |  50.233s  |  50.233s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |  49.337s  |  49.337s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   |  52.588s  |  52.588s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   |  55.527s  |  55.527s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |  18.256s  |  18.256s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   |  55.113s  |  55.113s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         |  32.992s  |  32.992s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   1.218s  |   1.218s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   1.020s  |   1.020s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |  10.117s  |  10.117s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         |  63.184s  |  63.184s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   3.343s  |   3.343s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        |  48.254s  |  48.254s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        |  54.262s  |  54.262s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   4.964s  |   4.964s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        |  57.189s  |  57.189s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        |  45.029s  |  45.029s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |  14.042s  |  14.042s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        |  57.934s  |  57.934s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   3.539s  |   3.539s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   1.788s  |   1.788s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  52.154s  |  52.154s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   2.193s  |   2.193s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   1.651s  |   1.651s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |  30.144s  |  30.144s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  22.694s  |  22.694s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |  54.425s  |  54.425s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |  12.785s  |  12.785s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            |  54.882s  |  54.882s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            |  53.371s  |  53.371s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |  15.697s  |  15.697s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            |  54.033s  |  54.033s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            |  48.339s  |  48.339s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   4.915s  |   4.915s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            |  60.442s  |  60.442s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  |  47.426s  |  47.426s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   2.788s  |   2.788s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  |  51.232s  |  51.232s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   0.852s  |   0.852s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            |  54.545s  |  54.545s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  25.068s  |  25.068s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  51.208s  |  51.208s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  40.331s  |  40.331s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   4.767s  |   4.767s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         |  55.610s  |  55.610s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |  22.503s  |  22.503s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         |  45.067s  |  45.067s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   2.069s  |   2.069s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         |  15.408s  |  15.408s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |   2.523s  |   2.523s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |   1.774s  |   1.774s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   6.928s  |   6.928s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   0.844s  |   0.844s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         |  43.249s  |  43.249s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   2.131s  |   2.131s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   4.635s  |   4.635s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   4.554s  |   4.554s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   1.208s  |   1.208s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   1.453s  |   1.453s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   1.793s  |   1.793s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   1.987s  |   1.987s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   |  29.667s  |  29.667s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           |   6.786s  |   6.786s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           |  59.400s  |  59.400s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           |  52.804s  |  52.804s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   1.232s  |   1.232s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |  36.767s  |  36.767s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           |  11.786s  |  11.786s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           |  47.242s  |  47.242s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           |  29.015s  |  29.015s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  |  36.605s  |  36.605s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   0.921s  |   0.921s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   0.746s  |   0.746s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   1.087s  |   1.087s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   0.779s  |   0.779s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   1.642s  |   1.642s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             |  38.434s  |  38.434s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   0.752s  |   0.752s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   4.364s  |   4.364s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   4.055s  |   4.055s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |  48.057s  |  48.057s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             |  64.482s  |  64.482s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |  51.625s  |  51.625s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   3.286s  |   3.286s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |   7.514s  |   7.514s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             |  36.695s  |  36.695s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   2.103s  |   2.103s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   1.144s  |   1.144s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |  37.991s  |  37.991s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             |  28.438s  |  28.438s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   3.008s  |   3.008s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |  50.159s  |  50.159s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             |  35.530s  |  35.530s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   8.685s  |   8.685s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |  17.167s  |  17.167s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              |  54.129s  |  54.129s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      |  52.619s  |  52.619s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   1.882s  |   1.882s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          |  20.292s  |  20.292s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                |  53.850s  |  53.850s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |  54.787s  |  54.787s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |  45.175s  |  45.175s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                |  54.924s  |  54.924s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                |  53.728s  |  53.728s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  42.654s  |  42.654s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                |  42.842s  |  42.842s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                |  55.741s  |  55.741s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  50.961s  |  50.961s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  33.197s  |  33.197s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          |  59.045s  |  59.045s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |  51.419s  |  51.419s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   1.970s  |   1.970s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   1.872s  |   1.872s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              |  55.867s  |  55.867s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       |  51.883s  |  51.883s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       |  51.690s  |  51.690s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  25.794s  |  25.794s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  37.917s  |  37.917s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  53.694s  |  53.694s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  56.550s  |  56.550s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           |  56.538s  |  56.538s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  30.218s  |  30.218s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  14.802s  |  14.802s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   2.433s  |   2.433s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             |  52.484s  |  52.484s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  47.309s  |  47.309s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |  51.080s  |  51.080s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  39.008s  |  39.008s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  54.644s  |  54.644s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  50.747s  |  50.747s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |  52.270s  |  52.270s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  47.447s  |  47.447s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  30.703s  |  30.703s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           |  56.955s  |  56.955s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           |  49.767s  |  49.767s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |  54.706s  |  54.706s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  31.200s  |  31.200s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 |  45.883s  |  45.883s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 |  51.038s  |  51.038s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |  13.838s  |  13.838s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |  49.246s  |  49.246s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                |  53.046s  |  53.046s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                |  56.965s  |  56.965s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  25.721s  |  25.721s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  51.838s  |  51.838s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          |  57.336s  |  57.336s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          |  52.754s  |  52.754s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          |  58.058s  |  58.058s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |   4.717s  |   4.717s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  48.452s  |  48.452s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     |  58.047s  |  58.047s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   1.765s  |   1.765s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                |  54.674s  |  54.674s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                |  46.478s  |  46.478s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   3.253s  |   3.253s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   1.058s  |   1.058s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            |  37.305s  |  37.305s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |  52.968s  |  52.968s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   2.440s  |   2.440s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  58.388s  |  58.388s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   3.162s  |   3.162s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   0.489s  |   0.489s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |   6.758s  |   6.758s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            |  32.649s  |  32.649s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      |  54.261s  |  54.261s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   0.802s  |   0.802s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      |   5.947s  |   5.947s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   3.317s  |   3.317s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.723s  |   0.723s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   0.913s  |   0.913s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  42.602s  |  42.602s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |  32.812s  |  32.812s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   1.880s  |   1.880s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  44.027s  |  44.027s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   2.151s  |   2.151s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |  23.779s  |  23.779s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |  49.765s  |  49.765s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |   5.746s  |   5.746s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   6.422s  |   6.422s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |  15.536s  |  15.536s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  |  25.276s  |  25.276s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |  25.153s  |  25.153s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           |  55.009s  |  55.009s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      |  56.146s  |  56.146s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   7.988s  |   7.988s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      |  47.527s  |  47.527s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           |  42.302s  |  42.302s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           |  58.424s  |  58.424s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        |  43.779s  |  43.779s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   2.924s  |   2.924s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |  23.662s  |  23.662s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   1.186s  |   1.186s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |  43.110s  |  43.110s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   3.104s  |   3.104s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   9.026s  |   9.026s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  20.327s  |  20.327s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   7.146s  |   7.146s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   1.652s  |   1.652s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        |  42.648s  |  42.648s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   0.764s  |   0.764s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |   7.124s  |   7.124s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   3.274s  |   3.274s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |   5.535s  |   5.535s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   4.595s  |   4.595s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   2.008s  |   2.008s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   1.862s  |   1.862s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   1.710s  |   1.710s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |  54.972s  |  54.972s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  24.527s  |  24.527s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |  15.776s  |  15.776s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   4.295s  |   4.295s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  33.613s  |  33.613s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  47.699s  |  47.699s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   3.313s  |   3.313s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |  41.100s  |  41.100s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   3.010s  |   3.010s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |   5.662s  |   5.662s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                |  63.153s  |  63.153s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                |  38.707s  |  38.707s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          |  45.180s  |  45.180s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   2.621s  |   2.621s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   0.775s  |   0.775s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   0.979s  |   0.979s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  12.378s  |  12.378s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |  52.226s  |  52.226s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |  53.480s  |  53.480s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  32.802s  |  32.802s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                |  37.798s  |  37.798s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |   1.935s  |   1.935s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   1.604s  |   1.604s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  20.635s  |  20.635s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   7.682s  |   7.682s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  39.476s  |  39.476s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   7.160s  |   7.160s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   7.005s  |   7.005s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   3.544s  |   3.544s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   7.325s  |   7.325s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  50.554s  |  50.554s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       |  54.900s  |  54.900s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       |  47.965s  |  47.965s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   7.320s  |   7.320s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       |  48.552s  |  48.552s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       |  41.856s  |  41.856s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       |  44.020s  |  44.020s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       |  36.213s  |  36.213s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |  18.990s  |  18.990s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   1.016s  |   1.016s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   2.425s  |   2.425s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       |  66.815s  |  66.815s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   1.846s  |   1.846s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       |  30.383s  |  30.383s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     |  29.745s  |  29.745s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   2.713s  |   2.713s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  55.224s  |  55.224s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   0.981s  |   0.981s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   3.950s  |   3.950s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   1.960s  |   1.960s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |  45.330s  |  45.330s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   3.689s  |   3.689s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |  11.970s  |  11.970s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.546s  |   0.546s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |  16.052s  |  16.052s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |  58.294s  |  58.294s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        |  39.961s  |  39.961s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        |  48.397s  |  48.397s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   1.042s  |   1.042s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  40.969s  |  40.969s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  |  45.662s  |  45.662s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  |  61.998s  |  61.998s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  31.617s  |  31.617s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |  27.588s  |  27.588s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   3.675s  |   3.675s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           |  48.441s  |  48.441s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           |  42.564s  |  42.564s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   1.558s  |   1.558s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   2.345s  |   2.345s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   8.751s  |   8.751s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   3.998s  |   3.998s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   6.911s  |   6.911s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   0.769s  |   0.769s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           |  53.633s  |  53.633s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   2.327s  |   2.327s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           |  34.881s  |  34.881s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           |  60.121s  |  60.121s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   1.534s  |   1.534s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   1.027s  |   1.027s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   4.657s  |   4.657s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   1.241s  |   1.241s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   7.839s  |   7.839s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   1.695s  |   1.695s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   1.796s  |   1.796s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |  41.211s  |  41.211s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   3.049s  |   3.049s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |  26.110s  |  26.110s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           |  25.740s  |  25.740s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   1.251s  |   1.251s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           |  35.154s  |  35.154s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   7.543s  |   7.543s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   8.028s  |   8.028s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   1.177s  |   1.177s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   7.511s  |   7.511s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |  31.420s  |  31.420s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           |  45.000s  |  45.000s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   6.972s  |   6.972s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   6.652s  |   6.652s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   8.160s  |   8.160s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   6.693s  |   6.693s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   1.185s  |   1.185s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |  44.110s  |  44.110s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   1.635s  |   1.635s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   5.438s  |   5.438s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   8.786s  |   8.786s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |  24.636s  |  24.636s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |   2.695s  |   2.695s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |  10.426s  |  10.426s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  35.536s  |  35.536s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   3.195s  |   3.195s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |  12.929s  |  12.929s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |  26.087s  |  26.087s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            |  37.147s  |  37.147s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   4.561s  |   4.561s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |  51.601s  |  51.601s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   3.090s  |   3.090s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   7.515s  |   7.515s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  38.788s  |  38.788s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           |  50.781s  |  50.781s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   4.512s  |   4.512s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   4.920s  |   4.920s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   4.657s  |   4.657s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   0.986s  |   0.986s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   3.279s  |   3.279s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   2.372s  |   2.372s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   1.279s  |   1.279s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   1.783s  |   1.783s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |  43.178s  |  43.178s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   5.521s  |   5.521s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   8.904s  |   8.904s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   1.551s  |   1.551s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.748s  |   0.748s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   8.407s  |   8.407s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   4.387s  |   4.387s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           |  44.296s  |  44.296s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   1.909s  |   1.909s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   8.139s  |   8.139s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           |  55.091s  |  55.091s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   1.330s  |   1.330s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   4.609s  |   4.609s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           |  44.084s  |  44.084s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   5.650s  |   5.650s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   8.742s  |   8.742s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   1.209s  |   1.209s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   6.148s  |   6.148s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   6.693s  |   6.693s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   6.084s  |   6.084s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   1.427s  |   1.427s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           |  46.571s  |  46.571s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  49.220s  |  49.220s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   1.452s  |   1.452s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   2.437s  |   2.437s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   7.676s  |   7.676s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   1.258s  |   1.258s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   5.117s  |   5.117s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   8.385s  |   8.385s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |  25.706s  |  25.706s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |  13.169s  |  13.169s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   0.865s  |   0.865s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   3.017s  |   3.017s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   5.411s  |   5.411s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            |  62.968s  |  62.968s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |  16.266s  |  16.266s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            |  57.339s  |  57.339s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            |  24.354s  |  24.354s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            |  43.453s  |  43.453s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            |  22.520s  |  22.520s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            |  58.125s  |  58.125s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.046s  |   0.046s  |   0.000s  | 0.0%|
</details>
