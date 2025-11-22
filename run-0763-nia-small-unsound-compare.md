Comparing data and data


# SUMMARY
- LHS tests = 2313
- RHS tests = 2313
- LHS success = 2312  (99.95676610462603%)
- RHS success = 2312  (99.95676610462603%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: nia-small-unsound
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 31a9f7696f0a29257caa65e60fcd0af352a958a1
Z3 branch: unsound
Z3 options: "-T:600"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: restart projection when found a non-trivial nullified polynomial, and remove is_square_free

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: nia-small-unsound
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 31a9f7696f0a29257caa65e60fcd0af352a958a1
Z3 branch: unsound
Z3 options: "-T:600"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: restart projection when found a non-trivial nullified polynomial, and remove is_square_free

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.887s  |   1.887s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.187s  |   1.187s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.053s  | 600.053s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.243s  |   0.243s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.887s  |   1.887s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.187s  |   1.187s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.053s  | 600.053s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.243s  |   0.243s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.887s  |   1.887s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.187s  |   1.187s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.053s  | 600.053s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.243s  |   0.243s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.887s  |   1.887s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.187s  |   1.187s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.053s  | 600.053s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.243s  |   0.243s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|term-0BB4ks.smt2                                                                           | 625.684s |384.0MiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                   | 621.974s |129.0MiB|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                       | 619.990s |288.0MiB|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                       | 618.917s |203.0MiB|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                         | 616.556s |420.0MiB|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                 | 614.409s |293.0MiB|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                | 614.259s |248.0MiB|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                | 614.050s |224.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          | 607.943s |1642.0MiB|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                               | 605.091s |1284.0MiB|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                         | 604.295s |555.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 601.420s |2348.0MiB|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                            | 601.339s |1975.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 600.958s |8275.0MiB|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                           | 600.941s |1152.0MiB|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                       | 600.788s |1494.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.616s |2469.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 600.569s |2768.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.559s |4928.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 600.549s |2646.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|term-0BB4ks.smt2                                                                           | 625.684s |384.0MiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                   | 621.974s |129.0MiB|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                       | 619.990s |288.0MiB|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                       | 618.917s |203.0MiB|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                         | 616.556s |420.0MiB|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                 | 614.409s |293.0MiB|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                | 614.259s |248.0MiB|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                | 614.050s |224.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          | 607.943s |1642.0MiB|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                               | 605.091s |1284.0MiB|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                         | 604.295s |555.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 601.420s |2348.0MiB|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                            | 601.339s |1975.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 600.958s |8275.0MiB|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                           | 600.941s |1152.0MiB|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                       | 600.788s |1494.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.616s |2469.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 600.569s |2768.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.559s |4928.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 600.549s |2646.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |91.744MiB|91.744MiB|0B| 0.0%|
|04.smt2                                                                                     |70.3MiB|70.3MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.632MiB|31.632MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.448MiB|30.448MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.68MiB|23.68MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.144MiB|24.144MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.344MiB|24.344MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.716MiB|24.716MiB|0B| 0.0%|
|107.smt2                                                                                    |22.3MiB|22.3MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.46MiB|27.46MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.204MiB|80.204MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.008MiB|23.008MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.9MiB|22.9MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.688MiB|23.688MiB|0B| 0.0%|
|11.smt2                                                                                     |70.912MiB|70.912MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.288MiB|24.288MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.392MiB|23.392MiB|0B| 0.0%|
|1113.smt2                                                                                   |25.024MiB|25.024MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.384MiB|25.384MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |91.744MiB|91.744MiB|0B| 0.0%|
|04.smt2                                                                                     |70.3MiB|70.3MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.632MiB|31.632MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.448MiB|30.448MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.68MiB|23.68MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.144MiB|24.144MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.344MiB|24.344MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.716MiB|24.716MiB|0B| 0.0%|
|107.smt2                                                                                    |22.3MiB|22.3MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.46MiB|27.46MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.204MiB|80.204MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.008MiB|23.008MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.9MiB|22.9MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.688MiB|23.688MiB|0B| 0.0%|
|11.smt2                                                                                     |70.912MiB|70.912MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.288MiB|24.288MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.392MiB|23.392MiB|0B| 0.0%|
|1113.smt2                                                                                   |25.024MiB|25.024MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.384MiB|25.384MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |91.744MiB|91.744MiB|0B| 0.0%|
|04.smt2                                                                                     |70.3MiB|70.3MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.632MiB|31.632MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.448MiB|30.448MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.68MiB|23.68MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.144MiB|24.144MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.344MiB|24.344MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.716MiB|24.716MiB|0B| 0.0%|
|107.smt2                                                                                    |22.3MiB|22.3MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.46MiB|27.46MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.204MiB|80.204MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.008MiB|23.008MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.9MiB|22.9MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.688MiB|23.688MiB|0B| 0.0%|
|11.smt2                                                                                     |70.912MiB|70.912MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.288MiB|24.288MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.392MiB|23.392MiB|0B| 0.0%|
|1113.smt2                                                                                   |25.024MiB|25.024MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.384MiB|25.384MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |91.744MiB|91.744MiB|0B| 0.0%|
|04.smt2                                                                                     |70.3MiB|70.3MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.632MiB|31.632MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.448MiB|30.448MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.68MiB|23.68MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.144MiB|24.144MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.344MiB|24.344MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.716MiB|24.716MiB|0B| 0.0%|
|107.smt2                                                                                    |22.3MiB|22.3MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.46MiB|27.46MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.204MiB|80.204MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.008MiB|23.008MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.9MiB|22.9MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.688MiB|23.688MiB|0B| 0.0%|
|11.smt2                                                                                     |70.912MiB|70.912MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.288MiB|24.288MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.392MiB|23.392MiB|0B| 0.0%|
|1113.smt2                                                                                   |25.024MiB|25.024MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.384MiB|25.384MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 600.958s |8275.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.559s |4928.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 600.546s |4911.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              | 600.543s |2967.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 600.569s |2768.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 365.321s |2724.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                          | 600.474s |2715.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 600.324s |2667.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 600.549s |2646.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                         | 600.503s |2521.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 600.473s |2478.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.616s |2469.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 600.498s |2418.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 586.980s |2410.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 601.420s |2348.0MiB|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                 | 600.452s |2288.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                         | 600.403s |2284.0MiB|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                              | 600.469s |2223.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2               | 600.433s |2222.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2            | 600.377s |2133.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 600.958s |8275.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.559s |4928.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 600.546s |4911.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              | 600.543s |2967.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 600.569s |2768.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 365.321s |2724.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                          | 600.474s |2715.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 600.324s |2667.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 600.549s |2646.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                         | 600.503s |2521.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 600.473s |2478.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.616s |2469.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 600.498s |2418.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 586.980s |2410.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 601.420s |2348.0MiB|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                 | 600.452s |2288.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                         | 600.403s |2284.0MiB|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                              | 600.469s |2223.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2               | 600.433s |2222.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2            | 600.377s |2133.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.887s  |   1.887s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.187s  |   1.187s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.053s  | 600.053s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|124.smt2                                                                                    | 600.042s  | 600.042s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   1.593s  |   1.593s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|140.smt2                                                                                    | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   2.895s  |   2.895s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   1.810s  |   1.810s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   5.209s  |   5.209s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   1.337s  |   1.337s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   5.133s  |   5.133s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   2.796s  |   2.796s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   1.273s  |   1.273s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|177.smt2                                                                                    | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   1.171s  |   1.171s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   1.991s  |   1.991s  |   0.000s  | 0.0%|
|181.smt2                                                                                    | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|182.smt2                                                                                    | 600.170s  | 600.170s  |   0.000s  | 0.0%|
|183.smt2                                                                                    | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|185.smt2                                                                                    | 600.289s  | 600.289s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.770s  |   0.770s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   1.177s  |   1.177s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   1.555s  |   1.555s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   1.232s  |   1.232s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   3.813s  |   3.813s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   5.000s  |   5.000s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   6.637s  |   6.637s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   6.514s  |   6.514s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   3.275s  |   3.275s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   3.258s  |   3.258s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   1.596s  |   1.596s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   1.350s  |   1.350s  |   0.000s  | 0.0%|
|35.smt2                                                                                     | 600.041s  | 600.041s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|40.smt2                                                                                     | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   1.717s  |   1.717s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   1.164s  |   1.164s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|54.smt2                                                                                     | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   2.729s  |   2.729s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   1.856s  |   1.856s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   2.682s  |   2.682s  |   0.000s  | 0.0%|
|58.smt2                                                                                     | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   2.273s  |   2.273s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   2.719s  |   2.719s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   5.291s  |   5.291s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|65.smt2                                                                                     | 600.057s  | 600.057s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   1.226s  |   1.226s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|73.smt2                                                                                     | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   3.607s  |   3.607s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   1.846s  |   1.846s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   3.589s  |   3.589s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|966.smt2                                                                                    | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|98.smt2                                                                                     | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|99.smt2                                                                                     | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  | 168.538s  | 168.538s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   3.800s  |   3.800s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          | 600.214s  | 600.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |   9.172s  |   9.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   1.349s  |   1.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |  35.765s  |  35.765s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.588s  |   0.588s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          | 118.954s  | 118.954s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   9.806s  |   9.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   1.963s  |   1.963s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            | 600.385s  | 600.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   4.739s  |   4.739s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   2.832s  |   2.832s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       |  21.818s  |  21.818s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   9.289s  |   9.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  79.325s  |  79.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   3.735s  |   3.735s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |   9.240s  |   9.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   1.805s  |   1.805s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           | 188.418s  | 188.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |  21.025s  |  21.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   5.615s  |   5.615s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  19.403s  |  19.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   3.000s  |   3.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |   7.403s  |   7.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             | 601.339s  | 601.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |  10.818s  |  10.818s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  11.797s  |  11.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 |  13.423s  |  13.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   3.371s  |   3.371s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   5.145s  |   5.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   6.482s  |   6.482s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   1.563s  |   1.563s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |  21.276s  |  21.276s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   2.355s  |   2.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |  91.643s  |  91.643s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         | 600.195s  | 600.195s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   8.917s  |   8.917s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |   2.655s  |   2.655s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |   6.591s  |   6.591s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 | 177.479s  | 177.479s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   2.101s  |   2.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   8.890s  |   8.890s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              | 271.819s  | 271.819s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   2.447s  |   2.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   5.444s  |   5.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          | 600.193s  | 600.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   1.570s  |   1.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          |  29.479s  |  29.479s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   3.906s  |   3.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         | 327.280s  | 327.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   2.709s  |   2.709s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      | 600.226s  | 600.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |  11.684s  |  11.684s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   4.307s  |   4.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   6.092s  |   6.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               | 600.218s  | 600.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  11.617s  |  11.617s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |  17.847s  |  17.847s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |  29.754s  |  29.754s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               |  11.199s  |  11.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   4.209s  |   4.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               |  58.519s  |  58.519s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |  15.650s  |  15.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   5.130s  |   5.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |   8.111s  |   8.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |  47.189s  |  47.189s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   7.545s  |   7.545s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   | 600.186s  | 600.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             | 600.245s  | 600.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  30.668s  |  30.668s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   1.526s  |   1.526s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    | 600.199s  | 600.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |   3.720s  |   3.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  18.326s  |  18.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  19.374s  |  19.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   3.975s  |   3.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   7.307s  |   7.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   3.910s  |   3.910s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |  16.588s  |  16.588s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               | 600.206s  | 600.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   1.256s  |   1.256s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   3.750s  |   3.750s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   5.050s  |   5.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   3.161s  |   3.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   2.713s  |   2.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   9.494s  |   9.494s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                | 600.174s  | 600.174s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   1.182s  |   1.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              | 600.181s  | 600.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   2.755s  |   2.755s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   8.199s  |   8.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  17.390s  |  17.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  72.615s  |  72.615s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   2.845s  |   2.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  13.365s  |  13.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          | 600.215s  | 600.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |  34.784s  |  34.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          | 600.240s  | 600.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          | 600.173s  | 600.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  33.239s  |  33.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   2.915s  |   2.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  13.136s  |  13.136s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   3.824s  |   3.824s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    | 600.230s  | 600.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   3.095s  |   3.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   2.754s  |   2.754s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    | 600.164s  | 600.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   3.651s  |   3.651s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   3.310s  |   3.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |  98.683s  |  98.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        | 128.809s  | 128.809s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        | 136.378s  | 136.378s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |   9.225s  |   9.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   8.278s  |   8.278s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        | 354.073s  | 354.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   1.723s  |   1.723s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  42.736s  |  42.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  48.584s  |  48.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  56.022s  |  56.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  28.684s  |  28.684s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  65.290s  |  65.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  49.717s  |  49.717s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  | 282.010s  | 282.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  |  99.118s  |  99.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |   6.748s  |   6.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |  84.616s  |  84.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   1.752s  |   1.752s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   2.060s  |   2.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |  48.784s  |  48.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |   4.668s  |   4.668s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   2.751s  |   2.751s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  18.356s  |  18.356s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        | 161.121s  | 161.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   2.573s  |   2.573s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |  86.332s  |  86.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |   4.331s  |   4.331s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   | 600.137s  | 600.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   4.469s  |   4.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   3.167s  |   3.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   1.647s  |   1.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                |  17.019s  |  17.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   1.582s  |   1.582s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      | 170.774s  | 170.774s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   3.909s  |   3.909s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   6.657s  |   6.657s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |   3.473s  |   3.473s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   0.778s  |   0.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   1.908s  |   1.908s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   5.476s  |   5.476s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   2.948s  |   2.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |  14.223s  |  14.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   6.168s  |   6.168s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |  80.687s  |  80.687s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  30.519s  |  30.519s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   5.618s  |   5.618s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                | 120.437s  | 120.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   5.921s  |   5.921s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |   8.417s  |   8.417s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   3.079s  |   3.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   4.461s  |   4.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   3.442s  |   3.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   6.293s  |   6.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   3.768s  |   3.768s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   5.848s  |   5.848s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   7.185s  |   7.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   3.416s  |   3.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  27.767s  |  27.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          | 604.295s  | 604.295s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |  10.669s  |  10.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |  10.585s  |  10.585s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |   9.404s  |   9.404s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          | 600.175s  | 600.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   6.944s  |   6.944s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   5.784s  |   5.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |  20.107s  |  20.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |  21.781s  |  21.781s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   9.049s  |   9.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |   6.682s  |   6.682s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   2.688s  |   2.688s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   3.556s  |   3.556s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |  39.348s  |  39.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   1.666s  |   1.666s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |  92.633s  |  92.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |  21.131s  |  21.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |   6.677s  |   6.677s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   2.618s  |   2.618s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   1.094s  |   1.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           | 600.311s  | 600.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   1.582s  |   1.582s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   2.476s  |   2.476s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   7.452s  |   7.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |  72.553s  |  72.553s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           | 600.179s  | 600.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   2.348s  |   2.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |  42.464s  |  42.464s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  40.591s  |  40.591s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |  14.218s  |  14.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           |   9.659s  |   9.659s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |  12.222s  |  12.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |  19.489s  |  19.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   2.247s  |   2.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  48.954s  |  48.954s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   1.736s  |   1.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |  17.717s  |  17.717s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   6.687s  |   6.687s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   6.267s  |   6.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |   1.654s  |   1.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   2.162s  |   2.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |  15.257s  |  15.257s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.732s  |   0.732s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           | 600.045s  | 600.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  28.221s  |  28.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   2.247s  |   2.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     | 600.243s  | 600.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   2.228s  |   2.228s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |   1.833s  |   1.833s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   1.246s  |   1.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |  44.027s  |  44.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   2.237s  |   2.237s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   8.948s  |   8.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |   6.626s  |   6.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.555s  |   0.555s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |  10.675s  |  10.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     | 520.436s  | 520.436s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |  36.822s  |  36.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   8.896s  |   8.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   1.789s  |   1.789s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   3.194s  |   3.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   2.693s  |   2.693s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   3.044s  |   3.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |  69.878s  |  69.878s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |  69.539s  |  69.539s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |   9.343s  |   9.343s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   5.553s  |   5.553s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |  10.660s  |  10.660s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               | 600.201s  | 600.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |   6.541s  |   6.541s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   2.999s  |   2.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |  12.757s  |  12.757s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |  37.697s  |  37.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |  13.444s  |  13.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   2.262s  |   2.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   3.092s  |   3.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |  16.284s  |  16.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |  14.586s  |  14.586s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     | 600.211s  | 600.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  13.489s  |  13.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   2.089s  |   2.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               | 100.070s  | 100.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   1.866s  |   1.866s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |   1.768s  |   1.768s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |   9.326s  |   9.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   1.206s  |   1.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |   4.688s  |   4.688s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               | 600.230s  | 600.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |   5.951s  |   5.951s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               | 215.299s  | 215.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               | 600.183s  | 600.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               | 600.176s  | 600.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               | 600.167s  | 600.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   6.199s  |   6.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   4.242s  |   4.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   0.812s  |   0.812s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  35.682s  |  35.682s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   0.866s  |   0.866s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |   7.353s  |   7.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |  24.311s  |  24.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   3.287s  |   3.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |  55.114s  |  55.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   9.835s  |   9.835s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   1.215s  |   1.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   6.500s  |   6.500s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               | 600.197s  | 600.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   2.619s  |   2.619s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |  10.523s  |  10.523s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |  13.807s  |  13.807s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |   1.728s  |   1.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   4.913s  |   4.913s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       | 126.922s  | 126.922s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |   1.995s  |   1.995s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   2.289s  |   2.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |  39.928s  |  39.928s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |   8.022s  |   8.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   2.391s  |   2.391s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   7.986s  |   7.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   2.206s  |   2.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   2.520s  |   2.520s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |   1.476s  |   1.476s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   6.251s  |   6.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   2.951s  |   2.951s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |  23.220s  |  23.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |   2.901s  |   2.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   2.350s  |   2.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   2.384s  |   2.384s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |  17.338s  |  17.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |  18.735s  |  18.735s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |   5.708s  |   5.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |   1.169s  |   1.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |  10.247s  |  10.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   5.423s  |   5.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   7.780s  |   7.780s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             | 600.313s  | 600.313s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |   6.052s  |   6.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   6.896s  |   6.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   1.285s  |   1.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             | 600.377s  | 600.377s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |   3.707s  |   3.707s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |   8.218s  |   8.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |   3.971s  |   3.971s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |   6.998s  |   6.998s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         | 221.573s  | 221.573s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   6.251s  |   6.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              | 251.008s  | 251.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   3.581s  |   3.581s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   2.262s  |   2.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |  19.564s  |  19.564s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |  35.894s  |  35.894s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   2.204s  |   2.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   2.451s  |   2.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   1.706s  |   1.706s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   2.257s  |   2.257s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   5.591s  |   5.591s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   1.844s  |   1.844s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   3.391s  |   3.391s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    | 600.197s  | 600.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   2.458s  |   2.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   2.914s  |   2.914s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |   1.053s  |   1.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   9.689s  |   9.689s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |  10.048s  |  10.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  51.827s  |  51.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  84.609s  |  84.609s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   2.383s  |   2.383s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    | 621.974s  | 621.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |   1.307s  |   1.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |  32.729s  |  32.729s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   2.349s  |   2.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   4.439s  |   4.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |  12.902s  |  12.902s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   2.344s  |   2.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   6.229s  |   6.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |   7.015s  |   7.015s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   2.199s  |   2.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   2.223s  |   2.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |  33.657s  |  33.657s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   5.423s  |   5.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |  11.534s  |  11.534s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   3.045s  |   3.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  24.807s  |  24.807s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |   2.100s  |   2.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |  13.299s  |  13.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   8.186s  |   8.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |  10.924s  |  10.924s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   1.930s  |   1.930s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   2.252s  |   2.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          | 600.057s  | 600.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   6.520s  |   6.520s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   2.675s  |   2.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   5.512s  |   5.512s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   6.675s  |   6.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |  13.508s  |  13.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |  16.071s  |  16.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  | 107.913s  | 107.913s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        | 139.955s  | 139.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |  54.044s  |  54.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |  18.293s  |  18.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   1.229s  |   1.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |  16.438s  |  16.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   1.023s  |   1.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |  11.968s  |  11.968s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |  12.756s  |  12.756s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |  77.514s  |  77.514s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |  22.582s  |  22.582s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   2.560s  |   2.560s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |   6.124s  |   6.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   2.957s  |   2.957s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |  61.796s  |  61.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        | 600.168s  | 600.168s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   2.185s  |   2.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |   8.761s  |   8.761s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |  31.322s  |  31.322s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   2.334s  |   2.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |  19.854s  |  19.854s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |  12.385s  |  12.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        | 600.186s  | 600.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |  14.273s  |  14.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |  14.457s  |  14.457s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   1.675s  |   1.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |   8.777s  |   8.777s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |  39.809s  |  39.809s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |   7.606s  |   7.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   1.492s  |   1.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        | 600.055s  | 600.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   2.072s  |   2.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   2.019s  |   2.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   7.530s  |   7.530s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |  44.443s  |  44.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |  15.879s  |  15.879s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |   1.645s  |   1.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   7.478s  |   7.478s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |  46.537s  |  46.537s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.803s  |   0.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  10.860s  |  10.860s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     | 232.723s  | 232.723s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   1.436s  |   1.436s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   8.036s  |   8.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |   7.264s  |   7.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       | 600.124s  | 600.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |   1.827s  |   1.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       | 331.856s  | 331.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   3.286s  |   3.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |  58.019s  |  58.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |  11.929s  |  11.929s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |  90.152s  |  90.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   2.433s  |   2.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   1.483s  |   1.483s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   2.227s  |   2.227s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |  67.029s  |  67.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       | 600.057s  | 600.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 | 122.549s  | 122.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   1.805s  |   1.805s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   2.734s  |   2.734s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       | 600.049s  | 600.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       | 600.221s  | 600.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |   7.952s  |   7.952s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 | 600.369s  | 600.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  93.710s  |  93.710s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |  36.152s  |  36.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  22.164s  |  22.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   2.742s  |   2.742s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |  13.843s  |  13.843s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  79.367s  |  79.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   1.966s  |   1.966s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  22.037s  |  22.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  39.333s  |  39.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   1.580s  |   1.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |  67.371s  |  67.371s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  | 230.259s  | 230.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   2.762s  |   2.762s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |  26.803s  |  26.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            | 600.335s  | 600.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   2.583s  |   2.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |  13.047s  |  13.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   3.104s  |   3.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   5.587s  |   5.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   2.664s  |   2.664s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   3.292s  |   3.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   2.436s  |   2.436s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                | 178.111s  | 178.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   3.504s  |   3.504s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   4.876s  |   4.876s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   2.020s  |   2.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   2.264s  |   2.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |  45.648s  |  45.648s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   3.381s  |   3.381s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   4.728s  |   4.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   5.386s  |   5.386s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   7.491s  |   7.491s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |   9.316s  |   9.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |  13.729s  |  13.729s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |  39.562s  |  39.562s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   1.561s  |   1.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   2.678s  |   2.678s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   3.433s  |   3.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   3.205s  |   3.205s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   5.107s  |   5.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  43.655s  |  43.655s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   9.244s  |   9.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                | 105.495s  | 105.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |   8.324s  |   8.324s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   3.902s  |   3.902s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  77.729s  |  77.729s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   5.758s  |   5.758s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |  10.188s  |  10.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   3.054s  |   3.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |  31.160s  |  31.160s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   3.681s  |   3.681s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   1.844s  |   1.844s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   2.956s  |   2.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   4.678s  |   4.678s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   8.381s  |   8.381s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |  61.418s  |  61.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   2.384s  |   2.384s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   2.447s  |   2.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   7.320s  |   7.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |  12.080s  |  12.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   4.501s  |   4.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   5.920s  |   5.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   3.589s  |   3.589s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   3.831s  |   3.831s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   3.103s  |   3.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   2.019s  |   2.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   8.583s  |   8.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  45.063s  |  45.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   1.649s  |   1.649s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   2.965s  |   2.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                | 600.433s  | 600.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   6.601s  |   6.601s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |  45.405s  |  45.405s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   3.264s  |   3.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   3.685s  |   3.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   9.763s  |   9.763s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  63.497s  |  63.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |  13.051s  |  13.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   2.197s  |   2.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   1.993s  |   1.993s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                | 600.186s  | 600.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   3.540s  |   3.540s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   2.726s  |   2.726s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   6.322s  |   6.322s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   2.528s  |   2.528s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |  50.343s  |  50.343s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   3.163s  |   3.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |  16.020s  |  16.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   8.225s  |   8.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  10.704s  |  10.704s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  11.201s  |  11.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   9.281s  |   9.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   3.041s  |   3.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   8.814s  |   8.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   3.172s  |   3.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   2.881s  |   2.881s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   7.165s  |   7.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                | 600.351s  | 600.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |   9.393s  |   9.393s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  39.303s  |  39.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   2.360s  |   2.360s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |  69.578s  |  69.578s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  40.837s  |  40.837s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   4.827s  |   4.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   7.525s  |   7.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   3.171s  |   3.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   2.046s  |   2.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   2.528s  |   2.528s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   3.708s  |   3.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  38.082s  |  38.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   3.975s  |   3.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |  14.310s  |  14.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   2.295s  |   2.295s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   2.144s  |   2.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   3.249s  |   3.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   2.818s  |   2.818s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |  23.362s  |  23.362s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   3.001s  |   3.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |   7.850s  |   7.850s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   2.230s  |   2.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   3.455s  |   3.455s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |  54.187s  |  54.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   2.307s  |   2.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   3.241s  |   3.241s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   6.682s  |   6.682s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   2.106s  |   2.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   9.076s  |   9.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   3.644s  |   3.644s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   2.876s  |   2.876s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |  21.411s  |  21.411s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   3.667s  |   3.667s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   2.262s  |   2.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   3.493s  |   3.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   6.213s  |   6.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          |  78.252s  |  78.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          |  84.188s  |  84.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          |  47.514s  |  47.514s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   6.299s  |   6.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   6.546s  |   6.546s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             | 600.229s  | 600.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            | 320.752s  | 320.752s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            | 230.956s  | 230.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   2.799s  |   2.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   2.316s  |   2.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   8.134s  |   8.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   4.651s  |   4.651s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |   5.087s  |   5.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   4.498s  |   4.498s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |   7.581s  |   7.581s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   3.642s  |   3.642s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   6.555s  |   6.555s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   8.980s  |   8.980s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   1.249s  |   1.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   4.293s  |   4.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   4.969s  |   4.969s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   9.021s  |   9.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   0.992s  |   0.992s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   3.908s  |   3.908s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   | 600.171s  | 600.171s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               | 441.834s  | 441.834s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |  42.734s  |  42.734s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |  58.618s  |  58.618s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               | 600.176s  | 600.176s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   5.716s  |   5.716s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   2.197s  |   2.197s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          | 600.198s  | 600.198s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   1.564s  |   1.564s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   1.398s  |   1.398s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               | 249.386s  | 249.386s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               | 600.383s  | 600.383s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  18.003s  |  18.003s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   4.466s  |   4.466s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         |  65.072s  |  65.072s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               | 600.459s  | 600.459s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               | 600.341s  | 600.341s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  90.825s  |  90.825s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   5.391s  |   5.391s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         | 600.396s  | 600.396s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         | 600.298s  | 600.298s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |   8.286s  |   8.286s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.695s  |   0.695s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         | 600.311s  | 600.311s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  18.069s  |  18.069s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  35.957s  |  35.957s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    | 600.958s  | 600.958s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  22.798s  |  22.798s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    | 600.462s  | 600.462s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  38.537s  |  38.537s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              | 600.298s  | 600.298s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  23.322s  |  23.322s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   5.037s  |   5.037s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   5.779s  |   5.779s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  49.732s  |  49.732s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   1.390s  |   1.390s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |  13.500s  |  13.500s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |  11.540s  |  11.540s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   5.236s  |   5.236s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   1.644s  |   1.644s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |   5.353s  |   5.353s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   6.762s  |   6.762s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  | 600.452s  | 600.452s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   4.296s  |   4.296s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  35.050s  |  35.050s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |   7.187s  |   7.187s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 | 600.219s  | 600.219s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  19.482s  |  19.482s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           | 607.943s  | 607.943s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |   9.712s  |   9.712s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |  58.583s  |  58.583s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   4.331s  |   4.331s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              | 600.124s  | 600.124s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  18.379s  |  18.379s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |  25.245s  |  25.245s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   4.955s  |   4.955s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |   9.037s  |   9.037s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  15.510s  |  15.510s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |   7.344s  |   7.344s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |  42.922s  |  42.922s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  74.956s  |  74.956s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  79.728s  |  79.728s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  24.550s  |  24.550s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  53.075s  |  53.075s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   5.518s  |   5.518s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   3.227s  |   3.227s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   2.115s  |   2.115s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             | 600.189s  | 600.189s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   2.920s  |   2.920s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.770s  |   0.770s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |  13.428s  |  13.428s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   3.623s  |   3.623s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   2.294s  |   2.294s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   6.797s  |   6.797s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |   1.974s  |   1.974s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   2.676s  |   2.676s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |  10.668s  |  10.668s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   2.597s  |   2.597s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   4.755s  |   4.755s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   6.272s  |   6.272s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   4.748s  |   4.748s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   1.174s  |   1.174s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   1.325s  |   1.325s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |   7.016s  |   7.016s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   2.352s  |   2.352s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               | 600.472s  | 600.472s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   0.816s  |   0.816s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            | 600.259s  | 600.259s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   2.166s  |   2.166s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 | 600.244s  | 600.244s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |   8.592s  |   8.592s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  31.109s  |  31.109s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |  10.272s  |  10.272s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |  12.902s  |  12.902s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |  11.712s  |  11.712s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 | 600.161s  | 600.161s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      | 289.825s  | 289.825s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |  13.191s  |  13.191s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |  12.606s  |  12.606s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  27.643s  |  27.643s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |  11.287s  |  11.287s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  30.466s  |  30.466s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |   6.420s  |   6.420s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   2.546s  |   2.546s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   5.098s  |   5.098s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      | 538.405s  | 538.405s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   3.333s  |   3.333s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |  10.709s  |  10.709s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   1.231s  |   1.231s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       | 431.565s  | 431.565s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   0.739s  |   0.739s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.606s  |   0.606s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |   8.127s  |   8.127s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.582s  |   0.582s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |  10.871s  |  10.871s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |  17.711s  |  17.711s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |  23.348s  |  23.348s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.661s  |   0.661s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       | 600.126s  | 600.126s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   9.068s  |   9.068s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   2.927s  |   2.927s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |   4.835s  |   4.835s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   3.091s  |   3.091s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       |  72.733s  |  72.733s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   3.553s  |   3.553s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   9.329s  |   9.329s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       | 187.271s  | 187.271s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   2.709s  |   2.709s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               | 265.315s  | 265.315s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         | 475.305s  | 475.305s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   3.292s  |   3.292s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.904s  |   0.904s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   2.075s  |   2.075s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 | 600.046s  | 600.046s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   1.010s  |   1.010s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |  11.139s  |  11.139s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |   8.047s  |   8.047s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |   4.092s  |   4.092s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   3.443s  |   3.443s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   4.695s  |   4.695s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   0.998s  |   0.998s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   3.116s  |   3.116s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                | 605.091s  | 605.091s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   4.325s  |   4.325s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   2.695s  |   2.695s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   2.933s  |   2.933s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   2.730s  |   2.730s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   6.627s  |   6.627s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |  12.862s  |  12.862s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   2.391s  |   2.391s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   1.880s  |   1.880s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   1.704s  |   1.704s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   1.919s  |   1.919s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   2.177s  |   2.177s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   1.192s  |   1.192s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   1.610s  |   1.610s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   3.254s  |   3.254s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   2.873s  |   2.873s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   2.078s  |   2.078s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |  11.428s  |  11.428s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   2.972s  |   2.972s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   3.521s  |   3.521s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   4.556s  |   4.556s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   7.949s  |   7.949s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   3.043s  |   3.043s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   1.244s  |   1.244s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   3.271s  |   3.271s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   4.039s  |   4.039s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   9.257s  |   9.257s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   2.695s  |   2.695s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   1.584s  |   1.584s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      | 121.787s  | 121.787s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   3.282s  |   3.282s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   2.790s  |   2.790s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   4.738s  |   4.738s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   8.124s  |   8.124s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   4.698s  |   4.698s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   4.633s  |   4.633s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   3.975s  |   3.975s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      | 246.853s  | 246.853s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      | 600.049s  | 600.049s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   1.922s  |   1.922s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   4.133s  |   4.133s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   1.447s  |   1.447s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   1.033s  |   1.033s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   5.164s  |   5.164s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   4.039s  |   4.039s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |  21.240s  |  21.240s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   1.637s  |   1.637s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   7.055s  |   7.055s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   3.266s  |   3.266s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |   5.102s  |   5.102s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |   5.939s  |   5.939s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   2.484s  |   2.484s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.881s  |   0.881s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   6.243s  |   6.243s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   2.880s  |   2.880s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   3.764s  |   3.764s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   2.786s  |   2.786s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   3.961s  |   3.961s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   4.631s  |   4.631s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   8.323s  |   8.323s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   3.535s  |   3.535s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   2.565s  |   2.565s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   2.226s  |   2.226s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   2.627s  |   2.627s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   8.312s  |   8.312s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   8.130s  |   8.130s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   1.866s  |   1.866s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   7.535s  |   7.535s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   3.680s  |   3.680s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   3.131s  |   3.131s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   6.365s  |   6.365s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   6.635s  |   6.635s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   4.890s  |   4.890s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |  11.538s  |  11.538s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            | 600.293s  | 600.293s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |   9.686s  |   9.686s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  44.724s  |  44.724s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |  17.482s  |  17.482s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  22.383s  |  22.383s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |  12.242s  |  12.242s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        | 600.484s  | 600.484s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        | 365.321s  | 365.321s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  18.720s  |  18.720s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   6.567s  |   6.567s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   5.487s  |   5.487s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     | 600.183s  | 600.183s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     | 529.518s  | 529.518s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     | 600.164s  | 600.164s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |  13.683s  |  13.683s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         | 600.397s  | 600.397s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               | 600.543s  | 600.543s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   1.899s  |   1.899s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |   3.953s  |   3.953s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               | 600.358s  | 600.358s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  | 600.232s  | 600.232s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |  63.552s  |  63.552s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     |  82.422s  |  82.422s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  24.352s  |  24.352s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  37.206s  |  37.206s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            |  74.356s  |  74.356s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            | 600.207s  | 600.207s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   4.088s  |   4.088s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   3.120s  |   3.120s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                | 600.178s  | 600.178s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   2.431s  |   2.431s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.778s  |   0.778s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  80.512s  |  80.512s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 | 600.277s  | 600.277s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 | 456.091s  | 456.091s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  64.553s  |  64.553s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 | 100.857s  | 100.857s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  16.509s  |  16.509s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |  21.609s  |  21.609s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           | 101.629s  | 101.629s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           | 600.195s  | 600.195s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |  32.173s  |  32.173s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  42.280s  |  42.280s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |  21.121s  |  21.121s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   9.092s  |   9.092s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  76.680s  |  76.680s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 | 600.446s  | 600.446s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  33.761s  |  33.761s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 | 544.884s  | 544.884s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   6.100s  |   6.100s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 | 195.080s  | 195.080s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 | 600.259s  | 600.259s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |  31.952s  |  31.952s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  16.313s  |  16.313s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 |  65.663s  |  65.663s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   8.097s  |   8.097s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 |  32.365s  |  32.365s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |  14.432s  |  14.432s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  27.248s  |  27.248s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |  42.898s  |  42.898s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |  26.796s  |  26.796s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |  20.763s  |  20.763s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  36.209s  |  36.209s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |  10.735s  |  10.735s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 | 589.871s  | 589.871s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 | 363.792s  | 363.792s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   5.214s  |   5.214s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |   6.291s  |   6.291s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 | 179.083s  | 179.083s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   3.704s  |   3.704s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |  67.391s  |  67.391s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   7.390s  |   7.390s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |  40.631s  |  40.631s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |  10.725s  |  10.725s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   3.077s  |   3.077s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   2.903s  |   2.903s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  18.625s  |  18.625s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 | 105.308s  | 105.308s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  47.838s  |  47.838s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 | 148.845s  | 148.845s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  20.329s  |  20.329s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        | 600.192s  | 600.192s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  37.231s  |  37.231s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  25.501s  |  25.501s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           | 130.845s  | 130.845s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           |  70.606s  |  70.606s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    | 600.185s  | 600.185s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       |  73.374s  |  73.374s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       | 290.475s  | 290.475s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  40.128s  |  40.128s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  75.937s  |  75.937s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |  13.580s  |  13.580s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  43.086s  |  43.086s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  27.207s  |  27.207s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 | 110.597s  | 110.597s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  47.157s  |  47.157s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  43.702s  |  43.702s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  | 600.178s  | 600.178s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  97.827s  |  97.827s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  30.813s  |  30.813s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   5.356s  |   5.356s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  43.627s  |  43.627s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     | 329.199s  | 329.199s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  74.185s  |  74.185s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          | 135.659s  | 135.659s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  76.615s  |  76.615s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  91.008s  |  91.008s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  21.541s  |  21.541s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  38.645s  |  38.645s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   4.561s  |   4.561s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   6.518s  |   6.518s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        |  66.295s  |  66.295s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        | 205.343s  | 205.343s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |  28.713s  |  28.713s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        | 619.990s  | 619.990s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        |  61.688s  |  61.688s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        | 600.117s  | 600.117s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        |  69.619s  |  69.619s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  | 600.206s  | 600.206s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   1.682s  |   1.682s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   1.546s  |   1.546s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   3.470s  |   3.470s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   6.210s  |   6.210s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  21.677s  |  21.677s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   3.374s  |   3.374s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 | 600.126s  | 600.126s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |   9.109s  |   9.109s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 | 600.148s  | 600.148s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |   9.940s  |   9.940s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   7.982s  |   7.982s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   3.351s  |   3.351s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   4.795s  |   4.795s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |   8.185s  |   8.185s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             | 600.124s  | 600.124s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             | 600.290s  | 600.290s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   5.744s  |   5.744s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             | 600.181s  | 600.181s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             | 600.214s  | 600.214s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   3.188s  |   3.188s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             | 190.320s  | 190.320s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             | 600.287s  | 600.287s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |   7.596s  |   7.596s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             | 600.281s  | 600.281s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   2.786s  |   2.786s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             | 319.809s  | 319.809s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             | 600.344s  | 600.344s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   4.267s  |   4.267s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   4.262s  |   4.262s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   4.136s  |   4.136s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   1.000s  |   1.000s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  23.075s  |  23.075s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   3.272s  |   3.272s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 | 600.133s  | 600.133s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 | 614.259s  | 614.259s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   3.417s  |   3.417s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   3.806s  |   3.806s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   5.548s  |   5.548s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 | 600.420s  | 600.420s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  |  59.071s  |  59.071s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |   3.391s  |   3.391s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 | 600.186s  | 600.186s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   1.824s  |   1.824s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |   6.234s  |   6.234s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   4.410s  |   4.410s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   2.925s  |   2.925s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 | 614.050s  | 614.050s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   3.582s  |   3.582s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   6.670s  |   6.670s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   8.608s  |   8.608s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |  16.308s  |  16.308s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  62.445s  |  62.445s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   2.344s  |   2.344s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   1.335s  |   1.335s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  | 614.409s  | 614.409s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            | 600.194s  | 600.194s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   3.155s  |   3.155s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |  18.072s  |  18.072s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   3.800s  |   3.800s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  |  50.921s  |  50.921s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   2.586s  |   2.586s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |  12.544s  |  12.544s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.670s  |   0.670s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |  13.705s  |  13.705s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   4.276s  |   4.276s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |  64.469s  |  64.469s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |  11.357s  |  11.357s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           | 600.262s  | 600.262s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           | 600.348s  | 600.348s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  21.478s  |  21.478s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               |  11.421s  |  11.421s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               | 600.469s  | 600.469s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               | 281.288s  | 281.288s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               | 600.335s  | 600.335s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               | 600.217s  | 600.217s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |   3.600s  |   3.600s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |  24.425s  |  24.425s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  74.878s  |  74.878s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |  17.302s  |  17.302s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   4.591s  |   4.591s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   1.295s  |   1.295s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |   2.993s  |   2.993s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   5.030s  |   5.030s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |  12.391s  |  12.391s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |   9.098s  |   9.098s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   4.079s  |   4.079s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   4.977s  |   4.977s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  30.776s  |  30.776s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  13.646s  |  13.646s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    | 600.199s  | 600.199s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   6.202s  |   6.202s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             | 600.192s  | 600.192s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   5.687s  |   5.687s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   5.410s  |   5.410s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  22.554s  |  22.554s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |  46.821s  |  46.821s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               | 332.896s  | 332.896s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         | 600.360s  | 600.360s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  17.873s  |  17.873s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  16.796s  |  16.796s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  15.696s  |  15.696s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  14.418s  |  14.418s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  17.457s  |  17.457s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        | 600.569s  | 600.569s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            |  37.892s  |  37.892s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            | 462.025s  | 462.025s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   4.080s  |   4.080s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |  41.712s  |  41.712s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |  11.869s  |  11.869s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            |  84.170s  |  84.170s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   2.743s  |   2.743s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  26.238s  |  26.238s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  39.425s  |  39.425s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              |  15.888s  |  15.888s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   1.614s  |   1.614s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  66.887s  |  66.887s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   2.831s  |   2.831s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |  23.166s  |  23.166s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  22.641s  |  22.641s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   4.045s  |   4.045s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   4.653s  |   4.653s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   4.620s  |   4.620s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   2.119s  |   2.119s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         | 104.673s  | 104.673s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |   4.949s  |   4.949s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           | 600.178s  | 600.178s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |  10.234s  |  10.234s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   4.661s  |   4.661s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   3.493s  |   3.493s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |   2.663s  |   2.663s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          | 600.273s  | 600.273s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          | 600.403s  | 600.403s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |  10.299s  |  10.299s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          | 600.411s  | 600.411s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          | 600.503s  | 600.503s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |  16.241s  |  16.241s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          | 600.259s  | 600.259s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          | 600.546s  | 600.546s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |   9.744s  |   9.744s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                | 600.239s  | 600.239s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                | 600.300s  | 600.300s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   2.354s  |   2.354s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                | 600.255s  | 600.255s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                | 601.420s  | 601.420s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |   9.756s  |   9.756s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                | 600.362s  | 600.362s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                | 600.498s  | 600.498s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |   9.128s  |   9.128s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                | 600.296s  | 600.296s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                | 600.473s  | 600.473s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          | 600.289s  | 600.289s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |  14.213s  |  14.213s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          | 600.170s  | 600.170s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   8.333s  |   8.333s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |  48.770s  |  48.770s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          | 413.415s  | 413.415s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |  46.697s  |  46.697s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   8.099s  |   8.099s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   4.427s  |   4.427s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |  29.864s  |  29.864s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   6.097s  |   6.097s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   6.779s  |   6.779s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |  29.858s  |  29.858s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   0.656s  |   0.656s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.876s  |   0.876s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                | 600.093s  | 600.093s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   5.384s  |   5.384s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   6.347s  |   6.347s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   5.688s  |   5.688s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   2.780s  |   2.780s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   5.941s  |   5.941s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   3.790s  |   3.790s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                | 304.664s  | 304.664s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   5.141s  |   5.141s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |  23.095s  |  23.095s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   5.104s  |   5.104s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   1.332s  |   1.332s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   0.703s  |   0.703s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |   3.623s  |   3.623s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |  88.609s  |  88.609s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   6.745s  |   6.745s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   6.453s  |   6.453s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   0.927s  |   0.927s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   5.475s  |   5.475s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |  18.868s  |  18.868s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   6.780s  |   6.780s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          | 490.603s  | 490.603s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   1.166s  |   1.166s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   1.380s  |   1.380s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   4.437s  |   4.437s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   8.400s  |   8.400s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   5.601s  |   5.601s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   1.290s  |   1.290s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   6.744s  |   6.744s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   2.593s  |   2.593s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   1.446s  |   1.446s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   7.513s  |   7.513s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |   5.358s  |   5.358s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          | 600.051s  | 600.051s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |   7.482s  |   7.482s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          |  15.086s  |  15.086s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  10.182s  |  10.182s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     | 116.689s  | 116.689s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           | 169.890s  | 169.890s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   2.949s  |   2.949s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  | 103.174s  | 103.174s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   3.583s  |   3.583s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   5.094s  |   5.094s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |   9.247s  |   9.247s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   4.898s  |   4.898s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |  43.892s  |  43.892s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        | 503.146s  | 503.146s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   5.399s  |   5.399s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |  87.725s  |  87.725s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |   9.695s  |   9.695s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   1.409s  |   1.409s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |  34.786s  |  34.786s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   5.368s  |   5.368s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   5.710s  |   5.710s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   1.063s  |   1.063s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |  12.135s  |  12.135s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   5.804s  |   5.804s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   1.682s  |   1.682s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   5.206s  |   5.206s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        | 600.126s  | 600.126s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   6.439s  |   6.439s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  19.703s  |  19.703s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   1.387s  |   1.387s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   6.881s  |   6.881s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   4.523s  |   4.523s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |  38.341s  |  38.341s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        | 285.610s  | 285.610s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |   5.315s  |   5.315s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            | 514.788s  | 514.788s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |  53.224s  |  53.224s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   0.753s  |   0.753s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   2.118s  |   2.118s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   1.688s  |   1.688s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   1.330s  |   1.330s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   5.842s  |   5.842s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   2.358s  |   2.358s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.928s  |   0.928s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.802s  |   0.802s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |  14.769s  |  14.769s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   4.634s  |   4.634s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  | 600.053s  | 600.053s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   0.642s  |   0.642s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |  30.405s  |  30.405s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                | 600.616s  | 600.616s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  68.992s  |  68.992s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   3.636s  |   3.636s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              | 127.680s  | 127.680s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        | 600.378s  | 600.378s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   | 600.226s  | 600.226s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   1.436s  |   1.436s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   | 600.204s  | 600.204s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |   2.822s  |   2.822s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   | 600.283s  | 600.283s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |   2.120s  |   2.120s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   3.513s  |   3.513s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |   9.299s  |   9.299s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         | 600.169s  | 600.169s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   1.548s  |   1.548s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        | 600.788s  | 600.788s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   8.171s  |   8.171s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        | 600.212s  | 600.212s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        | 600.245s  | 600.245s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |   7.696s  |   7.696s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        | 600.209s  | 600.209s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   1.963s  |   1.963s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   2.358s  |   2.358s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   6.910s  |   6.910s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  22.686s  |  22.686s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   8.811s  |   8.811s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   5.171s  |   5.171s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |  11.578s  |  11.578s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  37.561s  |  37.561s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |  17.445s  |  17.445s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |   9.234s  |   9.234s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            | 600.206s  | 600.206s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            | 600.285s  | 600.285s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |   8.171s  |   8.171s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            | 600.272s  | 600.272s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            | 600.204s  | 600.204s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   7.771s  |   7.771s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            | 600.941s  | 600.941s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   7.848s  |   7.848s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  | 600.171s  | 600.171s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   9.491s  |   9.491s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  14.822s  |  14.822s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  20.386s  |  20.386s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  16.247s  |  16.247s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  12.272s  |  12.272s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   6.228s  |   6.228s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |  80.047s  |  80.047s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         |  13.513s  |  13.513s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   3.212s  |   3.212s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         |  16.807s  |  16.807s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |  15.406s  |  15.406s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |   4.445s  |   4.445s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   3.959s  |   3.959s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   3.142s  |   3.142s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         | 135.278s  | 135.278s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   6.585s  |   6.585s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   5.854s  |   5.854s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   5.130s  |   5.130s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   2.750s  |   2.750s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   3.311s  |   3.311s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   2.217s  |   2.217s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   2.098s  |   2.098s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           | 600.236s  | 600.236s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |  48.006s  |  48.006s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           |  75.533s  |  75.533s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   0.924s  |   0.924s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   2.819s  |   2.819s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        | 618.917s  | 618.917s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   2.354s  |   2.354s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   3.439s  |   3.439s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   2.248s  |   2.248s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   3.122s  |   3.122s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   3.190s  |   3.190s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   2.866s  |   2.866s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   2.968s  |   2.968s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   4.010s  |   4.010s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             | 418.243s  | 418.243s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |  52.994s  |  52.994s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   6.471s  |   6.471s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |  36.340s  |  36.340s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   4.510s  |   4.510s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   0.796s  |   0.796s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |  75.912s  |  75.912s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   2.705s  |   2.705s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |  71.197s  |  71.197s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   5.950s  |   5.950s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |  13.137s  |  13.137s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   2.800s  |   2.800s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          | 600.324s  | 600.324s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                | 600.389s  | 600.389s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |  12.049s  |  12.049s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                | 600.213s  | 600.213s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                | 600.217s  | 600.217s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  17.950s  |  17.950s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                | 600.170s  | 600.170s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                | 600.393s  | 600.393s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  15.546s  |  15.546s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  21.441s  |  21.441s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |  17.691s  |  17.691s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   3.693s  |   3.693s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   2.556s  |   2.556s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              | 600.292s  | 600.292s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       | 600.549s  | 600.549s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       | 600.158s  | 600.158s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  18.365s  |  18.365s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  33.837s  |  33.837s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  50.385s  |  50.385s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           |  53.888s  |  53.888s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  16.644s  |  16.644s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  20.578s  |  20.578s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |  10.430s  |  10.430s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             | 600.201s  | 600.201s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  55.098s  |  55.098s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |  21.943s  |  21.943s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  17.326s  |  17.326s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  29.806s  |  29.806s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  40.439s  |  40.439s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |  21.394s  |  21.394s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  38.088s  |  38.088s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  21.324s  |  21.324s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           | 600.474s  | 600.474s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           | 600.559s  | 600.559s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           | 206.894s  | 206.894s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  15.429s  |  15.429s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 | 600.352s  | 600.352s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 | 600.258s  | 600.258s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   8.194s  |   8.194s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |   3.213s  |   3.213s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                | 600.236s  | 600.236s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                | 600.175s  | 600.175s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  13.475s  |  13.475s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  24.115s  |  24.115s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          | 600.519s  | 600.519s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          | 600.239s  | 600.239s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |  10.194s  |  10.194s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  15.299s  |  15.299s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   2.757s  |   2.757s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                |  49.489s  |  49.489s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   2.176s  |   2.176s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   5.059s  |   5.059s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   6.144s  |   6.144s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  33.261s  |  33.261s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   2.538s  |   2.538s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |  50.068s  |  50.068s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   2.222s  |   2.222s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   2.172s  |   2.172s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |  27.196s  |  27.196s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      | 134.074s  | 134.074s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   4.727s  |   4.727s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   0.998s  |   0.998s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      | 158.607s  | 158.607s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   3.248s  |   3.248s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   1.237s  |   1.237s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   1.576s  |   1.576s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  45.248s  |  45.248s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   2.178s  |   2.178s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  43.280s  |  43.280s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   4.236s  |   4.236s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |  15.365s  |  15.365s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |  15.767s  |  15.767s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   1.469s  |   1.469s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   9.228s  |   9.228s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |  17.417s  |  17.417s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  | 349.624s  | 349.624s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           | 600.487s  | 600.487s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   7.000s  |   7.000s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           | 201.782s  | 201.782s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   3.489s  |   3.489s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |  19.646s  |  19.646s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   2.000s  |   2.000s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.633s  |   0.633s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   2.555s  |   2.555s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   5.786s  |   5.786s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |  11.788s  |  11.788s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  12.906s  |  12.906s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   6.487s  |   6.487s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   1.885s  |   1.885s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   1.949s  |   1.949s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   1.785s  |   1.785s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |  14.253s  |  14.253s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   3.988s  |   3.988s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  | 278.699s  | 278.699s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   6.706s  |   6.706s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   3.558s  |   3.558s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   2.875s  |   2.875s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   4.155s  |   4.155s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   1.964s  |   1.964s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  29.317s  |  29.317s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  | 135.040s  | 135.040s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   3.850s  |   3.850s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  14.944s  |  14.944s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |   5.520s  |   5.520s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   2.908s  |   2.908s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   8.296s  |   8.296s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |  15.753s  |  15.753s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   5.027s  |   5.027s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   2.209s  |   2.209s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   1.015s  |   1.015s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   2.684s  |   2.684s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   0.979s  |   0.979s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  16.064s  |  16.064s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        | 532.727s  | 532.727s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.478s  |   0.478s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  42.771s  |  42.771s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                | 600.155s  | 600.155s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          | 616.556s  | 616.556s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   5.742s  |   5.742s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  11.949s  |  11.949s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   3.023s  |   3.023s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   4.415s  |   4.415s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       | 284.483s  | 284.483s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   3.489s  |   3.489s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |  38.504s  |  38.504s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   7.953s  |   7.953s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   3.686s  |   3.686s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       | 137.996s  | 137.996s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       | 600.199s  | 600.199s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   9.763s  |   9.763s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |   9.587s  |   9.587s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   4.602s  |   4.602s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   4.816s  |   4.816s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   1.935s  |   1.935s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   0.822s  |   0.822s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   3.718s  |   3.718s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |  11.273s  |  11.273s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |  10.101s  |  10.101s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   7.326s  |   7.326s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |  15.872s  |  15.872s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   3.117s  |   3.117s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        | 600.035s  | 600.035s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   7.385s  |   7.385s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  49.725s  |  49.725s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.848s  |   0.848s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  11.913s  |  11.913s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           | 101.341s  | 101.341s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   2.399s  |   2.399s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           |  15.431s  |  15.431s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   2.433s  |   2.433s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   3.167s  |   3.167s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   4.620s  |   4.620s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   3.794s  |   3.794s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   3.950s  |   3.950s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   0.846s  |   0.846s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   2.673s  |   2.673s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           |  39.745s  |  39.745s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   1.032s  |   1.032s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   1.040s  |   1.040s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           | 374.869s  | 374.869s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   2.200s  |   2.200s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   0.910s  |   0.910s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   3.375s  |   3.375s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   2.669s  |   2.669s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   2.647s  |   2.647s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   2.757s  |   2.757s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   2.260s  |   2.260s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   4.669s  |   4.669s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.886s  |   0.886s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |   8.977s  |   8.977s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   4.626s  |   4.626s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   2.461s  |   2.461s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           |  34.219s  |  34.219s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   4.418s  |   4.418s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   2.905s  |   2.905s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   4.690s  |   4.690s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.689s  |   0.689s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   1.345s  |   1.345s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   2.268s  |   2.268s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |   5.845s  |   5.845s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   1.915s  |   1.915s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           | 127.866s  | 127.866s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   2.502s  |   2.502s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   2.426s  |   2.426s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   8.010s  |   8.010s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   3.045s  |   3.045s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   3.204s  |   3.204s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |   4.127s  |   4.127s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   1.792s  |   1.792s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   4.618s  |   4.618s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   3.069s  |   3.069s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   2.644s  |   2.644s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   3.150s  |   3.150s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |   2.639s  |   2.639s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   2.314s  |   2.314s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  27.279s  |  27.279s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   3.531s  |   3.531s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |   5.888s  |   5.888s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.779s  |   0.779s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            |  69.386s  |  69.386s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   3.098s  |   3.098s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |   4.078s  |   4.078s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   6.009s  |   6.009s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   4.239s  |   4.239s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   1.572s  |   1.572s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  46.770s  |  46.770s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           | 134.592s  | 134.592s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   4.066s  |   4.066s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   8.420s  |   8.420s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  11.537s  |  11.537s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   2.522s  |   2.522s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   1.425s  |   1.425s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   3.533s  |   3.533s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   2.072s  |   2.072s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   2.006s  |   2.006s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   4.190s  |   4.190s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.565s  |   0.565s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |  65.782s  |  65.782s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   3.098s  |   3.098s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   2.501s  |   2.501s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   3.898s  |   3.898s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   1.176s  |   1.176s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |  10.451s  |  10.451s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   3.039s  |   3.039s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   3.113s  |   3.113s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   1.083s  |   1.083s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   5.496s  |   5.496s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.843s  |   0.843s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   0.925s  |   0.925s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   7.217s  |   7.217s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   2.344s  |   2.344s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   5.497s  |   5.497s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   3.155s  |   3.155s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   7.482s  |   7.482s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   3.704s  |   3.704s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |  10.645s  |  10.645s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   2.977s  |   2.977s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  41.496s  |  41.496s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.633s  |   0.633s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   2.318s  |   2.318s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   1.397s  |   1.397s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   5.845s  |   5.845s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   6.441s  |   6.441s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   2.469s  |   2.469s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |  11.469s  |  11.469s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   4.046s  |   4.046s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |  35.940s  |  35.940s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |  25.961s  |  25.961s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.916s  |   0.916s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.302s  |   1.302s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   1.902s  |   1.902s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   1.535s  |   1.535s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   1.464s  |   1.464s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   8.091s  |   8.091s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   1.156s  |   1.156s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            | 625.684s  | 625.684s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |  10.164s  |  10.164s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            | 523.385s  | 523.385s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            | 177.783s  | 177.783s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.807s  |   0.807s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.201s  |   0.201s  |   0.000s  | 0.0%|
</details>
