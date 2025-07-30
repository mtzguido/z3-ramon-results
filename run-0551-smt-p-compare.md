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
Job tag: smt-p
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
Job description: 
Job tag: smt-p
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
|02.smt2                                                                                     | 194.713s  | 194.713s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 199.632s  | 199.632s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.801s  |   1.801s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 197.046s  | 197.046s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.186s  |   0.186s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 194.713s  | 194.713s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 199.632s  | 199.632s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.801s  |   1.801s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 197.046s  | 197.046s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.186s  |   0.186s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 194.713s  | 194.713s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 199.632s  | 199.632s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.801s  |   1.801s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 197.046s  | 197.046s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.186s  |   0.186s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 194.713s  | 194.713s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 199.632s  | 199.632s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.801s  |   1.801s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 197.046s  | 197.046s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.186s  |   0.186s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2 | 228.827s |174.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 219.418s |299.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                        | 218.791s |1264.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                        | 215.801s |509.0MiB|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                              | 214.660s |330.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2            | 213.398s |398.0MiB|
|65.smt2                                                                                    | 212.229s |556.0MiB|
|73.smt2                                                                                    | 211.785s |542.0MiB|
|From_T2__s1.t2__p19014_safety_0.smt2                                                       | 211.261s |226.0MiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2              | 211.217s |584.0MiB|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                              | 210.937s |685.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 210.524s |320.0MiB|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                   | 209.299s |1034.0MiB|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                            | 209.074s |1349.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              | 209.063s |324.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2            | 209.038s |389.0MiB|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                               | 208.232s |837.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 207.728s |660.0MiB|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                         | 207.474s |1307.0MiB|
|177.smt2                                                                                   | 207.224s |619.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2 | 228.827s |174.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 219.418s |299.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                        | 218.791s |1264.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                        | 215.801s |509.0MiB|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                              | 214.660s |330.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2            | 213.398s |398.0MiB|
|65.smt2                                                                                    | 212.229s |556.0MiB|
|73.smt2                                                                                    | 211.785s |542.0MiB|
|From_T2__s1.t2__p19014_safety_0.smt2                                                       | 211.261s |226.0MiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2              | 211.217s |584.0MiB|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                              | 210.937s |685.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 210.524s |320.0MiB|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                   | 209.299s |1034.0MiB|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                            | 209.074s |1349.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              | 209.063s |324.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2            | 209.038s |389.0MiB|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                               | 208.232s |837.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 207.728s |660.0MiB|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                         | 207.474s |1307.0MiB|
|177.smt2                                                                                   | 207.224s |619.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |382.0MiB|382.0MiB|0B| 0.0%|
|04.smt2                                                                                     |314.0MiB|314.0MiB|0B| 0.0%|
|1.smt2                                                                                      |201.0MiB|201.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.888MiB|31.888MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.74MiB|30.74MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.812MiB|23.812MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.296MiB|24.296MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.54MiB|24.54MiB|0B| 0.0%|
|1063.smt2                                                                                   |25.236MiB|25.236MiB|0B| 0.0%|
|107.smt2                                                                                    |22.812MiB|22.812MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.932MiB|27.932MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.372MiB|80.372MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.136MiB|23.136MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.104MiB|23.104MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.696MiB|23.696MiB|0B| 0.0%|
|11.smt2                                                                                     |266.0MiB|266.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.92MiB|23.92MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.656MiB|23.656MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.928MiB|24.928MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.608MiB|25.608MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |382.0MiB|382.0MiB|0B| 0.0%|
|04.smt2                                                                                     |314.0MiB|314.0MiB|0B| 0.0%|
|1.smt2                                                                                      |201.0MiB|201.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.888MiB|31.888MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.74MiB|30.74MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.812MiB|23.812MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.296MiB|24.296MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.54MiB|24.54MiB|0B| 0.0%|
|1063.smt2                                                                                   |25.236MiB|25.236MiB|0B| 0.0%|
|107.smt2                                                                                    |22.812MiB|22.812MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.932MiB|27.932MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.372MiB|80.372MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.136MiB|23.136MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.104MiB|23.104MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.696MiB|23.696MiB|0B| 0.0%|
|11.smt2                                                                                     |266.0MiB|266.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.92MiB|23.92MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.656MiB|23.656MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.928MiB|24.928MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.608MiB|25.608MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |382.0MiB|382.0MiB|0B| 0.0%|
|04.smt2                                                                                     |314.0MiB|314.0MiB|0B| 0.0%|
|1.smt2                                                                                      |201.0MiB|201.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.888MiB|31.888MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.74MiB|30.74MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.812MiB|23.812MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.296MiB|24.296MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.54MiB|24.54MiB|0B| 0.0%|
|1063.smt2                                                                                   |25.236MiB|25.236MiB|0B| 0.0%|
|107.smt2                                                                                    |22.812MiB|22.812MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.932MiB|27.932MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.372MiB|80.372MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.136MiB|23.136MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.104MiB|23.104MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.696MiB|23.696MiB|0B| 0.0%|
|11.smt2                                                                                     |266.0MiB|266.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.92MiB|23.92MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.656MiB|23.656MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.928MiB|24.928MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.608MiB|25.608MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |382.0MiB|382.0MiB|0B| 0.0%|
|04.smt2                                                                                     |314.0MiB|314.0MiB|0B| 0.0%|
|1.smt2                                                                                      |201.0MiB|201.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.888MiB|31.888MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.74MiB|30.74MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.812MiB|23.812MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.296MiB|24.296MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.54MiB|24.54MiB|0B| 0.0%|
|1063.smt2                                                                                   |25.236MiB|25.236MiB|0B| 0.0%|
|107.smt2                                                                                    |22.812MiB|22.812MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.932MiB|27.932MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.372MiB|80.372MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.136MiB|23.136MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.104MiB|23.104MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.696MiB|23.696MiB|0B| 0.0%|
|11.smt2                                                                                     |266.0MiB|266.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.92MiB|23.92MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.656MiB|23.656MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.928MiB|24.928MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.608MiB|25.608MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  60.549s |4307.0MiB|
|185.smt2                                                                                   | 170.275s |3803.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  60.351s |3182.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  92.563s |2481.0MiB|
|From_T2__foo.t2__terminationS_12_0.smt2                                                    |  77.104s |2464.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  79.743s |2450.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            | 108.909s |2338.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  94.323s |2337.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           | 104.206s |2325.0MiB|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                | 141.350s |2157.0MiB|
|182.smt2                                                                                   | 161.621s |2125.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  60.311s |2068.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                    | 179.291s |2030.0MiB|
|183.smt2                                                                                   |  69.032s |1982.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                | 169.625s |1912.0MiB|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                            | 185.042s |1779.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              | 188.649s |1767.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                        | 167.892s |1741.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          | 164.036s |1598.0MiB|
|181.smt2                                                                                   | 129.622s |1583.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  60.549s |4307.0MiB|
|185.smt2                                                                                   | 170.275s |3803.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  60.351s |3182.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  92.563s |2481.0MiB|
|From_T2__foo.t2__terminationS_12_0.smt2                                                    |  77.104s |2464.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  79.743s |2450.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            | 108.909s |2338.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  94.323s |2337.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           | 104.206s |2325.0MiB|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                | 141.350s |2157.0MiB|
|182.smt2                                                                                   | 161.621s |2125.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  60.311s |2068.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                    | 179.291s |2030.0MiB|
|183.smt2                                                                                   |  69.032s |1982.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                | 169.625s |1912.0MiB|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                            | 185.042s |1779.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              | 188.649s |1767.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                        | 167.892s |1741.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          | 164.036s |1598.0MiB|
|181.smt2                                                                                   | 129.622s |1583.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 194.713s  | 194.713s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 199.632s  | 199.632s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.801s  |   1.801s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 197.046s  | 197.046s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|124.smt2                                                                                    | 206.747s  | 206.747s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   1.466s  |   1.466s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|140.smt2                                                                                    | 148.163s  | 148.163s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   0.936s  |   0.936s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   0.569s  |   0.569s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   2.036s  |   2.036s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   1.275s  |   1.275s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|177.smt2                                                                                    | 207.224s  | 207.224s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   0.751s  |   0.751s  |   0.000s  | 0.0%|
|181.smt2                                                                                    | 129.622s  | 129.622s  |   0.000s  | 0.0%|
|182.smt2                                                                                    | 161.621s  | 161.621s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  69.032s  |  69.032s  |   0.000s  | 0.0%|
|185.smt2                                                                                    | 170.275s  | 170.275s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   0.749s  |   0.749s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   0.881s  |   0.881s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   1.299s  |   1.299s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   2.365s  |   2.365s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   4.746s  |   4.746s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   1.145s  |   1.145s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   0.546s  |   0.546s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   0.520s  |   0.520s  |   0.000s  | 0.0%|
|35.smt2                                                                                     | 192.182s  | 192.182s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|40.smt2                                                                                     | 194.388s  | 194.388s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|54.smt2                                                                                     | 190.807s  | 190.807s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   1.966s  |   1.966s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   2.282s  |   2.282s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   0.779s  |   0.779s  |   0.000s  | 0.0%|
|58.smt2                                                                                     | 197.848s  | 197.848s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   0.908s  |   0.908s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   1.793s  |   1.793s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   1.530s  |   1.530s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|65.smt2                                                                                     | 212.229s  | 212.229s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   0.656s  |   0.656s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   1.355s  |   1.355s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|73.smt2                                                                                     | 211.785s  | 211.785s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   1.696s  |   1.696s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   0.739s  |   0.739s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   1.412s  |   1.412s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|966.smt2                                                                                    |   3.227s  |   3.227s  |   0.000s  | 0.0%|
|98.smt2                                                                                     | 204.185s  | 204.185s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|99.smt2                                                                                     | 188.833s  | 188.833s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  | 228.827s  | 228.827s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   0.908s  |   0.908s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          | 176.745s  | 176.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |   5.958s  |   5.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   1.968s  |   1.968s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |  51.540s  |  51.540s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          |  70.562s  |  70.562s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   3.018s  |   3.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   1.403s  |   1.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            | 186.021s  | 186.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   6.740s  |   6.740s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   1.934s  |   1.934s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       |  73.398s  |  73.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   1.274s  |   1.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          | 123.173s  | 123.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   5.567s  |   5.567s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |  40.894s  |  40.894s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   0.890s  |   0.890s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   0.903s  |   0.903s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           | 128.456s  | 128.456s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           | 114.380s  | 114.380s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |  64.026s  |  64.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   3.749s  |   3.749s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  32.953s  |  32.953s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   6.453s  |   6.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |   9.748s  |   9.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         |  77.483s  |  77.483s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             | 185.042s  | 185.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |  48.406s  |  48.406s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  24.680s  |  24.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             | 118.238s  | 118.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 |  33.084s  |  33.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   1.150s  |   1.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   3.506s  |   3.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   4.097s  |   4.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   1.209s  |   1.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              |   3.834s  |   3.834s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |   3.214s  |   3.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   1.218s  |   1.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |   3.435s  |   3.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               |  14.413s  |  14.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         | 189.230s  | 189.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   9.127s  |   9.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |   1.499s  |   1.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |  47.788s  |  47.788s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 | 194.383s  | 194.383s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      | 117.829s  | 117.829s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   7.683s  |   7.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   1.683s  |   1.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              |  96.143s  |  96.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   2.649s  |   2.649s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   6.498s  |   6.498s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          |  62.973s  |  62.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   0.936s  |   0.936s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          | 160.790s  | 160.790s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   6.030s  |   6.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         | 189.714s  | 189.714s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   2.100s  |   2.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      | 199.127s  | 199.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |  22.490s  |  22.490s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   1.861s  |   1.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   6.146s  |   6.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         | 136.406s  | 136.406s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      |  80.579s  |  80.579s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               | 178.893s  | 178.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  38.191s  |  38.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |  28.567s  |  28.567s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   3.318s  |   3.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           |  54.477s  |  54.477s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               | 160.505s  | 160.505s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               | 125.402s  | 125.402s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |  15.179s  |  15.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   2.151s  |   2.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |  12.080s  |  12.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |  22.707s  |  22.707s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   5.070s  |   5.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   |  41.382s  |  41.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   |  78.897s  |  78.897s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   | 100.839s  | 100.839s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             | 149.691s  | 149.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  12.980s  |  12.980s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   3.061s  |   3.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    | 186.798s  | 186.798s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |   6.651s  |   6.651s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        | 174.421s  | 174.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  58.838s  |  58.838s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  87.163s  |  87.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     | 197.376s  | 197.376s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               | 120.142s  | 120.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               | 123.399s  | 123.399s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   3.357s  |   3.357s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   2.448s  |   2.448s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |  33.855s  |  33.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |  76.517s  |  76.517s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               | 154.129s  | 154.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   3.880s  |   3.880s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   3.073s  |   3.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   3.359s  |   3.359s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   2.612s  |   2.612s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                | 136.139s  | 136.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   1.282s  |   1.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              | 177.608s  | 177.608s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |  74.021s  |  74.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   2.085s  |   2.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |  12.192s  |  12.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  73.355s  |  73.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              | 169.013s  | 169.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   0.989s  |   0.989s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  48.783s  |  48.783s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          |  31.575s  |  31.575s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          | 152.357s  | 152.357s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          | 121.239s  | 121.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |  29.287s  |  29.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          |  81.506s  |  81.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          | 155.974s  | 155.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  77.922s  |  77.922s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   2.136s  |   2.136s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  19.367s  |  19.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   2.901s  |   2.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    | 148.141s  | 148.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   7.118s  |   7.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   1.839s  |   1.839s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    | 161.461s  | 161.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   6.988s  |   6.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   7.357s  |   7.357s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |  25.058s  |  25.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |   7.480s  |   7.480s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        | 142.009s  | 142.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |   7.958s  |   7.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |   1.548s  |   1.548s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   2.481s  |   2.481s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        |  81.688s  |  81.688s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   0.827s  |   0.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  60.147s  |  60.147s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  50.939s  |  50.939s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  19.219s  |  19.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  24.579s  |  24.579s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  50.683s  |  50.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              |  90.845s  |  90.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             | 103.088s  | 103.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  | 140.856s  | 140.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  |  37.787s  |  37.787s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |   6.410s  |   6.410s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |  48.882s  |  48.882s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   1.012s  |   1.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              | 184.062s  | 184.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   5.709s  |   5.709s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             | 131.861s  | 131.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |  13.604s  |  13.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   8.243s  |   8.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  82.603s  |  82.603s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        | 174.818s  | 174.818s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   2.609s  |   2.609s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             | 180.794s  | 180.794s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |  15.444s  |  15.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   | 123.318s  | 123.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   |  92.549s  |  92.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     | 149.031s  | 149.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   2.980s  |   2.980s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   1.771s  |   1.771s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   1.853s  |   1.853s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     | 158.417s  | 158.417s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 | 122.653s  | 122.653s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                |  51.333s  |  51.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   3.382s  |   3.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                | 190.046s  | 190.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      | 128.858s  | 128.858s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |  20.698s  |  20.698s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      | 150.949s  | 150.949s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      |  74.745s  |  74.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   8.924s  |   8.924s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      |  47.561s  |  47.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |   3.468s  |   3.468s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   1.908s  |   1.908s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   5.102s  |   5.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   6.204s  |   6.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   2.381s  |   2.381s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |   3.201s  |   3.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   4.946s  |   4.946s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   | 124.187s  | 124.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  43.814s  |  43.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |  37.600s  |  37.600s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   8.568s  |   8.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          |  70.107s  |  70.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               |  76.920s  |  76.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                | 156.262s  | 156.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   6.126s  |   6.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |   5.823s  |   5.823s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   0.975s  |   0.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   7.189s  |   7.189s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   7.584s  |   7.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   2.760s  |   2.760s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   2.211s  |   2.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              | 145.647s  | 145.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   5.877s  |   5.877s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   2.040s  |   2.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   3.508s  |   3.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   5.526s  |   5.526s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  51.575s  |  51.575s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          |  79.823s  |  79.823s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |  19.033s  |  19.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          |  64.833s  |  64.833s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          | 100.149s  | 100.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |  21.699s  |  21.699s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          | 119.108s  | 119.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          | 170.077s  | 170.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |  22.726s  |  22.726s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          | 127.038s  | 127.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   3.498s  |   3.498s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            | 142.232s  | 142.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   2.204s  |   2.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |   6.323s  |   6.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |  21.447s  |  21.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            | 127.345s  | 127.345s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   1.996s  |   1.996s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |   1.225s  |   1.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |  11.853s  |  11.853s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   5.024s  |   5.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |   1.500s  |   1.500s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   4.465s  |   4.465s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   1.680s  |   1.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |   4.822s  |   4.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           | 197.064s  | 197.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           | 187.144s  | 187.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |   4.234s  |   4.234s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   5.358s  |   5.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   4.587s  |   4.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           | 189.717s  | 189.717s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   5.827s  |   5.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   5.695s  |   5.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   4.356s  |   4.356s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |  16.133s  |  16.133s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   3.132s  |   3.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           | 180.184s  | 180.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   7.015s  |   7.015s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |  14.233s  |  14.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  19.630s  |  19.630s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |  15.676s  |  15.676s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |  18.899s  |  18.899s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |   5.196s  |   5.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           |   0.801s  |   0.801s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |  17.112s  |  17.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   2.667s  |   2.667s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |  43.749s  |  43.749s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   6.647s  |   6.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  22.166s  |  22.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   5.171s  |   5.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |  10.274s  |  10.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   8.029s  |   8.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   2.567s  |   2.567s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |   3.631s  |   3.631s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   2.371s  |   2.371s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |  30.268s  |  30.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   1.850s  |   1.850s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           | 185.636s  | 185.636s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  85.551s  |  85.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           | 192.583s  | 192.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   6.317s  |   6.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           | 190.092s  | 190.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     | 179.291s  | 179.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   4.629s  |   4.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   5.762s  |   5.762s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |   5.456s  |   5.456s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   1.497s  |   1.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |   3.083s  |   3.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |  18.044s  |  18.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   5.377s  |   5.377s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   2.293s  |   2.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     | 176.376s  | 176.376s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |   1.920s  |   1.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |   6.376s  |   6.376s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |  63.424s  |  63.424s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   3.453s  |   3.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   6.604s  |   6.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |  16.729s  |  16.729s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   7.756s  |   7.756s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   7.297s  |   7.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   6.530s  |   6.530s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   5.219s  |   5.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   2.292s  |   2.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   0.723s  |   0.723s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     | 182.000s  | 182.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |   5.341s  |   5.341s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |  15.287s  |  15.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   0.618s  |   0.618s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   3.736s  |   3.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |  14.092s  |  14.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               | 144.323s  | 144.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |  12.026s  |  12.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   2.009s  |   2.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     | 179.943s  | 179.943s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |   1.529s  |   1.529s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |   6.676s  |   6.676s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   2.287s  |   2.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   4.463s  |   4.463s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |   2.211s  |   2.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   6.464s  |   6.464s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   2.372s  |   2.372s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |  64.708s  |  64.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   2.602s  |   2.602s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |  19.216s  |  19.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     |  25.986s  |  25.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     | 204.761s  | 204.761s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  56.639s  |  56.639s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   0.753s  |   0.753s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               |  94.925s  |  94.925s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   1.855s  |   1.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   6.376s  |   6.376s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |   1.803s  |   1.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               | 180.046s  | 180.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |  32.010s  |  32.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   4.246s  |   4.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |  17.332s  |  17.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               |  64.103s  |  64.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |  22.992s  |  22.992s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |  50.338s  |  50.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               | 141.644s  | 141.644s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               | 186.757s  | 186.757s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               | 190.773s  | 190.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               | 166.739s  | 166.739s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |   3.894s  |   3.894s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   7.263s  |   7.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   4.493s  |   4.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  17.723s  |  17.723s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               |   2.321s  |   2.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   0.957s  |   0.957s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               | 173.429s  | 173.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   2.042s  |   2.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   2.567s  |   2.567s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |   3.471s  |   3.471s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               | 100.328s  | 100.328s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |  33.945s  |  33.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   2.743s  |   2.743s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   6.845s  |   6.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   5.473s  |   5.473s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   6.096s  |   6.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               | 190.515s  | 190.515s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   2.274s  |   2.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   6.292s  |   6.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   7.129s  |   7.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               | 188.984s  | 188.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   1.287s  |   1.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               | 173.849s  | 173.849s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               | 211.217s  | 211.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   4.473s  |   4.473s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |  10.999s  |  10.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |   5.773s  |   5.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |   2.203s  |   2.203s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   4.014s  |   4.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |  12.688s  |  12.688s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |  66.551s  |  66.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   3.093s  |   3.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |   2.069s  |   2.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             | 213.398s  | 213.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |  23.591s  |  23.591s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   6.767s  |   6.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   9.011s  |   9.011s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   6.784s  |   6.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   6.882s  |   6.882s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   6.661s  |   6.661s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |  13.432s  |  13.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   3.282s  |   3.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |  11.747s  |  11.747s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   7.634s  |   7.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             | 173.860s  | 173.860s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |  45.532s  |  45.532s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |  10.767s  |  10.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   3.817s  |   3.817s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   1.374s  |   1.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             | 174.037s  | 174.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   7.118s  |   7.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             | 149.906s  | 149.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |   2.887s  |   2.887s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |   7.162s  |   7.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |   1.779s  |   1.779s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |  31.051s  |  31.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   0.903s  |   0.903s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |  21.893s  |  21.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |  18.009s  |  18.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             | 171.379s  | 171.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   9.761s  |   9.761s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   5.968s  |   5.968s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             | 194.743s  | 194.743s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |  13.442s  |  13.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             | 176.156s  | 176.156s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             | 169.441s  | 169.441s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             | 153.690s  | 153.690s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |  11.050s  |  11.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |  14.922s  |  14.922s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               |  13.612s  |  13.612s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |  18.508s  |  18.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |  17.970s  |  17.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         | 142.566s  | 142.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   3.225s  |   3.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              |  20.334s  |  20.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   5.600s  |   5.600s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   3.741s  |   3.741s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |   4.887s  |   4.887s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |  17.419s  |  17.419s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    | 131.197s  | 131.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |   4.423s  |   4.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |   4.192s  |   4.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   4.085s  |   4.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   4.916s  |   4.916s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   4.802s  |   4.802s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |  16.978s  |  16.978s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    | 177.535s  | 177.535s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   4.019s  |   4.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    | 174.317s  | 174.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   4.007s  |   4.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   6.920s  |   6.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   1.961s  |   1.961s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    | 189.317s  | 189.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    | 192.650s  | 192.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    | 193.185s  | 193.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   7.378s  |   7.378s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   6.886s  |   6.886s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |   3.637s  |   3.637s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |  13.781s  |  13.781s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    | 169.806s  | 169.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |  15.893s  |  15.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    | 136.840s  | 136.840s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   6.389s  |   6.389s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  71.661s  |  71.661s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |   9.831s  |   9.831s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |   3.265s  |   3.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   7.324s  |   7.324s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    | 160.057s  | 160.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |   5.662s  |   5.662s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |   3.741s  |   3.741s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   6.557s  |   6.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    | 205.970s  | 205.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   5.577s  |   5.577s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    |  76.126s  |  76.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |   1.587s  |   1.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   2.119s  |   2.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   5.812s  |   5.812s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   5.563s  |   5.563s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |   1.953s  |   1.953s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   5.938s  |   5.938s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |  18.325s  |  18.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   6.351s  |   6.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          | 179.155s  | 179.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   5.991s  |   5.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          | 156.945s  | 156.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |  13.755s  |  13.755s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  14.707s  |  14.707s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |   1.505s  |   1.505s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          | 176.923s  | 176.923s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |   2.794s  |   2.794s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          | 196.378s  | 196.378s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          | 188.827s  | 188.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   4.201s  |   4.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |  15.796s  |  15.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   7.678s  |   7.678s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   7.082s  |   7.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          | 167.020s  | 167.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          | 198.705s  | 198.705s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   1.282s  |   1.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   3.255s  |   3.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          | 171.708s  | 171.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   8.059s  |   8.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   6.375s  |   6.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |  11.232s  |  11.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        | 199.161s  | 199.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   3.130s  |   3.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        | 156.345s  | 156.345s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   0.867s  |   0.867s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |  35.391s  |  35.391s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |   5.195s  |   5.195s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |   2.539s  |   2.539s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |   1.283s  |   1.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |  10.587s  |  10.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |  27.403s  |  27.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |  14.975s  |  14.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   2.025s  |   2.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |  12.917s  |  12.917s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   1.998s  |   1.998s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |  12.778s  |  12.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |   7.100s  |   7.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   4.027s  |   4.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   1.572s  |   1.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |   7.799s  |   7.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |  18.354s  |  18.354s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   3.558s  |   3.558s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        | 165.616s  | 165.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   6.773s  |   6.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |   2.999s  |   2.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |  22.957s  |  22.957s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |  18.748s  |  18.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   6.609s  |   6.609s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |   4.204s  |   4.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   7.009s  |   7.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        | 189.370s  | 189.370s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |  49.656s  |  49.656s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        | 139.939s  | 139.939s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |  15.849s  |  15.849s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   4.327s  |   4.327s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |   1.089s  |   1.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |  51.589s  |  51.589s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |  33.781s  |  33.781s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        | 179.701s  | 179.701s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   6.877s  |   6.877s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  | 168.002s  | 168.002s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   1.143s  |   1.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   3.430s  |   3.430s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   4.469s  |   4.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   1.725s  |   1.725s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |   1.976s  |   1.976s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |  14.398s  |  14.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   2.306s  |   2.306s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   1.281s  |   1.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.987s  |   0.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     |   5.977s  |   5.977s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  62.838s  |  62.838s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   4.906s  |   4.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   7.550s  |   7.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     | 193.974s  | 193.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     |  82.263s  |  82.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     | 155.558s  | 155.558s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   7.654s  |   7.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |  23.726s  |  23.726s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   1.090s  |   1.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       | 154.470s  | 154.470s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |  13.813s  |  13.813s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |   5.282s  |   5.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   7.485s  |   7.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |  24.082s  |  24.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |  10.982s  |  10.982s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       | 137.040s  | 137.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   5.936s  |   5.936s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |  29.451s  |  29.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       | 147.903s  | 147.903s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   4.629s  |   4.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   8.129s  |   8.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   1.149s  |   1.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   6.467s  |   6.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       | 182.250s  | 182.250s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       | 203.080s  | 203.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |  15.354s  |  15.354s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   5.076s  |   5.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   1.584s  |   1.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   2.084s  |   2.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       | 165.314s  | 165.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       | 193.040s  | 193.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |  16.098s  |  16.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 | 159.138s  | 159.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  30.986s  |  30.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |  13.525s  |  13.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  43.093s  |  43.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   2.780s  |   2.780s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |  33.288s  |  33.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  14.694s  |  14.694s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   0.593s  |   0.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  28.091s  |  28.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |  12.853s  |  12.853s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |  19.802s  |  19.802s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  82.403s  |  82.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   2.750s  |   2.750s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |  22.141s  |  22.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            | 160.532s  | 160.532s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   3.773s  |   3.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   2.442s  |   2.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   1.037s  |   1.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   2.651s  |   2.651s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   1.659s  |   1.659s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                | 109.963s  | 109.963s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   1.654s  |   1.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   2.429s  |   2.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   4.271s  |   4.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   2.320s  |   2.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |   4.669s  |   4.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   2.232s  |   2.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   4.167s  |   4.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |  12.009s  |  12.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |  13.579s  |  13.579s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |  19.226s  |  19.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |  28.307s  |  28.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   2.684s  |   2.684s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |  13.851s  |  13.851s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   1.688s  |   1.688s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   2.485s  |   2.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                | 120.845s  | 120.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   3.392s  |   3.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  34.666s  |  34.666s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |  10.935s  |  10.935s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   5.250s  |   5.250s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   3.675s  |   3.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  33.000s  |  33.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   1.215s  |   1.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   5.671s  |   5.671s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   1.509s  |   1.509s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |  24.237s  |  24.237s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   3.247s  |   3.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   1.800s  |   1.800s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   2.599s  |   2.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   2.904s  |   2.904s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   1.992s  |   1.992s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   0.648s  |   0.648s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   0.642s  |   0.642s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   4.279s  |   4.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |  12.296s  |  12.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   1.979s  |   1.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   1.555s  |   1.555s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   1.311s  |   1.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   1.079s  |   1.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   1.242s  |   1.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   4.301s  |   4.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   4.477s  |   4.477s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  22.611s  |  22.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |  19.650s  |  19.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |  10.409s  |  10.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  78.552s  |  78.552s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   0.543s  |   0.543s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |  13.263s  |  13.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   1.902s  |   1.902s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |  10.724s  |  10.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   2.704s  |   2.704s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  61.940s  |  61.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |  12.199s  |  12.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   3.918s  |   3.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   2.727s  |   2.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  31.067s  |  31.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   1.921s  |   1.921s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   2.285s  |   2.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   2.455s  |   2.455s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |  21.591s  |  21.591s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   3.438s  |   3.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   4.874s  |   4.874s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   1.671s  |   1.671s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  12.124s  |  12.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  12.245s  |  12.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   3.001s  |   3.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   1.605s  |   1.605s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   2.971s  |   2.971s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   3.871s  |   3.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   2.522s  |   2.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   0.745s  |   0.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                | 158.992s  | 158.992s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |  13.604s  |  13.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  35.560s  |  35.560s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   1.200s  |   1.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |  83.339s  |  83.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  76.561s  |  76.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   1.104s  |   1.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   2.484s  |   2.484s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   9.338s  |   9.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   2.093s  |   2.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   3.432s  |   3.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   2.561s  |   2.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  22.797s  |  22.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   1.114s  |   1.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |  10.386s  |  10.386s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   0.827s  |   0.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   2.954s  |   2.954s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   1.601s  |   1.601s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   1.989s  |   1.989s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |  16.436s  |  16.436s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   1.723s  |   1.723s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |  12.688s  |  12.688s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   3.992s  |   3.992s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   1.977s  |   1.977s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   2.580s  |   2.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   4.103s  |   4.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   1.729s  |   1.729s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   2.465s  |   2.465s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   2.492s  |   2.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   3.073s  |   3.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   6.364s  |   6.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   4.611s  |   4.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |   3.355s  |   3.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   2.504s  |   2.504s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   2.224s  |   2.224s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   6.800s  |   6.800s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   2.118s  |   2.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          | 159.572s  | 159.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          | 160.249s  | 160.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          | 149.855s  | 149.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   7.983s  |   7.983s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   4.261s  |   4.261s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             | 108.909s  | 108.909s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            | 104.206s  | 104.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            |  94.323s  |  94.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   2.727s  |   2.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   3.612s  |   3.612s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   0.940s  |   0.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   7.784s  |   7.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |  27.329s  |  27.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   2.209s  |   2.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |  96.901s  |  96.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   7.918s  |   7.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      | 125.456s  | 125.456s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   2.780s  |   2.780s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   9.038s  |   9.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   6.357s  |   6.357s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   2.590s  |   2.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       | 143.663s  | 143.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   4.833s  |   4.833s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   4.762s  |   4.762s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   2.169s  |   2.169s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   | 117.887s  | 117.887s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |   6.485s  |   6.485s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |  18.238s  |  18.238s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |  17.888s  |  17.888s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.545s  |   0.545s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |  33.309s  |  33.309s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |  27.334s  |  27.334s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   5.374s  |   5.374s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   5.311s  |   5.311s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          | 165.442s  | 165.442s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          | 178.367s  | 178.367s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   1.646s  |   1.646s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   0.921s  |   0.921s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               | 165.279s  | 165.279s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               | 174.418s  | 174.418s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  49.898s  |  49.898s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               | 128.499s  | 128.499s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               | 181.856s  | 181.856s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   3.725s  |   3.725s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         | 122.428s  | 122.428s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         | 145.431s  | 145.431s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         | 145.769s  | 145.769s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |   4.833s  |   4.833s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               | 190.480s  | 190.480s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               | 148.157s  | 148.157s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   5.676s  |   5.676s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         | 218.791s  | 218.791s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         | 167.892s  | 167.892s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |   2.176s  |   2.176s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         |  60.086s  |  60.086s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  32.081s  |  32.081s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  74.393s  |  74.393s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    | 198.018s  | 198.018s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  63.305s  |  63.305s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    | 190.014s  | 190.014s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  17.833s  |  17.833s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  20.528s  |  20.528s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   4.446s  |   4.446s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              |  60.218s  |  60.218s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  89.975s  |  89.975s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   4.281s  |   4.281s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   4.368s  |   4.368s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  11.133s  |  11.133s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |   3.349s  |   3.349s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |   2.814s  |   2.814s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   4.787s  |   4.787s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   5.303s  |   5.303s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |   3.623s  |   3.623s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   4.313s  |   4.313s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  | 182.886s  | 182.886s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   1.351s  |   1.351s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  12.173s  |  12.173s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |   6.964s  |   6.964s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 | 141.350s  | 141.350s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  19.471s  |  19.471s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           | 164.036s  | 164.036s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |   4.917s  |   4.917s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |  20.310s  |  20.310s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              | 159.520s  | 159.520s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   7.159s  |   7.159s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              | 119.806s  | 119.806s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              | 120.198s  | 120.198s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  57.597s  |  57.597s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              | 145.137s  | 145.137s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              | 123.734s  | 123.734s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |  75.376s  |  75.376s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              | 127.228s  | 127.228s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              |  78.052s  |  78.052s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |  79.742s  |  79.742s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  97.775s  |  97.775s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |   4.183s  |   4.183s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      | 179.614s  | 179.614s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     | 181.223s  | 181.223s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  78.503s  |  78.503s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  31.339s  |  31.339s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  72.570s  |  72.570s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            | 110.898s  | 110.898s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   6.638s  |   6.638s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             | 192.381s  | 192.381s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   1.756s  |   1.756s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             | 157.341s  | 157.341s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             | 191.108s  | 191.108s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   3.803s  |   3.803s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             | 187.482s  | 187.482s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             | 136.916s  | 136.916s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   1.850s  |   1.850s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 | 174.288s  | 174.288s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   1.149s  |   1.149s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  | 178.732s  | 178.732s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |  51.115s  |  51.115s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   8.029s  |   8.029s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             | 162.470s  | 162.470s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   1.018s  |   1.018s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   4.122s  |   4.122s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |  25.165s  |  25.165s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |  23.599s  |  23.599s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   1.239s  |   1.239s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             |  65.035s  |  65.035s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   1.804s  |   1.804s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   3.068s  |   3.068s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   1.377s  |   1.377s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   2.373s  |   2.373s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   0.461s  |   0.461s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |  16.639s  |  16.639s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   1.194s  |   1.194s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   8.399s  |   8.399s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               |  60.311s  |  60.311s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   4.598s  |   4.598s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            | 154.952s  | 154.952s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   2.488s  |   2.488s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 | 169.625s  | 169.625s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |   7.556s  |   7.556s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  70.463s  |  70.463s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |  16.473s  |  16.473s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           | 189.767s  | 189.767s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |   6.598s  |   6.598s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |  14.811s  |  14.811s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 | 205.242s  | 205.242s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      | 162.274s  | 162.274s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |   4.687s  |   4.687s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |   5.052s  |   5.052s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           | 181.116s  | 181.116s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  44.197s  |  44.197s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |   5.403s  |   5.403s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  36.115s  |  36.115s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              | 110.193s  | 110.193s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |   7.321s  |   7.321s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   3.826s  |   3.826s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   1.053s  |   1.053s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      | 179.804s  | 179.804s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               | 103.120s  | 103.120s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              | 176.001s  | 176.001s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   1.293s  |   1.293s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       | 205.431s  | 205.431s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |   9.486s  |   9.486s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   1.603s  |   1.603s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       | 156.183s  | 156.183s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   1.906s  |   1.906s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       |  69.529s  |  69.529s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |  44.746s  |  44.746s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       | 181.265s  | 181.265s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   2.039s  |   2.039s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |   2.553s  |   2.553s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |  13.976s  |  13.976s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       | 188.707s  | 188.707s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |   3.861s  |   3.861s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       | 179.690s  | 179.690s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |  24.229s  |  24.229s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   2.053s  |   2.053s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       |  44.555s  |  44.555s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |  15.511s  |  15.511s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   1.124s  |   1.124s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   2.766s  |   2.766s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       |  66.411s  |  66.411s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       | 195.181s  | 195.181s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   4.255s  |   4.255s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       | 150.971s  | 150.971s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   2.640s  |   2.640s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   1.492s  |   1.492s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               |  62.173s  |  62.173s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         |  70.180s  |  70.180s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   5.650s  |   5.650s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   2.617s  |   2.617s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   2.458s  |   2.458s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 | 143.002s  | 143.002s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   1.125s  |   1.125s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |  17.126s  |  17.126s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |  21.795s  |  21.795s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |  16.296s  |  16.296s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   4.994s  |   4.994s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   7.671s  |   7.671s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                | 135.831s  | 135.831s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   1.768s  |   1.768s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   8.609s  |   8.609s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                | 181.055s  | 181.055s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   1.243s  |   1.243s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   2.961s  |   2.961s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   1.242s  |   1.242s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      | 186.581s  | 186.581s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   0.773s  |   0.773s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |   1.845s  |   1.845s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   4.820s  |   4.820s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   2.063s  |   2.063s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   0.613s  |   0.613s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   0.745s  |   0.745s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   2.436s  |   2.436s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   1.081s  |   1.081s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   0.946s  |   0.946s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |   2.046s  |   2.046s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   1.747s  |   1.747s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      |  68.206s  |  68.206s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      | 175.576s  | 175.576s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   1.419s  |   1.419s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   6.591s  |   6.591s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   5.005s  |   5.005s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   0.656s  |   0.656s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   1.273s  |   1.273s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   2.606s  |   2.606s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   0.844s  |   0.844s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   1.839s  |   1.839s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   7.443s  |   7.443s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |  23.479s  |  23.479s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      | 154.305s  | 154.305s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   3.932s  |   3.932s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   5.979s  |   5.979s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   0.984s  |   0.984s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   3.795s  |   3.795s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   1.849s  |   1.849s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |  12.856s  |  12.856s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   2.357s  |   2.357s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      | 113.232s  | 113.232s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   0.870s  |   0.870s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   1.648s  |   1.648s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   1.380s  |   1.380s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      | 152.978s  | 152.978s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      | 136.459s  | 136.459s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   1.462s  |   1.462s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |   2.559s  |   2.559s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   3.384s  |   3.384s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      | 148.699s  | 148.699s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   1.350s  |   1.350s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   1.156s  |   1.156s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |   8.026s  |   8.026s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |   5.219s  |   5.219s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   6.984s  |   6.984s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.809s  |   0.809s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   8.256s  |   8.256s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   2.893s  |   2.893s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   4.218s  |   4.218s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   0.779s  |   0.779s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   0.685s  |   0.685s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   6.367s  |   6.367s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   2.085s  |   2.085s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   1.077s  |   1.077s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   1.068s  |   1.068s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   2.135s  |   2.135s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   1.369s  |   1.369s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   2.650s  |   2.650s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   2.167s  |   2.167s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   0.613s  |   0.613s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   1.061s  |   1.061s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   4.565s  |   4.565s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   3.127s  |   3.127s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   1.766s  |   1.766s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |  31.236s  |  31.236s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            | 135.170s  | 135.170s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |   6.497s  |   6.497s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  75.973s  |  75.973s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |  32.985s  |  32.985s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  37.780s  |  37.780s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        | 129.887s  | 129.887s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        |  76.942s  |  76.942s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  43.442s  |  43.442s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       | 186.700s  | 186.700s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   4.382s  |   4.382s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   4.675s  |   4.675s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     |  77.104s  |  77.104s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     |  79.743s  |  79.743s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     |  92.563s  |  92.563s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |  21.574s  |  21.574s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         | 210.524s  | 210.524s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               |  93.500s  |  93.500s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         | 215.801s  | 215.801s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               | 209.063s  | 209.063s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   6.574s  |   6.574s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |  24.093s  |  24.093s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               | 214.660s  | 214.660s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  | 128.195s  | 128.195s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |  18.206s  |  18.206s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     | 111.189s  | 111.189s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  47.545s  |  47.545s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  21.975s  |  21.975s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            | 177.239s  | 177.239s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            | 180.287s  | 180.287s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   4.877s  |   4.877s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   1.389s  |   1.389s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                |  67.354s  |  67.354s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   1.590s  |   1.590s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  53.588s  |  53.588s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 |  60.292s  |  60.292s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 | 104.681s  | 104.681s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  78.956s  |  78.956s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 | 183.894s  | 183.894s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  30.565s  |  30.565s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |  27.282s  |  27.282s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           | 162.065s  | 162.065s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           | 184.203s  | 184.203s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           | 167.879s  | 167.879s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |  37.474s  |  37.474s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  | 108.478s  | 108.478s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |  43.963s  |  43.963s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   2.258s  |   2.258s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  68.450s  |  68.450s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 | 204.108s  | 204.108s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  45.780s  |  45.780s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 | 201.018s  | 201.018s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   2.619s  |   2.619s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 | 169.378s  | 169.378s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 | 187.011s  | 187.011s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |   1.373s  |   1.373s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  46.051s  |  46.051s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 | 140.594s  | 140.594s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   3.514s  |   3.514s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 | 120.675s  | 120.675s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |   2.467s  |   2.467s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |   4.623s  |   4.623s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 | 146.162s  | 146.162s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   7.131s  |   7.131s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   7.708s  |   7.708s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 | 149.334s  | 149.334s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  59.337s  |  59.337s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |   9.965s  |   9.965s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 | 168.228s  | 168.228s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 | 141.574s  | 141.574s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   4.811s  |   4.811s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |   9.210s  |   9.210s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 | 191.888s  | 191.888s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   8.035s  |   8.035s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 | 142.297s  | 142.297s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   1.768s  |   1.768s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 | 158.237s  | 158.237s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |   5.377s  |   5.377s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |  70.494s  |  70.494s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   9.472s  |   9.472s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   0.690s  |   0.690s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              | 185.483s  | 185.483s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  23.614s  |  23.614s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 | 121.533s  | 121.533s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 | 136.155s  | 136.155s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 | 149.691s  | 149.691s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  30.500s  |  30.500s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        | 192.079s  | 192.079s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  81.113s  |  81.113s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  68.993s  |  68.993s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |  55.702s  |  55.702s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           | 205.602s  | 205.602s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    | 195.012s  | 195.012s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    | 165.506s  | 165.506s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       | 138.629s  | 138.629s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       |  99.847s  |  99.847s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  37.269s  |  37.269s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       | 140.938s  | 140.938s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |  14.930s  |  14.930s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              | 188.446s  | 188.446s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  88.264s  |  88.264s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  21.363s  |  21.363s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  73.651s  |  73.651s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  74.113s  |  74.113s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  33.536s  |  33.536s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  | 162.778s  | 162.778s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  80.257s  |  80.257s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  56.423s  |  56.423s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   7.434s  |   7.434s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     | 134.327s  | 134.327s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |  58.076s  |  58.076s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  98.762s  |  98.762s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            | 181.780s  | 181.780s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          | 198.861s  | 198.861s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  58.588s  |  58.588s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  52.795s  |  52.795s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  54.651s  |  54.651s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               | 103.919s  | 103.919s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   1.577s  |   1.577s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   3.321s  |   3.321s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        |  38.795s  |  38.795s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        | 129.421s  | 129.421s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        | 175.923s  | 175.923s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        | 108.946s  | 108.946s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        | 108.824s  | 108.824s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        | 183.933s  | 183.933s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        |  17.414s  |  17.414s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        | 150.562s  | 150.562s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        | 168.236s  | 168.236s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  | 120.901s  | 120.901s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   1.386s  |   1.386s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |  30.273s  |  30.273s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   1.074s  |   1.074s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   9.663s  |   9.663s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  19.358s  |  19.358s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 | 168.874s  | 168.874s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   6.026s  |   6.026s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 | 153.861s  | 153.861s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 | 173.692s  | 173.692s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |  18.734s  |  18.734s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 | 171.557s  | 171.557s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 | 175.696s  | 175.696s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |  32.663s  |  32.663s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   3.300s  |   3.300s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   7.469s  |   7.469s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |  32.562s  |  32.562s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |  16.810s  |  16.810s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             | 146.605s  | 146.605s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             |  96.298s  |  96.298s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |  10.075s  |  10.075s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             | 116.348s  | 116.348s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             | 187.651s  | 187.651s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             | 175.194s  | 175.194s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             | 141.476s  | 141.476s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |  10.541s  |  10.541s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             | 106.546s  | 106.546s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             | 209.074s  | 209.074s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   5.448s  |   5.448s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             | 170.053s  | 170.053s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             | 114.486s  | 114.486s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   6.774s  |   6.774s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   7.298s  |   7.298s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  | 173.726s  | 173.726s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   1.463s  |   1.463s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                | 119.277s  | 119.277s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   1.426s  |   1.426s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  15.623s  |  15.623s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           | 188.812s  | 188.812s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 |  72.955s  |  72.955s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   3.445s  |   3.445s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 |  73.019s  |  73.019s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 |  72.110s  |  72.110s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   3.909s  |   3.909s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 | 106.912s  | 106.912s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 |  63.805s  |  63.805s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   6.732s  |   6.732s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           | 131.736s  | 131.736s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |  18.926s  |  18.926s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 | 130.900s  | 130.900s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 |  83.323s  |  83.323s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           | 184.862s  | 184.862s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  | 193.673s  | 193.673s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |  18.772s  |  18.772s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 | 182.968s  | 182.968s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 | 202.642s  | 202.642s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   2.537s  |   2.537s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   6.462s  |   6.462s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |   8.955s  |   8.955s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 |  76.493s  |  76.493s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   5.147s  |   5.147s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 | 192.527s  | 192.527s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 |  60.019s  |  60.019s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   6.673s  |   6.673s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 | 100.558s  | 100.558s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   7.715s  |   7.715s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   6.496s  |   6.496s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  | 119.743s  | 119.743s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   3.610s  |   3.610s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |   6.396s  |   6.396s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            |  21.317s  |  21.317s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            | 147.569s  | 147.569s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   1.048s  |   1.048s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  |  64.250s  |  64.250s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   4.199s  |   4.199s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  | 171.700s  | 171.700s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  |  33.118s  |  33.118s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            | 175.170s  | 175.170s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 | 139.822s  | 139.822s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |  49.960s  |  49.960s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  |  82.512s  |  82.512s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  | 105.639s  | 105.639s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  | 101.736s  | 101.736s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   6.323s  |   6.323s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  | 160.991s  | 160.991s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  | 100.632s  | 100.632s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |  12.093s  |  12.093s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  | 110.634s  | 110.634s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  | 172.871s  | 172.871s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.706s  |   0.706s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |  70.875s  |  70.875s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            |  94.072s  |  94.072s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   4.370s  |   4.370s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |  38.008s  |  38.008s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   1.856s  |   1.856s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           | 135.183s  | 135.183s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           | 182.225s  | 182.225s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           | 199.284s  | 199.284s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  64.343s  |  64.343s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               |  50.031s  |  50.031s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               | 176.342s  | 176.342s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               | 151.577s  | 151.577s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               | 133.306s  | 133.306s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               | 188.649s  | 188.649s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |  44.191s  |  44.191s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |  63.890s  |  63.890s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  89.350s  |  89.350s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |  23.871s  |  23.871s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   6.761s  |   6.761s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   4.791s  |   4.791s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             | 129.773s  | 129.773s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |  14.641s  |  14.641s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   1.740s  |   1.740s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |   4.578s  |   4.578s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |  16.236s  |  16.236s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   6.900s  |   6.900s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  74.810s  |  74.810s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  67.903s  |  67.903s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            | 174.340s  | 174.340s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    | 209.299s  | 209.299s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   4.192s  |   4.192s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               | 210.937s  | 210.937s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             | 185.401s  | 185.401s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             | 105.562s  | 105.562s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             | 194.152s  | 194.152s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   7.437s  |   7.437s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             | 174.046s  | 174.046s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             | 182.153s  | 182.153s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   5.637s  |   5.637s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             | 200.553s  | 200.553s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             | 167.755s  | 167.755s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  59.352s  |  59.352s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |  10.354s  |  10.354s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               | 193.429s  | 193.429s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         |  60.351s  |  60.351s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  13.332s  |  13.332s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  12.307s  |  12.307s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  25.849s  |  25.849s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  35.088s  |  35.088s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  53.658s  |  53.658s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        | 198.907s  | 198.907s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   1.578s  |   1.578s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            | 182.261s  | 182.261s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            |  57.628s  |  57.628s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   4.352s  |   4.352s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |  45.186s  |  45.186s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   0.827s  |   0.827s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            |  32.529s  |  32.529s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   1.289s  |   1.289s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  84.355s  |  84.355s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              | 181.317s  | 181.317s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  37.968s  |  37.968s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              |  20.170s  |  20.170s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   3.293s  |   3.293s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  37.406s  |  37.406s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          | 174.713s  | 174.713s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   2.105s  |   2.105s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |  37.471s  |  37.471s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  37.005s  |  37.005s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       | 153.618s  | 153.618s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   1.926s  |   1.926s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       | 112.982s  | 112.982s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   6.791s  |   6.791s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  12.773s  |  12.773s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |  29.426s  |  29.426s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         | 179.835s  | 179.835s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |  27.957s  |  27.957s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           | 161.173s  | 161.173s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |  15.536s  |  15.536s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  |  69.835s  |  69.835s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            |  80.850s  |  80.850s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              |  12.409s  |  12.409s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   1.731s  |   1.731s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   0.728s  |   0.728s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |  22.537s  |  22.537s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          | 178.403s  | 178.403s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          | 197.368s  | 197.368s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |  37.740s  |  37.740s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          | 164.857s  | 164.857s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          | 193.279s  | 193.279s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |  41.331s  |  41.331s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          | 179.659s  | 179.659s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          | 197.071s  | 197.071s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |  38.671s  |  38.671s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                | 133.085s  | 133.085s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                | 201.663s  | 201.663s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |  19.088s  |  19.088s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                | 173.541s  | 173.541s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                | 205.410s  | 205.410s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |  19.308s  |  19.308s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                | 157.814s  | 157.814s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                | 219.418s  | 219.418s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |  26.408s  |  26.408s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                | 173.152s  | 173.152s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                | 183.603s  | 183.603s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          | 119.191s  | 119.191s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |  36.241s  |  36.241s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          | 139.421s  | 139.421s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   3.716s  |   3.716s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |   8.482s  |   8.482s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          | 190.606s  | 190.606s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |  41.971s  |  41.971s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                | 156.349s  | 156.349s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   2.487s  |   2.487s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   2.943s  |   2.943s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |  12.833s  |  12.833s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   4.288s  |   4.288s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   4.401s  |   4.401s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |   4.148s  |   4.148s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |  16.118s  |  16.118s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                |  66.591s  |  66.591s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.837s  |   0.837s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |  19.133s  |  19.133s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                |  81.186s  |  81.186s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                |  14.672s  |  14.672s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |   5.313s  |   5.313s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |   5.705s  |   5.705s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   5.817s  |   5.817s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                |  71.288s  |  71.288s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   6.457s  |   6.457s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   5.257s  |   5.257s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   5.847s  |   5.847s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                | 184.589s  | 184.589s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   4.470s  |   4.470s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |  15.684s  |  15.684s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   2.169s  |   2.169s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |  18.050s  |  18.050s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   7.386s  |   7.386s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |  18.837s  |  18.837s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   7.190s  |   7.190s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                | 116.354s  | 116.354s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   6.642s  |   6.642s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   1.102s  |   1.102s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |  18.194s  |  18.194s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                | 184.111s  | 184.111s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                | 192.555s  | 192.555s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |  14.567s  |  14.567s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   7.944s  |   7.944s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   2.634s  |   2.634s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   2.126s  |   2.126s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |  16.212s  |  16.212s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          | 105.801s  | 105.801s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          | 187.705s  | 187.705s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   0.586s  |   0.586s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   1.850s  |   1.850s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |   5.830s  |   5.830s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   4.256s  |   4.256s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |   6.506s  |   6.506s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |  55.780s  |  55.780s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   5.663s  |   5.663s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   5.038s  |   5.038s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   2.852s  |   2.852s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |  12.844s  |  12.844s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          | 100.495s  | 100.495s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   4.624s  |   4.624s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   5.912s  |   5.912s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   6.691s  |   6.691s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   6.536s  |   6.536s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   7.029s  |   7.029s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |  17.153s  |  17.153s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   5.062s  |   5.062s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |  13.567s  |  13.567s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          | 112.272s  | 112.272s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          |  67.930s  |  67.930s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          |  93.687s  |  93.687s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          |  91.052s  |  91.052s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |  17.809s  |  17.809s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   1.518s  |   1.518s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          |  13.018s  |  13.018s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  46.093s  |  46.093s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     | 138.915s  | 138.915s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |  14.828s  |  14.828s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           | 103.463s  | 103.463s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           | 199.105s  | 199.105s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   2.155s  |   2.155s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  | 152.735s  | 152.735s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   2.644s  |   2.644s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   1.975s  |   1.975s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        | 198.125s  | 198.125s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   1.536s  |   1.536s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |  12.795s  |  12.795s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |   7.601s  |   7.601s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   6.600s  |   6.600s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |   6.474s  |   6.474s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   3.783s  |   3.783s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |  15.448s  |  15.448s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        | 211.261s  | 211.261s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   1.201s  |   1.201s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |  25.002s  |  25.002s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |  21.472s  |  21.472s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   2.587s  |   2.587s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |  13.841s  |  13.841s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |   6.846s  |   6.846s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   4.322s  |   4.322s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |  20.989s  |  20.989s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   4.871s  |   4.871s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   5.806s  |   5.806s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |  19.410s  |  19.410s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        | 110.427s  | 110.427s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   1.451s  |   1.451s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   2.799s  |   2.799s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   5.364s  |   5.364s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   4.087s  |   4.087s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |   2.842s  |   2.842s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        | 183.317s  | 183.317s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   5.153s  |   5.153s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        |  65.583s  |  65.583s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  14.914s  |  14.914s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   6.459s  |   6.459s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   1.177s  |   1.177s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   4.552s  |   4.552s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        | 148.112s  | 148.112s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        |  73.609s  |  73.609s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   2.107s  |   2.107s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |  33.361s  |  33.361s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        |  26.477s  |  26.477s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            | 159.385s  | 159.385s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            | 194.516s  | 194.516s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  |  99.663s  |  99.663s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  | 126.179s  | 126.179s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |  13.322s  |  13.322s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  |  86.330s  |  86.330s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  |  66.895s  |  66.895s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   4.253s  |   4.253s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   7.459s  |   7.459s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   5.664s  |   5.664s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   3.365s  |   3.365s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  |  93.843s  |  93.843s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |  13.321s  |  13.321s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   3.216s  |   3.216s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  | 193.667s  | 193.667s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  |  95.328s  |  95.328s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   3.316s  |   3.316s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |  13.907s  |  13.907s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                | 173.229s  | 173.229s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  66.631s  |  66.631s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |  17.960s  |  17.960s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              | 153.377s  | 153.377s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        | 176.970s  | 176.970s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   | 182.008s  | 182.008s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   | 190.996s  | 190.996s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   3.121s  |   3.121s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   | 170.454s  | 170.454s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   | 177.428s  | 177.428s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |  52.430s  |  52.430s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   | 198.227s  | 198.227s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   | 203.247s  | 203.247s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |  18.409s  |  18.409s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   | 155.517s  | 155.517s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         | 128.921s  | 128.921s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   1.678s  |   1.678s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   1.268s  |   1.268s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |  11.569s  |  11.569s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         | 196.962s  | 196.962s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   3.061s  |   3.061s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        | 178.219s  | 178.219s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        | 184.393s  | 184.393s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   5.227s  |   5.227s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        | 185.878s  | 185.878s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        | 156.920s  | 156.920s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |  18.021s  |  18.021s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        | 181.718s  | 181.718s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   4.032s  |   4.032s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   1.022s  |   1.022s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   2.588s  |   2.588s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  | 192.694s  | 192.694s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   2.061s  |   2.061s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   1.983s  |   1.983s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |  39.606s  |  39.606s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  24.749s  |  24.749s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |  63.519s  |  63.519s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |   4.471s  |   4.471s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            | 194.307s  | 194.307s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            | 192.845s  | 192.845s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |  16.973s  |  16.973s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            | 177.042s  | 177.042s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            | 170.922s  | 170.922s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |  15.028s  |  15.028s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            | 203.468s  | 203.468s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  | 193.896s  | 193.896s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   2.528s  |   2.528s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  | 183.067s  | 183.067s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   1.337s  |   1.337s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            | 190.822s  | 190.822s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  26.812s  |  26.812s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  69.442s  |  69.442s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  40.823s  |  40.823s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  43.246s  |  43.246s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   4.924s  |   4.924s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         | 175.291s  | 175.291s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |  25.577s  |  25.577s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         | 181.891s  | 181.891s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   1.693s  |   1.693s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         |  14.067s  |  14.067s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |   3.799s  |   3.799s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |   2.284s  |   2.284s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   7.611s  |   7.611s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   0.896s  |   0.896s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         | 144.489s  | 144.489s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   2.669s  |   2.669s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   5.496s  |   5.496s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   5.098s  |   5.098s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   0.918s  |   0.918s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   1.424s  |   1.424s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   1.491s  |   1.491s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   2.338s  |   2.338s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   1.582s  |   1.582s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   |  99.956s  |  99.956s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           |   8.627s  |   8.627s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           | 190.365s  | 190.365s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           | 165.513s  | 165.513s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   1.227s  |   1.227s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |  39.889s  |  39.889s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           |  13.014s  |  13.014s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           | 106.847s  | 106.847s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           | 153.593s  | 153.593s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  | 162.645s  | 162.645s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   1.428s  |   1.428s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   1.201s  |   1.201s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   1.484s  |   1.484s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   1.112s  |   1.112s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   2.067s  |   2.067s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             | 151.098s  | 151.098s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   0.767s  |   0.767s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   1.006s  |   1.006s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   4.558s  |   4.558s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   4.422s  |   4.422s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |  94.803s  |  94.803s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             | 145.743s  | 145.743s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             | 155.722s  | 155.722s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   3.545s  |   3.545s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |   7.303s  |   7.303s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             |  76.738s  |  76.738s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   1.514s  |   1.514s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   0.874s  |   0.874s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |  96.010s  |  96.010s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             |  68.279s  |  68.279s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   3.109s  |   3.109s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |  88.230s  |  88.230s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             |  82.649s  |  82.649s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   8.028s  |   8.028s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |  17.135s  |  17.135s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              | 191.691s  | 191.691s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      | 183.840s  | 183.840s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   2.390s  |   2.390s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          |  60.549s  |  60.549s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                | 208.232s  | 208.232s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |  73.533s  |  73.533s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |  50.827s  |  50.827s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                | 111.700s  | 111.700s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                | 144.608s  | 144.608s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  46.507s  |  46.507s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                | 122.236s  | 122.236s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                | 131.316s  | 131.316s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  64.851s  |  64.851s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  37.378s  |  37.378s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          | 188.640s  | 188.640s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |  53.301s  |  53.301s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   2.150s  |   2.150s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   2.207s  |   2.207s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              | 187.794s  | 187.794s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       | 207.728s  | 207.728s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       | 196.611s  | 196.611s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  30.178s  |  30.178s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  36.883s  |  36.883s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  66.272s  |  66.272s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           | 101.353s  | 101.353s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           | 161.324s  | 161.324s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  40.455s  |  40.455s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  12.076s  |  12.076s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   3.018s  |   3.018s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             | 209.038s  | 209.038s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  51.946s  |  51.946s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |  53.524s  |  53.524s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  45.327s  |  45.327s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  74.046s  |  74.046s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  74.798s  |  74.798s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |  47.634s  |  47.634s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  82.636s  |  82.636s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  41.486s  |  41.486s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           | 203.268s  | 203.268s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           | 197.777s  | 197.777s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           | 126.474s  | 126.474s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  37.981s  |  37.981s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 | 199.753s  | 199.753s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 | 206.484s  | 206.484s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |  14.201s  |  14.201s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |  52.202s  |  52.202s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                | 188.054s  | 188.054s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                | 174.522s  | 174.522s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  23.563s  |  23.563s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          | 122.850s  | 122.850s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          | 198.483s  | 198.483s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          | 207.474s  | 207.474s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          |  63.698s  |  63.698s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |   4.932s  |   4.932s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  51.068s  |  51.068s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     | 202.862s  | 202.862s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   1.518s  |   1.518s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                | 169.348s  | 169.348s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                |  88.700s  |  88.700s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   3.476s  |   3.476s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   1.599s  |   1.599s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            | 145.280s  | 145.280s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |  97.062s  |  97.062s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   2.131s  |   2.131s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  88.173s  |  88.173s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   4.465s  |   4.465s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |  80.267s  |  80.267s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            |  73.075s  |  73.075s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      | 190.767s  | 190.767s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   1.263s  |   1.263s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      |   6.203s  |   6.203s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   3.740s  |   3.740s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   0.738s  |   0.738s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  82.967s  |  82.967s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |  38.817s  |  38.817s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   1.752s  |   1.752s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  50.308s  |  50.308s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   3.286s  |   3.286s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |  23.078s  |  23.078s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |  74.719s  |  74.719s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  93.539s  |  93.539s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  17.019s  |  17.019s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |  17.259s  |  17.259s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  |  64.962s  |  64.962s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |  59.783s  |  59.783s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           | 189.879s  | 189.879s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      | 156.111s  | 156.111s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   7.712s  |   7.712s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      | 174.661s  | 174.661s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           | 115.233s  | 115.233s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           | 193.984s  | 193.984s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        | 121.181s  | 121.181s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   2.651s  |   2.651s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |  15.823s  |  15.823s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   1.697s  |   1.697s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |  85.516s  |  85.516s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.830s  |   0.830s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   3.671s  |   3.671s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   8.714s  |   8.714s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  21.847s  |  21.847s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   6.541s  |   6.541s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   2.249s  |   2.249s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        | 159.676s  | 159.676s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   0.861s  |   0.861s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   1.802s  |   1.802s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |   7.680s  |   7.680s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   3.617s  |   3.617s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |   7.041s  |   7.041s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   4.766s  |   4.766s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   2.520s  |   2.520s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   1.974s  |   1.974s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   2.460s  |   2.460s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           | 190.333s  | 190.333s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  74.403s  |  74.403s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |  15.030s  |  15.030s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   4.797s  |   4.797s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  74.259s  |  74.259s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            | 107.293s  | 107.293s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   3.138s  |   3.138s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |  93.296s  |  93.296s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   3.432s  |   3.432s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |   5.566s  |   5.566s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                | 154.677s  | 154.677s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                |  82.557s  |  82.557s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   0.986s  |   0.986s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          | 147.140s  | 147.140s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   3.326s  |   3.326s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   0.816s  |   0.816s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   0.832s  |   0.832s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   1.301s  |   1.301s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  13.526s  |  13.526s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           | 184.037s  | 184.037s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        | 186.628s  | 186.628s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  40.728s  |  40.728s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                |  78.779s  |  78.779s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |   2.171s  |   2.171s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   2.034s  |   2.034s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  41.952s  |  41.952s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   0.667s  |   0.667s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   7.531s  |   7.531s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  70.861s  |  70.861s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   7.331s  |   7.331s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   7.302s  |   7.302s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   4.292s  |   4.292s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   6.800s  |   6.800s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  66.056s  |  66.056s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       | 162.987s  | 162.987s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       | 182.939s  | 182.939s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   8.458s  |   8.458s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       | 151.958s  | 151.958s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       | 136.540s  | 136.540s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       | 124.785s  | 124.785s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       | 153.833s  | 153.833s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |  19.766s  |  19.766s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   1.442s  |   1.442s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   2.431s  |   2.431s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       | 168.063s  | 168.063s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   1.950s  |   1.950s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       |  76.516s  |  76.516s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     |  71.173s  |  71.173s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   3.861s  |   3.861s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                | 134.964s  | 134.964s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   4.026s  |   4.026s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   2.238s  |   2.238s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   | 120.394s  | 120.394s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   3.093s  |   3.093s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |  12.759s  |  12.759s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |  17.143s  |  17.143s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    | 101.187s  | 101.187s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        | 128.385s  | 128.385s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        | 177.376s  | 177.376s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  | 114.711s  | 114.711s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  | 134.131s  | 134.131s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  | 188.077s  | 188.077s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  71.638s  |  71.638s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |  68.556s  |  68.556s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   3.782s  |   3.782s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           | 132.109s  | 132.109s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           |  81.860s  |  81.860s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   1.343s  |   1.343s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   1.722s  |   1.722s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   9.013s  |   9.013s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   3.843s  |   3.843s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   6.928s  |   6.928s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           |  93.718s  |  93.718s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   2.258s  |   2.258s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           |  97.756s  |  97.756s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           | 151.109s  | 151.109s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   0.779s  |   0.779s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   1.488s  |   1.488s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   0.956s  |   0.956s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   6.190s  |   6.190s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   1.632s  |   1.632s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   7.652s  |   7.652s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   1.414s  |   1.414s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   1.701s  |   1.701s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |  58.813s  |  58.813s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   4.197s  |   4.197s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |  65.615s  |  65.615s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           |  65.667s  |  65.667s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   1.775s  |   1.775s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           | 151.410s  | 151.410s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   8.661s  |   8.661s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   8.019s  |   8.019s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   1.325s  |   1.325s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   8.336s  |   8.336s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |  60.176s  |  60.176s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   0.489s  |   0.489s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           | 143.424s  | 143.424s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   6.795s  |   6.795s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   7.126s  |   7.126s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   8.064s  |   8.064s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   6.847s  |   6.847s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   1.264s  |   1.264s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           | 144.689s  | 144.689s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   1.803s  |   1.803s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   8.234s  |   8.234s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   9.178s  |   9.178s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |  33.715s  |  33.715s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |   2.293s  |   2.293s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |  11.174s  |  11.174s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   1.056s  |   1.056s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  96.905s  |  96.905s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   3.032s  |   3.032s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |   7.074s  |   7.074s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |  12.619s  |  12.619s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            |  75.164s  |  75.164s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   4.252s  |   4.252s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           | 170.606s  | 170.606s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   4.322s  |   4.322s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   7.720s  |   7.720s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  85.767s  |  85.767s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           | 113.542s  | 113.542s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   4.656s  |   4.656s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   5.757s  |   5.757s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  65.030s  |  65.030s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   5.883s  |   5.883s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   1.209s  |   1.209s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   5.049s  |   5.049s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   2.802s  |   2.802s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   1.150s  |   1.150s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   2.549s  |   2.549s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |  48.534s  |  48.534s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   6.519s  |   6.519s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |  10.898s  |  10.898s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   2.171s  |   2.171s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   9.009s  |   9.009s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   3.944s  |   3.944s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           | 103.715s  | 103.715s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   1.938s  |   1.938s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   0.798s  |   0.798s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   8.288s  |   8.288s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           | 180.561s  | 180.561s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   1.267s  |   1.267s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   5.881s  |   5.881s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           | 127.714s  | 127.714s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   5.243s  |   5.243s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   8.384s  |   8.384s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   1.356s  |   1.356s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   6.853s  |   6.853s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   6.580s  |   6.580s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   8.525s  |   8.525s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   1.890s  |   1.890s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           | 126.182s  | 126.182s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  81.602s  |  81.602s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   1.240s  |   1.240s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   2.643s  |   2.643s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   8.021s  |   8.021s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   1.900s  |   1.900s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   6.435s  |   6.435s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   3.455s  |   3.455s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   8.457s  |   8.457s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |  94.365s  |  94.365s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |  13.170s  |  13.170s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.235s  |   1.235s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   0.619s  |   0.619s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   3.447s  |   3.447s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   5.824s  |   5.824s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            | 173.772s  | 173.772s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |  18.845s  |  18.845s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            | 138.507s  | 138.507s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            | 146.890s  | 146.890s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            | 142.578s  | 142.578s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            |  22.608s  |  22.608s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            | 184.954s  | 184.954s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.050s  |   0.050s  |   0.000s  | 0.0%|
</details>
