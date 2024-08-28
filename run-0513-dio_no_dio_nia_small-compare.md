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
Job tag: dio_no_dio_nia_small
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 36a0006f595c746a98c133ba38671ab5659dacf6
Z3 branch: 
Z3 options: "-T:600 -st lp.dio=false"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: remove testing code in is_big_term_on_no_term

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: dio_no_dio_nia_small
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 36a0006f595c746a98c133ba38671ab5659dacf6
Z3 branch: 
Z3 options: "-T:600 -st lp.dio=false"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: remove testing code in is_big_term_on_no_term

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 599.649s  | 599.649s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 598.937s  | 598.937s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.304s  |   1.304s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.631s  |   1.631s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.678s  | 598.678s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.222s  |   0.222s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 599.649s  | 599.649s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 598.937s  | 598.937s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.304s  |   1.304s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.631s  |   1.631s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.678s  | 598.678s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.222s  |   0.222s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 599.649s  | 599.649s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 598.937s  | 598.937s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.304s  |   1.304s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.631s  |   1.631s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.678s  | 598.678s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.222s  |   0.222s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 599.649s  | 599.649s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 598.937s  | 598.937s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.304s  |   1.304s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.631s  |   1.631s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.678s  | 598.678s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.222s  |   0.222s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.172s |2097.0MiB|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                         | 600.021s |1252.0MiB|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                               | 600.018s |254.0MiB|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                        | 600.018s |1062.0MiB|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                            | 600.006s |923.0MiB|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                           | 600.002s |1225.0MiB|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                  | 599.974s |809.0MiB|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                      | 599.972s |538.0MiB|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                            | 599.948s |1285.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                              | 599.947s |403.0MiB|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                         | 599.939s |650.0MiB|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                 | 599.937s |229.0MiB|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                    | 599.928s |254.0MiB|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                           | 599.922s |644.0MiB|
|aproveSMT7201733644041072759.smt2                                                          | 599.907s |236.0MiB|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                     | 599.905s |579.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 599.902s |768.0MiB|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                           | 599.895s |1467.0MiB|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                | 599.873s |493.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 599.870s |1762.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.172s |2097.0MiB|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                         | 600.021s |1252.0MiB|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                               | 600.018s |254.0MiB|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                        | 600.018s |1062.0MiB|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                            | 600.006s |923.0MiB|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                           | 600.002s |1225.0MiB|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                  | 599.974s |809.0MiB|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                      | 599.972s |538.0MiB|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                            | 599.948s |1285.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                              | 599.947s |403.0MiB|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                         | 599.939s |650.0MiB|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                 | 599.937s |229.0MiB|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                    | 599.928s |254.0MiB|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                           | 599.922s |644.0MiB|
|aproveSMT7201733644041072759.smt2                                                          | 599.907s |236.0MiB|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                     | 599.905s |579.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 599.902s |768.0MiB|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                           | 599.895s |1467.0MiB|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                | 599.873s |493.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 599.870s |1762.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |91.792MiB|91.792MiB|0B| 0.0%|
|04.smt2                                                                                     |73.632MiB|73.632MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |30.628MiB|30.628MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.556MiB|30.556MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.584MiB|23.584MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.568MiB|23.568MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.232MiB|24.232MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.764MiB|24.764MiB|0B| 0.0%|
|107.smt2                                                                                    |22.332MiB|22.332MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.212MiB|27.212MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.316MiB|80.316MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.904MiB|22.904MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.124MiB|23.124MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.524MiB|23.524MiB|0B| 0.0%|
|11.smt2                                                                                     |68.64MiB|68.64MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.868MiB|23.868MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.224MiB|23.224MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.944MiB|23.944MiB|0B| 0.0%|
|1126.smt2                                                                                   |24.888MiB|24.888MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |91.792MiB|91.792MiB|0B| 0.0%|
|04.smt2                                                                                     |73.632MiB|73.632MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |30.628MiB|30.628MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.556MiB|30.556MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.584MiB|23.584MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.568MiB|23.568MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.232MiB|24.232MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.764MiB|24.764MiB|0B| 0.0%|
|107.smt2                                                                                    |22.332MiB|22.332MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.212MiB|27.212MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.316MiB|80.316MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.904MiB|22.904MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.124MiB|23.124MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.524MiB|23.524MiB|0B| 0.0%|
|11.smt2                                                                                     |68.64MiB|68.64MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.868MiB|23.868MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.224MiB|23.224MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.944MiB|23.944MiB|0B| 0.0%|
|1126.smt2                                                                                   |24.888MiB|24.888MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |91.792MiB|91.792MiB|0B| 0.0%|
|04.smt2                                                                                     |73.632MiB|73.632MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |30.628MiB|30.628MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.556MiB|30.556MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.584MiB|23.584MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.568MiB|23.568MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.232MiB|24.232MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.764MiB|24.764MiB|0B| 0.0%|
|107.smt2                                                                                    |22.332MiB|22.332MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.212MiB|27.212MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.316MiB|80.316MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.904MiB|22.904MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.124MiB|23.124MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.524MiB|23.524MiB|0B| 0.0%|
|11.smt2                                                                                     |68.64MiB|68.64MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.868MiB|23.868MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.224MiB|23.224MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.944MiB|23.944MiB|0B| 0.0%|
|1126.smt2                                                                                   |24.888MiB|24.888MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |91.792MiB|91.792MiB|0B| 0.0%|
|04.smt2                                                                                     |73.632MiB|73.632MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |30.628MiB|30.628MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.556MiB|30.556MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.584MiB|23.584MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.568MiB|23.568MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.232MiB|24.232MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.764MiB|24.764MiB|0B| 0.0%|
|107.smt2                                                                                    |22.332MiB|22.332MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.212MiB|27.212MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.316MiB|80.316MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.904MiB|22.904MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.124MiB|23.124MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.524MiB|23.524MiB|0B| 0.0%|
|11.smt2                                                                                     |68.64MiB|68.64MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.868MiB|23.868MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.224MiB|23.224MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.944MiB|23.944MiB|0B| 0.0%|
|1126.smt2                                                                                   |24.888MiB|24.888MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 599.866s |3445.0MiB|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                               | 599.563s |3267.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              | 599.832s |3065.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 599.619s |2631.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               | 599.862s |2158.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.172s |2097.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 599.750s |1842.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                         | 599.362s |1767.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 599.870s |1762.0MiB|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                               | 598.794s |1744.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                         | 599.228s |1713.0MiB|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                          | 599.672s |1712.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 599.290s |1609.0MiB|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                            | 583.455s |1598.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 476.967s |1596.0MiB|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                               | 599.867s |1590.0MiB|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                           | 599.895s |1467.0MiB|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                           | 599.692s |1444.0MiB|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                       | 599.794s |1429.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 599.723s |1419.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 599.866s |3445.0MiB|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                               | 599.563s |3267.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              | 599.832s |3065.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 599.619s |2631.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               | 599.862s |2158.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.172s |2097.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 599.750s |1842.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                         | 599.362s |1767.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 599.870s |1762.0MiB|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                               | 598.794s |1744.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                         | 599.228s |1713.0MiB|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                          | 599.672s |1712.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 599.290s |1609.0MiB|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                            | 583.455s |1598.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 476.967s |1596.0MiB|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                               | 599.867s |1590.0MiB|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                           | 599.895s |1467.0MiB|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                           | 599.692s |1444.0MiB|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                       | 599.794s |1429.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 599.723s |1419.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 599.649s  | 599.649s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 598.937s  | 598.937s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.304s  |   1.304s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.631s  |   1.631s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 598.678s  | 598.678s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|124.smt2                                                                                    | 599.332s  | 599.332s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   1.673s  |   1.673s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.815s  |   0.815s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|140.smt2                                                                                    | 598.822s  | 598.822s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   1.907s  |   1.907s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   1.582s  |   1.582s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   1.145s  |   1.145s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   2.079s  |   2.079s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   4.504s  |   4.504s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   2.637s  |   2.637s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|177.smt2                                                                                    | 599.374s  | 599.374s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   0.898s  |   0.898s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   2.080s  |   2.080s  |   0.000s  | 0.0%|
|181.smt2                                                                                    | 599.027s  | 599.027s  |   0.000s  | 0.0%|
|182.smt2                                                                                    | 599.371s  | 599.371s  |   0.000s  | 0.0%|
|183.smt2                                                                                    | 598.582s  | 598.582s  |   0.000s  | 0.0%|
|185.smt2                                                                                    | 599.557s  | 599.557s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.633s  |   0.633s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   2.064s  |   2.064s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   2.298s  |   2.298s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   1.421s  |   1.421s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   2.273s  |   2.273s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   2.959s  |   2.959s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   4.670s  |   4.670s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   6.782s  |   6.782s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   2.388s  |   2.388s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   2.178s  |   2.178s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   3.480s  |   3.480s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   1.523s  |   1.523s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   2.096s  |   2.096s  |   0.000s  | 0.0%|
|35.smt2                                                                                     | 599.282s  | 599.282s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|40.smt2                                                                                     | 599.218s  | 599.218s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   2.186s  |   2.186s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   1.594s  |   1.594s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|54.smt2                                                                                     | 599.324s  | 599.324s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   1.578s  |   1.578s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   2.830s  |   2.830s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   1.510s  |   1.510s  |   0.000s  | 0.0%|
|58.smt2                                                                                     | 598.924s  | 598.924s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   1.635s  |   1.635s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   1.985s  |   1.985s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   3.254s  |   3.254s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|65.smt2                                                                                     | 599.486s  | 599.486s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   3.996s  |   3.996s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   2.069s  |   2.069s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|73.smt2                                                                                     | 599.063s  | 599.063s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   2.873s  |   2.873s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   1.872s  |   1.872s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   4.438s  |   4.438s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|966.smt2                                                                                    |   3.787s  |   3.787s  |   0.000s  | 0.0%|
|98.smt2                                                                                     | 599.563s  | 599.563s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|99.smt2                                                                                     | 597.795s  | 597.795s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  | 317.567s  | 317.567s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   5.357s  |   5.357s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          | 599.122s  | 599.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               | 485.542s  | 485.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   1.335s  |   1.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |  20.810s  |  20.810s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.543s  |   0.543s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          | 267.361s  | 267.361s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   8.303s  |   8.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   3.030s  |   3.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            | 600.002s  | 600.002s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   4.657s  |   4.657s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   3.363s  |   3.363s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       | 469.529s  | 469.529s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   4.249s  |   4.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  71.999s  |  71.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   4.432s  |   4.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               | 180.001s  | 180.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   1.510s  |   1.510s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   1.193s  |   1.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           | 599.779s  | 599.779s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           | 599.329s  | 599.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |   3.737s  |   3.737s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   5.299s  |   5.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  15.614s  |  15.614s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   6.332s  |   6.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |   7.670s  |   7.670s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         | 598.926s  | 598.926s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             | 598.877s  | 598.877s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |  54.116s  |  54.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  41.978s  |  41.978s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             | 599.427s  | 599.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.647s  |   0.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 | 315.672s  | 315.672s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   3.624s  |   3.624s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   4.875s  |   4.875s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |  11.666s  |  11.666s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   2.146s  |   2.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              |  11.767s  |  11.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  | 107.291s  | 107.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   2.194s  |   2.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |  17.159s  |  17.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               |  12.578s  |  12.578s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         | 599.117s  | 599.117s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   8.499s  |   8.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |  13.726s  |  13.726s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       | 330.985s  | 330.985s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 | 189.229s  | 189.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      | 599.359s  | 599.359s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   3.189s  |   3.189s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   4.129s  |   4.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              | 598.428s  | 598.428s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   3.514s  |   3.514s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   5.555s  |   5.555s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          | 598.882s  | 598.882s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   1.382s  |   1.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          | 296.027s  | 296.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   8.443s  |   8.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         | 156.906s  | 156.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   2.824s  |   2.824s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      | 598.915s  | 598.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |   9.803s  |   9.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   5.139s  |   5.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   5.972s  |   5.972s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         | 598.120s  | 598.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      | 599.905s  | 599.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               | 598.982s  | 598.982s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  56.251s  |  56.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |  43.417s  |  43.417s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   8.977s  |   8.977s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           | 598.820s  | 598.820s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               | 475.190s  | 475.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   3.817s  |   3.817s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               | 101.865s  | 101.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         | 599.565s  | 599.565s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   3.970s  |   3.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           | 103.471s  | 103.471s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |  15.545s  |  15.545s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   7.607s  |   7.607s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   | 599.030s  | 599.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   | 598.562s  | 598.562s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   | 598.493s  | 598.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             | 597.915s  | 597.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  12.318s  |  12.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   1.966s  |   1.966s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    | 599.304s  | 599.304s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |  49.488s  |  49.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        |  68.331s  |  68.331s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  72.560s  |  72.560s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  53.286s  |  53.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     | 598.816s  | 598.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               | 599.483s  | 599.483s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               | 200.122s  | 200.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |  18.579s  |  18.579s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   5.092s  |   5.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   4.531s  |   4.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |  54.755s  |  54.755s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               | 599.423s  | 599.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   1.397s  |   1.397s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   3.855s  |   3.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   7.386s  |   7.386s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   6.527s  |   6.527s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   2.439s  |   2.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   6.848s  |   6.848s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                | 600.018s  | 600.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   1.366s  |   1.366s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              | 598.580s  | 598.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |  41.264s  |  41.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   1.941s  |   1.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   9.244s  |   9.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  53.930s  |  53.930s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  70.067s  |  70.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   6.844s  |   6.844s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  33.242s  |  33.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          |  56.401s  |  56.401s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          | 599.247s  | 599.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          | 600.021s  | 600.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |   2.633s  |   2.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          | 598.893s  | 598.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          | 599.580s  | 599.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  78.061s  |  78.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   9.164s  |   9.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  14.375s  |  14.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   3.747s  |   3.747s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    | 599.210s  | 599.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   3.919s  |   3.919s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   3.068s  |   3.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    | 599.534s  | 599.534s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   4.069s  |   4.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   4.536s  |   4.536s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |  48.648s  |  48.648s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |  20.957s  |  20.957s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        | 599.388s  | 599.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |   5.470s  |   5.470s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |  15.759s  |  15.759s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   6.910s  |   6.910s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        |  87.808s  |  87.808s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   0.976s  |   0.976s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  46.362s  |  46.362s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  74.026s  |  74.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  53.153s  |  53.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  79.609s  |  79.609s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  89.504s  |  89.504s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              |  82.650s  |  82.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  35.058s  |  35.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  | 270.802s  | 270.802s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  |  80.100s  |  80.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |  83.140s  |  83.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |  51.010s  |  51.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   1.898s  |   1.898s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   1.149s  |   1.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              | 598.994s  | 598.994s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   3.393s  |   3.393s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |  54.733s  |  54.733s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |   9.138s  |   9.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   5.087s  |   5.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  41.911s  |  41.911s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        | 598.253s  | 598.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.623s  |   0.623s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   2.672s  |   2.672s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             | 441.588s  | 441.588s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |  11.335s  |  11.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   | 599.554s  | 599.554s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   | 598.734s  | 598.734s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     | 599.788s  | 599.788s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   4.229s  |   4.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   2.732s  |   2.732s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   4.185s  |   4.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     | 599.193s  | 599.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 | 599.392s  | 599.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                | 599.295s  | 599.295s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   2.363s  |   2.363s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                | 598.956s  | 598.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      | 598.324s  | 598.324s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   8.890s  |   8.890s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      | 599.589s  | 599.589s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      | 598.846s  | 598.846s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   7.481s  |   7.481s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      | 421.641s  | 421.641s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |  12.251s  |  12.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   1.473s  |   1.473s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   2.862s  |   2.862s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   5.129s  |   5.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   3.252s  |   3.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |  30.397s  |  30.397s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   6.844s  |   6.844s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |  37.378s  |  37.378s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  19.855s  |  19.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             | 599.220s  | 599.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   5.523s  |   5.523s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          | 598.958s  | 598.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               | 599.718s  | 599.718s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                | 270.334s  | 270.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   7.398s  |   7.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |  10.587s  |  10.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   2.701s  |   2.701s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   4.309s  |   4.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   3.863s  |   3.863s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   6.337s  |   6.337s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   1.408s  |   1.408s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              | 599.610s  | 599.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   8.849s  |   8.849s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   3.688s  |   3.688s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   9.542s  |   9.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   4.105s  |   4.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  30.511s  |  30.511s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          | 599.314s  | 599.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |  10.161s  |  10.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          | 599.350s  | 599.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          | 599.852s  | 599.852s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |  10.649s  |  10.649s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          | 599.608s  | 599.608s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          | 598.911s  | 598.911s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |  12.617s  |  12.617s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          | 599.419s  | 599.419s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   9.628s  |   9.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            | 599.483s  | 599.483s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   4.095s  |   4.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |   8.004s  |   8.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |  16.959s  |  16.959s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            | 599.201s  | 599.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   1.089s  |   1.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   8.568s  |   8.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |   6.775s  |   6.775s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   2.378s  |   2.378s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   3.429s  |   3.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   0.756s  |   0.756s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   2.961s  |   2.961s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |   6.614s  |   6.614s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   3.142s  |   3.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   2.799s  |   2.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           | 599.222s  | 599.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           | 599.174s  | 599.174s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           | 599.700s  | 599.700s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           | 598.663s  | 598.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   2.774s  |   2.774s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   1.258s  |   1.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           | 599.587s  | 599.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   2.487s  |   2.487s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   2.355s  |   2.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   4.300s  |   4.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |  28.094s  |  28.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   2.196s  |   2.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           | 599.224s  | 599.224s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   2.246s  |   2.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           | 597.737s  | 597.737s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  69.588s  |  69.588s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           | 599.232s  | 599.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |  14.372s  |  14.372s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |   8.544s  |   8.544s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           | 599.225s  | 599.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |   1.217s  |   1.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   2.452s  |   2.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |  46.092s  |  46.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   2.226s  |   2.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  31.323s  |  31.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   2.278s  |   2.278s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   5.980s  |   5.980s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   3.388s  |   3.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   1.202s  |   1.202s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |  13.171s  |  13.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   2.145s  |   2.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |  34.906s  |  34.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           | 599.562s  | 599.562s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  49.323s  |  49.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           | 599.399s  | 599.399s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   2.255s  |   2.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           | 599.466s  | 599.466s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     | 598.549s  | 598.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   2.088s  |   2.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   2.204s  |   2.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     | 599.675s  | 599.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   2.778s  |   2.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |   7.192s  |   7.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     | 111.312s  | 111.312s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   2.185s  |   2.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |  29.346s  |  29.346s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     | 599.260s  | 599.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |   1.898s  |   1.898s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.955s  |   0.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     | 598.879s  | 598.879s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |   9.822s  |   9.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   1.240s  |   1.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   1.796s  |   1.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   6.721s  |   6.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   2.720s  |   2.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   3.556s  |   3.556s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   2.350s  |   2.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   2.561s  |   2.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   4.998s  |   4.998s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   5.405s  |   5.405s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     | 599.388s  | 599.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     | 598.091s  | 598.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |  10.426s  |  10.426s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   1.368s  |   1.368s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   3.329s  |   3.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     | 599.445s  | 599.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               | 594.340s  | 594.340s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     | 598.691s  | 598.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   2.799s  |   2.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     | 598.289s  | 598.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |   0.995s  |   0.995s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |   4.308s  |   4.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   2.125s  |   2.125s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |  13.456s  |  13.456s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   2.199s  |   2.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   0.767s  |   0.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     | 488.442s  | 488.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     | 598.601s  | 598.601s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     | 599.185s  | 599.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     | 277.025s  | 277.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     | 598.706s  | 598.706s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  22.123s  |  22.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   7.127s  |   7.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               | 599.267s  | 599.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   2.265s  |   2.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               | 599.268s  | 599.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               | 599.410s  | 599.410s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |  10.807s  |  10.807s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   7.210s  |   7.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |   4.381s  |   4.381s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               | 599.037s  | 599.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               | 599.191s  | 599.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |  69.938s  |  69.938s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               | 599.177s  | 599.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               | 599.311s  | 599.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               | 599.259s  | 599.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               | 598.954s  | 598.954s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |  73.323s  |  73.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   2.693s  |   2.693s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   1.131s  |   1.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  34.782s  |  34.782s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               |  55.759s  |  55.759s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   2.209s  |   2.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               | 599.132s  | 599.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   9.246s  |   9.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   2.458s  |   2.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               | 599.268s  | 599.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               | 599.570s  | 599.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               | 599.352s  | 599.352s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   0.847s  |   0.847s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   2.863s  |   2.863s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               | 599.275s  | 599.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   1.216s  |   1.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   1.471s  |   1.471s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               | 598.680s  | 598.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   6.871s  |   6.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   2.234s  |   2.234s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   3.524s  |   3.524s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               | 599.374s  | 599.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   1.075s  |   1.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               | 598.859s  | 598.859s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               | 598.975s  | 598.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   3.232s  |   3.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |  10.306s  |  10.306s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |   8.473s  |   8.473s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               | 364.803s  | 364.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   5.570s  |   5.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |  18.816s  |  18.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |   1.023s  |   1.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   0.867s  |   0.867s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             | 512.629s  | 512.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |  71.262s  |  71.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             | 599.563s  | 599.563s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |   6.472s  |   6.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   2.258s  |   2.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |  10.647s  |  10.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   8.711s  |   8.711s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   2.221s  |   2.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   2.342s  |   2.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |  29.191s  |  29.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             | 599.453s  | 599.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |  18.396s  |  18.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   3.019s  |   3.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             | 598.961s  | 598.961s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             | 150.920s  | 150.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |   1.598s  |   1.598s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   5.216s  |   5.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.896s  |   0.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   1.959s  |   1.959s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             | 599.859s  | 599.859s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   2.193s  |   2.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             | 599.316s  | 599.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |  93.885s  |  93.885s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |   2.354s  |   2.354s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             | 598.748s  | 598.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |   6.615s  |   6.615s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   1.441s  |   1.441s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |   8.792s  |   8.792s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |  11.604s  |  11.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             | 599.829s  | 599.829s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   5.419s  |   5.419s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             | 598.879s  | 598.879s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             | 161.107s  | 161.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             | 599.593s  | 599.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   1.077s  |   1.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             | 599.158s  | 599.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   1.109s  |   1.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             | 599.172s  | 599.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |  17.836s  |  17.836s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |  31.929s  |  31.929s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               | 596.744s  | 596.744s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |   9.348s  |   9.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |   9.390s  |   9.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         | 599.528s  | 599.528s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        | 598.520s  | 598.520s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              | 161.650s  | 161.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   1.703s  |   1.703s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   2.174s  |   2.174s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   1.143s  |   1.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    | 599.558s  | 599.558s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    | 599.722s  | 599.722s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |   7.189s  |   7.189s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   2.151s  |   2.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   2.420s  |   2.420s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   9.111s  |   9.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |  27.006s  |  27.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    | 599.361s  | 599.361s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   2.208s  |   2.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    | 599.460s  | 599.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   5.300s  |   5.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   2.165s  |   2.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   2.723s  |   2.723s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    | 598.765s  | 598.765s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    | 599.522s  | 599.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    | 599.029s  | 599.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   2.396s  |   2.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   2.522s  |   2.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    | 598.737s  | 598.737s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   8.941s  |   8.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    | 599.776s  | 599.776s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |  85.362s  |  85.362s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    | 598.748s  | 598.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   1.144s  |   1.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    | 182.130s  | 182.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  30.262s  |  30.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |  24.342s  |  24.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   2.426s  |   2.426s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    | 599.421s  | 599.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    | 598.610s  | 598.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    | 532.593s  | 532.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   2.155s  |   2.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    | 599.350s  | 599.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   3.672s  |   3.672s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    | 598.978s  | 598.978s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |   7.659s  |   7.659s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   7.112s  |   7.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   2.424s  |   2.424s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   6.607s  |   6.607s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |   7.090s  |   7.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   2.299s  |   2.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   2.251s  |   2.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |  17.038s  |  17.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   2.330s  |   2.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          | 599.820s  | 599.820s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   2.513s  |   2.513s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          | 599.424s  | 599.424s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |  13.458s  |  13.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  10.027s  |  10.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |  14.454s  |  14.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          | 599.472s  | 599.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          | 599.126s  | 599.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          | 598.753s  | 598.753s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   1.151s  |   1.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          | 599.633s  | 599.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   9.876s  |   9.876s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |   9.334s  |   9.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   2.413s  |   2.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   2.140s  |   2.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          | 599.230s  | 599.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          | 598.772s  | 598.772s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   1.435s  |   1.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   2.521s  |   2.521s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          | 598.274s  | 598.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   5.339s  |   5.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   2.358s  |   2.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   6.108s  |   6.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        | 598.561s  | 598.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   7.346s  |   7.346s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        | 598.619s  | 598.619s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |  11.893s  |  11.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |   7.104s  |   7.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |  85.947s  |  85.947s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |  28.234s  |  28.234s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        | 598.629s  | 598.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |  14.693s  |  14.693s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |   8.700s  |   8.700s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   2.444s  |   2.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        | 599.830s  | 599.830s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   2.853s  |   2.853s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |   6.070s  |   6.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   7.121s  |   7.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |   6.368s  |   6.368s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   1.385s  |   1.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |   3.816s  |   3.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   2.461s  |   2.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   7.100s  |   7.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |   4.047s  |   4.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   0.575s  |   0.575s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   2.389s  |   2.389s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        | 599.088s  | 599.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   1.803s  |   1.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |  13.615s  |  13.615s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        | 599.459s  | 599.459s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        | 599.600s  | 599.600s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   2.321s  |   2.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |  15.804s  |  15.804s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   2.245s  |   2.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        | 598.750s  | 598.750s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |   9.097s  |   9.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        | 599.009s  | 599.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |  10.154s  |  10.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   2.380s  |   2.380s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        | 598.732s  | 598.732s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        | 448.259s  | 448.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |  17.848s  |  17.848s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        | 597.109s  | 597.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        | 599.025s  | 599.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   5.348s  |   5.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  | 598.930s  | 598.930s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   2.375s  |   2.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   6.068s  |   6.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   5.728s  |   5.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |  24.986s  |  24.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |   9.839s  |   9.839s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   9.028s  |   9.028s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |  37.296s  |  37.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   1.109s  |   1.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     |   8.237s  |   8.237s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  10.440s  |  10.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   2.453s  |   2.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   3.325s  |   3.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     | 599.008s  | 599.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     | 599.206s  | 599.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     | 598.824s  | 598.824s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   3.131s  |   3.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |  18.866s  |  18.866s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       | 599.820s  | 599.820s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |   7.105s  |   7.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |  10.898s  |  10.898s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |  22.627s  |  22.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       | 599.061s  | 599.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       | 137.045s  | 137.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       | 598.710s  | 598.710s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   4.696s  |   4.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       | 599.308s  | 599.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   2.529s  |   2.529s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   3.082s  |   3.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   2.148s  |   2.148s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   2.717s  |   2.717s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       | 599.577s  | 599.577s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       | 599.388s  | 599.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |  53.352s  |  53.352s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   2.372s  |   2.372s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   1.462s  |   1.462s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   2.580s  |   2.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   0.920s  |   0.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       | 599.529s  | 599.529s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       | 599.649s  | 599.649s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |  15.269s  |  15.269s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 | 599.321s  | 599.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  25.522s  |  25.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |  20.445s  |  20.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  41.404s  |  41.404s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   9.304s  |   9.304s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |  10.914s  |  10.914s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  20.983s  |  20.983s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   1.875s  |   1.875s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |   9.542s  |   9.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  81.425s  |  81.425s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   8.627s  |   8.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            | 178.206s  | 178.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  16.492s  |  16.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   1.544s  |   1.544s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |  25.169s  |  25.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            | 445.005s  | 445.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |  12.959s  |  12.959s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   6.784s  |   6.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   5.440s  |   5.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   3.961s  |   3.961s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   2.222s  |   2.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   3.800s  |   3.800s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   2.266s  |   2.266s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |  21.546s  |  21.546s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   3.026s  |   3.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   6.070s  |   6.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   6.690s  |   6.690s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   1.792s  |   1.792s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |  10.315s  |  10.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   3.514s  |   3.514s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   5.892s  |   5.892s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   9.340s  |   9.340s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   8.379s  |   8.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |  20.479s  |  20.479s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |  12.361s  |  12.361s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |  22.257s  |  22.257s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   1.435s  |   1.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   1.715s  |   1.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   3.219s  |   3.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   4.122s  |   4.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   4.374s  |   4.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  13.224s  |  13.224s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   9.029s  |   9.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  15.012s  |  15.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |   3.148s  |   3.148s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   3.816s  |   3.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |  11.366s  |  11.366s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   3.712s  |   3.712s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   2.333s  |   2.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   4.748s  |   4.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |  52.587s  |  52.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   3.002s  |   3.002s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   3.020s  |   3.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   2.530s  |   2.530s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   4.033s  |   4.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   3.156s  |   3.156s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |  11.799s  |  11.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   2.478s  |   2.478s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   2.138s  |   2.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   3.015s  |   3.015s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   8.552s  |   8.552s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |  10.928s  |  10.928s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   5.158s  |   5.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   3.465s  |   3.465s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   4.521s  |   4.521s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   3.462s  |   3.462s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   2.367s  |   2.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   2.103s  |   2.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  18.258s  |  18.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   3.439s  |   3.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   2.696s  |   2.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  19.803s  |  19.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   0.942s  |   0.942s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |  15.699s  |  15.699s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   3.025s  |   3.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   9.183s  |   9.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   7.188s  |   7.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  27.170s  |  27.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |  12.764s  |  12.764s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   2.889s  |   2.889s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   3.116s  |   3.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  67.605s  |  67.605s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   3.531s  |   3.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   2.609s  |   2.609s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   4.431s  |   4.431s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   7.628s  |   7.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |  13.354s  |  13.354s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   3.987s  |   3.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |  10.733s  |  10.733s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   7.528s  |   7.528s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  12.861s  |  12.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  14.013s  |  14.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   7.319s  |   7.319s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   3.200s  |   3.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   8.480s  |   8.480s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   7.596s  |   7.596s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   3.573s  |   3.573s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   1.930s  |   1.930s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                | 169.337s  | 169.337s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |  13.301s  |  13.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  24.069s  |  24.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   1.786s  |   1.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                | 599.116s  | 599.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  89.450s  |  89.450s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   4.769s  |   4.769s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   2.162s  |   2.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   2.613s  |   2.613s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   1.629s  |   1.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   3.029s  |   3.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   3.059s  |   3.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  61.493s  |  61.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   3.086s  |   3.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |  14.855s  |  14.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   1.797s  |   1.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   2.395s  |   2.395s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   2.980s  |   2.980s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   3.259s  |   3.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |  12.077s  |  12.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   2.667s  |   2.667s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |   9.773s  |   9.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |  16.070s  |  16.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   3.732s  |   3.732s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   3.222s  |   3.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   3.684s  |   3.684s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   1.733s  |   1.733s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   7.540s  |   7.540s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   2.742s  |   2.742s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   3.238s  |   3.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   2.880s  |   2.880s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   2.032s  |   2.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |  26.446s  |  26.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   9.325s  |   9.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   2.819s  |   2.819s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   6.502s  |   6.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   4.628s  |   4.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          | 368.762s  | 368.762s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          | 459.595s  | 459.595s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          | 194.386s  | 194.386s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   7.006s  |   7.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   8.599s  |   8.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             | 599.225s  | 599.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            | 599.159s  | 599.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            | 599.636s  | 599.636s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   3.386s  |   3.386s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   5.337s  |   5.337s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   2.284s  |   2.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   5.075s  |   5.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |  45.796s  |  45.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   3.601s  |   3.601s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |  71.575s  |  71.575s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   3.946s  |   3.946s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      | 598.788s  | 598.788s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   6.397s  |   6.397s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   8.152s  |   8.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   1.268s  |   1.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   4.428s  |   4.428s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   3.737s  |   3.737s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       |  77.792s  |  77.792s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   9.994s  |   9.994s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   1.924s  |   1.924s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   1.065s  |   1.065s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   4.897s  |   4.897s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   | 599.547s  | 599.547s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |  15.235s  |  15.235s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               | 476.755s  | 476.755s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |   9.965s  |   9.965s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |  50.233s  |  50.233s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |  51.623s  |  51.623s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |  13.767s  |  13.767s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   3.024s  |   3.024s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          | 599.550s  | 599.550s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          | 599.111s  | 599.111s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   2.249s  |   2.249s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   1.387s  |   1.387s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               | 158.340s  | 158.340s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               | 599.518s  | 599.518s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  17.762s  |  17.762s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               | 599.229s  | 599.229s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               | 598.792s  | 598.792s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   8.555s  |   8.555s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         | 599.312s  | 599.312s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         | 600.018s  | 600.018s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         | 103.411s  | 103.411s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |   6.483s  |   6.483s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               | 599.041s  | 599.041s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  97.398s  |  97.398s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   4.115s  |   4.115s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |   6.084s  |   6.084s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         | 598.783s  | 598.783s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |  17.417s  |  17.417s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.606s  |   0.606s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         | 599.407s  | 599.407s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  33.283s  |  33.283s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  66.999s  |  66.999s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    | 599.834s  | 599.834s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  52.107s  |  52.107s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    | 599.209s  | 599.209s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  15.717s  |  15.717s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   3.112s  |   3.112s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              | 599.750s  | 599.750s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  89.409s  |  89.409s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   6.311s  |   6.311s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   5.714s  |   5.714s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  55.909s  |  55.909s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |   8.440s  |   8.440s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |   8.841s  |   8.841s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   5.080s  |   5.080s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   2.815s  |   2.815s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |   4.705s  |   4.705s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   7.819s  |   7.819s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  | 189.006s  | 189.006s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |  16.559s  |  16.559s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  46.437s  |  46.437s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |   7.469s  |   7.469s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 | 599.464s  | 599.464s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  50.741s  |  50.741s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           | 599.041s  | 599.041s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |  12.718s  |  12.718s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |  24.266s  |  24.266s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              | 598.875s  | 598.875s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   4.237s  |   4.237s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              | 598.979s  | 598.979s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              | 598.642s  | 598.642s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  20.636s  |  20.636s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              | 599.039s  | 599.039s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              | 599.401s  | 599.401s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |  32.275s  |  32.275s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              | 598.412s  | 598.412s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              | 599.499s  | 599.499s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   3.109s  |   3.109s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |  25.639s  |  25.639s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  68.562s  |  68.562s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |  19.123s  |  19.123s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      | 383.316s  | 383.316s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     | 238.911s  | 238.911s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  70.838s  |  70.838s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  48.988s  |  48.988s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  51.547s  |  51.547s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            |  62.271s  |  62.271s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   5.197s  |   5.197s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             | 599.775s  | 599.775s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   4.454s  |   4.454s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             | 599.388s  | 599.388s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             | 599.220s  | 599.220s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   2.801s  |   2.801s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             | 599.438s  | 599.438s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             | 599.392s  | 599.392s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   1.662s  |   1.662s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 | 599.258s  | 599.258s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  | 599.498s  | 599.498s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |  18.103s  |  18.103s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   3.797s  |   3.797s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             | 598.845s  | 598.845s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   2.280s  |   2.280s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   5.066s  |   5.066s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |  13.173s  |  13.173s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   4.546s  |   4.546s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |  17.686s  |  17.686s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             | 599.311s  | 599.311s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   2.684s  |   2.684s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   4.790s  |   4.790s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   4.270s  |   4.270s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   1.607s  |   1.607s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |   9.607s  |   9.607s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   1.996s  |   1.996s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   3.935s  |   3.935s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               | 600.172s  | 600.172s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   2.490s  |   2.490s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            | 599.015s  | 599.015s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   2.079s  |   2.079s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 | 599.058s  | 599.058s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |  15.098s  |  15.098s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  26.797s  |  26.797s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |  10.461s  |  10.461s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           | 599.108s  | 599.108s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |  10.336s  |  10.336s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |  15.106s  |  15.106s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 | 599.705s  | 599.705s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      | 483.604s  | 483.604s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |   9.859s  |   9.859s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |  13.257s  |  13.257s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           | 599.367s  | 599.367s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  22.943s  |  22.943s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |  12.199s  |  12.199s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  33.565s  |  33.565s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              | 599.806s  | 599.806s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |   4.003s  |   4.003s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   3.707s  |   3.707s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   3.035s  |   3.035s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      | 569.055s  | 569.055s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               | 598.529s  | 598.529s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              | 599.439s  | 599.439s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   2.636s  |   2.636s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       | 598.532s  | 598.532s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |   4.176s  |   4.176s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   1.904s  |   1.904s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       | 126.433s  | 126.433s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   1.281s  |   1.281s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.580s  |   0.580s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       | 599.720s  | 599.720s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |  11.236s  |  11.236s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.713s  |   0.713s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       | 281.839s  | 281.839s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   1.097s  |   1.097s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   4.706s  |   4.706s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       | 599.431s  | 599.431s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |  11.129s  |  11.129s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       | 599.415s  | 599.415s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |  10.162s  |  10.162s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       | 599.087s  | 599.087s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   7.761s  |   7.761s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   2.642s  |   2.642s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       | 392.321s  | 392.321s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |   8.648s  |   8.648s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   2.051s  |   2.051s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   3.730s  |   3.730s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       |  89.493s  |  89.493s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       | 103.088s  | 103.088s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |  14.852s  |  14.852s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   2.248s  |   2.248s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       | 401.942s  | 401.942s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   2.858s  |   2.858s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   1.623s  |   1.623s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               | 598.847s  | 598.847s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         | 314.033s  | 314.033s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   3.673s  |   3.673s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   7.219s  |   7.219s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   1.701s  |   1.701s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 | 598.970s  | 598.970s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   1.050s  |   1.050s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |  16.968s  |  16.968s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |  11.347s  |  11.347s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |  17.416s  |  17.416s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   8.247s  |   8.247s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   4.740s  |   4.740s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                | 599.442s  | 599.442s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   1.287s  |   1.287s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |  12.972s  |  12.972s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                | 598.948s  | 598.948s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   3.704s  |   3.704s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |  16.038s  |  16.038s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   4.851s  |   4.851s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      | 599.764s  | 599.764s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   1.541s  |   1.541s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   3.364s  |   3.364s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |   7.174s  |   7.174s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   4.145s  |   4.145s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |  13.803s  |  13.803s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   1.183s  |   1.183s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   3.121s  |   3.121s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   1.824s  |   1.824s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   1.198s  |   1.198s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |  17.446s  |  17.446s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   4.784s  |   4.784s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   7.793s  |   7.793s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   1.184s  |   1.184s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |  10.992s  |  10.992s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   2.453s  |   2.453s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      | 598.735s  | 598.735s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   1.446s  |   1.446s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      | 599.710s  | 599.710s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   3.774s  |   3.774s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   7.478s  |   7.478s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   2.935s  |   2.935s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   1.334s  |   1.334s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   2.416s  |   2.416s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   8.317s  |   8.317s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   3.151s  |   3.151s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   5.734s  |   5.734s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   5.086s  |   5.086s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   2.686s  |   2.686s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |   1.941s  |   1.941s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   2.009s  |   2.009s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      | 599.509s  | 599.509s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |  27.571s  |  27.571s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |  19.932s  |  19.932s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   4.358s  |   4.358s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   4.643s  |   4.643s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   2.582s  |   2.582s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   2.612s  |   2.612s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   9.998s  |   9.998s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |   8.134s  |   8.134s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   1.598s  |   1.598s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |  10.207s  |  10.207s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   1.760s  |   1.760s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      | 598.158s  | 598.158s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   1.693s  |   1.693s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      | 598.732s  | 598.732s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   3.512s  |   3.512s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   4.678s  |   4.678s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |  10.353s  |  10.353s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   1.908s  |   1.908s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      | 598.924s  | 598.924s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   4.085s  |   4.085s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   3.867s  |   3.867s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |  12.445s  |  12.445s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |   4.004s  |   4.004s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   6.021s  |   6.021s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.722s  |   0.722s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   5.510s  |   5.510s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   3.892s  |   3.892s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   6.446s  |   6.446s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   2.184s  |   2.184s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   2.493s  |   2.493s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   4.445s  |   4.445s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   8.380s  |   8.380s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   2.539s  |   2.539s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   2.868s  |   2.868s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   3.077s  |   3.077s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   4.219s  |   4.219s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   3.773s  |   3.773s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   9.424s  |   9.424s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   1.974s  |   1.974s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   8.793s  |   8.793s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   3.098s  |   3.098s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   2.974s  |   2.974s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   8.413s  |   8.413s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |  14.127s  |  14.127s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   7.717s  |   7.717s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |  14.930s  |  14.930s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            | 598.730s  | 598.730s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |  12.725s  |  12.725s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  44.116s  |  44.116s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |  41.587s  |  41.587s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  33.108s  |  33.108s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |  57.521s  |  57.521s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        | 599.145s  | 599.145s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        | 476.967s  | 476.967s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  30.755s  |  30.755s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       |  85.730s  |  85.730s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   6.023s  |   6.023s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   5.410s  |   5.410s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     | 598.938s  | 598.938s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     | 599.526s  | 599.526s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     | 599.708s  | 599.708s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |  21.039s  |  21.039s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         | 599.723s  | 599.723s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               | 599.947s  | 599.947s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         | 599.055s  | 599.055s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               | 599.263s  | 599.263s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   3.174s  |   3.174s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |  21.513s  |  21.513s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               | 599.385s  | 599.385s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  | 598.919s  | 598.919s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |  22.142s  |  22.142s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     | 149.056s  | 149.056s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  46.603s  |  46.603s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  16.447s  |  16.447s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            | 155.243s  | 155.243s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            | 520.703s  | 520.703s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   3.479s  |   3.479s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   2.153s  |   2.153s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                | 598.960s  | 598.960s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   4.092s  |   4.092s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  74.961s  |  74.961s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 | 406.183s  | 406.183s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 | 599.194s  | 599.194s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  42.366s  |  42.366s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 | 599.415s  | 599.415s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  28.703s  |  28.703s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |  15.668s  |  15.668s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           | 111.775s  | 111.775s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           | 599.672s  | 599.672s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           | 278.713s  | 278.713s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |  87.740s  |  87.740s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  79.607s  |  79.607s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 | 125.627s  | 125.627s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   5.885s  |   5.885s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  43.802s  |  43.802s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 | 599.685s  | 599.685s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  29.760s  |  29.760s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 | 424.565s  | 424.565s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   4.050s  |   4.050s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 | 598.682s  | 598.682s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 | 599.471s  | 599.471s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |  50.133s  |  50.133s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  38.035s  |  38.035s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 | 128.701s  | 128.701s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   6.711s  |   6.711s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 | 599.873s  | 599.873s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |  16.907s  |  16.907s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  12.689s  |  12.689s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |  78.648s  |  78.648s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   6.464s  |   6.464s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   9.206s  |   9.206s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 |  85.535s  |  85.535s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  70.241s  |  70.241s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |  10.553s  |  10.553s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 | 151.744s  | 151.744s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 | 262.775s  | 262.775s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   6.411s  |   6.411s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |   5.626s  |   5.626s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 | 443.851s  | 443.851s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   4.074s  |   4.074s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 | 120.154s  | 120.154s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   1.956s  |   1.956s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |  70.308s  |  70.308s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |   6.482s  |   6.482s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |   8.700s  |   8.700s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   6.094s  |   6.094s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   4.710s  |   4.710s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              | 599.540s  | 599.540s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  21.544s  |  21.544s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 |  72.039s  |  72.039s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  68.941s  |  68.941s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 | 108.555s  | 108.555s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  27.872s  |  27.872s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        | 599.006s  | 599.006s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  40.382s  |  40.382s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  32.993s  |  32.993s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |  76.861s  |  76.861s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           | 204.125s  | 204.125s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    | 599.372s  | 599.372s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    | 599.595s  | 599.595s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       |  38.943s  |  38.943s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       | 115.738s  | 115.738s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  58.637s  |  58.637s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  87.142s  |  87.142s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |   9.146s  |   9.146s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              | 598.930s  | 598.930s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  68.368s  |  68.368s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  18.438s  |  18.438s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  49.794s  |  49.794s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  58.927s  |  58.927s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 | 157.716s  | 157.716s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  | 599.766s  | 599.766s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  65.702s  |  65.702s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  39.038s  |  39.038s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   5.548s  |   5.548s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  79.316s  |  79.316s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |  73.576s  |  73.576s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  49.953s  |  49.953s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            | 599.332s  | 599.332s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          | 167.210s  | 167.210s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  44.841s  |  44.841s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  42.826s  |  42.826s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  87.269s  |  87.269s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  64.474s  |  64.474s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   3.313s  |   3.313s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |  12.412s  |  12.412s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        | 406.283s  | 406.283s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        | 599.732s  | 599.732s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |  89.250s  |  89.250s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        | 599.482s  | 599.482s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        | 599.492s  | 599.492s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        | 493.622s  | 493.622s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        | 599.090s  | 599.090s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        | 599.174s  | 599.174s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        | 599.159s  | 599.159s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  | 598.911s  | 598.911s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   1.380s  |   1.380s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |  20.420s  |  20.420s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   1.187s  |   1.187s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   2.313s  |   2.313s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   5.875s  |   5.875s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  27.807s  |  27.807s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 | 599.265s  | 599.265s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   3.528s  |   3.528s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 | 599.503s  | 599.503s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 | 598.933s  | 598.933s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |  47.918s  |  47.918s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 | 599.185s  | 599.185s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 | 599.790s  | 599.790s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |  13.520s  |  13.520s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   7.485s  |   7.485s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   3.371s  |   3.371s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |  28.356s  |  28.356s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |  14.123s  |  14.123s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             | 304.459s  | 304.459s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             | 599.948s  | 599.948s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   6.121s  |   6.121s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             | 110.194s  | 110.194s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             | 599.320s  | 599.320s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   8.523s  |   8.523s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             | 126.386s  | 126.386s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             | 583.455s  | 583.455s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |   6.300s  |   6.300s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             | 165.790s  | 165.790s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             | 598.381s  | 598.381s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   2.964s  |   2.964s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             |  79.793s  |  79.793s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             | 597.248s  | 597.248s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   6.550s  |   6.550s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   3.406s  |   3.406s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  | 179.825s  | 179.825s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   0.934s  |   0.934s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   4.616s  |   4.616s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                | 599.421s  | 599.421s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   1.128s  |   1.128s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  10.900s  |  10.900s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           | 598.415s  | 598.415s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 | 599.501s  | 599.501s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   2.815s  |   2.815s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 | 599.630s  | 599.630s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 | 598.424s  | 598.424s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   2.126s  |   2.126s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 | 599.869s  | 599.869s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 | 599.435s  | 599.435s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   3.124s  |   3.124s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           | 599.020s  | 599.020s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   5.310s  |   5.310s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 | 599.532s  | 599.532s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 | 599.140s  | 599.140s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           | 599.164s  | 599.164s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  | 599.529s  | 599.529s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |  11.856s  |  11.856s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 | 599.148s  | 599.148s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 | 599.146s  | 599.146s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   3.287s  |   3.287s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   3.757s  |   3.757s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |   5.707s  |   5.707s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 | 599.598s  | 599.598s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   3.554s  |   3.554s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 | 599.262s  | 599.262s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 | 598.396s  | 598.396s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   3.234s  |   3.234s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 | 599.394s  | 599.394s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   5.294s  |   5.294s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   7.183s  |   7.183s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  |  47.650s  |  47.650s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   8.359s  |   8.359s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |  12.526s  |  12.526s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            | 350.287s  | 350.287s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  26.097s  |  26.097s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   2.073s  |   2.073s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  | 599.756s  | 599.756s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   2.345s  |   2.345s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  | 480.013s  | 480.013s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  |  17.064s  |  17.064s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            | 599.245s  | 599.245s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   5.658s  |   5.658s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 | 598.842s  | 598.842s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |  17.432s  |  17.432s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  | 598.837s  | 598.837s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   4.026s  |   4.026s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  | 599.855s  | 599.855s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  | 599.216s  | 599.216s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   5.297s  |   5.297s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  | 598.944s  | 598.944s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  | 599.497s  | 599.497s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   7.675s  |   7.675s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  | 599.110s  | 599.110s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  | 598.449s  | 598.449s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |  14.093s  |  14.093s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            | 599.455s  | 599.455s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   2.975s  |   2.975s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |  16.849s  |  16.849s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   1.505s  |   1.505s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |  12.829s  |  12.829s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           | 599.094s  | 599.094s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           | 599.327s  | 599.327s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           | 598.886s  | 598.886s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  39.573s  |  39.573s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               | 138.001s  | 138.001s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               | 599.310s  | 599.310s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               | 242.440s  | 242.440s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               | 598.876s  | 598.876s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               | 599.286s  | 599.286s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |  57.404s  |  57.404s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   | 123.366s  | 123.366s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 | 114.047s  | 114.047s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |   3.838s  |   3.838s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   4.109s  |   4.109s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   1.583s  |   1.583s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             | 598.827s  | 598.827s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |   3.137s  |   3.137s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   3.819s  |   3.819s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |   8.561s  |   8.561s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |  12.001s  |  12.001s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   4.942s  |   4.942s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   4.522s  |   4.522s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  30.821s  |  30.821s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  48.152s  |  48.152s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            | 599.805s  | 599.805s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    | 536.277s  | 536.277s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   7.614s  |   7.614s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               | 598.748s  | 598.748s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             | 599.719s  | 599.719s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             | 599.268s  | 599.268s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             | 600.006s  | 600.006s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   4.807s  |   4.807s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             | 599.441s  | 599.441s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             | 599.018s  | 599.018s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   4.556s  |   4.556s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             | 599.463s  | 599.463s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             | 599.381s  | 599.381s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  23.340s  |  23.340s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |   8.879s  |   8.879s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               | 599.832s  | 599.832s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         | 599.282s  | 599.282s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  17.264s  |  17.264s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  19.011s  |  19.011s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  19.712s  |  19.712s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  15.106s  |  15.106s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  47.528s  |  47.528s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        | 598.914s  | 598.914s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   1.184s  |   1.184s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            | 598.969s  | 598.969s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            | 599.922s  | 599.922s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   4.136s  |   4.136s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |   6.453s  |   6.453s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   4.500s  |   4.500s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            | 207.056s  | 207.056s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   2.414s  |   2.414s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  17.310s  |  17.310s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              | 598.815s  | 598.815s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  15.544s  |  15.544s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              | 503.164s  | 503.164s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   2.150s  |   2.150s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  32.220s  |  32.220s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          | 599.285s  | 599.285s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   4.146s  |   4.146s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |  13.621s  |  13.621s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  17.278s  |  17.278s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       | 599.175s  | 599.175s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   2.749s  |   2.749s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       |  37.720s  |  37.720s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   5.719s  |   5.719s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  10.865s  |  10.865s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   7.378s  |   7.378s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         | 239.601s  | 239.601s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |  14.260s  |  14.260s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           | 599.864s  | 599.864s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |   7.976s  |   7.976s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  | 599.474s  | 599.474s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            | 599.358s  | 599.358s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              | 599.537s  | 599.537s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   3.052s  |   3.052s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   3.447s  |   3.447s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |  11.218s  |  11.218s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          | 599.097s  | 599.097s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          | 598.866s  | 598.866s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |  22.509s  |  22.509s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          | 599.568s  | 599.568s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          | 599.228s  | 599.228s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |  20.233s  |  20.233s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          | 599.362s  | 599.362s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          | 599.866s  | 599.866s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |  16.438s  |  16.438s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                | 599.563s  | 599.563s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                | 599.862s  | 599.862s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   2.963s  |   2.963s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                | 599.867s  | 599.867s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                | 599.603s  | 599.603s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |  15.839s  |  15.839s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                | 598.567s  | 598.567s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                | 599.357s  | 599.357s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |  13.806s  |  13.806s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                | 598.794s  | 598.794s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                | 599.290s  | 599.290s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          | 599.300s  | 599.300s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |  18.069s  |  18.069s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          | 599.791s  | 599.791s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   3.492s  |   3.492s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |  73.555s  |  73.555s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          | 493.208s  | 493.208s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                | 241.270s  | 241.270s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                | 599.135s  | 599.135s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   9.103s  |   9.103s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   5.366s  |   5.366s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |  16.082s  |  16.082s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   4.947s  |   4.947s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   6.898s  |   6.898s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |  36.986s  |  36.986s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |  28.393s  |  28.393s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   1.044s  |   1.044s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                | 598.643s  | 598.643s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |  17.926s  |  17.926s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                | 599.502s  | 599.502s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                |   8.494s  |   8.494s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |   3.440s  |   3.440s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |  52.415s  |  52.415s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   5.642s  |   5.642s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                | 598.992s  | 598.992s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   7.317s  |   7.317s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |  14.121s  |  14.121s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                | 599.129s  | 599.129s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |  13.600s  |  13.600s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |  12.216s  |  12.216s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   3.147s  |   3.147s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |  89.781s  |  89.781s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   8.717s  |   8.717s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |  18.065s  |  18.065s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |  13.938s  |  13.938s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                | 599.281s  | 599.281s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   3.070s  |   3.070s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   1.191s  |   1.191s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |  12.258s  |  12.258s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                | 598.695s  | 598.695s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                | 599.654s  | 599.654s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |  19.121s  |  19.121s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |  17.765s  |  17.765s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   8.834s  |   8.834s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   1.284s  |   1.284s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |  32.792s  |  32.792s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          | 599.502s  | 599.502s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          | 599.292s  | 599.292s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   2.632s  |   2.632s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   4.744s  |   4.744s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |   1.862s  |   1.862s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   6.240s  |   6.240s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |   8.993s  |   8.993s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |  60.593s  |  60.593s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   2.855s  |   2.855s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   2.575s  |   2.575s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |  10.154s  |  10.154s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   9.520s  |   9.520s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          | 599.678s  | 599.678s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |  14.239s  |  14.239s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   1.918s  |   1.918s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   8.861s  |   8.861s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   7.418s  |   7.418s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   2.502s  |   2.502s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |   9.678s  |   9.678s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |  11.262s  |  11.262s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |  15.754s  |  15.754s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          | 591.531s  | 591.531s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          | 599.045s  | 599.045s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          | 599.330s  | 599.330s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          | 599.138s  | 599.138s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |  12.736s  |  12.736s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   2.466s  |   2.466s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          | 205.828s  | 205.828s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  22.354s  |  22.354s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |  68.844s  |  68.844s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |  33.341s  |  33.341s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           | 598.732s  | 598.732s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           | 599.299s  | 599.299s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   3.265s  |   3.265s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  | 196.244s  | 196.244s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   5.121s  |   5.121s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   1.412s  |   1.412s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        | 598.622s  | 598.622s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   4.480s  |   4.480s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |   8.774s  |   8.774s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |   1.892s  |   1.892s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   5.666s  |   5.666s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |  19.874s  |  19.874s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   0.955s  |   0.955s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |  29.875s  |  29.875s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        | 599.037s  | 599.037s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |  14.188s  |  14.188s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |  43.449s  |  43.449s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |  11.681s  |  11.681s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |  26.259s  |  26.259s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |  15.297s  |  15.297s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   2.507s  |   2.507s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |  25.621s  |  25.621s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |  13.225s  |  13.225s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |  14.796s  |  14.796s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   2.289s  |   2.289s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        | 599.528s  | 599.528s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   4.960s  |   4.960s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   5.967s  |   5.967s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   2.979s  |   2.979s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |  12.524s  |  12.524s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |  46.350s  |  46.350s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        | 599.010s  | 599.010s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |  12.311s  |  12.311s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        | 599.458s  | 599.458s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  35.624s  |  35.624s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   2.707s  |   2.707s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   1.143s  |   1.143s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   6.732s  |   6.732s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        | 599.235s  | 599.235s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        | 598.986s  | 598.986s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   9.592s  |   9.592s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        | 142.688s  | 142.688s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        | 159.279s  | 159.279s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            | 599.692s  | 599.692s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            | 333.262s  | 333.262s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  | 599.775s  | 599.775s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  | 599.132s  | 599.132s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |   9.352s  |   9.352s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  | 598.947s  | 598.947s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  | 599.524s  | 599.524s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   2.590s  |   2.590s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   1.679s  |   1.679s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   2.620s  |   2.620s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   2.343s  |   2.343s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   6.177s  |   6.177s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  | 598.977s  | 598.977s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.941s  |   0.941s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   1.436s  |   1.436s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |  18.387s  |  18.387s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   7.556s  |   7.556s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  | 599.096s  | 599.096s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  | 599.937s  | 599.937s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   1.526s  |   1.526s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |  11.770s  |  11.770s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                | 599.535s  | 599.535s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                | 165.895s  | 165.895s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   3.587s  |   3.587s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              | 123.901s  | 123.901s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        | 599.543s  | 599.543s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   | 599.237s  | 599.237s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   | 599.870s  | 599.870s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   8.087s  |   8.087s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   | 599.193s  | 599.193s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   | 599.974s  | 599.974s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |  24.177s  |  24.177s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   | 599.012s  | 599.012s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   | 599.185s  | 599.185s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |  22.009s  |  22.009s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   | 599.433s  | 599.433s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         | 456.664s  | 456.664s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   2.235s  |   2.235s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   3.361s  |   3.361s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |   8.949s  |   8.949s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         | 599.569s  | 599.569s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   6.455s  |   6.455s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        | 599.654s  | 599.654s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        | 599.794s  | 599.794s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   9.066s  |   9.066s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        | 599.516s  | 599.516s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        | 599.038s  | 599.038s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |  11.378s  |  11.378s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        | 598.930s  | 598.930s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   4.118s  |   4.118s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   2.490s  |   2.490s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   1.676s  |   1.676s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  35.399s  |  35.399s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   6.366s  |   6.366s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   3.163s  |   3.163s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |  40.200s  |  40.200s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  34.944s  |  34.944s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      | 111.584s  | 111.584s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |   8.967s  |   8.967s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            | 597.059s  | 597.059s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            | 599.568s  | 599.568s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |  11.886s  |  11.886s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            | 598.937s  | 598.937s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            | 599.895s  | 599.895s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   8.683s  |   8.683s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            | 599.293s  | 599.293s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  | 599.311s  | 599.311s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   7.141s  |   7.141s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  | 598.929s  | 598.929s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   2.395s  |   2.395s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            | 599.174s  | 599.174s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  77.951s  |  77.951s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  47.304s  |  47.304s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  44.596s  |  44.596s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  61.155s  |  61.155s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   9.141s  |   9.141s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         | 599.022s  | 599.022s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   | 409.175s  | 409.175s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         | 599.018s  | 599.018s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   2.398s  |   2.398s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         |  13.482s  |  13.482s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |  27.410s  |  27.410s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |  23.293s  |  23.293s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   5.606s  |   5.606s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   4.046s  |   4.046s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         | 598.917s  | 598.917s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   9.760s  |   9.760s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   7.355s  |   7.355s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   5.705s  |   5.705s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   4.131s  |   4.131s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   3.053s  |   3.053s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   5.231s  |   5.231s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |  17.926s  |  17.926s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   3.388s  |   3.388s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   | 598.825s  | 598.825s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           |   5.557s  |   5.557s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           | 599.639s  | 599.639s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           | 598.801s  | 598.801s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   1.622s  |   1.622s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           | 102.900s  | 102.900s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           | 154.895s  | 154.895s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           |  14.082s  |  14.082s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           |  45.066s  |  45.066s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  | 598.674s  | 598.674s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   2.708s  |   2.708s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   3.370s  |   3.370s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   2.204s  |   2.204s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   3.219s  |   3.219s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   2.218s  |   2.218s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   3.388s  |   3.388s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             | 598.818s  | 598.818s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   2.178s  |   2.178s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   2.004s  |   2.004s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   4.721s  |   4.721s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   4.710s  |   4.710s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |  25.212s  |  25.212s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             | 598.657s  | 598.657s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   1.552s  |   1.552s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             | 101.984s  | 101.984s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   5.016s  |   5.016s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |   4.072s  |   4.072s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             | 599.786s  | 599.786s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   6.985s  |   6.985s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   1.472s  |   1.472s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |  36.535s  |  36.535s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             | 599.671s  | 599.671s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   3.849s  |   3.849s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             | 127.305s  | 127.305s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             | 599.192s  | 599.192s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   5.103s  |   5.103s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |  23.640s  |  23.640s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              | 598.927s  | 598.927s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      | 599.461s  | 599.461s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   4.896s  |   4.896s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          | 599.619s  | 599.619s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                | 599.188s  | 599.188s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |  51.262s  |  51.262s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |  81.752s  |  81.752s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                | 599.183s  | 599.183s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                | 599.089s  | 599.089s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  38.881s  |  38.881s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                | 599.692s  | 599.692s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                | 598.797s  | 598.797s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  16.960s  |  16.960s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  31.181s  |  31.181s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          | 598.790s  | 598.790s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |  23.997s  |  23.997s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   4.157s  |   4.157s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   6.784s  |   6.784s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              | 599.526s  | 599.526s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       | 598.158s  | 598.158s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       | 599.105s  | 599.105s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  28.478s  |  28.478s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  27.442s  |  27.442s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  44.337s  |  44.337s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  66.743s  |  66.743s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           | 118.513s  | 118.513s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  69.564s  |  69.564s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |   9.613s  |   9.613s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   7.834s  |   7.834s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             | 599.327s  | 599.327s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  76.517s  |  76.517s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |  85.687s  |  85.687s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  33.340s  |  33.340s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  52.006s  |  52.006s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  32.573s  |  32.573s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |  41.783s  |  41.783s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  36.400s  |  36.400s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  52.979s  |  52.979s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           | 599.414s  | 599.414s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           | 599.902s  | 599.902s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |  87.697s  |  87.697s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  29.092s  |  29.092s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 | 599.147s  | 599.147s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 | 598.092s  | 598.092s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |  10.546s  |  10.546s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |  40.207s  |  40.207s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                | 599.563s  | 599.563s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                | 598.991s  | 598.991s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  90.372s  |  90.372s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          | 126.822s  | 126.822s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          | 599.939s  | 599.939s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          | 599.565s  | 599.565s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          | 599.492s  | 599.492s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |  12.474s  |  12.474s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  14.554s  |  14.554s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     | 599.928s  | 599.928s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   2.258s  |   2.258s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                | 104.904s  | 104.904s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                | 598.756s  | 598.756s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   2.562s  |   2.562s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   4.169s  |   4.169s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            | 598.851s  | 598.851s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |  45.662s  |  45.662s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   5.984s  |   5.984s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  38.091s  |  38.091s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   3.008s  |   3.008s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |   3.162s  |   3.162s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   2.547s  |   2.547s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   1.355s  |   1.355s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |  20.658s  |  20.658s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            | 599.122s  | 599.122s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      | 543.199s  | 543.199s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   2.401s  |   2.401s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   0.952s  |   0.952s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      |  38.735s  |  38.735s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   1.818s  |   1.818s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   2.352s  |   2.352s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   1.355s  |   1.355s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  47.816s  |  47.816s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |  87.549s  |  87.549s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   2.620s  |   2.620s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  31.077s  |  31.077s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   5.748s  |   5.748s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |  79.730s  |  79.730s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |  15.767s  |  15.767s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   1.625s  |   1.625s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           | 598.945s  | 598.945s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  14.546s  |  14.546s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       | 124.033s  | 124.033s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  | 598.412s  | 598.412s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  | 142.112s  | 142.112s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           | 599.321s  | 599.321s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      | 599.232s  | 599.232s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   3.825s  |   3.825s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      | 598.995s  | 598.995s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           | 599.169s  | 599.169s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           | 124.129s  | 124.129s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        | 599.311s  | 599.311s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   2.793s  |   2.793s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   3.181s  |   3.181s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   1.406s  |   1.406s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             | 599.734s  | 599.734s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   2.726s  |   2.726s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   5.009s  |   5.009s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |  21.374s  |  21.374s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  41.921s  |  41.921s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   4.647s  |   4.647s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   2.416s  |   2.416s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        | 599.398s  | 599.398s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   2.153s  |   2.153s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   1.428s  |   1.428s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |  13.660s  |  13.660s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   3.483s  |   3.483s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  | 584.659s  | 584.659s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |  10.367s  |  10.367s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   8.846s  |   8.846s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   5.057s  |   5.057s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   2.608s  |   2.608s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   2.848s  |   2.848s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           | 221.128s  | 221.128s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     | 403.915s  | 403.915s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |  11.445s  |  11.445s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   3.191s  |   3.191s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  37.365s  |  37.365s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  51.067s  |  51.067s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   5.077s  |   5.077s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            | 599.563s  | 599.563s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   5.559s  |   5.559s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |  14.722s  |  14.722s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                | 598.855s  | 598.855s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                | 598.658s  | 598.658s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   4.842s  |   4.842s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          | 599.063s  | 599.063s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   2.033s  |   2.033s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   6.784s  |   6.784s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   0.912s  |   0.912s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  10.552s  |  10.552s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           | 599.005s  | 599.005s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        | 187.911s  | 187.911s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  29.054s  |  29.054s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                | 599.543s  | 599.543s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |  25.908s  |  25.908s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   6.486s  |   6.486s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   1.981s  |   1.981s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   4.299s  |   4.299s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  18.231s  |  18.231s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   3.828s  |   3.828s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   4.667s  |   4.667s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |  11.244s  |  11.244s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   3.590s  |   3.590s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  82.494s  |  82.494s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       | 599.972s  | 599.972s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       | 599.245s  | 599.245s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   4.628s  |   4.628s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       | 599.466s  | 599.466s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       | 599.413s  | 599.413s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       | 598.977s  | 598.977s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       | 599.590s  | 599.590s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |   8.921s  |   8.921s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   8.575s  |   8.575s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       | 599.744s  | 599.744s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   4.021s  |   4.021s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       | 599.349s  | 599.349s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     | 599.757s  | 599.757s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   2.099s  |   2.099s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                | 598.864s  | 598.864s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   1.265s  |   1.265s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   8.587s  |   8.587s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   3.501s  |   3.501s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |  21.839s  |  21.839s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   9.960s  |   9.960s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   2.686s  |   2.686s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   3.377s  |   3.377s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |  10.907s  |  10.907s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    | 599.740s  | 599.740s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        | 599.167s  | 599.167s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        | 599.124s  | 599.124s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   7.900s  |   7.900s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  | 517.687s  | 517.687s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  | 599.081s  | 599.081s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  | 598.951s  | 598.951s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  38.918s  |  38.918s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |  27.401s  |  27.401s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   6.570s  |   6.570s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           | 461.549s  | 461.549s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           | 341.259s  | 341.259s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   2.205s  |   2.205s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   4.232s  |   4.232s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   5.599s  |   5.599s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   3.888s  |   3.888s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   5.143s  |   5.143s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   1.149s  |   1.149s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           | 594.560s  | 594.560s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   2.379s  |   2.379s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   4.034s  |   4.034s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           | 132.630s  | 132.630s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   1.078s  |   1.078s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           | 589.318s  | 589.318s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   2.448s  |   2.448s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   5.903s  |   5.903s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   4.425s  |   4.425s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   1.140s  |   1.140s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   2.425s  |   2.425s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   4.130s  |   4.130s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   2.456s  |   2.456s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   4.643s  |   4.643s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.846s  |   0.846s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |   5.933s  |   5.933s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   4.395s  |   4.395s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   3.293s  |   3.293s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           | 294.480s  | 294.480s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   5.987s  |   5.987s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           | 494.818s  | 494.818s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   2.814s  |   2.814s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   5.684s  |   5.684s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   1.290s  |   1.290s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   2.224s  |   2.224s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |  32.291s  |  32.291s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   1.292s  |   1.292s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           | 108.943s  | 108.943s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   2.752s  |   2.752s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   2.499s  |   2.499s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   8.801s  |   8.801s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   2.915s  |   2.915s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |  77.796s  |  77.796s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   1.114s  |   1.114s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   6.843s  |   6.843s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   4.708s  |   4.708s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   2.671s  |   2.671s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   3.043s  |   3.043s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |  12.305s  |  12.305s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |   2.512s  |   2.512s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   2.794s  |   2.794s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  19.330s  |  19.330s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   3.608s  |   3.608s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |   3.785s  |   3.785s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   2.355s  |   2.355s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            | 208.582s  | 208.582s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   2.818s  |   2.818s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |   4.826s  |   4.826s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   6.230s  |   6.230s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   4.138s  |   4.138s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   2.277s  |   2.277s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  69.887s  |  69.887s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           | 116.184s  | 116.184s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   3.788s  |   3.788s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   6.238s  |   6.238s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           | 148.961s  | 148.961s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   1.303s  |   1.303s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   2.836s  |   2.836s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   3.142s  |   3.142s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   2.986s  |   2.986s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   2.333s  |   2.333s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   3.414s  |   3.414s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           | 123.109s  | 123.109s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   4.167s  |   4.167s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   2.482s  |   2.482s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           | 598.489s  | 598.489s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   7.467s  |   7.467s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   5.010s  |   5.010s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           | 599.907s  | 599.907s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   2.985s  |   2.985s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   0.968s  |   0.968s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   5.847s  |   5.847s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           | 121.035s  | 121.035s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.663s  |   0.663s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   1.210s  |   1.210s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   6.670s  |   6.670s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           | 599.052s  | 599.052s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   2.446s  |   2.446s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   4.534s  |   4.534s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   8.350s  |   8.350s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   8.223s  |   8.223s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   4.694s  |   4.694s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |  10.444s  |  10.444s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   2.137s  |   2.137s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           | 598.858s  | 598.858s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  36.708s  |  36.708s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   2.204s  |   2.204s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   2.191s  |   2.191s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   5.612s  |   5.612s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   4.355s  |   4.355s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   2.348s  |   2.348s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |  10.360s  |  10.360s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   4.203s  |   4.203s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |  89.576s  |  89.576s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |   2.712s  |   2.712s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.722s  |   0.722s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   1.221s  |   1.221s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.561s  |   1.561s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   2.023s  |   2.023s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   1.873s  |   1.873s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   8.542s  |   8.542s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   1.377s  |   1.377s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            | 599.070s  | 599.070s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            | 231.784s  | 231.784s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            | 599.812s  | 599.812s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            | 599.563s  | 599.563s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            | 389.859s  | 389.859s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            | 108.945s  | 108.945s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            | 598.954s  | 598.954s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
</details>
