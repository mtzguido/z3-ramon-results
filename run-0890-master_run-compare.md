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
Job description: master run
Job tag: master_run
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 1f855efa094171e0aa7f79ca4165146f2230b9f1
Z3 branch: master
Z3 options: "-T:200"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: Fix nightly validation workflow failures and add Python wheel tests (#8490)

* Initial plan

* Fix nightly validation workflow issues and add Python wheel tests

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: master run
Job tag: master_run
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 1f855efa094171e0aa7f79ca4165146f2230b9f1
Z3 branch: master
Z3 options: "-T:200"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: Fix nightly validation workflow failures and add Python wheel tests (#8490)

* Initial plan

* Fix nightly validation workflow issues and add Python wheel tests

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 200.112s  | 200.112s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 200.104s  | 200.104s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.377s  |   0.377s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 200.112s  | 200.112s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 200.104s  | 200.104s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.377s  |   0.377s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 200.112s  | 200.112s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 200.104s  | 200.104s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.377s  |   0.377s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 200.112s  | 200.112s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 200.104s  | 200.104s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.377s  |   0.377s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 200.516s |2072.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 200.508s |859.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 200.463s |1130.0MiB|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                               | 200.412s |657.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 200.406s |833.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    | 200.380s |675.0MiB|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                         | 200.375s |756.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 200.366s |2610.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                | 200.364s |1007.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 200.355s |788.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                         | 200.334s |845.0MiB|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                           | 200.328s |524.0MiB|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                           | 200.322s |632.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 200.322s |1144.0MiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       | 200.319s |1214.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 200.312s |755.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                         | 200.312s |749.0MiB|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                         | 200.310s |586.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 200.302s |1717.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 200.298s |905.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 200.516s |2072.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 200.508s |859.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 200.463s |1130.0MiB|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                               | 200.412s |657.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 200.406s |833.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    | 200.380s |675.0MiB|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                         | 200.375s |756.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 200.366s |2610.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                | 200.364s |1007.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 200.355s |788.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                         | 200.334s |845.0MiB|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                           | 200.328s |524.0MiB|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                           | 200.322s |632.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 200.322s |1144.0MiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       | 200.319s |1214.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 200.312s |755.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                         | 200.312s |749.0MiB|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                         | 200.310s |586.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 200.302s |1717.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 200.298s |905.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |89.084MiB|89.084MiB|0B| 0.0%|
|04.smt2                                                                                     |74.448MiB|74.448MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.656MiB|31.656MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.54MiB|30.54MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.52MiB|23.52MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.076MiB|24.076MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.076MiB|24.076MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.892MiB|24.892MiB|0B| 0.0%|
|107.smt2                                                                                    |22.612MiB|22.612MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.504MiB|27.504MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.316MiB|80.316MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.804MiB|22.804MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.792MiB|22.792MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.688MiB|23.688MiB|0B| 0.0%|
|11.smt2                                                                                     |46.964MiB|46.964MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.0MiB|24.0MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.556MiB|23.556MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.684MiB|24.684MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.68MiB|25.68MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |89.084MiB|89.084MiB|0B| 0.0%|
|04.smt2                                                                                     |74.448MiB|74.448MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.656MiB|31.656MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.54MiB|30.54MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.52MiB|23.52MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.076MiB|24.076MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.076MiB|24.076MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.892MiB|24.892MiB|0B| 0.0%|
|107.smt2                                                                                    |22.612MiB|22.612MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.504MiB|27.504MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.316MiB|80.316MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.804MiB|22.804MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.792MiB|22.792MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.688MiB|23.688MiB|0B| 0.0%|
|11.smt2                                                                                     |46.964MiB|46.964MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.0MiB|24.0MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.556MiB|23.556MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.684MiB|24.684MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.68MiB|25.68MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |89.084MiB|89.084MiB|0B| 0.0%|
|04.smt2                                                                                     |74.448MiB|74.448MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.656MiB|31.656MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.54MiB|30.54MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.52MiB|23.52MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.076MiB|24.076MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.076MiB|24.076MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.892MiB|24.892MiB|0B| 0.0%|
|107.smt2                                                                                    |22.612MiB|22.612MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.504MiB|27.504MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.316MiB|80.316MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.804MiB|22.804MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.792MiB|22.792MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.688MiB|23.688MiB|0B| 0.0%|
|11.smt2                                                                                     |46.964MiB|46.964MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.0MiB|24.0MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.556MiB|23.556MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.684MiB|24.684MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.68MiB|25.68MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |89.084MiB|89.084MiB|0B| 0.0%|
|04.smt2                                                                                     |74.448MiB|74.448MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.656MiB|31.656MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.54MiB|30.54MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.52MiB|23.52MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.076MiB|24.076MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.076MiB|24.076MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.892MiB|24.892MiB|0B| 0.0%|
|107.smt2                                                                                    |22.612MiB|22.612MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.504MiB|27.504MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.316MiB|80.316MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.804MiB|22.804MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.792MiB|22.792MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.688MiB|23.688MiB|0B| 0.0%|
|11.smt2                                                                                     |46.964MiB|46.964MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.0MiB|24.0MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.556MiB|23.556MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.684MiB|24.684MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.68MiB|25.68MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                        | 136.672s |32.331GiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 200.366s |2610.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 200.291s |2171.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 200.516s |2072.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 200.302s |1717.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 200.269s |1583.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 200.253s |1447.0MiB|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                           | 200.182s |1215.0MiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       | 200.319s |1214.0MiB|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                 | 200.258s |1173.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 200.322s |1144.0MiB|
|185.smt2                                                                                   | 200.247s |1139.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 200.463s |1130.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 200.168s |1074.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              | 200.187s |1057.0MiB|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                            | 200.208s |1024.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 200.224s |1022.0MiB|
|From_T2__select.t2__p21345_terminationG_0.smt2                                             | 181.521s |1019.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                | 200.364s |1007.0MiB|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                           | 200.240s |1003.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                        | 136.672s |32.331GiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 200.366s |2610.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 200.291s |2171.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 200.516s |2072.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 200.302s |1717.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 200.269s |1583.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 200.253s |1447.0MiB|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                           | 200.182s |1215.0MiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       | 200.319s |1214.0MiB|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                 | 200.258s |1173.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 200.322s |1144.0MiB|
|185.smt2                                                                                   | 200.247s |1139.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 200.463s |1130.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 200.168s |1074.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              | 200.187s |1057.0MiB|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                            | 200.208s |1024.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 200.224s |1022.0MiB|
|From_T2__select.t2__p21345_terminationG_0.smt2                                             | 181.521s |1019.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                | 200.364s |1007.0MiB|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                           | 200.240s |1003.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 200.112s  | 200.112s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 200.104s  | 200.104s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|124.smt2                                                                                    | 200.035s  | 200.035s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.927s  |   0.927s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   1.761s  |   1.761s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|140.smt2                                                                                    | 200.091s  | 200.091s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   2.299s  |   2.299s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   1.483s  |   1.483s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.896s  |   0.896s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   1.863s  |   1.863s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   4.856s  |   4.856s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   4.509s  |   4.509s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   1.326s  |   1.326s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.555s  |   0.555s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|177.smt2                                                                                    | 200.077s  | 200.077s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   1.005s  |   1.005s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   2.787s  |   2.787s  |   0.000s  | 0.0%|
|181.smt2                                                                                    | 200.121s  | 200.121s  |   0.000s  | 0.0%|
|182.smt2                                                                                    | 200.102s  | 200.102s  |   0.000s  | 0.0%|
|183.smt2                                                                                    | 200.228s  | 200.228s  |   0.000s  | 0.0%|
|185.smt2                                                                                    | 200.247s  | 200.247s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.790s  |   0.790s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   2.201s  |   2.201s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   2.051s  |   2.051s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   2.063s  |   2.063s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   6.635s  |   6.635s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   4.975s  |   4.975s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   6.366s  |   6.366s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   5.607s  |   5.607s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   2.487s  |   2.487s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   2.484s  |   2.484s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   2.349s  |   2.349s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   1.441s  |   1.441s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   1.463s  |   1.463s  |   0.000s  | 0.0%|
|35.smt2                                                                                     | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|40.smt2                                                                                     | 200.153s  | 200.153s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   4.967s  |   4.967s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|54.smt2                                                                                     | 200.111s  | 200.111s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   2.796s  |   2.796s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   2.847s  |   2.847s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   1.742s  |   1.742s  |   0.000s  | 0.0%|
|58.smt2                                                                                     | 200.134s  | 200.134s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   2.251s  |   2.251s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   2.007s  |   2.007s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   6.217s  |   6.217s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|65.smt2                                                                                     | 200.101s  | 200.101s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   1.441s  |   1.441s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   0.515s  |   0.515s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|73.smt2                                                                                     | 200.088s  | 200.088s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   3.381s  |   3.381s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   1.492s  |   1.492s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   4.205s  |   4.205s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|966.smt2                                                                                    | 200.146s  | 200.146s  |   0.000s  | 0.0%|
|98.smt2                                                                                     | 200.076s  | 200.076s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|99.smt2                                                                                     | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |  14.163s  |  14.163s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.618s  |   0.618s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   4.535s  |   4.535s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          | 200.176s  | 200.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |   2.549s  |   2.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   1.035s  |   1.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |  14.383s  |  14.383s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          |   3.742s  |   3.742s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   3.721s  |   3.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   2.168s  |   2.168s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            | 200.175s  | 200.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   6.580s  |   6.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   4.127s  |   4.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       | 149.233s  | 149.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   3.051s  |   3.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  78.220s  |  78.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   3.383s  |   3.383s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |   9.454s  |   9.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   1.121s  |   1.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   1.838s  |   1.838s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           | 114.129s  | 114.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           |   3.972s  |   3.972s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |  55.665s  |  55.665s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   6.985s  |   6.985s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  20.586s  |  20.586s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   4.413s  |   4.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |   9.163s  |   9.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         | 200.072s  | 200.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             | 200.263s  | 200.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |  11.777s  |  11.777s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  12.242s  |  12.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 | 200.075s  | 200.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   2.060s  |   2.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   4.047s  |   4.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   8.083s  |   8.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              | 200.056s  | 200.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |   4.255s  |   4.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   1.296s  |   1.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               | 200.083s  | 200.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               | 131.922s  | 131.922s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         | 200.158s  | 200.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   7.859s  |   7.859s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |   2.411s  |   2.411s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       | 117.186s  | 117.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 |  31.344s  |  31.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      | 200.205s  | 200.205s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   1.812s  |   1.812s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   3.446s  |   3.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              | 200.113s  | 200.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   1.734s  |   1.734s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   4.490s  |   4.490s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          | 200.082s  | 200.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   1.353s  |   1.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   2.562s  |   2.562s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         |  12.124s  |  12.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   3.308s  |   3.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      | 200.188s  | 200.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |   2.025s  |   2.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               | 200.073s  | 200.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   7.449s  |   7.449s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         | 200.105s  | 200.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      | 200.056s  | 200.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               | 200.203s  | 200.203s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  22.121s  |  22.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |  14.786s  |  14.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   5.924s  |   5.924s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           | 200.064s  | 200.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               |  22.079s  |  22.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   4.661s  |   4.661s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               | 156.801s  | 156.801s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |   7.475s  |   7.475s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   5.249s  |   5.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           | 149.668s  | 149.668s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            | 200.141s  | 200.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   3.390s  |   3.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   |  48.135s  |  48.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   | 200.051s  | 200.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   | 200.189s  | 200.189s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             |   4.153s  |   4.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  29.169s  |  29.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   1.497s  |   1.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    | 200.111s  | 200.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |   3.744s  |   3.744s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        |   3.531s  |   3.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  24.706s  |  24.706s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  32.985s  |  32.985s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     | 200.061s  | 200.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               | 200.098s  | 200.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   7.683s  |   7.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   5.905s  |   5.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   2.886s  |   2.886s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |  13.124s  |  13.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               | 200.121s  | 200.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   1.333s  |   1.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   3.325s  |   3.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   4.690s  |   4.690s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   2.926s  |   2.926s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   1.712s  |   1.712s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   5.990s  |   5.990s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                | 200.145s  | 200.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   1.073s  |   1.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              |   3.527s  |   3.527s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |  18.412s  |  18.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   2.037s  |   2.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   6.943s  |   6.943s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  13.435s  |  13.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  43.136s  |  43.136s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   2.603s  |   2.603s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |   4.517s  |   4.517s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          | 107.495s  | 107.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          | 200.127s  | 200.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          |  46.937s  |  46.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |   3.481s  |   3.481s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          | 200.139s  | 200.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          | 200.118s  | 200.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  31.453s  |  31.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   1.706s  |   1.706s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  15.460s  |  15.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   1.967s  |   1.967s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    | 200.216s  | 200.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   4.645s  |   4.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   3.353s  |   3.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    |   3.787s  |   3.787s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   3.632s  |   3.632s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   2.975s  |   2.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |  45.669s  |  45.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        | 200.151s  | 200.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        | 200.058s  | 200.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        | 200.111s  | 200.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |   4.265s  |   4.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   5.193s  |   5.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        | 200.084s  | 200.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  51.560s  |  51.560s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  36.291s  |  36.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  70.805s  |  70.805s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  26.982s  |  26.982s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  50.380s  |  50.380s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              | 200.120s  | 200.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  50.439s  |  50.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  | 133.198s  | 133.198s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  |  95.677s  |  95.677s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  | 104.645s  | 104.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |  73.880s  |  73.880s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   3.119s  |   3.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.971s  |   0.971s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              | 200.108s  | 200.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   2.126s  |   2.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |  34.318s  |  34.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |  11.886s  |  11.886s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   2.969s  |   2.969s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  11.888s  |  11.888s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        |   3.251s  |   3.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   4.190s  |   4.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |   4.912s  |   4.912s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |   5.340s  |   5.340s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   |   2.995s  |   2.995s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     |  19.276s  |  19.276s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   2.460s  |   2.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   5.799s  |   5.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   0.958s  |   0.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     | 200.105s  | 200.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                | 200.122s  | 200.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   2.061s  |   2.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                |   4.891s  |   4.891s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      | 200.104s  | 200.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   2.284s  |   2.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      | 200.144s  | 200.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      | 200.156s  | 200.156s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   6.866s  |   6.866s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      | 131.596s  | 131.596s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |   3.691s  |   3.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   1.293s  |   1.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   4.126s  |   4.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   4.450s  |   4.450s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |   5.406s  |   5.406s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   4.870s  |   4.870s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |   7.736s  |   7.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  26.623s  |  26.623s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             | 200.077s  | 200.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   5.908s  |   5.908s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          | 200.107s  | 200.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               | 200.196s  | 200.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                | 100.248s  | 100.248s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |  16.483s  |  16.483s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |   5.089s  |   5.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   1.896s  |   1.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   1.399s  |   1.399s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   1.308s  |   1.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   5.177s  |   5.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              | 200.096s  | 200.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   2.645s  |   2.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   5.400s  |   5.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   9.301s  |   9.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   2.287s  |   2.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  10.129s  |  10.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          | 200.244s  | 200.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |   3.822s  |   3.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          |   3.626s  |   3.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          | 200.278s  | 200.278s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |   9.138s  |   9.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          | 200.142s  | 200.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          | 200.234s  | 200.234s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |  10.557s  |  10.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   8.113s  |   8.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   4.816s  |   4.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |   3.159s  |   3.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |   5.472s  |   5.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            | 200.096s  | 200.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |   5.785s  |   5.785s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   2.679s  |   2.679s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   3.226s  |   3.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     | 181.599s  | 181.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   4.153s  |   4.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |  29.292s  |  29.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |  14.554s  |  14.554s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           | 200.112s  | 200.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           | 200.090s  | 200.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |  37.748s  |  37.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   0.990s  |   0.990s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   1.418s  |   1.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           |   2.200s  |   2.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   0.770s  |   0.770s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   0.823s  |   0.823s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |   8.856s  |   8.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   2.275s  |   2.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   2.254s  |   2.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           | 200.102s  | 200.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  27.096s  |  27.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           | 200.112s  | 200.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |  19.661s  |  19.661s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |  65.013s  |  65.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |  19.398s  |  19.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   2.013s  |   2.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |   8.158s  |   8.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   2.452s  |   2.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  87.123s  |  87.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   1.456s  |   1.456s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   1.253s  |   1.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   1.634s  |   1.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |   5.828s  |   5.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   2.207s  |   2.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |   2.241s  |   2.241s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           | 200.049s  | 200.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  21.118s  |  21.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           | 200.090s  | 200.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   2.424s  |   2.424s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     | 200.150s  | 200.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   0.635s  |   0.635s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   1.367s  |   1.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |   1.070s  |   1.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   0.779s  |   0.779s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |  35.763s  |  35.763s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |  51.319s  |  51.319s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   1.432s  |   1.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   7.022s  |   7.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     | 200.130s  | 200.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |  22.888s  |  22.888s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |  13.380s  |  13.380s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |   2.239s  |   2.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   7.808s  |   7.808s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   0.767s  |   0.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   3.569s  |   3.569s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   1.462s  |   1.462s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   1.463s  |   1.463s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |  47.293s  |  47.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   5.527s  |   5.527s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     | 200.113s  | 200.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |   8.456s  |   8.456s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |   0.910s  |   0.910s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |   2.128s  |   2.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               | 200.154s  | 200.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |   1.150s  |   1.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   1.897s  |   1.897s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |   2.009s  |   2.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |   2.173s  |   2.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   1.489s  |   1.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   1.918s  |   1.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |   1.082s  |   1.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   0.907s  |   0.907s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   3.333s  |   3.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |  10.904s  |  10.904s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   7.607s  |   7.607s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     |   6.540s  |   6.540s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     | 200.124s  | 200.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  14.112s  |  14.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |  18.872s  |  18.872s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               | 200.073s  | 200.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   1.792s  |   1.792s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   3.822s  |   3.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               | 200.243s  | 200.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               | 200.106s  | 200.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |   9.754s  |   9.754s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |   4.353s  |   4.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               | 200.080s  | 200.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |   5.904s  |   5.904s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               | 200.139s  | 200.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               | 200.132s  | 200.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               | 200.141s  | 200.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               | 200.097s  | 200.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               | 200.159s  | 200.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   1.318s  |   1.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   1.815s  |   1.815s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   2.413s  |   2.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  58.550s  |  58.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               |   7.812s  |   7.812s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               |   2.121s  |   2.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   6.349s  |   6.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   0.632s  |   0.632s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |   6.379s  |   6.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               | 200.094s  | 200.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   0.913s  |   0.913s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   1.002s  |   1.002s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   6.647s  |   6.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   1.190s  |   1.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   2.208s  |   2.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               |   2.171s  |   2.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |  57.158s  |  57.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               | 200.117s  | 200.117s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   6.204s  |   6.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               | 200.199s  | 200.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               | 200.097s  | 200.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   2.325s  |   2.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |  31.271s  |  31.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |  65.842s  |  65.842s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   4.064s  |   4.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |  32.485s  |  32.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   1.484s  |   1.484s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |  10.383s  |  10.383s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             | 200.106s  | 200.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             | 200.082s  | 200.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |   9.141s  |   9.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   1.093s  |   1.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   1.121s  |   1.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   1.128s  |   1.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |   1.135s  |   1.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |  14.447s  |  14.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             | 200.097s  | 200.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   1.658s  |   1.658s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             | 200.143s  | 200.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |   2.874s  |   2.874s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   2.423s  |   2.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   2.506s  |   2.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             |   2.169s  |   2.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |  38.480s  |  38.480s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |  49.329s  |  49.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |   1.334s  |   1.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |   6.525s  |   6.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |   1.118s  |   1.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             | 200.092s  | 200.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   1.161s  |   1.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             | 200.175s  | 200.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |   7.931s  |   7.931s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             | 200.091s  | 200.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |  12.491s  |  12.491s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             | 200.075s  | 200.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             | 200.151s  | 200.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |   3.398s  |   3.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |  37.108s  |  37.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               |  17.163s  |  17.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |   1.925s  |   1.925s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         | 200.145s  | 200.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   6.208s  |   6.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              | 200.171s  | 200.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   1.044s  |   1.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   2.204s  |   2.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |   1.593s  |   1.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    | 200.078s  | 200.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |   5.762s  |   5.762s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |  18.492s  |  18.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   1.696s  |   1.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   2.367s  |   2.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |   6.640s  |   6.640s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   1.999s  |   1.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    | 200.056s  | 200.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   7.316s  |   7.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   0.830s  |   0.830s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   3.719s  |   3.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    | 200.098s  | 200.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    | 200.095s  | 200.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   1.865s  |   1.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   1.354s  |   1.354s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |   5.511s  |   5.511s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   1.221s  |   1.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    | 200.101s  | 200.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |   6.294s  |   6.294s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    | 200.086s  | 200.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   2.107s  |   2.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  32.098s  |  32.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              | 200.147s  | 200.147s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   1.527s  |   1.527s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    | 200.092s  | 200.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |  10.485s  |  10.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |  34.012s  |  34.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   2.314s  |   2.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    |   2.154s  |   2.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   4.768s  |   4.768s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    | 200.093s  | 200.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |   2.152s  |   2.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   7.565s  |   7.565s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   1.454s  |   1.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   7.368s  |   7.368s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |   1.680s  |   1.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   2.279s  |   2.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |  23.325s  |  23.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   1.426s  |   1.426s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          | 200.122s  | 200.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   7.918s  |   7.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          | 200.084s  | 200.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   3.315s  |   3.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  24.261s  |  24.261s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |   6.257s  |   6.257s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          | 200.156s  | 200.156s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          | 200.139s  | 200.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   2.154s  |   2.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          | 200.115s  | 200.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   2.153s  |   2.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          | 200.178s  | 200.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          |   2.092s  |   2.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          | 200.145s  | 200.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   6.294s  |   6.294s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   1.286s  |   1.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        | 200.166s  | 200.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   6.567s  |   6.567s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        | 200.126s  | 200.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |   2.116s  |   2.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |  12.489s  |  12.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |  29.887s  |  29.887s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |  11.448s  |  11.448s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |   2.169s  |   2.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |   6.124s  |   6.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   0.766s  |   0.766s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |   5.873s  |   5.873s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |  51.072s  |  51.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   5.528s  |   5.528s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |   2.150s  |   2.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |   6.726s  |   6.726s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   2.531s  |   2.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   1.032s  |   1.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |   2.446s  |   2.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   2.719s  |   2.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   3.151s  |   3.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        | 200.090s  | 200.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |  10.885s  |  10.885s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |   2.216s  |   2.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |   2.419s  |   2.419s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   8.666s  |   8.666s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        |   2.184s  |   2.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |   2.372s  |   2.372s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        | 200.094s  | 200.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |   8.967s  |   8.967s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   2.120s  |   2.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |  29.388s  |  29.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |  12.527s  |  12.527s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |  35.667s  |  35.667s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        |   2.222s  |   2.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   8.409s  |   8.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  | 200.152s  | 200.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   2.112s  |   2.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |  16.650s  |  16.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   1.449s  |   1.449s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |   0.775s  |   0.775s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |  35.482s  |  35.482s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   1.401s  |   1.401s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   2.251s  |   2.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     | 200.086s  | 200.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  14.233s  |  14.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   2.267s  |   2.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   0.674s  |   0.674s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     | 200.192s  | 200.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     | 200.048s  | 200.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     | 200.093s  | 200.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   1.458s  |   1.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |  14.653s  |  14.653s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       | 200.092s  | 200.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |   1.636s  |   1.636s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |  28.962s  |  28.962s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   1.865s  |   1.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |  24.508s  |  24.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |  15.587s  |  15.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       | 200.091s  | 200.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   0.865s  |   0.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |  13.399s  |  13.399s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       | 200.094s  | 200.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   2.107s  |   2.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   1.199s  |   1.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   7.494s  |   7.494s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       | 200.088s  | 200.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |   1.768s  |   1.768s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   1.682s  |   1.682s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   2.898s  |   2.898s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       | 200.052s  | 200.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       | 200.147s  | 200.147s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |  11.091s  |  11.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 | 200.178s  | 200.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            | 153.322s  | 153.322s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |  17.593s  |  17.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  24.618s  |  24.618s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   3.697s  |   3.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |  14.897s  |  14.897s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  62.722s  |  62.722s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   2.088s  |   2.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  38.438s  |  38.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   7.537s  |   7.537s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |  17.101s  |  17.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  70.742s  |  70.742s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   1.588s  |   1.588s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |  21.454s  |  21.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            | 140.402s  | 140.402s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   3.096s  |   3.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   7.798s  |   7.798s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   3.475s  |   3.475s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   3.760s  |   3.760s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   4.319s  |   4.319s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   2.543s  |   2.543s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   2.739s  |   2.739s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |  35.667s  |  35.667s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   3.210s  |   3.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   3.240s  |   3.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   2.503s  |   2.503s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   1.692s  |   1.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |   9.602s  |   9.602s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   4.027s  |   4.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |  10.441s  |  10.441s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   5.504s  |   5.504s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   3.162s  |   3.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |  14.458s  |  14.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |  12.069s  |  12.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |  14.678s  |  14.678s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   1.578s  |   1.578s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |  10.451s  |  10.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   8.636s  |   8.636s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   5.799s  |   5.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   3.601s  |   3.601s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  18.134s  |  18.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   8.242s  |   8.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  13.823s  |  13.823s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |  14.341s  |  14.341s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   4.955s  |   4.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   2.893s  |   2.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  37.279s  |  37.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   8.428s  |   8.428s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                | 200.088s  | 200.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   3.198s  |   3.198s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |  14.539s  |  14.539s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   3.960s  |   3.960s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   1.832s  |   1.832s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   2.996s  |   2.996s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   3.444s  |   3.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   7.862s  |   7.862s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   4.251s  |   4.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   3.259s  |   3.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   1.688s  |   1.688s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   2.710s  |   2.710s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   3.395s  |   3.395s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |  10.369s  |  10.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   4.556s  |   4.556s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   3.373s  |   3.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   4.572s  |   4.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   5.334s  |   5.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   2.819s  |   2.819s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   1.849s  |   1.849s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  18.301s  |  18.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   2.920s  |   2.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   2.736s  |   2.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                | 200.227s  | 200.227s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   1.554s  |   1.554s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |  13.088s  |  13.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   2.427s  |   2.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   3.886s  |   3.886s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |  23.280s  |  23.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  19.803s  |  19.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |  17.761s  |  17.761s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   3.632s  |   3.632s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   1.668s  |   1.668s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  31.922s  |  31.922s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   4.156s  |   4.156s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   2.784s  |   2.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   7.079s  |   7.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   1.750s  |   1.750s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |  71.853s  |  71.853s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |  26.229s  |  26.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |  19.170s  |  19.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |  21.687s  |  21.687s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  11.751s  |  11.751s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  22.224s  |  22.224s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |  12.906s  |  12.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   3.465s  |   3.465s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   3.472s  |   3.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   1.909s  |   1.909s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   3.567s  |   3.567s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   4.009s  |   4.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                | 200.201s  | 200.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |  12.960s  |  12.960s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  15.669s  |  15.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   2.392s  |   2.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |  58.452s  |  58.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  31.835s  |  31.835s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   3.541s  |   3.541s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   1.687s  |   1.687s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   1.970s  |   1.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   3.416s  |   3.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   2.666s  |   2.666s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   2.504s  |   2.504s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  13.773s  |  13.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   6.896s  |   6.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |  17.895s  |  17.895s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   1.464s  |   1.464s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   1.944s  |   1.944s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   3.118s  |   3.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   1.901s  |   1.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |  21.734s  |  21.734s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   2.646s  |   2.646s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |  15.880s  |  15.880s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   1.636s  |   1.636s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   3.704s  |   3.704s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   3.993s  |   3.993s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   3.237s  |   3.237s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   4.106s  |   4.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   5.631s  |   5.631s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   3.289s  |   3.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   3.063s  |   3.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   2.214s  |   2.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   7.080s  |   7.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |   9.057s  |   9.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   3.881s  |   3.881s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   3.165s  |   3.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   4.975s  |   4.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          |  66.724s  |  66.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          | 200.141s  | 200.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          |  83.857s  |  83.857s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   4.351s  |   4.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   4.463s  |   4.463s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             | 200.185s  | 200.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            | 116.427s  | 116.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            | 104.744s  | 104.744s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   2.679s  |   2.679s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   3.215s  |   3.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   7.209s  |   7.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   9.828s  |   9.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |   5.112s  |   5.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   2.672s  |   2.672s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |   6.058s  |   6.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   3.904s  |   3.904s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      | 200.072s  | 200.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   6.279s  |   6.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   9.038s  |   9.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   0.891s  |   0.891s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   5.642s  |   5.642s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   3.559s  |   3.559s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       | 200.132s  | 200.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   3.919s  |   3.919s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   1.549s  |   1.549s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   1.461s  |   1.461s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   6.412s  |   6.412s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   | 200.090s  | 200.090s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |  22.801s  |  22.801s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |  18.150s  |  18.150s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |   3.503s  |   3.503s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |  95.252s  |  95.252s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |   4.094s  |   4.094s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   5.744s  |   5.744s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   1.513s  |   1.513s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          | 147.679s  | 147.679s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          | 200.114s  | 200.114s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   2.132s  |   2.132s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   1.920s  |   1.920s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               | 200.128s  | 200.128s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               | 200.272s  | 200.272s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  21.759s  |  21.759s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               | 200.133s  | 200.133s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               | 200.091s  | 200.091s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   8.202s  |   8.202s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         | 200.187s  | 200.187s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         | 118.702s  | 118.702s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |   7.706s  |   7.706s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               | 200.236s  | 200.236s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  84.605s  |  84.605s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   3.866s  |   3.866s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |   6.482s  |   6.482s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         | 200.193s  | 200.193s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |  10.224s  |  10.224s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         | 200.261s  | 200.261s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  20.258s  |  20.258s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  35.265s  |  35.265s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    | 200.269s  | 200.269s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  73.743s  |  73.743s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    | 200.212s  | 200.212s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  20.826s  |  20.826s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  58.693s  |  58.693s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   1.612s  |   1.612s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              | 200.322s  | 200.322s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  78.747s  |  78.747s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   6.454s  |   6.454s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   6.135s  |   6.135s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |   8.875s  |   8.875s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   1.228s  |   1.228s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |  15.380s  |  15.380s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |  13.593s  |  13.593s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   6.479s  |   6.479s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   1.230s  |   1.230s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |   5.868s  |   5.868s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   7.276s  |   7.276s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  | 200.258s  | 200.258s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   4.286s  |   4.286s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 | 105.590s  | 105.590s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |  31.788s  |  31.788s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 | 200.164s  | 200.164s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  12.439s  |  12.439s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           | 200.181s  | 200.181s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |  10.416s  |  10.416s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |  35.461s  |  35.461s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              | 200.094s  | 200.094s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |  15.415s  |  15.415s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              | 200.080s  | 200.080s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  29.664s  |  29.664s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              |   5.116s  |   5.116s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              |   2.112s  |   2.112s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |  13.673s  |  13.673s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              | 200.095s  | 200.095s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              | 200.126s  | 200.126s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   4.437s  |   4.437s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |   9.014s  |   9.014s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  29.489s  |  29.489s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |  11.190s  |  11.190s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |  91.215s  |  91.215s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  47.863s  |  47.863s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  83.297s  |  83.297s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  48.338s  |  48.338s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  40.882s  |  40.882s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            | 144.922s  | 144.922s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   5.872s  |   5.872s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   2.339s  |   2.339s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             | 200.082s  | 200.082s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             | 200.064s  | 200.064s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   8.449s  |   8.449s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             | 200.135s  | 200.135s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   2.742s  |   2.742s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 | 200.088s  | 200.088s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  | 200.109s  | 200.109s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |   9.447s  |   9.447s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   3.793s  |   3.793s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             | 200.120s  | 200.120s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   4.027s  |   4.027s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   6.637s  |   6.637s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |   1.652s  |   1.652s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   4.958s  |   4.958s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |   3.677s  |   3.677s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   3.204s  |   3.204s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   3.442s  |   3.442s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   6.140s  |   6.140s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   4.902s  |   4.902s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   1.172s  |   1.172s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   1.285s  |   1.285s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |  36.918s  |  36.918s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   1.984s  |   1.984s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   9.719s  |   9.719s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               | 200.516s  | 200.516s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            | 200.158s  | 200.158s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   1.441s  |   1.441s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 | 200.251s  | 200.251s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |   9.539s  |   9.539s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  33.515s  |  33.515s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |   9.532s  |   9.532s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           | 200.094s  | 200.094s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |  11.119s  |  11.119s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |   9.481s  |   9.481s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 | 200.116s  | 200.116s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      | 200.140s  | 200.140s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |  12.779s  |  12.779s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |  11.791s  |  11.791s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           | 200.121s  | 200.121s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  31.442s  |  31.442s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |   9.467s  |   9.467s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  28.411s  |  28.411s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              | 200.091s  | 200.091s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |   3.924s  |   3.924s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   2.739s  |   2.739s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   5.804s  |   5.804s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      | 200.167s  | 200.167s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               |   3.805s  |   3.805s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              | 200.183s  | 200.183s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   3.237s  |   3.237s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       | 200.099s  | 200.099s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       | 200.109s  | 200.109s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   3.047s  |   3.047s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       | 200.122s  | 200.122s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       | 200.048s  | 200.048s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |  15.939s  |  15.939s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.844s  |   0.844s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       | 200.055s  | 200.055s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   0.886s  |   0.886s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   5.342s  |   5.342s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       | 200.118s  | 200.118s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       | 200.128s  | 200.128s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   1.096s  |   1.096s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       | 200.095s  | 200.095s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       | 200.098s  | 200.098s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       | 200.142s  | 200.142s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       | 200.072s  | 200.072s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   2.905s  |   2.905s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       | 200.148s  | 200.148s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |  59.703s  |  59.703s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   0.815s  |   0.815s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   5.318s  |   5.318s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       | 200.154s  | 200.154s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       | 200.080s  | 200.080s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   4.117s  |   4.117s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   1.680s  |   1.680s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       |   4.184s  |   4.184s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |  25.470s  |  25.470s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   0.906s  |   0.906s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.950s  |   0.950s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         | 200.199s  | 200.199s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   2.200s  |   2.200s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   1.313s  |   1.313s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 | 200.100s  | 200.100s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |   5.206s  |   5.206s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |   7.923s  |   7.923s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |   4.998s  |   4.998s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   3.883s  |   3.883s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   5.947s  |   5.947s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   1.235s  |   1.235s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   4.332s  |   4.332s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                | 200.248s  | 200.248s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   1.399s  |   1.399s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   5.761s  |   5.761s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   3.124s  |   3.124s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      |   4.232s  |   4.232s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   2.621s  |   2.621s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   2.564s  |   2.564s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      | 200.103s  | 200.103s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   1.945s  |   1.945s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   1.330s  |   1.330s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   6.121s  |   6.121s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   1.367s  |   1.367s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |  32.831s  |  32.831s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   1.902s  |   1.902s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   8.110s  |   8.110s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   2.580s  |   2.580s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   8.359s  |   8.359s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   1.443s  |   1.443s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |  11.520s  |  11.520s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.484s  |   0.484s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   8.240s  |   8.240s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      | 200.120s  | 200.120s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   4.733s  |   4.733s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      |   4.577s  |   4.577s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   2.211s  |   2.211s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   4.959s  |   4.959s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   2.177s  |   2.177s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   1.245s  |   1.245s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   2.061s  |   2.061s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   8.126s  |   8.126s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   8.825s  |   8.825s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   7.751s  |   7.751s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   5.177s  |   5.177s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   1.495s  |   1.495s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      | 200.116s  | 200.116s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   3.606s  |   3.606s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      | 200.122s  | 200.122s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   9.090s  |   9.090s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   4.012s  |   4.012s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   4.567s  |   4.567s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      | 200.213s  | 200.213s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   4.159s  |   4.159s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   2.950s  |   2.950s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   7.974s  |   7.974s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      | 200.104s  | 200.104s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   1.924s  |   1.924s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   2.527s  |   2.527s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   3.115s  |   3.115s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      | 200.073s  | 200.073s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   1.660s  |   1.660s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      | 200.151s  | 200.151s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   3.087s  |   3.087s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   2.980s  |   2.980s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      | 200.100s  | 200.100s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   1.915s  |   1.915s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      | 200.061s  | 200.061s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   3.090s  |   3.090s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   4.259s  |   4.259s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |   5.642s  |   5.642s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |   5.528s  |   5.528s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   2.805s  |   2.805s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.906s  |   0.906s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   5.866s  |   5.866s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   1.861s  |   1.861s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   4.042s  |   4.042s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   3.341s  |   3.341s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   2.656s  |   2.656s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   4.497s  |   4.497s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   8.692s  |   8.692s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   3.140s  |   3.140s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   2.935s  |   2.935s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   2.232s  |   2.232s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   5.577s  |   5.577s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   3.499s  |   3.499s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   7.993s  |   7.993s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   3.699s  |   3.699s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   6.293s  |   6.293s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   1.982s  |   1.982s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   2.851s  |   2.851s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   6.554s  |   6.554s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   6.256s  |   6.256s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   4.605s  |   4.605s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |   3.185s  |   3.185s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            | 200.240s  | 200.240s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |  28.818s  |  28.818s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  43.349s  |  43.349s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |  23.157s  |  23.157s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  34.915s  |  34.915s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |   4.167s  |   4.167s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        | 200.319s  | 200.319s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        | 200.302s  | 200.302s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  17.956s  |  17.956s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       |  90.012s  |  90.012s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   5.029s  |   5.029s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   3.336s  |   3.336s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     | 200.201s  | 200.201s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     | 200.380s  | 200.380s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     | 200.162s  | 200.162s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |  12.376s  |  12.376s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         | 200.224s  | 200.224s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               | 200.092s  | 200.092s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         | 200.232s  | 200.232s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               | 200.284s  | 200.284s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   1.551s  |   1.551s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |  11.208s  |  11.208s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               | 200.158s  | 200.158s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  | 200.171s  | 200.171s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  | 130.899s  | 130.899s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     | 119.675s  | 119.675s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  22.369s  |  22.369s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  19.294s  |  19.294s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            |   4.267s  |   4.267s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            | 200.159s  | 200.159s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   3.468s  |   3.468s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   1.897s  |   1.897s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   2.365s  |   2.365s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  79.429s  |  79.429s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 | 129.116s  | 129.116s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 | 200.263s  | 200.263s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  47.781s  |  47.781s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 | 200.117s  | 200.117s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  15.961s  |  15.961s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |  16.027s  |  16.027s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           | 157.128s  | 157.128s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           | 200.125s  | 200.125s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           | 124.468s  | 124.468s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |  10.624s  |  10.624s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  20.805s  |  20.805s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |  28.725s  |  28.725s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   5.802s  |   5.802s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 | 105.589s  | 105.589s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 | 200.172s  | 200.172s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  20.629s  |  20.629s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   6.204s  |   6.204s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 |   4.357s  |   4.357s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 | 200.122s  | 200.122s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |  16.135s  |  16.135s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  13.641s  |  13.641s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 | 200.205s  | 200.205s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   6.047s  |   6.047s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 | 150.483s  | 150.483s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |   9.001s  |   9.001s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  62.908s  |  62.908s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 | 200.075s  | 200.075s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   5.520s  |   5.520s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   7.497s  |   7.497s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 |   3.278s  |   3.278s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  43.256s  |  43.256s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |   7.102s  |   7.102s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 | 200.107s  | 200.107s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 | 165.997s  | 165.997s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   3.559s  |   3.559s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |   5.363s  |   5.363s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 |  87.652s  |  87.652s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   3.577s  |   3.577s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |  34.568s  |  34.568s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   1.930s  |   1.930s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 | 159.206s  | 159.206s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |   6.408s  |   6.408s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |  12.064s  |  12.064s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   2.707s  |   2.707s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   3.610s  |   3.610s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              | 200.179s  | 200.179s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  22.967s  |  22.967s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 | 107.356s  | 107.356s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  57.193s  |  57.193s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 |  80.927s  |  80.927s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  22.240s  |  22.240s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        | 200.165s  | 200.165s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  49.475s  |  49.475s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  23.325s  |  23.325s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           | 108.445s  | 108.445s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           | 139.721s  | 139.721s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    | 200.085s  | 200.085s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       | 106.636s  | 106.636s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       | 188.807s  | 188.807s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  49.083s  |  49.083s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       | 149.304s  | 149.304s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |  15.033s  |  15.033s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              | 200.228s  | 200.228s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 | 147.116s  | 147.116s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  32.784s  |  32.784s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  93.088s  |  93.088s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  52.563s  |  52.563s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  30.643s  |  30.643s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  |  44.448s  |  44.448s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     | 173.336s  | 173.336s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  28.902s  |  28.902s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   5.421s  |   5.421s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  52.815s  |  52.815s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     | 114.436s  | 114.436s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  95.796s  |  95.796s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            | 200.099s  | 200.099s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          | 131.552s  | 131.552s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  53.875s  |  53.875s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  68.015s  |  68.015s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  79.925s  |  79.925s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  52.818s  |  52.818s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   5.011s  |   5.011s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   9.164s  |   9.164s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        | 200.201s  | 200.201s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        | 200.235s  | 200.235s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |  30.309s  |  30.309s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        | 200.119s  | 200.119s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        | 200.096s  | 200.096s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        |  48.700s  |  48.700s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        | 200.132s  | 200.132s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        | 200.130s  | 200.130s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        |  48.111s  |  48.111s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  | 200.157s  | 200.157s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   2.116s  |   2.116s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     | 200.086s  | 200.086s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   1.102s  |   1.102s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   3.123s  |   3.123s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   5.864s  |   5.864s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  39.312s  |  39.312s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 | 200.091s  | 200.091s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   1.934s  |   1.934s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 | 200.108s  | 200.108s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 | 200.160s  | 200.160s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |   3.502s  |   3.502s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 | 200.082s  | 200.082s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 | 200.084s  | 200.084s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |   5.564s  |   5.564s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   8.091s  |   8.091s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   2.618s  |   2.618s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   6.153s  |   6.153s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |   2.888s  |   2.888s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             | 145.374s  | 145.374s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             | 200.120s  | 200.120s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   5.168s  |   5.168s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             | 199.765s  | 199.765s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             | 200.208s  | 200.208s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   8.868s  |   8.868s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |  78.806s  |  78.806s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             | 200.204s  | 200.204s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |   3.919s  |   3.919s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             | 122.688s  | 122.688s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             | 200.168s  | 200.168s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   3.085s  |   3.085s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             |  70.949s  |  70.949s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             | 200.172s  | 200.172s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   4.805s  |   4.805s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   4.360s  |   4.360s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  | 121.475s  | 121.475s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   1.450s  |   1.450s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   3.133s  |   3.133s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                | 200.086s  | 200.086s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   1.090s  |   1.090s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  10.805s  |  10.805s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           | 200.080s  | 200.080s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 | 200.074s  | 200.074s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   3.418s  |   3.418s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 | 200.105s  | 200.105s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 | 200.105s  | 200.105s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   2.777s  |   2.777s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 | 200.106s  | 200.106s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 | 200.093s  | 200.093s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   2.275s  |   2.275s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   4.737s  |   4.737s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 | 200.129s  | 200.129s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 | 200.132s  | 200.132s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           |   4.752s  |   4.752s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  | 200.286s  | 200.286s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |   3.931s  |   3.931s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 | 200.090s  | 200.090s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 | 200.137s  | 200.137s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   1.668s  |   1.668s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   1.987s  |   1.987s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |  18.702s  |  18.702s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 | 200.134s  | 200.134s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   2.922s  |   2.922s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 | 200.166s  | 200.166s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 | 200.182s  | 200.182s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   2.222s  |   2.222s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 |   3.263s  |   3.263s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   4.216s  |   4.216s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   6.559s  |   6.559s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  |  51.937s  |  51.937s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   2.876s  |   2.876s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |  13.379s  |  13.379s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            | 200.108s  | 200.108s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  23.658s  |  23.658s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   2.046s  |   2.046s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   2.023s  |   2.023s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  |  76.232s  |  76.232s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  | 200.098s  | 200.098s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            | 200.129s  | 200.129s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   2.422s  |   2.422s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 | 200.077s  | 200.077s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |   9.846s  |   9.846s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  | 200.090s  | 200.090s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   2.823s  |   2.823s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  |  16.013s  |  16.013s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  | 200.068s  | 200.068s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   2.135s  |   2.135s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  | 200.104s  | 200.104s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  | 200.056s  | 200.056s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   2.313s  |   2.313s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  | 200.107s  | 200.107s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  | 200.058s  | 200.058s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.675s  |   0.675s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |   6.098s  |   6.098s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            | 200.074s  | 200.074s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   3.729s  |   3.729s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |   3.703s  |   3.703s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   1.571s  |   1.571s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |   5.758s  |   5.758s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           |   4.387s  |   4.387s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           | 200.160s  | 200.160s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           | 200.109s  | 200.109s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  22.574s  |  22.574s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               |  12.528s  |  12.528s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               | 200.173s  | 200.173s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               | 160.630s  | 160.630s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               |   4.222s  |   4.222s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               | 200.196s  | 200.196s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |   2.536s  |   2.536s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |   6.540s  |   6.540s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  67.583s  |  67.583s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |   8.422s  |   8.422s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   3.736s  |   3.736s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   0.764s  |   0.764s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             | 200.137s  | 200.137s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |   2.887s  |   2.887s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   6.998s  |   6.998s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |   9.720s  |   9.720s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |   3.296s  |   3.296s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   3.106s  |   3.106s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   4.483s  |   4.483s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  16.726s  |  16.726s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  14.081s  |  14.081s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            | 200.101s  | 200.101s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    | 200.135s  | 200.135s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   7.742s  |   7.742s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               | 200.106s  | 200.106s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             | 200.092s  | 200.092s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   5.914s  |   5.914s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             | 200.056s  | 200.056s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             | 200.155s  | 200.155s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   4.745s  |   4.745s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             | 200.080s  | 200.080s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             | 200.152s  | 200.152s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  18.831s  |  18.831s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |   2.346s  |   2.346s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               | 200.187s  | 200.187s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         | 200.463s  | 200.463s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  22.676s  |  22.676s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  17.711s  |  17.711s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  16.229s  |  16.229s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  12.777s  |  12.777s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  18.564s  |  18.564s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        | 200.312s  | 200.312s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            |   4.537s  |   4.537s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   4.020s  |   4.020s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |  87.948s  |  87.948s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   4.891s  |   4.891s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            | 200.151s  | 200.151s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   2.917s  |   2.917s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.742s  |   0.742s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  10.569s  |  10.569s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              | 200.130s  | 200.130s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  22.964s  |  22.964s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              | 200.092s  | 200.092s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   1.811s  |   1.811s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          | 200.203s  | 200.203s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   4.100s  |   4.100s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          | 200.112s  | 200.112s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  12.061s  |  12.061s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       | 200.090s  | 200.090s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   4.763s  |   4.763s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       | 200.136s  | 200.136s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   6.296s  |   6.296s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   4.524s  |   4.524s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |  18.451s  |  18.451s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         | 113.680s  | 113.680s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |   5.984s  |   5.984s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           | 200.056s  | 200.056s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |  32.823s  |  32.823s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            | 200.092s  | 200.092s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              | 200.077s  | 200.077s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   3.411s  |   3.411s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   2.642s  |   2.642s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |   2.920s  |   2.920s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          | 200.312s  | 200.312s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          | 200.334s  | 200.334s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |   9.861s  |   9.861s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          | 200.187s  | 200.187s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          |   3.530s  |   3.530s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |   3.493s  |   3.493s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          | 200.158s  | 200.158s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          | 200.291s  | 200.291s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |   2.128s  |   2.128s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                | 200.101s  | 200.101s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                | 200.181s  | 200.181s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   2.098s  |   2.098s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                | 200.191s  | 200.191s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                | 200.298s  | 200.298s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |   9.604s  |   9.604s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                |   4.636s  |   4.636s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                | 200.355s  | 200.355s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |  10.605s  |  10.605s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                | 200.412s  | 200.412s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                | 200.508s  | 200.508s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          |   3.472s  |   3.472s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |   3.605s  |   3.605s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          |   3.880s  |   3.880s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   2.764s  |   2.764s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |   4.990s  |   4.990s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          | 200.117s  | 200.117s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   3.693s  |   3.693s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   5.102s  |   5.102s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |  11.221s  |  11.221s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   6.564s  |   6.564s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   4.283s  |   4.283s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                | 114.939s  | 114.939s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                | 200.100s  | 200.100s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                | 200.082s  | 200.082s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |   9.169s  |   9.169s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                | 200.058s  | 200.058s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                | 200.199s  | 200.199s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                | 200.115s  | 200.115s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |   3.555s  |   3.555s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   4.761s  |   4.761s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                | 200.088s  | 200.088s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   5.637s  |   5.637s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   6.670s  |   6.670s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                | 200.055s  | 200.055s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   4.562s  |   4.562s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                | 200.110s  | 200.110s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   3.469s  |   3.469s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |  61.880s  |  61.880s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   4.664s  |   4.664s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |  12.977s  |  12.977s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   5.149s  |   5.149s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                | 200.088s  | 200.088s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   0.841s  |   0.841s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |   5.978s  |   5.978s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                | 200.132s  | 200.132s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                | 200.050s  | 200.050s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |  34.391s  |  34.391s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   6.026s  |   6.026s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   7.123s  |   7.123s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   0.723s  |   0.723s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          | 200.100s  | 200.100s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          | 200.045s  | 200.045s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          | 200.105s  | 200.105s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   0.842s  |   0.842s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   5.209s  |   5.209s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |  43.907s  |  43.907s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   4.390s  |   4.390s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |   2.620s  |   2.620s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          | 200.064s  | 200.064s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   0.666s  |   0.666s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   0.992s  |   0.992s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   3.136s  |   3.136s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   3.739s  |   3.739s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          | 200.090s  | 200.090s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   8.873s  |   8.873s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   0.894s  |   0.894s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   6.519s  |   6.519s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   1.876s  |   1.876s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   0.841s  |   0.841s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |  12.610s  |  12.610s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   6.287s  |   6.287s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |   6.415s  |   6.415s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          | 200.096s  | 200.096s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          | 200.159s  | 200.159s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          | 200.075s  | 200.075s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          | 200.037s  | 200.037s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |   5.798s  |   5.798s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          |   3.827s  |   3.827s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  43.502s  |  43.502s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |   8.203s  |   8.203s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           | 200.099s  | 200.099s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   3.970s  |   3.970s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |  27.281s  |  27.281s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   5.453s  |   5.453s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        | 200.086s  | 200.086s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   4.019s  |   4.019s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        | 200.130s  | 200.130s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |  64.859s  |  64.859s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   9.255s  |   9.255s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |   4.921s  |   4.921s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   0.520s  |   0.520s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        | 112.506s  | 112.506s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        | 200.172s  | 200.172s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |   4.577s  |   4.577s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   5.039s  |   5.039s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        | 200.116s  | 200.116s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |  14.344s  |  14.344s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   0.781s  |   0.781s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   7.781s  |   7.781s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   7.160s  |   7.160s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   2.060s  |   2.060s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        |   2.573s  |   2.573s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   3.996s  |   3.996s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   6.501s  |   6.501s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   1.081s  |   1.081s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   5.891s  |   5.891s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |  19.779s  |  19.779s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        | 200.136s  | 200.136s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   5.117s  |   5.117s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        | 200.073s  | 200.073s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  53.693s  |  53.693s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   0.834s  |   0.834s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.626s  |   0.626s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   5.004s  |   5.004s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        | 200.098s  | 200.098s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        | 200.068s  | 200.068s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   3.748s  |   3.748s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        |  38.477s  |  38.477s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |   6.747s  |   6.747s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            | 200.182s  | 200.182s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  | 200.097s  | 200.097s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |  29.039s  |  29.039s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  | 200.130s  | 200.130s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   0.701s  |   0.701s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   0.912s  |   0.912s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   0.677s  |   0.677s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   1.119s  |   1.119s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   6.595s  |   6.595s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   1.710s  |   1.710s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  | 200.128s  | 200.128s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.648s  |   0.648s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   1.103s  |   1.103s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |   4.031s  |   4.031s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   9.169s  |   9.169s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  | 200.104s  | 200.104s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  | 200.044s  | 200.044s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   0.814s  |   0.814s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |  76.514s  |  76.514s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                | 200.214s  | 200.214s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  82.005s  |  82.005s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   9.089s  |   9.089s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              | 181.521s  | 181.521s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        | 200.290s  | 200.290s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   | 200.159s  | 200.159s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   | 200.168s  | 200.168s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   1.496s  |   1.496s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   | 200.072s  | 200.072s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   | 200.153s  | 200.153s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |   1.925s  |   1.925s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   | 200.110s  | 200.110s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   | 200.151s  | 200.151s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |   3.913s  |   3.913s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   |   2.314s  |   2.314s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         |  88.697s  |  88.697s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   1.671s  |   1.671s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   4.791s  |   4.791s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |   7.911s  |   7.911s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         |   3.150s  |   3.150s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   1.328s  |   1.328s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        | 200.195s  | 200.195s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        | 200.233s  | 200.233s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   8.312s  |   8.312s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        | 200.130s  | 200.130s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        | 200.191s  | 200.191s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |   7.955s  |   7.955s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        | 200.250s  | 200.250s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   1.959s  |   1.959s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   3.511s  |   3.511s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   8.264s  |   8.264s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  21.940s  |  21.940s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   6.364s  |   6.364s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   5.385s  |   5.385s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |   9.892s  |   9.892s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  15.220s  |  15.220s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |  11.476s  |  11.476s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |   3.375s  |   3.375s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            | 200.164s  | 200.164s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            | 200.178s  | 200.178s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |   8.117s  |   8.117s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            | 200.322s  | 200.322s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            | 200.136s  | 200.136s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   1.896s  |   1.896s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            | 200.328s  | 200.328s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  | 200.069s  | 200.069s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   7.180s  |   7.180s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  | 200.211s  | 200.211s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   4.286s  |   4.286s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            | 200.076s  | 200.076s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  17.204s  |  17.204s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  27.262s  |  27.262s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  13.461s  |  13.461s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  13.896s  |  13.896s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   6.979s  |   6.979s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   | 200.236s  | 200.236s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         |  11.643s  |  11.643s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   1.973s  |   1.973s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         | 200.105s  | 200.105s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |   8.261s  |   8.261s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |   3.723s  |   3.723s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   3.880s  |   3.880s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   3.460s  |   3.460s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         | 184.439s  | 184.439s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   8.095s  |   8.095s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   4.205s  |   4.205s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   6.271s  |   6.271s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   5.782s  |   5.782s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   2.894s  |   2.894s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   6.798s  |   6.798s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   3.049s  |   3.049s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   2.751s  |   2.751s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   | 200.128s  | 200.128s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           | 200.209s  | 200.209s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           | 200.282s  | 200.282s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           | 200.194s  | 200.194s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   1.963s  |   1.963s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |   4.780s  |   4.780s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           | 200.159s  | 200.159s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           |  28.889s  |  28.889s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   1.176s  |   1.176s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  |  54.518s  |  54.518s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   2.875s  |   2.875s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   2.193s  |   2.193s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   2.915s  |   2.915s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   2.227s  |   2.227s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   2.678s  |   2.678s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             | 200.068s  | 200.068s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   3.986s  |   3.986s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   2.007s  |   2.007s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   3.916s  |   3.916s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   4.094s  |   4.094s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             | 200.076s  | 200.076s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   0.816s  |   0.816s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |   4.184s  |   4.184s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   4.582s  |   4.582s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |   3.684s  |   3.684s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   4.552s  |   4.552s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |  42.081s  |  42.081s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             | 200.108s  | 200.108s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   2.902s  |   2.902s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |  20.726s  |  20.726s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   5.719s  |   5.719s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |  13.819s  |  13.819s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              | 200.131s  | 200.131s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   3.520s  |   3.520s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          | 200.366s  | 200.366s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                | 200.255s  | 200.255s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                | 160.172s  | 160.172s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |  10.877s  |  10.877s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                | 200.207s  | 200.207s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                | 200.164s  | 200.164s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  15.961s  |  15.961s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                | 200.126s  | 200.126s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                | 200.214s  | 200.214s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  15.541s  |  15.541s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                | 200.130s  | 200.130s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          | 200.152s  | 200.152s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |  10.284s  |  10.284s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   2.865s  |   2.865s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   2.779s  |   2.779s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              | 200.148s  | 200.148s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       | 200.406s  | 200.406s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       | 200.152s  | 200.152s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  16.887s  |  16.887s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  16.353s  |  16.353s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  35.326s  |  35.326s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  85.203s  |  85.203s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           |  34.021s  |  34.021s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  16.808s  |  16.808s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  43.105s  |  43.105s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   9.165s  |   9.165s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             | 200.130s  | 200.130s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  37.716s  |  37.716s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |  26.072s  |  26.072s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  36.379s  |  36.379s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  28.694s  |  28.694s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  42.335s  |  42.335s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |  18.357s  |  18.357s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  45.307s  |  45.307s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  44.088s  |  44.088s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           | 200.296s  | 200.296s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           | 200.253s  | 200.253s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           | 120.161s  | 120.161s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  11.295s  |  11.295s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 | 200.364s  | 200.364s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 | 200.280s  | 200.280s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   8.189s  |   8.189s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |  10.223s  |  10.223s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                | 200.219s  | 200.219s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                | 200.151s  | 200.151s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  11.646s  |  11.646s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  23.724s  |  23.724s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          | 200.375s  | 200.375s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          | 200.310s  | 200.310s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          | 182.673s  | 182.673s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |  11.673s  |  11.673s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |   5.292s  |   5.292s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     |   4.507s  |   4.507s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   2.023s  |   2.023s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                |  47.346s  |  47.346s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                | 200.117s  | 200.117s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   3.910s  |   3.910s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   4.011s  |   4.011s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            | 200.131s  | 200.131s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |  17.975s  |  17.975s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   3.263s  |   3.263s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  26.228s  |  26.228s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   2.537s  |   2.537s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |  56.347s  |  56.347s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   2.664s  |   2.664s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   1.409s  |   1.409s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            | 200.055s  | 200.055s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      | 200.144s  | 200.144s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   2.071s  |   2.071s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   0.954s  |   0.954s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      | 200.084s  | 200.084s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   0.814s  |   0.814s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   0.951s  |   0.951s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   1.653s  |   1.653s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  27.237s  |  27.237s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |   3.798s  |   3.798s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   1.946s  |   1.946s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 | 115.100s  | 115.100s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   2.177s  |   2.177s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |  10.679s  |  10.679s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   2.465s  |   2.465s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  11.239s  |  11.239s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |   5.325s  |   5.325s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  | 200.122s  | 200.122s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           |   3.969s  |   3.969s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      | 200.180s  | 200.180s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   2.942s  |   2.942s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      | 200.069s  | 200.069s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           | 200.052s  | 200.052s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           |  89.132s  |  89.132s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        | 200.068s  | 200.068s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   3.516s  |   3.516s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   1.882s  |   1.882s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   1.111s  |   1.111s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |   3.277s  |   3.277s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   2.422s  |   2.422s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   7.705s  |   7.705s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   5.294s  |   5.294s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |   8.985s  |   8.985s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   4.843s  |   4.843s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   1.843s  |   1.843s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   2.583s  |   2.583s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   1.022s  |   1.022s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |  77.958s  |  77.958s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   2.939s  |   2.939s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |  36.620s  |  36.620s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   8.518s  |   8.518s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   5.965s  |   5.965s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   3.213s  |   3.213s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   2.435s  |   2.435s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   1.831s  |   1.831s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |  15.769s  |  15.769s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  31.762s  |  31.762s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |   1.973s  |   1.973s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   3.314s  |   3.314s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  26.555s  |  26.555s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  19.364s  |  19.364s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   4.980s  |   4.980s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   5.564s  |   5.564s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                | 174.123s  | 174.123s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                | 200.094s  | 200.094s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                | 200.127s  | 200.127s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          | 189.241s  | 189.241s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   4.716s  |   4.716s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   2.343s  |   2.343s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   2.363s  |   2.363s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |   9.860s  |   9.860s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |   9.919s  |   9.919s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |  47.530s  |  47.530s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  13.318s  |  13.318s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                | 200.131s  | 200.131s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |   5.951s  |   5.951s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   3.347s  |   3.347s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  16.409s  |  16.409s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   2.625s  |   2.625s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   4.051s  |   4.051s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       | 200.113s  | 200.113s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   3.235s  |   3.235s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |  48.659s  |  48.659s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   6.622s  |   6.622s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   4.118s  |   4.118s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  70.665s  |  70.665s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       |   4.828s  |   4.828s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   3.024s  |   3.024s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       | 200.111s  | 200.111s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       |   4.229s  |   4.229s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       | 200.085s  | 200.085s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |   8.874s  |   8.874s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.999s  |   0.999s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   5.985s  |   5.985s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       | 200.080s  | 200.080s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   4.510s  |   4.510s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       | 200.092s  | 200.092s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     | 200.092s  | 200.092s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   2.091s  |   2.091s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  10.058s  |  10.058s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |  27.581s  |  27.581s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   3.652s  |   3.652s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |   1.436s  |   1.436s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   5.124s  |   5.124s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   3.303s  |   3.303s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   2.091s  |   2.091s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   2.865s  |   2.865s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |  23.389s  |  23.389s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        |   3.477s  |   3.477s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |  32.879s  |  32.879s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  29.607s  |  29.607s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  | 200.083s  | 200.083s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  | 200.106s  | 200.106s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.793s  |   0.793s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  38.272s  |  38.272s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |  10.500s  |  10.500s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   9.527s  |   9.527s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           | 200.118s  | 200.118s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           | 200.099s  | 200.099s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   1.668s  |   1.668s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   3.272s  |   3.272s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   4.296s  |   4.296s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   3.992s  |   3.992s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   3.899s  |   3.899s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           | 200.173s  | 200.173s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   3.580s  |   3.580s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   1.357s  |   1.357s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           | 200.085s  | 200.085s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           | 200.167s  | 200.167s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   2.231s  |   2.231s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   1.230s  |   1.230s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   4.072s  |   4.072s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   0.938s  |   0.938s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   2.285s  |   2.285s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   4.785s  |   4.785s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   2.389s  |   2.389s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   7.132s  |   7.132s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.884s  |   0.884s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |   8.943s  |   8.943s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   4.844s  |   4.844s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   2.826s  |   2.826s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           | 200.103s  | 200.103s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   3.532s  |   3.532s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           | 200.064s  | 200.064s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   6.682s  |   6.682s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   1.268s  |   1.268s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |   5.785s  |   5.785s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   1.548s  |   1.548s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           | 119.918s  | 119.918s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   1.297s  |   1.297s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   1.351s  |   1.351s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   5.968s  |   5.968s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   2.485s  |   2.485s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   2.842s  |   2.842s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |   3.877s  |   3.877s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.864s  |   0.864s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.771s  |   0.771s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   5.416s  |   5.416s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   5.163s  |   5.163s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   2.771s  |   2.771s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   1.204s  |   1.204s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           | 200.122s  | 200.122s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |   2.540s  |   2.540s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   1.364s  |   1.364s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   2.263s  |   2.263s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           | 145.668s  | 145.668s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   3.393s  |   3.393s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |   6.511s  |   6.511s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.942s  |   0.942s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            | 200.144s  | 200.144s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   3.095s  |   3.095s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |   4.454s  |   4.454s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   6.534s  |   6.534s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   2.693s  |   2.693s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   1.084s  |   1.084s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  75.961s  |  75.961s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           | 200.113s  | 200.113s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   3.708s  |   3.708s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   4.733s  |   4.733s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  10.975s  |  10.975s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   1.214s  |   1.214s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   3.035s  |   3.035s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   1.303s  |   1.303s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   2.603s  |   2.603s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   4.473s  |   4.473s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |  11.806s  |  11.806s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   3.488s  |   3.488s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   2.369s  |   2.369s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   3.934s  |   3.934s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   9.039s  |   9.039s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   7.959s  |   7.959s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           | 200.091s  | 200.091s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   3.128s  |   3.128s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   1.572s  |   1.572s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   6.388s  |   6.388s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           | 200.116s  | 200.116s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.647s  |   0.647s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   5.871s  |   5.871s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           | 200.148s  | 200.148s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   0.751s  |   0.751s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   5.041s  |   5.041s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   2.645s  |   2.645s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   7.814s  |   7.814s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   3.827s  |   3.827s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |  10.549s  |  10.549s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   2.233s  |   2.233s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.617s  |   0.617s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           | 200.093s  | 200.093s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  31.369s  |  31.369s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   2.467s  |   2.467s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   1.359s  |   1.359s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   9.447s  |   9.447s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   2.902s  |   2.902s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   1.320s  |   1.320s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |  11.742s  |  11.742s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   4.544s  |   4.544s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |   8.639s  |   8.639s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   0.951s  |   0.951s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.209s  |   1.209s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   1.682s  |   1.682s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   2.917s  |   2.917s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   2.060s  |   2.060s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   1.417s  |   1.417s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   1.289s  |   1.289s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            | 200.133s  | 200.133s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            | 200.080s  | 200.080s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            | 200.127s  | 200.127s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            | 200.150s  | 200.150s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            | 112.577s  | 112.577s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            | 200.090s  | 200.090s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.114s  |   0.114s  |   0.000s  | 0.0%|
</details>
