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
Job tag: add_zero_assump_reverted
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 7168589dd1d1880b2a3b302677b5830fd559f121
Z3 branch: 
Z3 options: "-st -T:600"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: revert the behavior of add_zero_assumption

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: add_zero_assump_reverted
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 7168589dd1d1880b2a3b302677b5830fd559f121
Z3 branch: 
Z3 options: "-st -T:600"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: revert the behavior of add_zero_assumption

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 598.249s  | 598.249s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 598.160s  | 598.160s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.891s  |   1.891s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.711s  | 598.711s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 598.249s  | 598.249s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 598.160s  | 598.160s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.891s  |   1.891s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.711s  | 598.711s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 598.249s  | 598.249s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 598.160s  | 598.160s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.891s  |   1.891s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.711s  | 598.711s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 598.249s  | 598.249s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 598.160s  | 598.160s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.891s  |   1.891s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.711s  | 598.711s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                    | 599.904s |252.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                              | 599.889s |393.0MiB|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                | 599.883s |493.0MiB|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                        | 599.875s |1064.0MiB|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                         | 599.859s |1274.0MiB|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                     | 599.851s |605.0MiB|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                 | 599.798s |230.0MiB|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                             | 599.794s |319.0MiB|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                     | 599.782s |401.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 599.768s |1753.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 599.764s |733.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 599.739s |760.0MiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                   | 599.730s |278.0MiB|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                           | 599.703s |481.0MiB|
|term-K5O3aH.smt2                                                                           | 599.675s |263.0MiB|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                 | 599.669s |272.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                      | 599.663s |690.0MiB|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                            | 599.657s |982.0MiB|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                     | 599.634s |367.0MiB|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                         | 599.631s |338.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                    | 599.904s |252.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                              | 599.889s |393.0MiB|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                | 599.883s |493.0MiB|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                        | 599.875s |1064.0MiB|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                         | 599.859s |1274.0MiB|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                     | 599.851s |605.0MiB|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                 | 599.798s |230.0MiB|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                             | 599.794s |319.0MiB|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                     | 599.782s |401.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 599.768s |1753.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 599.764s |733.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 599.739s |760.0MiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                   | 599.730s |278.0MiB|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                           | 599.703s |481.0MiB|
|term-K5O3aH.smt2                                                                           | 599.675s |263.0MiB|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                 | 599.669s |272.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                      | 599.663s |690.0MiB|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                            | 599.657s |982.0MiB|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                     | 599.634s |367.0MiB|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                         | 599.631s |338.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |94.34MiB|94.34MiB|0B| 0.0%|
|04.smt2                                                                                     |70.092MiB|70.092MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |30.864MiB|30.864MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.668MiB|30.668MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.744MiB|23.744MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.568MiB|23.568MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.392MiB|24.392MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.688MiB|24.688MiB|0B| 0.0%|
|107.smt2                                                                                    |22.276MiB|22.276MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.396MiB|27.396MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.316MiB|80.316MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.172MiB|23.172MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.012MiB|23.012MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.24MiB|23.24MiB|0B| 0.0%|
|11.smt2                                                                                     |73.348MiB|73.348MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.208MiB|24.208MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.188MiB|23.188MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.36MiB|23.36MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.236MiB|25.236MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |94.34MiB|94.34MiB|0B| 0.0%|
|04.smt2                                                                                     |70.092MiB|70.092MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |30.864MiB|30.864MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.668MiB|30.668MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.744MiB|23.744MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.568MiB|23.568MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.392MiB|24.392MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.688MiB|24.688MiB|0B| 0.0%|
|107.smt2                                                                                    |22.276MiB|22.276MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.396MiB|27.396MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.316MiB|80.316MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.172MiB|23.172MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.012MiB|23.012MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.24MiB|23.24MiB|0B| 0.0%|
|11.smt2                                                                                     |73.348MiB|73.348MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.208MiB|24.208MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.188MiB|23.188MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.36MiB|23.36MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.236MiB|25.236MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |94.34MiB|94.34MiB|0B| 0.0%|
|04.smt2                                                                                     |70.092MiB|70.092MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |30.864MiB|30.864MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.668MiB|30.668MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.744MiB|23.744MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.568MiB|23.568MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.392MiB|24.392MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.688MiB|24.688MiB|0B| 0.0%|
|107.smt2                                                                                    |22.276MiB|22.276MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.396MiB|27.396MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.316MiB|80.316MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.172MiB|23.172MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.012MiB|23.012MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.24MiB|23.24MiB|0B| 0.0%|
|11.smt2                                                                                     |73.348MiB|73.348MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.208MiB|24.208MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.188MiB|23.188MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.36MiB|23.36MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.236MiB|25.236MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |94.34MiB|94.34MiB|0B| 0.0%|
|04.smt2                                                                                     |70.092MiB|70.092MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |30.864MiB|30.864MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.668MiB|30.668MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.744MiB|23.744MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.568MiB|23.568MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.392MiB|24.392MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.688MiB|24.688MiB|0B| 0.0%|
|107.smt2                                                                                    |22.276MiB|22.276MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.396MiB|27.396MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.316MiB|80.316MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.172MiB|23.172MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.012MiB|23.012MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.24MiB|23.24MiB|0B| 0.0%|
|11.smt2                                                                                     |73.348MiB|73.348MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.208MiB|24.208MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.188MiB|23.188MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.36MiB|23.36MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.236MiB|25.236MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                               | 598.793s |3390.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 599.430s |3318.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              | 599.155s |3028.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 598.181s |2626.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 599.486s |2097.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                         | 598.697s |1878.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               | 596.440s |1809.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 599.768s |1753.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 597.997s |1747.0MiB|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                           | 598.840s |1716.0MiB|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                               | 599.073s |1667.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 599.351s |1638.0MiB|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                          | 599.027s |1635.0MiB|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                            | 593.960s |1598.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 458.196s |1596.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 598.326s |1588.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 598.355s |1582.0MiB|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                               | 597.611s |1523.0MiB|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                           | 597.842s |1466.0MiB|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                           | 597.781s |1448.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                               | 598.793s |3390.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 599.430s |3318.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              | 599.155s |3028.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 598.181s |2626.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 599.486s |2097.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                         | 598.697s |1878.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               | 596.440s |1809.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 599.768s |1753.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 597.997s |1747.0MiB|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                           | 598.840s |1716.0MiB|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                               | 599.073s |1667.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 599.351s |1638.0MiB|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                          | 599.027s |1635.0MiB|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                            | 593.960s |1598.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 458.196s |1596.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 598.326s |1588.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 598.355s |1582.0MiB|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                               | 597.611s |1523.0MiB|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                           | 597.842s |1466.0MiB|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                           | 597.781s |1448.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 598.249s  | 598.249s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 598.160s  | 598.160s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.891s  |   1.891s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.711s  | 598.711s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|124.smt2                                                                                    | 598.728s  | 598.728s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   1.170s  |   1.170s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|140.smt2                                                                                    | 599.210s  | 599.210s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   1.371s  |   1.371s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   1.235s  |   1.235s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.974s  |   0.974s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   1.793s  |   1.793s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   7.048s  |   7.048s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   3.086s  |   3.086s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   1.864s  |   1.864s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|177.smt2                                                                                    | 597.624s  | 597.624s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   1.113s  |   1.113s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   4.593s  |   4.593s  |   0.000s  | 0.0%|
|181.smt2                                                                                    | 598.690s  | 598.690s  |   0.000s  | 0.0%|
|182.smt2                                                                                    | 598.392s  | 598.392s  |   0.000s  | 0.0%|
|183.smt2                                                                                    | 598.091s  | 598.091s  |   0.000s  | 0.0%|
|185.smt2                                                                                    | 597.864s  | 597.864s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   1.891s  |   1.891s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   1.645s  |   1.645s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   1.422s  |   1.422s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   2.559s  |   2.559s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   3.285s  |   3.285s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   7.101s  |   7.101s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   7.458s  |   7.458s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   3.148s  |   3.148s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   3.209s  |   3.209s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   1.368s  |   1.368s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   1.924s  |   1.924s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   1.564s  |   1.564s  |   0.000s  | 0.0%|
|35.smt2                                                                                     | 599.247s  | 599.247s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|40.smt2                                                                                     | 598.065s  | 598.065s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   1.762s  |   1.762s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   1.370s  |   1.370s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|54.smt2                                                                                     | 598.506s  | 598.506s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   1.816s  |   1.816s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   3.053s  |   3.053s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   1.571s  |   1.571s  |   0.000s  | 0.0%|
|58.smt2                                                                                     | 598.513s  | 598.513s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   2.311s  |   2.311s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   3.119s  |   3.119s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   3.471s  |   3.471s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|65.smt2                                                                                     | 597.587s  | 597.587s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   1.237s  |   1.237s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   2.006s  |   2.006s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|73.smt2                                                                                     | 597.788s  | 597.788s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.961s  |   0.961s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   3.351s  |   3.351s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   1.112s  |   1.112s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   3.207s  |   3.207s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|966.smt2                                                                                    |   3.575s  |   3.575s  |   0.000s  | 0.0%|
|98.smt2                                                                                     | 598.650s  | 598.650s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|99.smt2                                                                                     | 599.042s  | 599.042s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  | 302.046s  | 302.046s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   4.377s  |   4.377s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          | 597.592s  | 597.592s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               | 506.602s  | 506.602s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   1.371s  |   1.371s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   1.700s  |   1.700s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          | 270.313s  | 270.313s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   9.173s  |   9.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   3.994s  |   3.994s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            | 598.179s  | 598.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   4.513s  |   4.513s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       | 482.197s  | 482.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   2.714s  |   2.714s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  69.561s  |  69.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   4.612s  |   4.612s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |  46.503s  |  46.503s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   1.470s  |   1.470s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   1.798s  |   1.798s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           | 599.245s  | 599.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           | 598.598s  | 598.598s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |  13.763s  |  13.763s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   5.438s  |   5.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  16.100s  |  16.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   4.265s  |   4.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |   9.946s  |   9.946s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         | 574.006s  | 574.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             | 416.861s  | 416.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |  43.505s  |  43.505s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  45.102s  |  45.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             | 599.151s  | 599.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 | 380.515s  | 380.515s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   2.611s  |   2.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   6.232s  |   6.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |  10.130s  |  10.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   2.518s  |   2.518s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              |  14.307s  |  14.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  | 109.376s  | 109.376s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   1.583s  |   1.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |  22.422s  |  22.422s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               |  12.872s  |  12.872s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         | 597.998s  | 597.998s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   8.319s  |   8.319s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |  14.814s  |  14.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |  98.252s  |  98.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 | 194.210s  | 194.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      | 598.133s  | 598.133s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   3.472s  |   3.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   4.197s  |   4.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              | 598.191s  | 598.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   3.453s  |   3.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   5.643s  |   5.643s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          | 598.912s  | 598.912s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   1.666s  |   1.666s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          | 323.130s  | 323.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   9.432s  |   9.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         | 123.027s  | 123.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   2.585s  |   2.585s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      | 598.197s  | 598.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |  11.462s  |  11.462s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   4.580s  |   4.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   5.004s  |   5.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         | 598.047s  | 598.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      | 599.851s  | 599.851s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               | 597.695s  | 597.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  47.412s  |  47.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |  41.541s  |  41.541s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   9.767s  |   9.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           | 598.263s  | 598.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               | 546.403s  | 546.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   2.445s  |   2.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               |  80.521s  |  80.521s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         | 132.305s  | 132.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   4.181s  |   4.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           | 135.410s  | 135.410s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |  16.005s  |  16.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   6.184s  |   6.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   | 599.021s  | 599.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   | 598.679s  | 598.679s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   | 598.638s  | 598.638s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             | 597.617s  | 597.617s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  17.476s  |  17.476s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   2.257s  |   2.257s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    | 598.563s  | 598.563s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |  37.303s  |  37.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        |  70.119s  |  70.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      | 105.412s  | 105.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  44.288s  |  44.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     | 598.713s  | 598.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               | 598.051s  | 598.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               | 597.823s  | 597.823s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   4.567s  |   4.567s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   6.943s  |   6.943s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   3.733s  |   3.733s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |  49.905s  |  49.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               | 598.297s  | 598.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   1.049s  |   1.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   4.119s  |   4.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   4.022s  |   4.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   5.919s  |   5.919s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   3.465s  |   3.465s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |  12.611s  |  12.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                | 599.080s  | 599.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   1.230s  |   1.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              | 597.220s  | 597.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |  40.934s  |  40.934s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   2.371s  |   2.371s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   9.799s  |   9.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  51.432s  |  51.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  81.583s  |  81.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   4.424s  |   4.424s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  31.760s  |  31.760s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          |  54.558s  |  54.558s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          | 598.626s  | 598.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          | 599.859s  | 599.859s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |   2.754s  |   2.754s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          | 599.539s  | 599.539s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          | 599.197s  | 599.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  84.358s  |  84.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   3.669s  |   3.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  13.663s  |  13.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   3.620s  |   3.620s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    | 598.178s  | 598.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   4.484s  |   4.484s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   2.166s  |   2.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    | 598.521s  | 598.521s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   4.379s  |   4.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   3.892s  |   3.892s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |  41.132s  |  41.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |  23.815s  |  23.815s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        | 598.537s  | 598.537s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |   5.492s  |   5.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |  15.654s  |  15.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   6.318s  |   6.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        |  96.116s  |  96.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   1.379s  |   1.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  34.113s  |  34.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   | 117.886s  | 117.886s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  52.130s  |  52.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  81.558s  |  81.558s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  97.051s  |  97.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              |  94.942s  |  94.942s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  27.251s  |  27.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  | 210.678s  | 210.678s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  |  53.827s  |  53.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |  85.773s  |  85.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |  47.218s  |  47.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   2.982s  |   2.982s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.797s  |   0.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              | 597.301s  | 597.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   3.311s  |   3.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |  57.732s  |  57.732s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |  10.786s  |  10.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   4.422s  |   4.422s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  34.464s  |  34.464s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        | 598.407s  | 598.407s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.685s  |   0.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   2.796s  |   2.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             | 428.338s  | 428.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |  11.296s  |  11.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   | 598.852s  | 598.852s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   | 598.426s  | 598.426s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     | 598.249s  | 598.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   5.316s  |   5.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   2.605s  |   2.605s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   2.651s  |   2.651s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     | 598.873s  | 598.873s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 | 598.507s  | 598.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                | 599.127s  | 599.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   2.975s  |   2.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                | 598.764s  | 598.764s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      | 597.705s  | 597.705s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   9.519s  |   9.519s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      | 597.271s  | 597.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      | 598.589s  | 598.589s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   7.412s  |   7.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      | 437.315s  | 437.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |   2.791s  |   2.791s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   0.987s  |   0.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   3.116s  |   3.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   4.827s  |   4.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   3.758s  |   3.758s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |  28.968s  |  28.968s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   6.674s  |   6.674s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |  38.433s  |  38.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  25.131s  |  25.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             | 596.810s  | 596.810s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   5.510s  |   5.510s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          | 598.797s  | 598.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               | 589.272s  | 589.272s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                | 274.314s  | 274.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   5.681s  |   5.681s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |   9.436s  |   9.436s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   3.066s  |   3.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   4.106s  |   4.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   3.741s  |   3.741s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   6.544s  |   6.544s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   1.007s  |   1.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              | 599.094s  | 599.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   7.334s  |   7.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   5.211s  |   5.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   6.539s  |   6.539s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   4.551s  |   4.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  37.351s  |  37.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          | 599.631s  | 599.631s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |   6.222s  |   6.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          | 598.716s  | 598.716s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          | 598.854s  | 598.854s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |  10.779s  |  10.779s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          | 598.411s  | 598.411s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          | 598.436s  | 598.436s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |  11.990s  |  11.990s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          | 598.656s  | 598.656s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   6.389s  |   6.389s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            | 598.470s  | 598.470s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   4.380s  |   4.380s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |   8.948s  |   8.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 | 128.870s  | 128.870s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            | 599.421s  | 599.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   7.396s  |   7.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |   7.686s  |   7.686s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   2.291s  |   2.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   3.408s  |   3.408s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   0.821s  |   0.821s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   3.141s  |   3.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |   6.496s  |   6.496s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   3.103s  |   3.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   2.748s  |   2.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           | 597.834s  | 597.834s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           | 598.805s  | 598.805s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           | 598.568s  | 598.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           | 597.530s  | 597.530s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   2.815s  |   2.815s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   1.342s  |   1.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           | 597.775s  | 597.775s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   2.373s  |   2.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   2.279s  |   2.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   4.595s  |   4.595s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |  22.712s  |  22.712s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   2.239s  |   2.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           | 599.027s  | 599.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   2.250s  |   2.250s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   1.423s  |   1.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           | 598.461s  | 598.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  50.440s  |  50.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           | 598.317s  | 598.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |  13.495s  |  13.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |   9.040s  |   9.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           | 596.823s  | 596.823s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |   1.273s  |   1.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   2.386s  |   2.386s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |  37.247s  |  37.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   2.186s  |   2.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  30.235s  |  30.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   2.256s  |   2.256s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   6.008s  |   6.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   3.377s  |   3.377s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |  15.620s  |  15.620s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   2.176s  |   2.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |  46.315s  |  46.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   2.197s  |   2.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           | 598.122s  | 598.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  47.960s  |  47.960s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           | 598.442s  | 598.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   2.188s  |   2.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           | 598.420s  | 598.420s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     | 597.737s  | 597.737s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   2.108s  |   2.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   2.181s  |   2.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     | 598.103s  | 598.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   1.970s  |   1.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |   9.065s  |   9.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |  76.327s  |  76.327s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   2.151s  |   2.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |  10.052s  |  10.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     | 598.109s  | 598.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |   1.822s  |   1.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     | 598.868s  | 598.868s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |   8.691s  |   8.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   1.364s  |   1.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   1.607s  |   1.607s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   6.997s  |   6.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   2.841s  |   2.841s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   3.621s  |   3.621s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   2.367s  |   2.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   2.588s  |   2.588s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   5.962s  |   5.962s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   5.403s  |   5.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     | 599.175s  | 599.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     | 597.771s  | 597.771s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |  10.089s  |  10.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   1.229s  |   1.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   3.215s  |   3.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |   1.680s  |   1.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               | 599.596s  | 599.596s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     | 598.381s  | 598.381s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   2.706s  |   2.706s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     | 598.013s  | 598.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |   0.903s  |   0.903s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |   4.434s  |   4.434s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   2.221s  |   2.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   9.244s  |   9.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |  11.972s  |  11.972s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   2.218s  |   2.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   0.734s  |   0.734s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     | 455.969s  | 455.969s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   1.954s  |   1.954s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     | 597.952s  | 597.952s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     | 263.778s  | 263.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     | 598.427s  | 598.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  36.963s  |  36.963s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   5.924s  |   5.924s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               | 597.303s  | 597.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   1.433s  |   1.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   2.262s  |   2.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               | 598.454s  | 598.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               | 597.677s  | 597.677s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |  12.606s  |  12.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   7.959s  |   7.959s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |   4.592s  |   4.592s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               | 598.146s  | 598.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               | 598.940s  | 598.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |  53.380s  |  53.380s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               | 598.455s  | 598.455s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               | 598.315s  | 598.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               | 598.713s  | 598.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               | 599.033s  | 599.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |  83.018s  |  83.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   2.664s  |   2.664s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   1.092s  |   1.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  33.253s  |  33.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               |  55.161s  |  55.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   2.260s  |   2.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               | 598.360s  | 598.360s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   8.608s  |   8.608s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   2.369s  |   2.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               | 598.008s  | 598.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               | 599.288s  | 599.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               | 598.051s  | 598.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   2.955s  |   2.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               | 599.124s  | 599.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   1.193s  |   1.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   1.745s  |   1.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               | 597.280s  | 597.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   6.756s  |   6.756s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   2.253s  |   2.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   3.166s  |   3.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               | 597.831s  | 597.831s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   1.122s  |   1.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               | 598.337s  | 598.337s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               | 597.840s  | 597.840s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   2.654s  |   2.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |   7.717s  |   7.717s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |   9.014s  |   9.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               | 272.355s  | 272.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   5.246s  |   5.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |  16.859s  |  16.859s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |   1.104s  |   1.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   0.783s  |   0.783s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             | 598.631s  | 598.631s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             | 597.938s  | 597.938s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |   7.453s  |   7.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   2.351s  |   2.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   9.555s  |   9.555s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   9.403s  |   9.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   2.182s  |   2.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   2.422s  |   2.422s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |  25.525s  |  25.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             | 598.183s  | 598.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |  22.740s  |  22.740s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   2.971s  |   2.971s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             | 598.857s  | 598.857s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             | 119.479s  | 119.479s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |   1.499s  |   1.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   5.453s  |   5.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   2.212s  |   2.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             | 599.545s  | 599.545s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   2.267s  |   2.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             | 598.404s  | 598.404s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |  79.429s  |  79.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |   2.425s  |   2.425s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             | 596.594s  | 596.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |   7.194s  |   7.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   1.291s  |   1.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |   6.575s  |   6.575s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |  13.206s  |  13.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             | 597.829s  | 597.829s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   5.628s  |   5.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   0.572s  |   0.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             | 598.021s  | 598.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             | 158.494s  | 158.494s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             | 598.903s  | 598.903s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   1.088s  |   1.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             | 587.603s  | 587.603s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             | 598.157s  | 598.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |  15.008s  |  15.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |  32.768s  |  32.768s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               | 599.594s  | 599.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |  10.440s  |  10.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |   8.797s  |   8.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         | 597.983s  | 597.983s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        | 598.757s  | 598.757s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              | 109.864s  | 109.864s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   2.155s  |   2.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |   1.243s  |   1.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   1.197s  |   1.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    | 598.023s  | 598.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    | 599.730s  | 599.730s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |  11.850s  |  11.850s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   2.169s  |   2.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   2.506s  |   2.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   9.273s  |   9.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |  24.725s  |  24.725s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    | 598.424s  | 598.424s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   2.188s  |   2.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    | 599.242s  | 599.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   5.284s  |   5.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   2.172s  |   2.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   2.548s  |   2.548s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    | 598.409s  | 598.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    | 598.192s  | 598.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    | 598.092s  | 598.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   2.373s  |   2.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |  31.742s  |  31.742s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    | 591.690s  | 591.690s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   8.956s  |   8.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    | 599.528s  | 599.528s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |  80.272s  |  80.272s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    | 597.472s  | 597.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   1.010s  |   1.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    | 184.583s  | 184.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  34.995s  |  34.995s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |  63.837s  |  63.837s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   2.474s  |   2.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    | 598.433s  | 598.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    | 598.163s  | 598.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    | 596.457s  | 596.457s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   2.138s  |   2.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    | 597.495s  | 597.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   3.453s  |   3.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    | 597.476s  | 597.476s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |   5.439s  |   5.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   7.784s  |   7.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   2.343s  |   2.343s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   6.390s  |   6.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |   6.304s  |   6.304s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   1.214s  |   1.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   2.151s  |   2.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |  17.010s  |  17.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   2.365s  |   2.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          | 598.572s  | 598.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   2.585s  |   2.585s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          | 598.824s  | 598.824s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   8.806s  |   8.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |   8.649s  |   8.649s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |  14.669s  |  14.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          | 591.611s  | 591.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          | 597.692s  | 597.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          | 598.828s  | 598.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   1.075s  |   1.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          | 598.273s  | 598.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   8.576s  |   8.576s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |  10.673s  |  10.673s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   2.351s  |   2.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   2.208s  |   2.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          | 598.413s  | 598.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          | 596.496s  | 596.496s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   1.585s  |   1.585s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   2.651s  |   2.651s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          | 598.674s  | 598.674s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   6.284s  |   6.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   2.272s  |   2.272s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   6.144s  |   6.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        | 598.224s  | 598.224s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   7.800s  |   7.800s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        | 598.256s  | 598.256s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   0.843s  |   0.843s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |   7.023s  |   7.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        | 116.207s  | 116.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |  36.953s  |  36.953s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        | 597.294s  | 597.294s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |   9.023s  |   9.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |   7.728s  |   7.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   2.670s  |   2.670s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |   2.041s  |   2.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   1.188s  |   1.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |   6.526s  |   6.526s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   6.986s  |   6.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.489s  |   0.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |   6.543s  |   6.543s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   1.495s  |   1.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |   4.051s  |   4.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   2.566s  |   2.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   7.290s  |   7.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |   4.078s  |   4.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   2.369s  |   2.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        | 599.245s  | 599.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   2.238s  |   2.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |  11.281s  |  11.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        | 598.390s  | 598.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        | 598.898s  | 598.898s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   2.318s  |   2.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |  13.183s  |  13.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   2.240s  |   2.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        | 598.134s  | 598.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |  10.067s  |  10.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        | 598.538s  | 598.538s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |   9.296s  |   9.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   2.401s  |   2.401s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        | 598.647s  | 598.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        | 443.803s  | 443.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |  18.071s  |  18.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        | 598.618s  | 598.618s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        | 598.040s  | 598.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   5.364s  |   5.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  | 598.230s  | 598.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.565s  |   0.565s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   2.126s  |   2.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   5.909s  |   5.909s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   6.577s  |   6.577s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |  23.432s  |  23.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |   9.457s  |   9.457s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   8.853s  |   8.853s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |  52.423s  |  52.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   1.285s  |   1.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     |   8.375s  |   8.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  10.051s  |  10.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   0.604s  |   0.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   2.121s  |   2.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   3.753s  |   3.753s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     | 599.049s  | 599.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     | 599.328s  | 599.328s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     | 599.014s  | 599.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   3.087s  |   3.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |  19.046s  |  19.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   0.546s  |   0.546s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       | 599.663s  | 599.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |   6.996s  |   6.996s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |  10.542s  |  10.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   2.989s  |   2.989s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       | 598.063s  | 598.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       | 129.262s  | 129.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       | 597.329s  | 597.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   4.116s  |   4.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       | 597.747s  | 597.747s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   2.437s  |   2.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   3.213s  |   3.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   2.217s  |   2.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   2.551s  |   2.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       | 598.350s  | 598.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       | 598.338s  | 598.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |  55.092s  |  55.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   2.455s  |   2.455s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   1.365s  |   1.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   2.599s  |   2.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   0.566s  |   0.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       | 597.980s  | 597.980s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       | 598.695s  | 598.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |  16.384s  |  16.384s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 | 598.553s  | 598.553s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  24.768s  |  24.768s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |  21.412s  |  21.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  48.131s  |  48.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |  10.223s  |  10.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |  10.908s  |  10.908s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  19.129s  |  19.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   1.414s  |   1.414s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  11.742s  |  11.742s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  58.155s  |  58.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   8.977s  |   8.977s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            | 126.906s  | 126.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  18.316s  |  18.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   1.828s  |   1.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |  38.286s  |  38.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            | 598.238s  | 598.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   6.519s  |   6.519s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   3.440s  |   3.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   4.948s  |   4.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   6.142s  |   6.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   3.153s  |   3.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   2.452s  |   2.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   3.001s  |   3.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |  22.092s  |  22.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   8.513s  |   8.513s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   4.545s  |   4.545s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   6.824s  |   6.824s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   1.402s  |   1.402s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |  10.147s  |  10.147s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   2.730s  |   2.730s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   4.750s  |   4.750s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   6.225s  |   6.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   8.164s  |   8.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |  18.451s  |  18.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |  14.296s  |  14.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |  30.006s  |  30.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   1.467s  |   1.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   1.867s  |   1.867s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   3.328s  |   3.328s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   3.766s  |   3.766s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   5.419s  |   5.419s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  16.778s  |  16.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   9.038s  |   9.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  15.379s  |  15.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |   3.115s  |   3.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   3.911s  |   3.911s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   9.629s  |   9.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  22.435s  |  22.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   3.581s  |   3.581s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   4.584s  |   4.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                | 141.316s  | 141.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   4.282s  |   4.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   2.369s  |   2.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   1.863s  |   1.863s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   6.157s  |   6.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   2.451s  |   2.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   9.412s  |   9.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   1.273s  |   1.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   2.326s  |   2.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   2.974s  |   2.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   8.508s  |   8.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |  11.615s  |  11.615s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   6.429s  |   6.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   3.494s  |   3.494s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   3.609s  |   3.609s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   4.074s  |   4.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   2.847s  |   2.847s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   2.205s  |   2.205s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  18.012s  |  18.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   3.208s  |   3.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   2.523s  |   2.523s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  26.539s  |  26.539s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   0.940s  |   0.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |  15.929s  |  15.929s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   2.724s  |   2.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   9.344s  |   9.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   3.096s  |   3.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  28.364s  |  28.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |  11.142s  |  11.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   1.915s  |   1.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   1.926s  |   1.926s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  70.535s  |  70.535s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   3.713s  |   3.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   1.789s  |   1.789s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   6.182s  |   6.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   7.719s  |   7.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |  10.102s  |  10.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   5.439s  |   5.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   3.065s  |   3.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   4.662s  |   4.662s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  11.412s  |  11.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  13.160s  |  13.160s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   7.524s  |   7.524s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   3.249s  |   3.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   9.353s  |   9.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   2.559s  |   2.559s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   3.308s  |   3.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   2.431s  |   2.431s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                | 131.468s  | 131.468s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |  13.958s  |  13.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  18.880s  |  18.880s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   1.752s  |   1.752s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                | 598.284s  | 598.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  81.704s  |  81.704s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   1.642s  |   1.642s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   2.354s  |   2.354s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   1.822s  |   1.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   3.169s  |   3.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   2.622s  |   2.622s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  56.859s  |  56.859s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   3.100s  |   3.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |  12.627s  |  12.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   2.485s  |   2.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   2.915s  |   2.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   4.161s  |   4.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   2.366s  |   2.366s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |   3.112s  |   3.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   3.593s  |   3.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |   9.837s  |   9.837s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |  67.738s  |  67.738s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   4.980s  |   4.980s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   3.321s  |   3.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   3.629s  |   3.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   1.941s  |   1.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   5.383s  |   5.383s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |  10.290s  |  10.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   3.324s  |   3.324s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   4.120s  |   4.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   2.001s  |   2.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |  34.232s  |  34.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   8.053s  |   8.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   1.892s  |   1.892s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   8.197s  |   8.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   7.449s  |   7.449s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          | 560.895s  | 560.895s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          | 323.664s  | 323.664s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          | 597.616s  | 597.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   5.219s  |   5.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   5.711s  |   5.711s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             | 599.058s  | 599.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            | 598.109s  | 598.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            | 597.605s  | 597.605s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   3.335s  |   3.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   5.394s  |   5.394s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   1.727s  |   1.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   5.172s  |   5.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |  20.196s  |  20.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   6.156s  |   6.156s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |  58.192s  |  58.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   4.031s  |   4.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      | 598.241s  | 598.241s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   6.621s  |   6.621s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   8.785s  |   8.785s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |  12.758s  |  12.758s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   3.365s  |   3.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       |  63.211s  |  63.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   9.797s  |   9.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   2.742s  |   2.742s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   1.165s  |   1.165s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   6.236s  |   6.236s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   | 599.161s  | 599.161s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |  15.410s  |  15.410s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |   3.338s  |   3.338s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |   8.858s  |   8.858s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.835s  |   0.835s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |  43.298s  |  43.298s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |  49.788s  |  49.788s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |  11.636s  |  11.636s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   4.198s  |   4.198s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          | 598.579s  | 598.579s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          | 598.867s  | 598.867s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   2.335s  |   2.335s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   1.230s  |   1.230s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               | 201.209s  | 201.209s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               | 597.567s  | 597.567s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  18.139s  |  18.139s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               | 596.877s  | 596.877s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               | 597.286s  | 597.286s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |  11.021s  |  11.021s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         | 598.217s  | 598.217s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         | 599.875s  | 599.875s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         | 556.070s  | 556.070s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               | 597.815s  | 597.815s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               | 598.480s  | 598.480s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  75.113s  |  75.113s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   4.501s  |   4.501s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |   7.725s  |   7.725s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         | 599.274s  | 599.274s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |  43.617s  |  43.617s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.722s  |   0.722s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         | 597.292s  | 597.292s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  20.569s  |  20.569s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  76.648s  |  76.648s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    | 599.764s  | 599.764s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  42.296s  |  42.296s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    | 598.618s  | 598.618s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  18.594s  |  18.594s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  14.505s  |  14.505s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   2.531s  |   2.531s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              | 597.997s  | 597.997s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  87.298s  |  87.298s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   5.142s  |   5.142s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   5.761s  |   5.761s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  45.734s  |  45.734s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |   9.723s  |   9.723s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |   9.280s  |   9.280s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   6.519s  |   6.519s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   2.865s  |   2.865s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |   6.577s  |   6.577s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   7.731s  |   7.731s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  | 284.893s  | 284.893s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   2.789s  |   2.789s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  52.702s  |  52.702s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 | 599.000s  | 599.000s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 | 597.009s  | 597.009s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  18.930s  |  18.930s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           | 597.968s  | 597.968s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |  11.635s  |  11.635s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |  27.026s  |  27.026s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              | 598.403s  | 598.403s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   3.414s  |   3.414s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              | 598.362s  | 598.362s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              | 598.869s  | 598.869s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  19.934s  |  19.934s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              | 597.653s  | 597.653s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              | 597.773s  | 597.773s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |  23.695s  |  23.695s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              | 598.744s  | 598.744s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              | 598.374s  | 598.374s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   2.589s  |   2.589s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |  26.275s  |  26.275s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  71.026s  |  71.026s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |  20.128s  |  20.128s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      | 380.360s  | 380.360s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     | 168.800s  | 168.800s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  68.205s  |  68.205s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  44.894s  |  44.894s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  60.335s  |  60.335s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            |  47.171s  |  47.171s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             | 252.093s  | 252.093s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             | 599.236s  | 599.236s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   3.904s  |   3.904s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             | 597.939s  | 597.939s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             | 597.103s  | 597.103s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   1.808s  |   1.808s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             | 598.773s  | 598.773s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             | 599.106s  | 599.106s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   1.709s  |   1.709s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 | 598.621s  | 598.621s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.572s  |   0.572s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  | 597.621s  | 597.621s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |  35.899s  |  35.899s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   3.598s  |   3.598s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             | 596.814s  | 596.814s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   2.376s  |   2.376s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   5.584s  |   5.584s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |  12.787s  |  12.787s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   4.203s  |   4.203s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |   5.147s  |   5.147s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   2.516s  |   2.516s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             | 598.513s  | 598.513s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   3.001s  |   3.001s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   5.370s  |   5.370s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   3.900s  |   3.900s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   2.109s  |   2.109s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   0.978s  |   0.978s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |   9.770s  |   9.770s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   2.027s  |   2.027s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   4.191s  |   4.191s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               | 599.486s  | 599.486s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   3.106s  |   3.106s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            | 598.633s  | 598.633s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   1.999s  |   1.999s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 | 598.820s  | 598.820s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |  12.462s  |  12.462s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  29.121s  |  29.121s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |  11.903s  |  11.903s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           | 597.935s  | 597.935s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |  11.984s  |  11.984s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |  14.851s  |  14.851s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 | 597.227s  | 597.227s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      | 462.586s  | 462.586s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |  10.640s  |  10.640s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |  12.059s  |  12.059s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           | 597.456s  | 597.456s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  32.595s  |  32.595s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |  11.324s  |  11.324s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  44.930s  |  44.930s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              | 599.794s  | 599.794s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |   4.931s  |   4.931s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   5.084s  |   5.084s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   3.462s  |   3.462s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      | 381.015s  | 381.015s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               | 597.132s  | 597.132s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              | 598.201s  | 598.201s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   3.979s  |   3.979s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       | 597.561s  | 597.561s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |   4.400s  |   4.400s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   1.527s  |   1.527s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       | 169.295s  | 169.295s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   1.616s  |   1.616s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.767s  |   0.767s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       | 599.619s  | 599.619s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |  17.188s  |  17.188s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       | 232.825s  | 232.825s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   1.754s  |   1.754s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   4.133s  |   4.133s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       | 582.539s  | 582.539s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |  10.371s  |  10.371s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       | 598.882s  | 598.882s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |  10.004s  |  10.004s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       | 598.421s  | 598.421s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   8.672s  |   8.672s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   2.735s  |   2.735s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |   9.458s  |   9.458s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   1.104s  |   1.104s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   2.543s  |   2.543s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       |  81.540s  |  81.540s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       |  82.217s  |  82.217s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |  16.366s  |  16.366s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   2.305s  |   2.305s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       | 352.650s  | 352.650s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   3.535s  |   3.535s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   1.676s  |   1.676s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.957s  |   0.957s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               | 598.685s  | 598.685s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         | 335.351s  | 335.351s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   3.950s  |   3.950s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   8.025s  |   8.025s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   1.306s  |   1.306s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 | 598.128s  | 598.128s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   1.005s  |   1.005s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |  12.493s  |  12.493s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |   9.731s  |   9.731s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |  11.742s  |  11.742s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   7.874s  |   7.874s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   6.008s  |   6.008s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                | 598.759s  | 598.759s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   1.454s  |   1.454s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   5.452s  |   5.452s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                | 597.855s  | 597.855s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   4.466s  |   4.466s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |  16.719s  |  16.719s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   3.678s  |   3.678s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      | 599.782s  | 599.782s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   2.565s  |   2.565s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   3.900s  |   3.900s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |   7.283s  |   7.283s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   4.976s  |   4.976s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |  14.455s  |  14.455s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   1.399s  |   1.399s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   2.101s  |   2.101s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   1.256s  |   1.256s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   1.368s  |   1.368s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |  19.432s  |  19.432s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   4.115s  |   4.115s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   3.229s  |   3.229s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   1.327s  |   1.327s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |  11.300s  |  11.300s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   3.190s  |   3.190s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      | 597.256s  | 597.256s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   1.480s  |   1.480s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      | 599.634s  | 599.634s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   3.849s  |   3.849s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   7.780s  |   7.780s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   3.105s  |   3.105s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   1.233s  |   1.233s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   2.354s  |   2.354s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   8.932s  |   8.932s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   4.590s  |   4.590s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   3.259s  |   3.259s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   2.287s  |   2.287s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |   3.364s  |   3.364s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   1.972s  |   1.972s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      | 597.934s  | 597.934s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |  14.077s  |  14.077s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |  25.091s  |  25.091s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   3.150s  |   3.150s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   4.523s  |   4.523s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   3.665s  |   3.665s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   3.855s  |   3.855s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   9.862s  |   9.862s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |   9.166s  |   9.166s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   1.669s  |   1.669s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |  10.573s  |  10.573s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   1.865s  |   1.865s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      | 598.550s  | 598.550s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   1.891s  |   1.891s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      | 597.418s  | 597.418s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   3.450s  |   3.450s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   5.831s  |   5.831s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |  10.221s  |  10.221s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   2.563s  |   2.563s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      | 597.301s  | 597.301s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   3.358s  |   3.358s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   2.822s  |   2.822s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |  12.549s  |  12.549s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |   2.989s  |   2.989s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   5.480s  |   5.480s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.887s  |   0.887s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   4.082s  |   4.082s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   2.931s  |   2.931s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   7.168s  |   7.168s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   2.116s  |   2.116s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   3.759s  |   3.759s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   7.641s  |   7.641s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   8.479s  |   8.479s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   2.584s  |   2.584s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   2.763s  |   2.763s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   3.642s  |   3.642s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   3.526s  |   3.526s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   4.063s  |   4.063s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   9.440s  |   9.440s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   2.341s  |   2.341s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |  10.404s  |  10.404s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   5.406s  |   5.406s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   2.934s  |   2.934s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   6.657s  |   6.657s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |  18.199s  |  18.199s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   5.925s  |   5.925s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |  13.721s  |  13.721s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            | 598.743s  | 598.743s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |  11.773s  |  11.773s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  34.345s  |  34.345s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |  26.064s  |  26.064s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  32.574s  |  32.574s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |  44.120s  |  44.120s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        | 598.479s  | 598.479s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        | 458.196s  | 458.196s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  32.682s  |  32.682s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       |  89.627s  |  89.627s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   5.446s  |   5.446s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   7.492s  |   7.492s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     | 598.341s  | 598.341s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     | 598.418s  | 598.418s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     | 598.103s  | 598.103s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |  14.565s  |  14.565s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         | 597.128s  | 597.128s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               | 599.889s  | 599.889s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         | 597.396s  | 597.396s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               | 597.995s  | 597.995s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   2.779s  |   2.779s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |  17.862s  |  17.862s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               | 599.250s  | 599.250s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  | 598.983s  | 598.983s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |  24.326s  |  24.326s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     | 153.741s  | 153.741s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  53.653s  |  53.653s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  16.998s  |  16.998s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            | 244.159s  | 244.159s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            | 558.589s  | 558.589s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   4.093s  |   4.093s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                | 598.193s  | 598.193s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   3.580s  |   3.580s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  67.928s  |  67.928s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 | 569.521s  | 569.521s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 | 598.268s  | 598.268s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  47.253s  |  47.253s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 | 598.080s  | 598.080s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  35.908s  |  35.908s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |  15.651s  |  15.651s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           | 124.972s  | 124.972s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           | 599.027s  | 599.027s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           | 330.612s  | 330.612s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |  45.772s  |  45.772s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  49.802s  |  49.802s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 | 102.338s  | 102.338s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   7.410s  |   7.410s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  51.547s  |  51.547s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 | 597.355s  | 597.355s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  29.401s  |  29.401s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 | 435.624s  | 435.624s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   5.478s  |   5.478s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 | 505.077s  | 505.077s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 | 596.639s  | 596.639s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |  44.542s  |  44.542s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  40.507s  |  40.507s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 | 153.885s  | 153.885s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   6.799s  |   6.799s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 | 599.883s  | 599.883s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |  17.543s  |  17.543s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  12.593s  |  12.593s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |  74.335s  |  74.335s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   5.868s  |   5.868s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   9.665s  |   9.665s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 | 118.751s  | 118.751s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  66.794s  |  66.794s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |  10.917s  |  10.917s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 | 163.391s  | 163.391s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 | 360.766s  | 360.766s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |  14.097s  |  14.097s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |   5.676s  |   5.676s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 | 596.428s  | 596.428s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   3.514s  |   3.514s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 | 147.854s  | 147.854s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   3.190s  |   3.190s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |  88.616s  |  88.616s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |   6.282s  |   6.282s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |   9.708s  |   9.708s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   6.178s  |   6.178s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   3.117s  |   3.117s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              | 598.124s  | 598.124s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  22.010s  |  22.010s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 |  70.448s  |  70.448s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  70.636s  |  70.636s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 | 124.756s  | 124.756s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  18.657s  |  18.657s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        | 598.373s  | 598.373s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  47.889s  |  47.889s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  41.542s  |  41.542s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           | 100.208s  | 100.208s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           | 202.301s  | 202.301s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    | 598.156s  | 598.156s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    | 598.517s  | 598.517s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       |  43.591s  |  43.591s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       |  99.761s  |  99.761s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  41.073s  |  41.073s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  87.488s  |  87.488s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |   9.295s  |   9.295s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              | 599.579s  | 599.579s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  70.491s  |  70.491s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  17.381s  |  17.381s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  48.150s  |  48.150s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  79.522s  |  79.522s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  59.697s  |  59.697s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  | 598.077s  | 598.077s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  48.205s  |  48.205s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  41.182s  |  41.182s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   5.518s  |   5.518s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  77.513s  |  77.513s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |  65.524s  |  65.524s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  48.794s  |  48.794s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            | 599.125s  | 599.125s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          | 210.275s  | 210.275s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  53.396s  |  53.396s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  41.146s  |  41.146s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  56.826s  |  56.826s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  55.400s  |  55.400s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   3.654s  |   3.654s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |  12.643s  |  12.643s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        | 379.346s  | 379.346s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        | 594.443s  | 594.443s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        | 101.783s  | 101.783s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        | 597.534s  | 597.534s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        | 598.611s  | 598.611s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        | 438.719s  | 438.719s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        | 597.843s  | 597.843s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        | 597.378s  | 597.378s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        | 599.504s  | 599.504s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  | 598.586s  | 598.586s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   1.508s  |   1.508s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |  18.965s  |  18.965s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.821s  |   0.821s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   2.327s  |   2.327s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   6.141s  |   6.141s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  25.456s  |  25.456s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 | 599.458s  | 599.458s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   3.581s  |   3.581s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 | 597.777s  | 597.777s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 | 599.564s  | 599.564s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |  51.601s  |  51.601s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 | 597.251s  | 597.251s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 | 599.347s  | 599.347s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |  11.532s  |  11.532s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   5.787s  |   5.787s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   3.354s  |   3.354s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |  26.088s  |  26.088s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |  14.798s  |  14.798s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             | 267.449s  | 267.449s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             | 598.862s  | 598.862s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   6.222s  |   6.222s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             | 119.380s  | 119.380s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             | 597.707s  | 597.707s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   8.736s  |   8.736s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             | 151.724s  | 151.724s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             | 593.960s  | 593.960s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |   6.008s  |   6.008s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             | 275.378s  | 275.378s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             | 597.309s  | 597.309s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   3.339s  |   3.339s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             |  59.581s  |  59.581s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             | 599.426s  | 599.426s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |  28.116s  |  28.116s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   3.547s  |   3.547s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  | 185.947s  | 185.947s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   1.164s  |   1.164s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   6.145s  |   6.145s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                | 598.835s  | 598.835s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   1.006s  |   1.006s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  11.124s  |  11.124s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           | 599.009s  | 599.009s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 | 599.189s  | 599.189s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   2.906s  |   2.906s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 | 599.177s  | 599.177s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 | 598.854s  | 598.854s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   2.124s  |   2.124s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 | 597.917s  | 597.917s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 | 598.883s  | 598.883s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   2.260s  |   2.260s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           | 597.989s  | 597.989s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   6.406s  |   6.406s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 | 599.003s  | 599.003s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 | 597.543s  | 597.543s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           | 598.249s  | 598.249s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  | 598.747s  | 598.747s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |  11.650s  |  11.650s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 | 598.803s  | 598.803s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 | 598.081s  | 598.081s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   3.186s  |   3.186s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   3.313s  |   3.313s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |   6.019s  |   6.019s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 | 598.202s  | 598.202s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   3.715s  |   3.715s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 | 598.210s  | 598.210s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 | 595.680s  | 595.680s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   3.339s  |   3.339s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 | 597.320s  | 597.320s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   4.869s  |   4.869s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   5.560s  |   5.560s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  |  35.190s  |  35.190s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   9.655s  |   9.655s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |  13.269s  |  13.269s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            | 377.355s  | 377.355s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  28.131s  |  28.131s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   3.455s  |   3.455s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  | 598.995s  | 598.995s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   1.648s  |   1.648s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  | 396.066s  | 396.066s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  |  16.199s  |  16.199s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            | 597.605s  | 597.605s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   4.517s  |   4.517s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 | 599.054s  | 599.054s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |  19.402s  |  19.402s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  | 598.905s  | 598.905s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   4.505s  |   4.505s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  | 599.669s  | 599.669s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  | 599.521s  | 599.521s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   3.797s  |   3.797s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  | 598.134s  | 598.134s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  | 598.439s  | 598.439s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   7.999s  |   7.999s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  | 598.304s  | 598.304s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  | 598.071s  | 598.071s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |  14.638s  |  14.638s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            | 598.754s  | 598.754s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   2.992s  |   2.992s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |  15.570s  |  15.570s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   1.721s  |   1.721s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |  10.670s  |  10.670s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           | 599.422s  | 599.422s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           | 598.198s  | 598.198s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           | 598.523s  | 598.523s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  29.471s  |  29.471s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               | 167.864s  | 167.864s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               | 599.237s  | 599.237s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               | 264.643s  | 264.643s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               | 599.322s  | 599.322s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               | 599.076s  | 599.076s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |  66.734s  |  66.734s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   | 148.055s  | 148.055s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 | 124.515s  | 124.515s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |  14.934s  |  14.934s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   4.334s  |   4.334s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   2.116s  |   2.116s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             | 598.481s  | 598.481s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |   7.171s  |   7.171s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   4.221s  |   4.221s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |   9.335s  |   9.335s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |  11.635s  |  11.635s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   4.313s  |   4.313s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   5.172s  |   5.172s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  21.799s  |  21.799s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  69.628s  |  69.628s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            | 599.703s  | 599.703s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    | 597.902s  | 597.902s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   7.640s  |   7.640s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               | 598.081s  | 598.081s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             | 599.081s  | 599.081s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             | 597.600s  | 597.600s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             | 599.657s  | 599.657s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   4.495s  |   4.495s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             | 597.401s  | 597.401s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             | 596.720s  | 596.720s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   4.680s  |   4.680s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             | 597.107s  | 597.107s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             | 599.315s  | 599.315s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  25.944s  |  25.944s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |   8.914s  |   8.914s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               | 599.155s  | 599.155s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         | 598.355s  | 598.355s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  20.409s  |  20.409s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  20.284s  |  20.284s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  21.241s  |  21.241s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  18.979s  |  18.979s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  45.300s  |  45.300s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        | 598.287s  | 598.287s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   1.094s  |   1.094s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            | 598.385s  | 598.385s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            | 599.482s  | 599.482s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   6.890s  |   6.890s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |   6.210s  |   6.210s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   5.320s  |   5.320s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            | 368.769s  | 368.769s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   3.614s  |   3.614s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  17.353s  |  17.353s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              | 597.004s  | 597.004s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  15.194s  |  15.194s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              | 565.036s  | 565.036s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   2.173s  |   2.173s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  20.386s  |  20.386s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          | 599.245s  | 599.245s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   4.441s  |   4.441s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |  14.826s  |  14.826s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  20.320s  |  20.320s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       | 598.486s  | 598.486s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   3.795s  |   3.795s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       | 503.443s  | 503.443s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   4.302s  |   4.302s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  10.488s  |  10.488s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   7.072s  |   7.072s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         | 239.282s  | 239.282s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |  17.319s  |  17.319s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           | 599.178s  | 599.178s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |   8.641s  |   8.641s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  | 598.871s  | 598.871s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            | 597.439s  | 597.439s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              | 599.161s  | 599.161s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   4.581s  |   4.581s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   3.805s  |   3.805s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |   9.945s  |   9.945s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          | 596.969s  | 596.969s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          | 598.572s  | 598.572s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |  17.959s  |  17.959s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          | 598.804s  | 598.804s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          | 599.086s  | 599.086s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |  18.413s  |  18.413s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          | 598.697s  | 598.697s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          | 599.430s  | 599.430s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |  18.568s  |  18.568s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                | 598.793s  | 598.793s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                | 596.440s  | 596.440s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   2.954s  |   2.954s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                | 597.611s  | 597.611s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                | 598.326s  | 598.326s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |  22.467s  |  22.467s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                | 599.572s  | 599.572s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                | 597.500s  | 597.500s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |  16.171s  |  16.171s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                | 599.073s  | 599.073s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                | 599.351s  | 599.351s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          | 598.989s  | 598.989s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |  16.332s  |  16.332s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          | 598.274s  | 598.274s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   3.869s  |   3.869s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          | 140.281s  | 140.281s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          | 598.189s  | 598.189s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                | 366.998s  | 366.998s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                | 599.122s  | 599.122s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |  10.722s  |  10.722s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   8.024s  |   8.024s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |  14.205s  |  14.205s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   5.215s  |   5.215s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   5.373s  |   5.373s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |  42.880s  |  42.880s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |  26.208s  |  26.208s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   1.555s  |   1.555s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                | 598.646s  | 598.646s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |  20.763s  |  20.763s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                | 597.075s  | 597.075s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                |   8.716s  |   8.716s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |  30.435s  |  30.435s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |  54.471s  |  54.471s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   5.690s  |   5.690s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                | 598.452s  | 598.452s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   7.188s  |   7.188s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |  14.333s  |  14.333s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   1.630s  |   1.630s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                | 598.961s  | 598.961s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |  10.822s  |  10.822s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |  15.491s  |  15.491s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   3.143s  |   3.143s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |  19.247s  |  19.247s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   8.787s  |   8.787s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |  17.332s  |  17.332s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   6.735s  |   6.735s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                | 599.200s  | 599.200s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   2.813s  |   2.813s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   0.985s  |   0.985s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |  13.071s  |  13.071s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                | 598.955s  | 598.955s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                | 598.758s  | 598.758s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |  18.536s  |  18.536s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |  15.058s  |  15.058s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   7.628s  |   7.628s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |  37.764s  |  37.764s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          | 596.960s  | 596.960s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          | 598.209s  | 598.209s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   2.902s  |   2.902s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   3.852s  |   3.852s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |   2.948s  |   2.948s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   6.842s  |   6.842s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |  10.765s  |  10.765s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |  46.999s  |  46.999s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   2.801s  |   2.801s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   2.694s  |   2.694s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |  11.053s  |  11.053s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   8.345s  |   8.345s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          | 428.254s  | 428.254s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |  14.187s  |  14.187s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   1.911s  |   1.911s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   6.827s  |   6.827s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   7.597s  |   7.597s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   2.352s  |   2.352s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |   9.519s  |   9.519s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |  13.530s  |  13.530s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |  15.204s  |  15.204s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          | 598.179s  | 598.179s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          | 599.457s  | 599.457s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          | 597.556s  | 597.556s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          | 598.904s  | 598.904s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |  14.369s  |  14.369s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   2.271s  |   2.271s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          | 166.900s  | 166.900s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  60.874s  |  60.874s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |  75.380s  |  75.380s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |  27.732s  |  27.732s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           | 598.285s  | 598.285s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           | 597.694s  | 597.694s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   4.533s  |   4.533s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  | 144.068s  | 144.068s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   5.138s  |   5.138s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   1.735s  |   1.735s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        | 598.344s  | 598.344s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   4.592s  |   4.592s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |  10.986s  |  10.986s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |   2.037s  |   2.037s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   5.317s  |   5.317s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |  18.095s  |  18.095s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   0.874s  |   0.874s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |  30.662s  |  30.662s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        | 593.054s  | 593.054s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   0.614s  |   0.614s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |  13.688s  |  13.688s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |  61.135s  |  61.135s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |  13.625s  |  13.625s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |  25.223s  |  25.223s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |  14.874s  |  14.874s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   2.080s  |   2.080s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |  23.009s  |  23.009s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |  14.777s  |  14.777s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |  16.201s  |  16.201s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   2.443s  |   2.443s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        | 598.856s  | 598.856s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   3.285s  |   3.285s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   4.679s  |   4.679s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   3.148s  |   3.148s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |  11.759s  |  11.759s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |  37.267s  |  37.267s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        | 598.353s  | 598.353s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |  12.442s  |  12.442s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        | 598.851s  | 598.851s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  31.352s  |  31.352s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   2.564s  |   2.564s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.936s  |   0.936s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   4.556s  |   4.556s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        | 598.080s  | 598.080s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        | 598.487s  | 598.487s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   9.427s  |   9.427s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |  96.229s  |  96.229s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        | 150.646s  | 150.646s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            | 597.781s  | 597.781s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            | 347.445s  | 347.445s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  | 598.963s  | 598.963s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  | 596.511s  | 596.511s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |   9.670s  |   9.670s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  | 598.408s  | 598.408s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  | 586.465s  | 586.465s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   2.836s  |   2.836s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   1.260s  |   1.260s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   2.450s  |   2.450s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   2.295s  |   2.295s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   6.178s  |   6.178s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   1.088s  |   1.088s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  | 598.669s  | 598.669s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   1.151s  |   1.151s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |  19.607s  |  19.607s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   7.720s  |   7.720s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  | 596.708s  | 596.708s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  | 599.798s  | 599.798s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   1.575s  |   1.575s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |  10.151s  |  10.151s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                | 599.398s  | 599.398s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                | 128.297s  | 128.297s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   2.911s  |   2.911s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              |  90.301s  |  90.301s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        | 599.201s  | 599.201s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   | 597.948s  | 597.948s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   | 599.768s  | 599.768s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   7.985s  |   7.985s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   | 598.667s  | 598.667s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   | 597.821s  | 597.821s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |  21.730s  |  21.730s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   | 599.212s  | 599.212s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   | 598.359s  | 598.359s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |  21.283s  |  21.283s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   | 598.066s  | 598.066s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         | 387.695s  | 387.695s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   2.346s  |   2.346s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   3.262s  |   3.262s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |   8.114s  |   8.114s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         | 598.323s  | 598.323s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   7.259s  |   7.259s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        | 597.877s  | 597.877s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        | 597.776s  | 597.776s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   9.570s  |   9.570s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        | 598.398s  | 598.398s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        | 598.791s  | 598.791s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |   8.748s  |   8.748s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        | 598.513s  | 598.513s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   3.545s  |   3.545s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   2.619s  |   2.619s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   1.720s  |   1.720s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  54.869s  |  54.869s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   5.885s  |   5.885s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   3.014s  |   3.014s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |  32.911s  |  32.911s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  32.333s  |  32.333s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      | 119.545s  | 119.545s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |   3.015s  |   3.015s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            | 598.019s  | 598.019s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            | 598.840s  | 598.840s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |  11.674s  |  11.674s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            | 599.069s  | 599.069s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            | 597.842s  | 597.842s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   9.652s  |   9.652s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            | 598.529s  | 598.529s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  | 597.400s  | 597.400s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   5.064s  |   5.064s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  | 598.206s  | 598.206s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   2.548s  |   2.548s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            | 596.810s  | 596.810s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  34.604s  |  34.604s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  40.488s  |  40.488s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  46.723s  |  46.723s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  71.772s  |  71.772s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   9.742s  |   9.742s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         | 598.621s  | 598.621s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   | 459.593s  | 459.593s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         | 597.325s  | 597.325s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   1.762s  |   1.762s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         |  17.567s  |  17.567s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |  27.312s  |  27.312s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |  23.670s  |  23.670s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   5.413s  |   5.413s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   3.208s  |   3.208s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         | 598.963s  | 598.963s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |  10.369s  |  10.369s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   6.347s  |   6.347s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   5.635s  |   5.635s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   3.215s  |   3.215s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   4.212s  |   4.212s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   6.215s  |   6.215s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |  11.470s  |  11.470s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   3.006s  |   3.006s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   | 597.746s  | 597.746s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           |   7.178s  |   7.178s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           | 598.700s  | 598.700s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           | 599.305s  | 599.305s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   4.292s  |   4.292s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |  67.119s  |  67.119s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           | 129.631s  | 129.631s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           |  13.855s  |  13.855s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           |  44.921s  |  44.921s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   1.122s  |   1.122s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  | 597.750s  | 597.750s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   2.476s  |   2.476s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   3.701s  |   3.701s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   3.221s  |   3.221s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   3.268s  |   3.268s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   2.492s  |   2.492s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   4.264s  |   4.264s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             | 597.578s  | 597.578s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   3.103s  |   3.103s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   3.008s  |   3.008s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   4.855s  |   4.855s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   3.301s  |   3.301s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |  24.566s  |  24.566s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             | 598.394s  | 598.394s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   2.082s  |   2.082s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             | 107.733s  | 107.733s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   5.589s  |   5.589s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |   4.054s  |   4.054s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             | 599.336s  | 599.336s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   4.912s  |   4.912s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |  21.898s  |  21.898s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             | 597.641s  | 597.641s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   3.632s  |   3.632s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             | 100.354s  | 100.354s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             | 599.253s  | 599.253s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   5.323s  |   5.323s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |  29.771s  |  29.771s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              | 598.572s  | 598.572s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      | 599.070s  | 599.070s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   4.442s  |   4.442s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          | 598.181s  | 598.181s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                | 598.866s  | 598.866s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |  47.235s  |  47.235s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                | 103.950s  | 103.950s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                | 598.353s  | 598.353s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                | 597.314s  | 597.314s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  44.947s  |  44.947s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                | 599.608s  | 599.608s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                | 598.885s  | 598.885s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  20.877s  |  20.877s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  62.940s  |  62.940s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          | 599.345s  | 599.345s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |  31.093s  |  31.093s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   4.549s  |   4.549s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   3.528s  |   3.528s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              | 598.882s  | 598.882s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       | 598.189s  | 598.189s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       | 598.776s  | 598.776s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  14.211s  |  14.211s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  26.621s  |  26.621s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  51.470s  |  51.470s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  82.170s  |  82.170s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           | 121.415s  | 121.415s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  51.629s  |  51.629s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  11.867s  |  11.867s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   8.670s  |   8.670s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             | 598.469s  | 598.469s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  65.321s  |  65.321s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 | 103.080s  | 103.080s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  33.271s  |  33.271s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  72.986s  |  72.986s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  32.069s  |  32.069s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |  62.487s  |  62.487s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  38.172s  |  38.172s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  52.791s  |  52.791s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           | 598.317s  | 598.317s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           | 599.739s  | 599.739s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |  79.076s  |  79.076s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  19.921s  |  19.921s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 | 597.535s  | 597.535s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 | 597.301s  | 597.301s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   9.749s  |   9.749s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |  30.200s  |  30.200s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                | 598.540s  | 598.540s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                | 518.267s  | 518.267s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  96.670s  |  96.670s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          | 144.040s  | 144.040s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          | 598.903s  | 598.903s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          | 599.063s  | 599.063s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          | 598.418s  | 598.418s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |  14.688s  |  14.688s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  13.951s  |  13.951s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     | 599.904s  | 599.904s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   2.254s  |   2.254s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                |  87.825s  |  87.825s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                | 598.344s  | 598.344s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   2.440s  |   2.440s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   5.212s  |   5.212s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            | 596.897s  | 596.897s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |  39.194s  |  39.194s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   5.798s  |   5.798s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  38.393s  |  38.393s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   3.504s  |   3.504s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |   3.231s  |   3.231s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   1.553s  |   1.553s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   1.402s  |   1.402s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |  26.658s  |  26.658s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            | 598.317s  | 598.317s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      | 598.864s  | 598.864s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   2.017s  |   2.017s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   1.315s  |   1.315s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      |  41.673s  |  41.673s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   1.809s  |   1.809s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   2.358s  |   2.358s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   2.343s  |   2.343s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  60.675s  |  60.675s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 | 112.574s  | 112.574s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   3.555s  |   3.555s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  34.612s  |  34.612s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   4.907s  |   4.907s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |  98.876s  |  98.876s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |  15.415s  |  15.415s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   2.380s  |   2.380s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           | 596.824s  | 596.824s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  13.471s  |  13.471s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       | 104.997s  | 104.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  | 596.642s  | 596.642s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  | 132.634s  | 132.634s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           | 571.317s  | 571.317s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      | 597.755s  | 597.755s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   4.133s  |   4.133s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      | 598.288s  | 598.288s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           | 598.705s  | 598.705s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           | 119.448s  | 119.448s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        | 597.649s  | 597.649s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   4.038s  |   4.038s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   3.315s  |   3.315s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   1.362s  |   1.362s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             | 598.951s  | 598.951s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.953s  |   0.953s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   2.837s  |   2.837s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   5.213s  |   5.213s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   7.642s  |   7.642s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  42.011s  |  42.011s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   5.913s  |   5.913s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |  15.349s  |  15.349s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        | 597.856s  | 597.856s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   2.958s  |   2.958s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   1.424s  |   1.424s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |  10.832s  |  10.832s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   4.324s  |   4.324s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  | 211.639s  | 211.639s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |  10.173s  |  10.173s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   5.563s  |   5.563s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   4.669s  |   4.669s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   2.638s  |   2.638s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   2.699s  |   2.699s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           | 410.178s  | 410.178s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     | 394.112s  | 394.112s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |   9.794s  |   9.794s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   3.635s  |   3.635s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  41.413s  |  41.413s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  45.853s  |  45.853s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   4.774s  |   4.774s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            | 267.324s  | 267.324s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   6.837s  |   6.837s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |  15.642s  |  15.642s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                | 598.318s  | 598.318s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                | 598.149s  | 598.149s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   4.565s  |   4.565s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          | 597.359s  | 597.359s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   3.331s  |   3.331s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   6.699s  |   6.699s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   0.823s  |   0.823s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  12.031s  |  12.031s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           | 597.409s  | 597.409s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        | 142.285s  | 142.285s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  24.475s  |  24.475s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                | 597.951s  | 597.951s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |  22.599s  |  22.599s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   3.454s  |   3.454s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  32.594s  |  32.594s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   2.204s  |   2.204s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   3.785s  |   3.785s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  11.595s  |  11.595s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   3.570s  |   3.570s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   4.916s  |   4.916s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   6.831s  |   6.831s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   3.172s  |   3.172s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  80.128s  |  80.128s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       | 598.217s  | 598.217s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       | 598.627s  | 598.627s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   3.676s  |   3.676s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       | 599.237s  | 599.237s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       | 598.190s  | 598.190s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       | 598.090s  | 598.090s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       | 597.894s  | 597.894s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |   8.853s  |   8.853s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   6.661s  |   6.661s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       | 598.519s  | 598.519s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   4.326s  |   4.326s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       | 598.300s  | 598.300s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     | 598.059s  | 598.059s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   2.624s  |   2.624s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                | 597.835s  | 597.835s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   3.514s  |   3.514s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   9.077s  |   9.077s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   3.360s  |   3.360s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |  21.391s  |  21.391s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   5.598s  |   5.598s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |  24.954s  |  24.954s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   3.086s  |   3.086s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |  10.400s  |  10.400s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    | 593.369s  | 593.369s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        | 598.979s  | 598.979s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        | 598.637s  | 598.637s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   6.861s  |   6.861s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  58.500s  |  58.500s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  | 598.650s  | 598.650s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  | 598.410s  | 598.410s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  35.967s  |  35.967s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.704s  |   0.704s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |  30.581s  |  30.581s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   2.719s  |   2.719s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           | 580.857s  | 580.857s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           | 278.352s  | 278.352s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   2.221s  |   2.221s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   4.135s  |   4.135s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   5.432s  |   5.432s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   3.675s  |   3.675s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   5.049s  |   5.049s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   1.289s  |   1.289s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           | 599.488s  | 599.488s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   1.657s  |   1.657s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.776s  |   0.776s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           | 114.401s  | 114.401s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   0.954s  |   0.954s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           | 587.058s  | 587.058s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   1.584s  |   1.584s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   1.191s  |   1.191s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   4.288s  |   4.288s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   1.121s  |   1.121s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   2.499s  |   2.499s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   3.998s  |   3.998s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   2.259s  |   2.259s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   7.013s  |   7.013s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   1.034s  |   1.034s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |   6.287s  |   6.287s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   5.208s  |   5.208s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   3.462s  |   3.462s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           | 310.816s  | 310.816s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   5.856s  |   5.856s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           | 599.210s  | 599.210s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   2.859s  |   2.859s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   5.095s  |   5.095s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.811s  |   0.811s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   1.291s  |   1.291s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   2.251s  |   2.251s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |  43.316s  |  43.316s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   2.058s  |   2.058s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           | 111.024s  | 111.024s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   2.498s  |   2.498s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   2.385s  |   2.385s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   8.119s  |   8.119s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   2.745s  |   2.745s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   3.016s  |   3.016s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |  77.253s  |  77.253s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   2.141s  |   2.141s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   5.345s  |   5.345s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   5.069s  |   5.069s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   2.595s  |   2.595s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   3.608s  |   3.608s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |  11.530s  |  11.530s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |   2.534s  |   2.534s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   1.151s  |   1.151s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   2.152s  |   2.152s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  19.684s  |  19.684s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   3.659s  |   3.659s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |   4.391s  |   4.391s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   2.412s  |   2.412s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            | 216.153s  | 216.153s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   2.910s  |   2.910s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |   4.001s  |   4.001s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   7.919s  |   7.919s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   4.261s  |   4.261s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   1.914s  |   1.914s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  81.304s  |  81.304s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           | 198.972s  | 198.972s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   4.034s  |   4.034s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   6.122s  |   6.122s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  67.942s  |  67.942s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   1.265s  |   1.265s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   2.349s  |   2.349s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   4.591s  |   4.591s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   3.011s  |   3.011s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   2.597s  |   2.597s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   3.530s  |   3.530s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           | 170.081s  | 170.081s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   5.289s  |   5.289s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   2.659s  |   2.659s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           | 598.529s  | 598.529s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |  10.010s  |  10.010s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   5.242s  |   5.242s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           | 377.593s  | 377.593s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   3.090s  |   3.090s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   1.567s  |   1.567s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   8.248s  |   8.248s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           | 118.586s  | 118.586s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.462s  |   0.462s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   0.880s  |   0.880s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   6.105s  |   6.105s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           | 598.248s  | 598.248s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   2.247s  |   2.247s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |  14.059s  |  14.059s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   3.662s  |   3.662s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   9.016s  |   9.016s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   5.654s  |   5.654s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   7.571s  |   7.571s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   1.830s  |   1.830s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           | 598.758s  | 598.758s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  39.392s  |  39.392s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.515s  |   0.515s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   2.913s  |   2.913s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   1.279s  |   1.279s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   7.619s  |   7.619s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   4.393s  |   4.393s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   2.426s  |   2.426s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   9.727s  |   9.727s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   3.969s  |   3.969s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |  58.563s  |  58.563s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |   2.813s  |   2.813s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   1.086s  |   1.086s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.327s  |   1.327s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.624s  |   0.624s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   1.367s  |   1.367s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   1.951s  |   1.951s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   2.731s  |   2.731s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   8.471s  |   8.471s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.548s  |   0.548s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   1.525s  |   1.525s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            | 598.162s  | 598.162s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |  52.473s  |  52.473s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            | 599.675s  | 599.675s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            | 599.117s  | 599.117s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            | 495.979s  | 495.979s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            | 108.179s  | 108.179s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            | 598.155s  | 598.155s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
</details>
