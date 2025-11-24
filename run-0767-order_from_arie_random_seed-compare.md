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
Job tag: order_from_arie_random_seed
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: ead16e5743ae3c1eae147eb740b144f5ed1c86b1
Z3 branch: order_switch
Z3 options: "-T:600 nlsat.correct_order=true smt.random_seed=555"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: parameter correct order experiment

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: order_from_arie_random_seed
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: ead16e5743ae3c1eae147eb740b144f5ed1c86b1
Z3 branch: order_switch
Z3 options: "-T:600 nlsat.correct_order=true smt.random_seed=555"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: parameter correct order experiment

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.452s  |   1.452s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.452s  |   1.452s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.452s  |   1.452s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.452s  |   1.452s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 600.640s |5413.0MiB|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                       | 600.572s |2829.0MiB|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                         | 600.555s |1421.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 600.555s |2416.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.527s |2072.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 600.527s |2239.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                         | 600.512s |2442.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.507s |4362.0MiB|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                         | 600.473s |1469.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 600.457s |1778.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              | 600.454s |1529.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 600.451s |2214.0MiB|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                   | 600.445s |2663.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                         | 600.444s |1656.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 600.439s |1599.0MiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       | 600.437s |1532.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 600.435s |3280.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                        | 600.433s |1937.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.425s |2324.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2               | 600.422s |1781.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 600.640s |5413.0MiB|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                       | 600.572s |2829.0MiB|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                         | 600.555s |1421.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 600.555s |2416.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.527s |2072.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 600.527s |2239.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                         | 600.512s |2442.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.507s |4362.0MiB|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                         | 600.473s |1469.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 600.457s |1778.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              | 600.454s |1529.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 600.451s |2214.0MiB|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                   | 600.445s |2663.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                         | 600.444s |1656.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 600.439s |1599.0MiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       | 600.437s |1532.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 600.435s |3280.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                        | 600.433s |1937.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.425s |2324.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2               | 600.422s |1781.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |92.5MiB|92.5MiB|0B| 0.0%|
|04.smt2                                                                                     |71.968MiB|71.968MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.688MiB|31.688MiB|0B| 0.0%|
|1010.smt2                                                                                   |28.756MiB|28.756MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.632MiB|23.632MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.068MiB|23.068MiB|0B| 0.0%|
|1034.smt2                                                                                   |23.872MiB|23.872MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.86MiB|24.86MiB|0B| 0.0%|
|107.smt2                                                                                    |22.484MiB|22.484MiB|0B| 0.0%|
|1082.smt2                                                                                   |26.472MiB|26.472MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.284MiB|80.284MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.132MiB|23.132MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.888MiB|22.888MiB|0B| 0.0%|
|1092.smt2                                                                                   |22.92MiB|22.92MiB|0B| 0.0%|
|11.smt2                                                                                     |75.476MiB|75.476MiB|0B| 0.0%|
|1104.smt2                                                                                   |22.988MiB|22.988MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.46MiB|23.46MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.196MiB|23.196MiB|0B| 0.0%|
|1126.smt2                                                                                   |23.616MiB|23.616MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |92.5MiB|92.5MiB|0B| 0.0%|
|04.smt2                                                                                     |71.968MiB|71.968MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.688MiB|31.688MiB|0B| 0.0%|
|1010.smt2                                                                                   |28.756MiB|28.756MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.632MiB|23.632MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.068MiB|23.068MiB|0B| 0.0%|
|1034.smt2                                                                                   |23.872MiB|23.872MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.86MiB|24.86MiB|0B| 0.0%|
|107.smt2                                                                                    |22.484MiB|22.484MiB|0B| 0.0%|
|1082.smt2                                                                                   |26.472MiB|26.472MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.284MiB|80.284MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.132MiB|23.132MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.888MiB|22.888MiB|0B| 0.0%|
|1092.smt2                                                                                   |22.92MiB|22.92MiB|0B| 0.0%|
|11.smt2                                                                                     |75.476MiB|75.476MiB|0B| 0.0%|
|1104.smt2                                                                                   |22.988MiB|22.988MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.46MiB|23.46MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.196MiB|23.196MiB|0B| 0.0%|
|1126.smt2                                                                                   |23.616MiB|23.616MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |92.5MiB|92.5MiB|0B| 0.0%|
|04.smt2                                                                                     |71.968MiB|71.968MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.688MiB|31.688MiB|0B| 0.0%|
|1010.smt2                                                                                   |28.756MiB|28.756MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.632MiB|23.632MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.068MiB|23.068MiB|0B| 0.0%|
|1034.smt2                                                                                   |23.872MiB|23.872MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.86MiB|24.86MiB|0B| 0.0%|
|107.smt2                                                                                    |22.484MiB|22.484MiB|0B| 0.0%|
|1082.smt2                                                                                   |26.472MiB|26.472MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.284MiB|80.284MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.132MiB|23.132MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.888MiB|22.888MiB|0B| 0.0%|
|1092.smt2                                                                                   |22.92MiB|22.92MiB|0B| 0.0%|
|11.smt2                                                                                     |75.476MiB|75.476MiB|0B| 0.0%|
|1104.smt2                                                                                   |22.988MiB|22.988MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.46MiB|23.46MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.196MiB|23.196MiB|0B| 0.0%|
|1126.smt2                                                                                   |23.616MiB|23.616MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |92.5MiB|92.5MiB|0B| 0.0%|
|04.smt2                                                                                     |71.968MiB|71.968MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.688MiB|31.688MiB|0B| 0.0%|
|1010.smt2                                                                                   |28.756MiB|28.756MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.632MiB|23.632MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.068MiB|23.068MiB|0B| 0.0%|
|1034.smt2                                                                                   |23.872MiB|23.872MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.86MiB|24.86MiB|0B| 0.0%|
|107.smt2                                                                                    |22.484MiB|22.484MiB|0B| 0.0%|
|1082.smt2                                                                                   |26.472MiB|26.472MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.284MiB|80.284MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.132MiB|23.132MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.888MiB|22.888MiB|0B| 0.0%|
|1092.smt2                                                                                   |22.92MiB|22.92MiB|0B| 0.0%|
|11.smt2                                                                                     |75.476MiB|75.476MiB|0B| 0.0%|
|1104.smt2                                                                                   |22.988MiB|22.988MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.46MiB|23.46MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.196MiB|23.196MiB|0B| 0.0%|
|1126.smt2                                                                                   |23.616MiB|23.616MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 600.640s |5413.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.507s |4362.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 600.388s |3451.0MiB|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                             | 600.406s |3403.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 600.435s |3280.0MiB|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                       | 600.572s |2829.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              | 600.411s |2718.0MiB|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                   | 600.445s |2663.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 600.317s |2641.0MiB|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                           | 600.377s |2457.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                         | 600.512s |2442.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                         | 600.421s |2423.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                          | 600.369s |2422.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 600.555s |2416.0MiB|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                            | 600.311s |2394.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.425s |2324.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 600.527s |2239.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 600.451s |2214.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              | 600.250s |2085.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.527s |2072.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 600.640s |5413.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.507s |4362.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 600.388s |3451.0MiB|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                             | 600.406s |3403.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 600.435s |3280.0MiB|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                       | 600.572s |2829.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              | 600.411s |2718.0MiB|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                   | 600.445s |2663.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 600.317s |2641.0MiB|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                           | 600.377s |2457.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                         | 600.512s |2442.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                         | 600.421s |2423.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                          | 600.369s |2422.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 600.555s |2416.0MiB|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                            | 600.311s |2394.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.425s |2324.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 600.527s |2239.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 600.451s |2214.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              | 600.250s |2085.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.527s |2072.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.452s  |   1.452s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.593s  |   0.593s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|124.smt2                                                                                    | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   0.910s  |   0.910s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   1.295s  |   1.295s  |   0.000s  | 0.0%|
|140.smt2                                                                                    | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   2.321s  |   2.321s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   1.434s  |   1.434s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   2.284s  |   2.284s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   6.218s  |   6.218s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   3.654s  |   3.654s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   2.342s  |   2.342s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|177.smt2                                                                                    | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   0.731s  |   0.731s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   3.583s  |   3.583s  |   0.000s  | 0.0%|
|181.smt2                                                                                    | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|182.smt2                                                                                    | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|183.smt2                                                                                    | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|185.smt2                                                                                    | 600.282s  | 600.282s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   3.440s  |   3.440s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   1.723s  |   1.723s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   2.314s  |   2.314s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   3.020s  |   3.020s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   4.244s  |   4.244s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   6.173s  |   6.173s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   2.997s  |   2.997s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   2.082s  |   2.082s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   1.300s  |   1.300s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   1.473s  |   1.473s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   3.573s  |   3.573s  |   0.000s  | 0.0%|
|35.smt2                                                                                     | 600.053s  | 600.053s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|40.smt2                                                                                     | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   1.901s  |   1.901s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   1.097s  |   1.097s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|54.smt2                                                                                     | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   2.417s  |   2.417s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   1.802s  |   1.802s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   1.982s  |   1.982s  |   0.000s  | 0.0%|
|58.smt2                                                                                     | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   2.610s  |   2.610s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   3.271s  |   3.271s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   5.180s  |   5.180s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|65.smt2                                                                                     | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   1.673s  |   1.673s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|73.smt2                                                                                     | 600.046s  | 600.046s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   3.266s  |   3.266s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   2.677s  |   2.677s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   4.725s  |   4.725s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|966.smt2                                                                                    | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|98.smt2                                                                                     | 600.057s  | 600.057s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|99.smt2                                                                                     | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |  15.709s  |  15.709s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.803s  |   0.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   5.622s  |   5.622s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          | 600.231s  | 600.231s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |  11.637s  |  11.637s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   1.036s  |   1.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.678s  |   0.678s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |  16.139s  |  16.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          |  61.904s  |  61.904s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   2.388s  |   2.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   1.693s  |   1.693s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            | 600.333s  | 600.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   4.590s  |   4.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   2.773s  |   2.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       |  30.012s  |  30.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   8.200s  |   8.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |   3.519s  |   3.519s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |  20.511s  |  20.511s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |   9.176s  |   9.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   1.571s  |   1.571s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   1.177s  |   1.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           |   3.942s  |   3.942s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           | 136.741s  | 136.741s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         | 119.326s  | 119.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   5.612s  |   5.612s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  22.024s  |  22.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   3.809s  |   3.809s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |  14.502s  |  14.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             | 600.287s  | 600.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |  13.453s  |  13.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  13.555s  |  13.555s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 |  10.680s  |  10.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   3.896s  |   3.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   5.496s  |   5.496s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |  13.152s  |  13.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   1.699s  |   1.699s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              |   4.345s  |   4.345s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |   5.336s  |   5.336s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   0.941s  |   0.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |   6.818s  |   6.818s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               |  40.722s  |  40.722s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         | 600.137s  | 600.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   8.967s  |   8.967s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |  14.508s  |  14.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |  14.987s  |  14.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 |  34.710s  |  34.710s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   2.131s  |   2.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   3.274s  |   3.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   2.808s  |   2.808s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   5.550s  |   5.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   1.001s  |   1.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          |  12.915s  |  12.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   2.951s  |   2.951s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   3.265s  |   3.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      | 600.210s  | 600.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |   2.815s  |   2.815s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   5.130s  |   5.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  16.490s  |  16.490s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |  11.341s  |  11.341s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |  41.884s  |  41.884s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   2.387s  |   2.387s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               | 434.916s  | 434.916s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |   3.405s  |   3.405s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   6.480s  |   6.480s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   6.636s  |   6.636s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   |  33.327s  |  33.327s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   |   4.566s  |   4.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             | 600.282s  | 600.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  26.330s  |  26.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   2.012s  |   2.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    | 600.239s  | 600.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |  16.586s  |  16.586s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        |   3.165s  |   3.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  38.003s  |  38.003s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  28.263s  |  28.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     |   4.915s  |   4.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               | 548.068s  | 548.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   4.247s  |   4.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   4.400s  |   4.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   3.573s  |   3.573s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |  13.451s  |  13.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               | 600.338s  | 600.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   1.389s  |   1.389s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   3.647s  |   3.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   6.198s  |   6.198s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   2.827s  |   2.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   1.331s  |   1.331s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   6.452s  |   6.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                | 600.241s  | 600.241s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              |   4.043s  |   4.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |  19.261s  |  19.261s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   1.615s  |   1.615s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   8.018s  |   8.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  14.089s  |  14.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  37.949s  |  37.949s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   2.724s  |   2.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  50.141s  |  50.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          | 600.164s  | 600.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          | 600.197s  | 600.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |  21.182s  |  21.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          | 600.229s  | 600.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          | 600.238s  | 600.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  28.706s  |  28.706s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   4.946s  |   4.946s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  21.866s  |  21.866s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   3.471s  |   3.471s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    | 600.215s  | 600.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   4.225s  |   4.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   2.041s  |   2.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    |   3.886s  |   3.886s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   4.522s  |   4.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   2.586s  |   2.586s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |   4.552s  |   4.552s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |  63.394s  |  63.394s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |   6.284s  |   6.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   5.101s  |   5.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   1.284s  |   1.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  59.157s  |  59.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  49.061s  |  49.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  40.521s  |  40.521s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  41.444s  |  41.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  78.795s  |  78.795s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  60.825s  |  60.825s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  | 263.676s  | 263.676s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  | 154.984s  | 154.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |   5.495s  |   5.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |   3.705s  |   3.705s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   3.599s  |   3.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.889s  |   0.889s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   1.890s  |   1.890s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |  93.353s  |  93.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |   8.225s  |   8.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   2.578s  |   2.578s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  10.641s  |  10.641s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        | 520.006s  | 520.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.635s  |   0.635s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   4.709s  |   4.709s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |   4.432s  |   4.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |   3.323s  |   3.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   | 600.159s  | 600.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     |  21.715s  |  21.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   4.439s  |   4.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   4.883s  |   4.883s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   1.891s  |   1.891s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                | 434.520s  | 434.520s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   1.321s  |   1.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                |   5.072s  |   5.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   2.824s  |   2.824s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   6.322s  |   6.322s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      |  27.309s  |  27.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |   2.242s  |   2.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   1.856s  |   1.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   4.765s  |   4.765s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   2.697s  |   2.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |  10.321s  |  10.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   3.924s  |   3.924s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |   8.281s  |   8.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |  23.345s  |  23.345s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   6.358s  |   6.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                | 143.501s  | 143.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   4.910s  |   4.910s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |   4.474s  |   4.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   2.868s  |   2.868s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   3.308s  |   3.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   2.884s  |   2.884s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |  11.277s  |  11.277s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              | 600.053s  | 600.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   4.940s  |   4.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   5.715s  |   5.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   8.192s  |   8.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   2.049s  |   2.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  14.423s  |  14.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |   4.973s  |   4.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          | 600.369s  | 600.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |  10.208s  |  10.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          | 600.151s  | 600.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |  15.856s  |  15.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          |   2.101s  |   2.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   6.435s  |   6.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   4.661s  |   4.661s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |  72.531s  |  72.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |   3.616s  |   3.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |  41.731s  |  41.731s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |  10.222s  |  10.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   0.712s  |   0.712s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   2.840s  |   2.840s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   3.338s  |   3.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |   2.212s  |   2.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   4.510s  |   4.510s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |  12.679s  |  12.679s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |  18.970s  |  18.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           |   2.197s  |   2.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |   1.035s  |   1.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   2.500s  |   2.500s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   2.939s  |   2.939s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   7.337s  |   7.337s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |   6.499s  |   6.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   2.244s  |   2.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   1.948s  |   1.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   2.317s  |   2.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |   1.116s  |   1.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           | 195.776s  | 195.776s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |   8.534s  |   8.534s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |   6.916s  |   6.916s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |  12.871s  |  12.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |  17.491s  |  17.491s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   2.671s  |   2.671s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |   2.189s  |   2.189s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   1.054s  |   1.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   1.214s  |   1.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   7.626s  |   7.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   8.342s  |   8.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   1.571s  |   1.571s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           | 592.115s  | 592.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   2.148s  |   2.148s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |  32.809s  |  32.809s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |   2.243s  |   2.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   2.231s  |   2.231s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     | 600.252s  | 600.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |   6.717s  |   6.717s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |  20.916s  |  20.916s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   2.270s  |   2.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   7.004s  |   7.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |   1.683s  |   1.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |  49.571s  |  49.571s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     | 188.610s  | 188.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     | 213.458s  | 213.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   5.987s  |   5.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   1.323s  |   1.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   0.634s  |   0.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   1.625s  |   1.625s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   2.117s  |   2.117s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |  32.586s  |  32.586s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |   2.603s  |   2.603s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |   0.953s  |   0.953s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |   7.528s  |   7.528s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               | 600.255s  | 600.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   3.178s  |   3.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |  16.893s  |  16.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |  10.356s  |  10.356s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   2.454s  |   2.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   5.679s  |   5.679s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |   5.755s  |   5.755s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   1.445s  |   1.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   1.816s  |   1.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |   9.865s  |   9.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   1.029s  |   1.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  23.778s  |  23.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   0.756s  |   0.756s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |   1.216s  |   1.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               | 600.155s  | 600.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |   6.107s  |   6.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   7.871s  |   7.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |   4.659s  |   4.659s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |   0.613s  |   0.613s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |  42.166s  |  42.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               | 600.228s  | 600.228s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |  92.404s  |  92.404s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   1.507s  |   1.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   0.907s  |   0.907s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   1.950s  |   1.950s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  25.834s  |  25.834s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               | 580.157s  | 580.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   1.334s  |   1.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   1.590s  |   1.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   2.735s  |   2.735s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |  38.508s  |  38.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   0.851s  |   0.851s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   3.617s  |   3.617s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   6.445s  |   6.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   1.025s  |   1.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   8.699s  |   8.699s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               | 600.324s  | 600.324s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   1.306s  |   1.306s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |  90.509s  |  90.509s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               |   2.243s  |   2.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   0.563s  |   0.563s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               | 600.216s  | 600.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               | 600.191s  | 600.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   2.612s  |   2.612s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |   5.524s  |   5.524s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |   2.178s  |   2.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |  20.181s  |  20.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   3.769s  |   3.769s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |   2.195s  |   2.195s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |   1.734s  |   1.734s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   1.176s  |   1.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |   2.213s  |   2.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   2.211s  |   2.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             | 186.806s  | 186.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   0.802s  |   0.802s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   1.407s  |   1.407s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |   6.267s  |   6.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   6.046s  |   6.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   0.895s  |   0.895s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |   2.155s  |   2.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |   3.033s  |   3.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   2.152s  |   2.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   2.192s  |   2.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   2.396s  |   2.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |  11.940s  |  11.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |  21.415s  |  21.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             | 530.012s  | 530.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |  15.614s  |  15.614s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             | 600.176s  | 600.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             | 600.154s  | 600.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   5.700s  |   5.700s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   1.555s  |   1.555s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   7.943s  |   7.943s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             | 600.211s  | 600.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             |   2.194s  |   2.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |   3.528s  |   3.528s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |  12.334s  |  12.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               |  27.005s  |  27.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |   1.372s  |   1.372s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |  22.586s  |  22.586s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         | 120.096s  | 120.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              | 119.486s  | 119.486s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   0.927s  |   0.927s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   2.590s  |   2.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |   1.738s  |   1.738s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   2.099s  |   2.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |  29.285s  |  29.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |   9.710s  |   9.710s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   2.476s  |   2.476s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |  26.750s  |  26.750s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   1.348s  |   1.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    | 600.148s  | 600.148s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   0.639s  |   0.639s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   0.676s  |   0.676s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   3.273s  |   3.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   1.316s  |   1.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   0.770s  |   0.770s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |  19.705s  |  19.705s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   1.261s  |   1.261s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    | 600.046s  | 600.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |   9.369s  |   9.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   2.371s  |   2.371s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  21.284s  |  21.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              | 118.264s  | 118.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |  20.280s  |  20.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   1.934s  |   1.934s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    |   2.182s  |   2.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |   1.753s  |   1.753s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   2.288s  |   2.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   4.721s  |   4.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |  39.007s  |  39.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   0.814s  |   0.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   5.942s  |   5.942s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |  77.233s  |  77.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   0.565s  |   0.565s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  | 109.647s  | 109.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |  45.323s  |  45.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          | 600.186s  | 600.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |  70.532s  |  70.532s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   2.856s  |   2.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  13.001s  |  13.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |   1.492s  |   1.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   6.425s  |   6.425s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |  13.796s  |  13.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   0.974s  |   0.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   2.196s  |   2.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   1.596s  |   1.596s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          | 600.137s  | 600.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   5.252s  |   5.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   2.183s  |   2.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   0.764s  |   0.764s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |  28.445s  |  28.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |  18.781s  |  18.781s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |  50.377s  |  50.377s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |  13.457s  |  13.457s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |  48.442s  |  48.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |  11.643s  |  11.643s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |   5.491s  |   5.491s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   2.403s  |   2.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        | 104.498s  | 104.498s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   1.267s  |   1.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |  29.162s  |  29.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   1.741s  |   1.741s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        | 600.127s  | 600.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   2.484s  |   2.484s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   1.000s  |   1.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        | 600.188s  | 600.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   1.160s  |   1.160s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   2.985s  |   2.985s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   2.225s  |   2.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |  16.064s  |  16.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |   9.317s  |   9.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |   1.755s  |   1.755s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   2.463s  |   2.463s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |  10.870s  |  10.870s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |   7.664s  |   7.664s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |   9.141s  |   9.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   1.896s  |   1.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |   5.748s  |   5.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |  33.727s  |  33.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |   9.489s  |   9.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   1.867s  |   1.867s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   2.176s  |   2.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  | 600.173s  | 600.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   2.257s  |   2.257s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   2.174s  |   2.174s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |  28.613s  |  28.613s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   2.101s  |   2.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  97.135s  |  97.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |  15.697s  |  15.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   1.751s  |   1.751s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   6.890s  |   6.890s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |  12.567s  |  12.567s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       | 600.026s  | 600.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |   0.989s  |   0.989s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |  12.593s  |  12.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |   1.117s  |   1.117s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |  70.997s  |  70.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   4.499s  |   4.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |  12.855s  |  12.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   0.913s  |   0.913s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   1.319s  |   1.319s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   2.184s  |   2.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   1.918s  |   1.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   1.407s  |   1.407s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 | 600.345s  | 600.345s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  69.148s  |  69.148s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |  16.724s  |  16.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  26.553s  |  26.553s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   2.590s  |   2.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |  13.290s  |  13.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  20.415s  |  20.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   1.409s  |   1.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  42.268s  |  42.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  42.775s  |  42.775s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |  12.220s  |  12.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |  44.007s  |  44.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  34.035s  |  34.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   1.423s  |   1.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            | 169.069s  | 169.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   1.937s  |   1.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   1.689s  |   1.689s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |  10.312s  |  10.312s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   6.544s  |   6.544s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   6.744s  |   6.744s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   3.707s  |   3.707s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   3.129s  |   3.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |  21.021s  |  21.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   9.057s  |   9.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   6.196s  |   6.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   2.883s  |   2.883s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   1.325s  |   1.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |  41.196s  |  41.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   2.507s  |   2.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   5.652s  |   5.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   8.597s  |   8.597s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   7.175s  |   7.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |   3.197s  |   3.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |  12.675s  |  12.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |  21.339s  |  21.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |  30.630s  |  30.630s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |  17.936s  |  17.936s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   4.136s  |   4.136s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |  14.813s  |  14.813s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   4.041s  |   4.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  50.895s  |  50.895s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   8.799s  |   8.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  34.841s  |  34.841s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |  13.342s  |  13.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   4.109s  |   4.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   2.660s  |   2.660s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  45.428s  |  45.428s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   8.657s  |   8.657s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   3.069s  |   3.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |  14.786s  |  14.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   4.115s  |   4.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   4.745s  |   4.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |  25.699s  |  25.699s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   9.292s  |   9.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   1.815s  |   1.815s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   4.445s  |   4.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   3.554s  |   3.554s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   1.301s  |   1.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   9.286s  |   9.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   3.843s  |   3.843s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   5.164s  |   5.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   3.631s  |   3.631s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   3.794s  |   3.794s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   5.290s  |   5.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |  11.812s  |  11.812s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |  12.408s  |  12.408s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   1.594s  |   1.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  13.570s  |  13.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   3.368s  |   3.368s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   8.233s  |   8.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                | 600.422s  | 600.422s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   2.496s  |   2.496s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |  11.352s  |  11.352s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   2.472s  |   2.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   2.499s  |   2.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   2.134s  |   2.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  11.147s  |  11.147s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |   3.148s  |   3.148s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   4.610s  |   4.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   3.393s  |   3.393s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  93.140s  |  93.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   3.254s  |   3.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   2.119s  |   2.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   6.439s  |   6.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   3.901s  |   3.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                | 562.673s  | 562.673s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   8.589s  |   8.589s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   3.252s  |   3.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   4.041s  |   4.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  11.590s  |  11.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  19.267s  |  19.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |  13.440s  |  13.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   3.798s  |   3.798s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   9.496s  |   9.496s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   9.480s  |   9.480s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   2.323s  |   2.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |  10.199s  |  10.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                | 600.414s  | 600.414s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |  21.899s  |  21.899s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  17.233s  |  17.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   2.515s  |   2.515s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |  63.150s  |  63.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  14.681s  |  14.681s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   4.867s  |   4.867s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   1.622s  |   1.622s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   3.467s  |   3.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |  12.533s  |  12.533s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   4.189s  |   4.189s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   2.486s  |   2.486s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  17.137s  |  17.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |  10.652s  |  10.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |   9.326s  |   9.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   2.359s  |   2.359s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   3.634s  |   3.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   3.059s  |   3.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   2.186s  |   2.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |  10.299s  |  10.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   3.627s  |   3.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |  16.180s  |  16.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   2.373s  |   2.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   3.570s  |   3.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   2.910s  |   2.910s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |  13.212s  |  13.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |  13.342s  |  13.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   6.105s  |   6.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   3.026s  |   3.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |  13.349s  |  13.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   9.570s  |   9.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   8.425s  |   8.425s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |   8.725s  |   8.725s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |  10.231s  |  10.231s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   1.625s  |   1.625s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   3.184s  |   3.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   5.241s  |   5.241s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          | 146.675s  | 146.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          | 141.059s  | 141.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          |  56.586s  |  56.586s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   3.167s  |   3.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   6.097s  |   6.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            | 132.231s  | 132.231s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            | 387.895s  | 387.895s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   2.747s  |   2.747s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   2.396s  |   2.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   2.512s  |   2.512s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   2.353s  |   2.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    | 262.761s  | 262.761s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   4.446s  |   4.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       | 591.014s  | 591.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   3.392s  |   3.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   4.232s  |   4.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |  21.263s  |  21.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   1.830s  |   1.830s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   6.060s  |   6.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   8.973s  |   8.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       | 389.855s  | 389.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   2.258s  |   2.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   2.503s  |   2.503s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   1.125s  |   1.125s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   9.660s  |   9.660s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |   9.998s  |   9.998s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |   4.296s  |   4.296s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |  39.258s  |  39.258s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.883s  |   0.883s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |   3.532s  |   3.532s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               | 159.186s  | 159.186s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   6.733s  |   6.733s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   2.570s  |   2.570s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          | 257.309s  | 257.309s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   1.971s  |   1.971s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   1.983s  |   1.983s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               |   3.940s  |   3.940s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               | 600.183s  | 600.183s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  23.119s  |  23.119s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   3.829s  |   3.829s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         | 600.198s  | 600.198s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         |   4.320s  |   4.320s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |   6.741s  |   6.741s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               | 600.454s  | 600.454s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  55.152s  |  55.152s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   9.981s  |   9.981s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |   6.200s  |   6.200s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         | 600.433s  | 600.433s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |   7.910s  |   7.910s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   1.419s  |   1.419s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         | 600.208s  | 600.208s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  22.874s  |  22.874s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  54.235s  |  54.235s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    | 600.640s  | 600.640s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  12.512s  |  12.512s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    | 600.445s  | 600.445s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  23.505s  |  23.505s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  28.534s  |  28.534s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   1.290s  |   1.290s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              | 600.420s  | 600.420s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  42.931s  |  42.931s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   5.268s  |   5.268s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   5.892s  |   5.892s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  66.257s  |  66.257s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.872s  |   0.872s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |   3.445s  |   3.445s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |   3.066s  |   3.066s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   7.398s  |   7.398s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   1.844s  |   1.844s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |   4.689s  |   4.689s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   2.763s  |   2.763s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  | 600.359s  | 600.359s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   2.953s  |   2.953s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  37.676s  |  37.676s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |   7.096s  |   7.096s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 | 593.561s  | 593.561s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  13.806s  |  13.806s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           | 600.346s  | 600.346s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |  10.713s  |  10.713s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   3.557s  |   3.557s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  16.948s  |  16.948s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |   2.150s  |   2.150s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   5.930s  |   5.930s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |  10.030s  |  10.030s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |   6.015s  |   6.015s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |  15.436s  |  15.436s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      | 126.617s  | 126.617s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  41.501s  |  41.501s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  52.777s  |  52.777s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  23.633s  |  23.633s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  60.467s  |  60.467s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            | 408.596s  | 408.596s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   4.234s  |   4.234s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             |   3.575s  |   3.575s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   1.810s  |   1.810s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             | 600.223s  | 600.223s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   2.886s  |   2.886s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |   4.388s  |   4.388s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   3.595s  |   3.595s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   2.815s  |   2.815s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   6.140s  |   6.140s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |   2.258s  |   2.258s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   2.603s  |   2.603s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |   5.427s  |   5.427s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   2.707s  |   2.707s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   4.550s  |   4.550s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   8.634s  |   8.634s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   3.573s  |   3.573s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   1.703s  |   1.703s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   1.293s  |   1.293s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |   9.723s  |   9.723s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   2.114s  |   2.114s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |  25.280s  |  25.280s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               | 600.527s  | 600.527s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   1.948s  |   1.948s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            | 600.221s  | 600.221s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   1.229s  |   1.229s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 | 600.298s  | 600.298s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |  17.458s  |  17.458s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  28.795s  |  28.795s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |  10.474s  |  10.474s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |  14.619s  |  14.619s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |  11.806s  |  11.806s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 | 183.347s  | 183.347s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      | 450.968s  | 450.968s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |  13.336s  |  13.336s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |  12.198s  |  12.198s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  31.008s  |  31.008s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |  12.859s  |  12.859s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  19.014s  |  19.014s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              | 600.043s  | 600.043s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |  56.708s  |  56.708s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   3.227s  |   3.227s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   3.320s  |   3.320s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      | 600.211s  | 600.211s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   3.242s  |   3.242s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       | 145.548s  | 145.548s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   1.286s  |   1.286s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       | 279.154s  | 279.154s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   0.695s  |   0.695s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.702s  |   0.702s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   9.834s  |   9.834s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |  33.991s  |  33.991s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |   2.134s  |   2.134s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.987s  |   0.987s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       | 600.117s  | 600.117s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   8.915s  |   8.915s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |  22.241s  |  22.241s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       |   2.145s  |   2.145s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |  10.065s  |  10.065s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   1.213s  |   1.213s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   5.259s  |   5.259s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       | 413.593s  | 413.593s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       |   3.282s  |   3.282s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   2.622s  |   2.622s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |  23.665s  |  23.665s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   4.552s  |   4.552s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   0.898s  |   0.898s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.950s  |   0.950s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   2.545s  |   2.545s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   2.527s  |   2.527s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   1.124s  |   1.124s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   0.848s  |   0.848s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |  13.371s  |  13.371s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |   7.814s  |   7.814s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |   9.931s  |   9.931s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   3.126s  |   3.126s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   5.421s  |   5.421s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   1.326s  |   1.326s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   6.388s  |   6.388s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                | 600.211s  | 600.211s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   3.192s  |   3.192s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   2.087s  |   2.087s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   1.992s  |   1.992s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      | 600.049s  | 600.049s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   1.401s  |   1.401s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   8.218s  |   8.218s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |   1.889s  |   1.889s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   3.271s  |   3.271s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   7.508s  |   7.508s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   1.970s  |   1.970s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   1.419s  |   1.419s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   1.257s  |   1.257s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   1.357s  |   1.357s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   1.781s  |   1.781s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   3.741s  |   3.741s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   5.971s  |   5.971s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   1.464s  |   1.464s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |   7.197s  |   7.197s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |  13.040s  |  13.040s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   1.905s  |   1.905s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   2.050s  |   2.050s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   3.703s  |   3.703s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   3.026s  |   3.026s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   4.179s  |   4.179s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   3.061s  |   3.061s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   3.756s  |   3.756s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   8.341s  |   8.341s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |  68.627s  |  68.627s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   2.250s  |   2.250s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   2.631s  |   2.631s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      | 572.103s  | 572.103s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   4.807s  |   4.807s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   2.021s  |   2.021s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   2.246s  |   2.246s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   4.429s  |   4.429s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   7.674s  |   7.674s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   8.802s  |   8.802s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   2.354s  |   2.354s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   2.678s  |   2.678s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   1.823s  |   1.823s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   2.362s  |   2.362s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   1.596s  |   1.596s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   2.210s  |   2.210s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   3.394s  |   3.394s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   3.229s  |   3.229s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      | 138.013s  | 138.013s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   1.682s  |   1.682s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   3.032s  |   3.032s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   4.512s  |   4.512s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |   7.386s  |   7.386s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |   3.558s  |   3.558s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   1.382s  |   1.382s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   1.010s  |   1.010s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   4.235s  |   4.235s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   2.475s  |   2.475s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   3.706s  |   3.706s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   2.427s  |   2.427s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   3.622s  |   3.622s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   5.185s  |   5.185s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |  14.509s  |  14.509s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   2.363s  |   2.363s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   3.535s  |   3.535s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   3.372s  |   3.372s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   2.621s  |   2.621s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   9.941s  |   9.941s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   3.159s  |   3.159s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   5.627s  |   5.627s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   5.299s  |   5.299s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   4.581s  |   4.581s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   9.935s  |   9.935s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   7.348s  |   7.348s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   7.794s  |   7.794s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |   9.607s  |   9.607s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            | 600.377s  | 600.377s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |   3.362s  |   3.362s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  30.479s  |  30.479s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |  10.521s  |  10.521s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |   3.469s  |   3.469s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |   4.135s  |   4.135s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        | 600.437s  | 600.437s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        | 600.435s  | 600.435s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |   4.224s  |   4.224s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       | 139.967s  | 139.967s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   7.110s  |   7.110s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   5.108s  |   5.108s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     | 327.238s  | 327.238s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     | 600.375s  | 600.375s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     | 420.685s  | 420.685s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |   9.909s  |   9.909s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         | 600.555s  | 600.555s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               | 600.045s  | 600.045s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         | 600.338s  | 600.338s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               | 600.411s  | 600.411s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   4.160s  |   4.160s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |   4.208s  |   4.208s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               | 600.289s  | 600.289s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  | 600.283s  | 600.283s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |  55.912s  |  55.912s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     |  90.383s  |  90.383s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  14.139s  |  14.139s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  16.089s  |  16.089s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            | 263.381s  | 263.381s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            | 600.285s  | 600.285s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   4.654s  |   4.654s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   3.202s  |   3.202s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   3.152s  |   3.152s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  67.300s  |  67.300s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 | 263.267s  | 263.267s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 | 600.227s  | 600.227s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  51.103s  |  51.103s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 | 600.349s  | 600.349s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  29.182s  |  29.182s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |   2.868s  |   2.868s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           |  57.922s  |  57.922s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           | 544.673s  | 544.673s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           | 239.967s  | 239.967s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |   4.235s  |   4.235s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  46.692s  |  46.692s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |  18.190s  |  18.190s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   5.003s  |   5.003s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 | 217.234s  | 217.234s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 | 600.325s  | 600.325s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  82.205s  |  82.205s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 | 108.567s  | 108.567s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   4.347s  |   4.347s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 | 239.272s  | 239.272s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 | 600.185s  | 600.185s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |  21.556s  |  21.556s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  26.892s  |  26.892s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   6.573s  |   6.573s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 |  46.160s  |  46.160s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |   5.382s  |   5.382s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  77.189s  |  77.189s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |  54.419s  |  54.419s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   7.475s  |   7.475s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |  10.510s  |  10.510s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 | 226.843s  | 226.843s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  34.761s  |  34.761s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |   6.803s  |   6.803s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 |  52.589s  |  52.589s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 | 582.891s  | 582.891s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   6.850s  |   6.850s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |   6.692s  |   6.692s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 | 303.187s  | 303.187s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   4.235s  |   4.235s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |  67.256s  |  67.256s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   3.020s  |   3.020s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |  59.385s  |  59.385s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |  14.029s  |  14.029s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |  14.181s  |  14.181s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   2.538s  |   2.538s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   2.026s  |   2.026s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  14.993s  |  14.993s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 | 127.302s  | 127.302s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  65.662s  |  65.662s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 | 153.237s  | 153.237s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  22.914s  |  22.914s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           | 109.040s  | 109.040s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  26.220s  |  26.220s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |  41.294s  |  41.294s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           |  67.158s  |  67.158s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    | 600.133s  | 600.133s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    | 600.198s  | 600.198s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       | 168.865s  | 168.865s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       | 127.303s  | 127.303s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  53.039s  |  53.039s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  60.734s  |  60.734s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |   8.479s  |   8.479s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  66.640s  |  66.640s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  42.033s  |  42.033s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  49.605s  |  49.605s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  32.051s  |  32.051s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  30.130s  |  30.130s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  |  33.068s  |  33.068s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  56.544s  |  56.544s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  30.909s  |  30.909s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   5.323s  |   5.323s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  33.824s  |  33.824s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |  34.390s  |  34.390s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  19.398s  |  19.398s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            | 516.043s  | 516.043s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          | 197.856s  | 197.856s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  51.433s  |  51.433s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  55.972s  |  55.972s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  48.097s  |  48.097s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               | 222.905s  | 222.905s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   2.988s  |   2.988s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   6.422s  |   6.422s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        | 242.945s  | 242.945s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        | 481.862s  | 481.862s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |  32.990s  |  32.990s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        |  29.527s  |  29.527s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        |   3.525s  |   3.525s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        |   3.590s  |   3.590s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        |  36.515s  |  36.515s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        |  64.643s  |  64.643s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   1.643s  |   1.643s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |  51.970s  |  51.970s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.736s  |   0.736s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   2.132s  |   2.132s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   8.723s  |   8.723s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  61.171s  |  61.171s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   2.031s  |   2.031s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |  11.249s  |  11.249s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |   5.337s  |   5.337s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |  14.547s  |  14.547s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   3.554s  |   3.554s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   4.466s  |   4.466s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |   9.966s  |   9.966s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             | 345.280s  | 345.280s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             | 600.206s  | 600.206s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   9.082s  |   9.082s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             |  81.210s  |  81.210s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             | 600.311s  | 600.311s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   9.447s  |   9.447s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |   3.912s  |   3.912s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             | 600.244s  | 600.244s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |   2.539s  |   2.539s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             | 142.063s  | 142.063s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             | 600.338s  | 600.338s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   2.599s  |   2.599s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             | 160.862s  | 160.862s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             | 600.365s  | 600.365s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   6.103s  |   6.103s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   4.498s  |   4.498s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   1.152s  |   1.152s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   5.119s  |   5.119s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                |   4.871s  |   4.871s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   0.773s  |   0.773s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  45.362s  |  45.362s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   3.970s  |   3.970s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   1.628s  |   1.628s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 | 600.213s  | 600.213s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   1.749s  |   1.749s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           | 600.057s  | 600.057s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   4.648s  |   4.648s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 |  54.103s  |  54.103s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  | 168.120s  | 168.120s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |   2.445s  |   2.445s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 | 600.204s  | 600.204s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   2.132s  |   2.132s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   1.827s  |   1.827s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |   3.364s  |   3.364s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   2.646s  |   2.646s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   4.380s  |   4.380s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   4.354s  |   4.354s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   6.394s  |   6.394s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  |  27.155s  |  27.155s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   3.033s  |   3.033s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  69.884s  |  69.884s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   4.140s  |   4.140s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  | 600.057s  | 600.057s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   1.246s  |   1.246s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  |  27.891s  |  27.891s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            | 600.234s  | 600.234s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   3.987s  |   3.987s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |  14.805s  |  14.805s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   4.031s  |   4.031s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  |  52.307s  |  52.307s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   2.647s  |   2.647s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  | 354.591s  | 354.591s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.614s  |   0.614s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |   4.149s  |   4.149s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   3.897s  |   3.897s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |   4.697s  |   4.697s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   1.488s  |   1.488s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |   3.604s  |   3.604s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           | 600.286s  | 600.286s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           | 600.245s  | 600.245s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  19.823s  |  19.823s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               |  23.872s  |  23.872s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               | 538.322s  | 538.322s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               | 255.072s  | 255.072s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               | 600.267s  | 600.267s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               | 600.300s  | 600.300s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |  10.676s  |  10.676s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |  37.747s  |  37.747s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  26.938s  |  26.938s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |   9.131s  |   9.131s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   3.479s  |   3.479s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             | 600.057s  | 600.057s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |   8.733s  |   8.733s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   4.792s  |   4.792s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |  10.309s  |  10.309s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |   4.185s  |   4.185s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   3.341s  |   3.341s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   3.516s  |   3.516s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  20.290s  |  20.290s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |   4.065s  |   4.065s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    | 600.234s  | 600.234s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   7.624s  |   7.624s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               | 600.169s  | 600.169s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             |   4.257s  |   4.257s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   5.184s  |   5.184s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   4.758s  |   4.758s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             | 600.170s  | 600.170s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  10.615s  |  10.615s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |   9.589s  |   9.589s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               | 600.250s  | 600.250s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         | 600.268s  | 600.268s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  12.927s  |  12.927s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  14.753s  |  14.753s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  20.230s  |  20.230s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  10.999s  |  10.999s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  21.398s  |  21.398s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        | 600.527s  | 600.527s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            |   7.848s  |   7.848s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   3.003s  |   3.003s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |  19.828s  |  19.828s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   4.102s  |   4.102s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            |   3.983s  |   3.983s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   3.912s  |   3.912s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |   3.468s  |   3.468s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  13.570s  |  13.570s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              |  12.409s  |  12.409s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   1.212s  |   1.212s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  12.208s  |  12.208s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   4.845s  |   4.845s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |  81.436s  |  81.436s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  13.335s  |  13.335s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   2.779s  |   2.779s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       |   8.007s  |   8.007s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   5.243s  |   5.243s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   3.550s  |   3.550s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   4.004s  |   4.004s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         | 259.695s  | 259.695s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |   6.503s  |   6.503s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           | 141.167s  | 141.167s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            | 600.216s  | 600.216s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              |  51.603s  |  51.603s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   9.964s  |   9.964s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   2.228s  |   2.228s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |   2.935s  |   2.935s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          | 600.375s  | 600.375s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          | 600.512s  | 600.512s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |   9.748s  |   9.748s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          | 600.444s  | 600.444s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          | 600.421s  | 600.421s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |   9.848s  |   9.848s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          |   2.275s  |   2.275s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          | 600.388s  | 600.388s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |   8.376s  |   8.376s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                | 600.284s  | 600.284s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                | 600.389s  | 600.389s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   9.453s  |   9.453s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                | 600.260s  | 600.260s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                | 600.451s  | 600.451s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |   8.523s  |   8.523s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                |   3.914s  |   3.914s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                | 600.439s  | 600.439s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |   7.712s  |   7.712s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                | 600.117s  | 600.117s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                | 600.457s  | 600.457s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          | 600.473s  | 600.473s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |  12.573s  |  12.573s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          |   4.292s  |   4.292s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   7.923s  |   7.923s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |   3.786s  |   3.786s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          |  87.260s  |  87.260s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |  56.252s  |  56.252s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   5.015s  |   5.015s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   7.421s  |   7.421s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |   3.230s  |   3.230s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   6.202s  |   6.202s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   4.180s  |   4.180s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |  14.432s  |  14.432s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |  14.024s  |  14.024s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                | 600.052s  | 600.052s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                |   2.517s  |   2.517s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                | 298.706s  | 298.706s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |  13.181s  |  13.181s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   5.668s  |   5.668s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   6.436s  |   6.436s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   6.252s  |   6.252s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   0.831s  |   0.831s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                | 600.051s  | 600.051s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   7.472s  |   7.472s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   9.663s  |   9.663s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |   3.164s  |   3.164s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   6.297s  |   6.297s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |   2.881s  |   2.881s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   5.326s  |   5.326s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |   6.323s  |   6.323s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                | 600.043s  | 600.043s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                | 148.650s  | 148.650s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   5.893s  |   5.893s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   7.003s  |   7.003s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   2.453s  |   2.453s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |  38.339s  |  38.339s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   2.930s  |   2.930s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   4.519s  |   4.519s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |   9.400s  |   9.400s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   6.519s  |   6.519s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          | 600.051s  | 600.051s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   1.766s  |   1.766s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   0.722s  |   0.722s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   4.838s  |   4.838s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   5.190s  |   5.190s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   1.060s  |   1.060s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   7.381s  |   7.381s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   1.052s  |   1.052s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   2.430s  |   2.430s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |   3.602s  |   3.602s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   5.802s  |   5.802s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |   7.201s  |   7.201s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          | 600.172s  | 600.172s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          | 600.049s  | 600.049s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |   5.988s  |   5.988s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   0.543s  |   0.543s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          | 511.381s  | 511.381s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  12.871s  |  12.871s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     | 183.992s  | 183.992s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           | 315.160s  | 315.160s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |  10.526s  |  10.526s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |   3.281s  |   3.281s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   4.447s  |   4.447s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   3.955s  |   3.955s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |   5.420s  |   5.420s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |  14.956s  |  14.956s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |  51.977s  |  51.977s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        | 385.384s  | 385.384s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |  10.765s  |  10.765s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |   3.921s  |   3.921s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |  10.717s  |  10.717s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |  50.296s  |  50.296s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   6.249s  |   6.249s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   5.981s  |   5.981s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   5.748s  |   5.748s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        | 600.053s  | 600.053s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   7.447s  |   7.447s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   6.939s  |   6.939s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   4.715s  |   4.715s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |  21.988s  |  21.988s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   7.122s  |   7.122s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  15.440s  |  15.440s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   1.024s  |   1.024s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.812s  |   0.812s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   5.760s  |   5.760s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   3.692s  |   3.692s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |  41.744s  |  41.744s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        | 600.055s  | 600.055s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            | 150.957s  | 150.957s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            | 241.804s  | 241.804s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  | 600.151s  | 600.151s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |   4.237s  |   4.237s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  | 600.093s  | 600.093s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   2.935s  |   2.935s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   1.093s  |   1.093s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   0.969s  |   0.969s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   5.748s  |   5.748s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   2.929s  |   2.929s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   2.751s  |   2.751s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   3.028s  |   3.028s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  | 211.339s  | 211.339s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   7.387s  |   7.387s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |  13.560s  |  13.560s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                | 600.425s  | 600.425s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  35.894s  |  35.894s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   3.648s  |   3.648s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              | 256.067s  | 256.067s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        | 600.572s  | 600.572s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   |   3.434s  |   3.434s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   | 600.214s  | 600.214s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   1.417s  |   1.417s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   |   4.644s  |   4.644s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   |   3.748s  |   3.748s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |   1.877s  |   1.877s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   | 600.193s  | 600.193s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |   3.462s  |   3.462s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   5.110s  |   5.110s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   8.601s  |   8.601s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |   7.941s  |   7.941s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   1.811s  |   1.811s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        | 600.313s  | 600.313s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        | 600.292s  | 600.292s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   1.868s  |   1.868s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        | 600.205s  | 600.205s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        | 600.263s  | 600.263s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |   7.924s  |   7.924s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        | 600.185s  | 600.185s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   2.140s  |   2.140s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   4.790s  |   4.790s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              | 184.726s  | 184.726s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |   9.432s  |   9.432s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   6.100s  |   6.100s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   8.740s  |   8.740s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  11.858s  |  11.858s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |  14.181s  |  14.181s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |   8.572s  |   8.572s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            | 600.195s  | 600.195s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            | 600.217s  | 600.217s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |   8.726s  |   8.726s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            | 600.243s  | 600.243s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            | 600.320s  | 600.320s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   2.003s  |   2.003s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            |   2.657s  |   2.657s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   4.699s  |   4.699s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   5.133s  |   5.133s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  21.180s  |  21.180s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  16.079s  |  16.079s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  13.323s  |  13.323s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  19.482s  |  19.482s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   3.708s  |   3.708s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |   3.503s  |   3.503s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   2.622s  |   2.622s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |   9.973s  |   9.973s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |   3.474s  |   3.474s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   4.811s  |   4.811s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   8.525s  |   8.525s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   6.894s  |   6.894s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   4.256s  |   4.256s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   5.263s  |   5.263s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   4.249s  |   4.249s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   2.889s  |   2.889s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   5.389s  |   5.389s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   2.029s  |   2.029s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   1.875s  |   1.875s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           |  53.242s  |  53.242s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   2.476s  |   2.476s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |   7.155s  |   7.155s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           |  14.651s  |  14.651s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           |   7.003s  |   7.003s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   1.224s  |   1.224s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  |  54.856s  |  54.856s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   4.860s  |   4.860s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   3.199s  |   3.199s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   3.559s  |   3.559s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   4.053s  |   4.053s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   2.289s  |   2.289s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   3.348s  |   3.348s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   3.390s  |   3.390s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   3.229s  |   3.229s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   2.713s  |   2.713s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   2.496s  |   2.496s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |  18.250s  |  18.250s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   1.304s  |   1.304s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |  44.054s  |  44.054s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   7.336s  |   7.336s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |  27.977s  |  27.977s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             | 600.046s  | 600.046s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   4.374s  |   4.374s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |  18.404s  |  18.404s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             |   3.621s  |   3.621s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   3.926s  |   3.926s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |  13.730s  |  13.730s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   7.565s  |   7.565s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |   8.205s  |   8.205s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   5.035s  |   5.035s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          | 600.317s  | 600.317s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                | 600.315s  | 600.315s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |   6.392s  |   6.392s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |  10.812s  |  10.812s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                | 600.249s  | 600.249s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                | 600.158s  | 600.158s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  11.713s  |  11.713s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                | 600.250s  | 600.250s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  17.985s  |  17.985s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                | 365.343s  | 365.343s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |   7.982s  |   7.982s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   2.690s  |   2.690s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   4.836s  |   4.836s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              | 600.406s  | 600.406s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       | 600.325s  | 600.325s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       | 600.196s  | 600.196s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  14.282s  |  14.282s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  12.021s  |  12.021s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  27.407s  |  27.407s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  43.558s  |  43.558s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           |  70.694s  |  70.694s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  32.660s  |  32.660s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  18.191s  |  18.191s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   6.497s  |   6.497s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             | 600.172s  | 600.172s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  65.009s  |  65.009s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |  36.473s  |  36.473s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  24.463s  |  24.463s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  24.027s  |  24.027s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  34.054s  |  34.054s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |   4.060s  |   4.060s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  56.632s  |  56.632s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  54.954s  |  54.954s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           | 600.369s  | 600.369s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           | 600.507s  | 600.507s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           | 238.528s  | 238.528s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  14.214s  |  14.214s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 | 600.367s  | 600.367s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 | 600.197s  | 600.197s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   8.088s  |   8.088s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |  10.713s  |  10.713s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                | 600.154s  | 600.154s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                | 600.181s  | 600.181s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  14.492s  |  14.492s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  28.653s  |  28.653s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          | 600.555s  | 600.555s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          | 600.325s  | 600.325s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          |   3.510s  |   3.510s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |  18.163s  |  18.163s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  17.752s  |  17.752s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     |  35.421s  |  35.421s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   3.407s  |   3.407s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                | 237.539s  | 237.539s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   5.281s  |   5.281s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |  43.755s  |  43.755s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   6.352s  |   6.352s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  41.339s  |  41.339s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   9.335s  |   9.335s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |   2.128s  |   2.128s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   2.312s  |   2.312s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   1.900s  |   1.900s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |   1.744s  |   1.744s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      | 600.264s  | 600.264s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   5.380s  |   5.380s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   0.884s  |   0.884s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   1.814s  |   1.814s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   1.498s  |   1.498s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  46.984s  |  46.984s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |  56.459s  |  56.459s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   3.121s  |   3.121s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  33.618s  |  33.618s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   3.907s  |   3.907s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |  29.740s  |  29.740s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |   2.234s  |   2.234s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   1.734s  |   1.734s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           | 600.038s  | 600.038s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   8.623s  |   8.623s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |   6.456s  |   6.456s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   2.889s  |   2.889s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           |   5.485s  |   5.485s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           | 150.969s  | 150.969s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        | 600.051s  | 600.051s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   4.053s  |   4.053s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   3.990s  |   3.990s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   1.490s  |   1.490s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |  29.908s  |  29.908s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   3.112s  |   3.112s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   6.888s  |   6.888s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |  15.568s  |  15.568s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  10.302s  |  10.302s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   7.216s  |   7.216s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   2.212s  |   2.212s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   2.709s  |   2.709s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   1.356s  |   1.356s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |  10.567s  |  10.567s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   2.907s  |   2.907s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   6.718s  |   6.718s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   6.317s  |   6.317s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   6.400s  |   6.400s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   2.667s  |   2.667s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |   5.382s  |   5.382s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  11.400s  |  11.400s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |   6.834s  |   6.834s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   4.254s  |   4.254s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  26.472s  |  26.472s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  15.564s  |  15.564s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   3.142s  |   3.142s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |  13.499s  |  13.499s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   7.892s  |   7.892s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |  13.201s  |  13.201s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   1.241s  |   1.241s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   2.789s  |   2.789s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   0.793s  |   0.793s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   2.669s  |   2.669s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   1.560s  |   1.560s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  10.552s  |  10.552s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |   9.311s  |   9.311s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |   6.296s  |   6.296s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |   6.639s  |   6.639s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.820s  |   0.820s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                | 600.212s  | 600.212s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |  13.562s  |  13.562s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   6.587s  |   6.587s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |   5.209s  |   5.209s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   1.670s  |   1.670s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   3.653s  |   3.653s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       | 151.539s  | 151.539s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   3.576s  |   3.576s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |  54.520s  |  54.520s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   9.604s  |   9.604s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   5.455s  |   5.455s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       | 204.037s  | 204.037s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       | 600.269s  | 600.269s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   9.250s  |   9.250s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       | 600.192s  | 600.192s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       |   3.597s  |   3.597s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |   2.150s  |   2.150s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.473s  |   0.473s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   4.164s  |   4.164s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   5.362s  |   5.362s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   1.683s  |   1.683s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |   4.282s  |   4.282s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   1.170s  |   1.170s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   2.871s  |   2.871s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   4.624s  |   4.624s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |   8.113s  |   8.113s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |  12.143s  |  12.143s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   2.174s  |   2.174s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   2.418s  |   2.418s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   3.265s  |   3.265s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    | 600.235s  | 600.235s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        | 600.053s  | 600.053s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        | 600.042s  | 600.042s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  56.466s  |  56.466s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  | 600.040s  | 600.040s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.489s  |   0.489s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  54.380s  |  54.380s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           | 198.044s  | 198.044s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   6.535s  |   6.535s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           | 600.169s  | 600.169s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   3.113s  |   3.113s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   3.929s  |   3.929s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   5.123s  |   5.123s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   5.342s  |   5.342s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   5.465s  |   5.465s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   0.822s  |   0.822s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           |  92.690s  |  92.690s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   1.481s  |   1.481s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   1.896s  |   1.896s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           | 220.973s  | 220.973s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   1.106s  |   1.106s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           | 182.939s  | 182.939s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   1.198s  |   1.198s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   6.697s  |   6.697s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   1.483s  |   1.483s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   3.958s  |   3.958s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   3.378s  |   3.378s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   8.322s  |   8.322s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   1.381s  |   1.381s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |   7.323s  |   7.323s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   3.796s  |   3.796s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   3.559s  |   3.559s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           |   6.518s  |   6.518s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   3.206s  |   3.206s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           |  28.844s  |  28.844s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   3.155s  |   3.155s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   7.051s  |   7.051s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   1.218s  |   1.218s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   2.663s  |   2.663s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |   3.568s  |   3.568s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   1.314s  |   1.314s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           | 171.679s  | 171.679s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   1.444s  |   1.444s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   0.982s  |   0.982s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   7.796s  |   7.796s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   3.750s  |   3.750s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   4.453s  |   4.453s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |   3.856s  |   3.856s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   1.349s  |   1.349s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   7.245s  |   7.245s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   6.367s  |   6.367s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   2.664s  |   2.664s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   3.332s  |   3.332s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |  19.296s  |  19.296s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |   2.676s  |   2.676s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   1.089s  |   1.089s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   2.539s  |   2.539s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   1.080s  |   1.080s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  71.527s  |  71.527s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   4.359s  |   4.359s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |   4.812s  |   4.812s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   0.890s  |   0.890s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            | 600.242s  | 600.242s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   1.321s  |   1.321s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |   4.824s  |   4.824s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   6.501s  |   6.501s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   2.871s  |   2.871s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   1.142s  |   1.142s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           | 150.259s  | 150.259s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           | 322.546s  | 322.546s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   3.418s  |   3.418s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   5.964s  |   5.964s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  13.280s  |  13.280s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   2.517s  |   2.517s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   2.985s  |   2.985s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   3.049s  |   3.049s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   3.118s  |   3.118s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   4.138s  |   4.138s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   3.069s  |   3.069s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   2.529s  |   2.529s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   4.205s  |   4.205s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |  10.004s  |  10.004s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   5.502s  |   5.502s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           | 600.173s  | 600.173s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   3.123s  |   3.123s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   1.663s  |   1.663s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   8.297s  |   8.297s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           |  47.647s  |  47.647s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.825s  |   0.825s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   2.615s  |   2.615s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |  12.179s  |  12.179s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           |   6.169s  |   6.169s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   2.358s  |   2.358s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   4.194s  |   4.194s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   2.878s  |   2.878s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   8.103s  |   8.103s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   5.372s  |   5.372s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   9.279s  |   9.279s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   1.931s  |   1.931s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  37.844s  |  37.844s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   2.557s  |   2.557s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   3.237s  |   3.237s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.648s  |   0.648s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   1.601s  |   1.601s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   4.999s  |   4.999s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   4.894s  |   4.894s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   1.048s  |   1.048s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   8.321s  |   8.321s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   4.474s  |   4.474s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |  53.367s  |  53.367s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |  17.330s  |  17.330s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.666s  |   0.666s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   1.049s  |   1.049s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.240s  |   1.240s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   2.463s  |   2.463s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   1.827s  |   1.827s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   2.762s  |   2.762s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   1.637s  |   1.637s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   1.320s  |   1.320s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |   2.230s  |   2.230s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.727s  |   0.727s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            |  21.775s  |  21.775s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
</details>
