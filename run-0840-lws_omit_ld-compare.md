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
Job description: benchmark run
Job tag: lws_omit_ld
Runner: GCR-SANDBOX-011
Z3 repo: Z3Prover/z3
Z3 commit: f6decec23be93b32d1ba220f1471b40e2128b6d0
Z3 branch: lws
Z3 options: "-T:600"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: avoid ldcf with the projective theorem

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: benchmark run
Job tag: lws_omit_ld
Runner: GCR-SANDBOX-011
Z3 repo: Z3Prover/z3
Z3 commit: f6decec23be93b32d1ba220f1471b40e2128b6d0
Z3 branch: lws
Z3 options: "-T:600"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: avoid ldcf with the projective theorem

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.034s  | 600.034s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.037s  | 600.037s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.034s  | 600.034s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.037s  | 600.037s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.034s  | 600.034s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.037s  | 600.037s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.034s  | 600.034s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.037s  | 600.037s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                        | 600.577s |5028.0MiB|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                               | 600.541s |5903.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2               | 600.521s |6836.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 600.486s |7382.0MiB|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                             | 600.484s |4978.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                | 600.480s |5225.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 600.464s |3018.0MiB|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                       | 600.458s |5805.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              | 600.456s |6317.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 600.424s |5882.0MiB|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                              | 600.419s |5693.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               | 600.413s |6604.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          | 600.396s |5309.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                          | 600.375s |5825.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.371s |4855.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 600.356s |5058.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                         | 600.348s |4428.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 600.339s |4606.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.331s |4863.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                         | 600.310s |4518.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                        | 600.577s |5028.0MiB|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                               | 600.541s |5903.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2               | 600.521s |6836.0MiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 600.486s |7382.0MiB|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                             | 600.484s |4978.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                | 600.480s |5225.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 600.464s |3018.0MiB|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                       | 600.458s |5805.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              | 600.456s |6317.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 600.424s |5882.0MiB|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                              | 600.419s |5693.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               | 600.413s |6604.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          | 600.396s |5309.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                          | 600.375s |5825.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.371s |4855.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 600.356s |5058.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                         | 600.348s |4428.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 600.339s |4606.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.331s |4863.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                         | 600.310s |4518.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |172.0MiB|172.0MiB|0B| 0.0%|
|04.smt2                                                                                     |116.0MiB|116.0MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.604MiB|31.604MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.352MiB|30.352MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.48MiB|23.48MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.112MiB|24.112MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.156MiB|24.156MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.832MiB|24.832MiB|0B| 0.0%|
|107.smt2                                                                                    |22.324MiB|22.324MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.132MiB|27.132MiB|0B| 0.0%|
|1085.smt2                                                                                   |79.972MiB|79.972MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.784MiB|22.784MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.004MiB|23.004MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.556MiB|23.556MiB|0B| 0.0%|
|11.smt2                                                                                     |116.0MiB|116.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.024MiB|24.024MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.368MiB|23.368MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.748MiB|24.748MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.456MiB|25.456MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |172.0MiB|172.0MiB|0B| 0.0%|
|04.smt2                                                                                     |116.0MiB|116.0MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.604MiB|31.604MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.352MiB|30.352MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.48MiB|23.48MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.112MiB|24.112MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.156MiB|24.156MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.832MiB|24.832MiB|0B| 0.0%|
|107.smt2                                                                                    |22.324MiB|22.324MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.132MiB|27.132MiB|0B| 0.0%|
|1085.smt2                                                                                   |79.972MiB|79.972MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.784MiB|22.784MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.004MiB|23.004MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.556MiB|23.556MiB|0B| 0.0%|
|11.smt2                                                                                     |116.0MiB|116.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.024MiB|24.024MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.368MiB|23.368MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.748MiB|24.748MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.456MiB|25.456MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |172.0MiB|172.0MiB|0B| 0.0%|
|04.smt2                                                                                     |116.0MiB|116.0MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.604MiB|31.604MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.352MiB|30.352MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.48MiB|23.48MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.112MiB|24.112MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.156MiB|24.156MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.832MiB|24.832MiB|0B| 0.0%|
|107.smt2                                                                                    |22.324MiB|22.324MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.132MiB|27.132MiB|0B| 0.0%|
|1085.smt2                                                                                   |79.972MiB|79.972MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.784MiB|22.784MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.004MiB|23.004MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.556MiB|23.556MiB|0B| 0.0%|
|11.smt2                                                                                     |116.0MiB|116.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.024MiB|24.024MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.368MiB|23.368MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.748MiB|24.748MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.456MiB|25.456MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |172.0MiB|172.0MiB|0B| 0.0%|
|04.smt2                                                                                     |116.0MiB|116.0MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |31.604MiB|31.604MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.352MiB|30.352MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.48MiB|23.48MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.112MiB|24.112MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.156MiB|24.156MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.832MiB|24.832MiB|0B| 0.0%|
|107.smt2                                                                                    |22.324MiB|22.324MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.132MiB|27.132MiB|0B| 0.0%|
|1085.smt2                                                                                   |79.972MiB|79.972MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.784MiB|22.784MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.004MiB|23.004MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.556MiB|23.556MiB|0B| 0.0%|
|11.smt2                                                                                     |116.0MiB|116.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |24.024MiB|24.024MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.368MiB|23.368MiB|0B| 0.0%|
|1113.smt2                                                                                   |24.748MiB|24.748MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.456MiB|25.456MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                         | 600.074s |10.934GiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 600.486s |7382.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2               | 600.521s |6836.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               | 600.413s |6604.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              | 600.456s |6317.0MiB|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                               | 600.541s |5903.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 600.424s |5882.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                          | 600.375s |5825.0MiB|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                       | 600.458s |5805.0MiB|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                              | 600.419s |5693.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          | 600.396s |5309.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                | 600.480s |5225.0MiB|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                | 520.357s |5108.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 600.356s |5058.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                        | 600.577s |5028.0MiB|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                             | 600.484s |4978.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 600.300s |4872.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              | 471.745s |4872.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.331s |4863.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.371s |4855.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                         | 600.074s |10.934GiB|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                      | 600.486s |7382.0MiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2               | 600.521s |6836.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               | 600.413s |6604.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              | 600.456s |6317.0MiB|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                               | 600.541s |5903.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 600.424s |5882.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                          | 600.375s |5825.0MiB|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                       | 600.458s |5805.0MiB|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                              | 600.419s |5693.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          | 600.396s |5309.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                | 600.480s |5225.0MiB|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                | 520.357s |5108.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 600.356s |5058.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                        | 600.577s |5028.0MiB|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                             | 600.484s |4978.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 600.300s |4872.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              | 471.745s |4872.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.331s |4863.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.371s |4855.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.034s  | 600.034s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.037s  | 600.037s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|124.smt2                                                                                    | 600.033s  | 600.033s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.889s  |   0.889s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   0.677s  |   0.677s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|140.smt2                                                                                    | 600.031s  | 600.031s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   1.491s  |   1.491s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   1.015s  |   1.015s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|177.smt2                                                                                    | 600.043s  | 600.043s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|181.smt2                                                                                    | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|182.smt2                                                                                    | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|183.smt2                                                                                    | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|185.smt2                                                                                    | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   0.478s  |   0.478s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   0.847s  |   0.847s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   0.883s  |   0.883s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   1.909s  |   1.909s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   1.758s  |   1.758s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|35.smt2                                                                                     | 600.037s  | 600.037s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|40.smt2                                                                                     | 600.049s  | 600.049s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   0.558s  |   0.558s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|54.smt2                                                                                     | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   0.846s  |   0.846s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   0.902s  |   0.902s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|58.smt2                                                                                     | 600.037s  | 600.037s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   0.776s  |   0.776s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   0.957s  |   0.957s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   1.169s  |   1.169s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|65.smt2                                                                                     | 600.039s  | 600.039s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|73.smt2                                                                                     | 600.049s  | 600.049s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   0.565s  |   0.565s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|966.smt2                                                                                    | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|98.smt2                                                                                     | 600.049s  | 600.049s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|99.smt2                                                                                     | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |  15.220s  |  15.220s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   0.760s  |   0.760s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          | 600.191s  | 600.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |   1.132s  |   1.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |   2.953s  |   2.953s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          |   2.543s  |   2.543s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   1.537s  |   1.537s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   0.695s  |   0.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            |   2.800s  |   2.800s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   1.244s  |   1.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   1.298s  |   1.298s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       | 497.866s  | 497.866s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   1.013s  |   1.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  16.518s  |  16.518s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   1.111s  |   1.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |   1.911s  |   1.911s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           | 158.909s  | 158.909s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           |  89.713s  |  89.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         | 147.051s  | 147.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   5.383s  |   5.383s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  13.169s  |  13.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   1.346s  |   1.346s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |   4.107s  |   4.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         |   3.626s  |   3.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             | 254.870s  | 254.870s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |   1.774s  |   1.774s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |   1.937s  |   1.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 | 600.029s  | 600.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   0.674s  |   0.674s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   0.802s  |   0.802s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   3.804s  |   3.804s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              | 263.606s  | 263.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |   6.613s  |   6.613s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               | 600.042s  | 600.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               | 221.044s  | 221.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   4.069s  |   4.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |   6.074s  |   6.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 |  24.146s  |  24.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      | 600.045s  | 600.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   0.954s  |   0.954s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   2.721s  |   2.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   3.890s  |   3.890s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          |  17.623s  |  17.623s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   1.274s  |   1.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         |   9.797s  |   9.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   1.254s  |   1.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      | 600.286s  | 600.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |   1.872s  |   1.872s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   7.461s  |   7.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   1.807s  |   1.807s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         | 600.033s  | 600.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      | 600.017s  | 600.017s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  11.109s  |  11.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |   9.779s  |   9.779s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   1.844s  |   1.844s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               |   8.813s  |   8.813s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   0.766s  |   0.766s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               |   2.354s  |   2.354s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |   2.834s  |   2.834s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   1.010s  |   1.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           | 357.669s  | 357.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   1.421s  |   1.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   |  12.556s  |  12.556s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   | 600.030s  | 600.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             | 600.243s  | 600.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |   8.185s  |   8.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   0.612s  |   0.612s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    | 600.157s  | 600.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |   1.205s  |   1.205s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        | 179.852s  | 179.852s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  14.646s  |  14.646s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  20.211s  |  20.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               | 600.055s  | 600.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               | 242.321s  | 242.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   1.313s  |   1.313s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   1.305s  |   1.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   2.322s  |   2.322s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   1.215s  |   1.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   1.482s  |   1.482s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   1.956s  |   1.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              | 106.053s  | 106.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |   9.468s  |   9.468s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   1.885s  |   1.885s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |   9.671s  |   9.671s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  93.768s  |  93.768s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         | 600.057s  | 600.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          | 155.067s  | 155.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          |  36.595s  |  36.595s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |  14.589s  |  14.589s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          | 152.370s  | 152.370s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  21.079s  |  21.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   0.991s  |   0.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  10.316s  |  10.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    | 600.186s  | 600.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   2.308s  |   2.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    |   2.783s  |   2.783s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   1.521s  |   1.521s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |  12.724s  |  12.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        | 279.778s  | 279.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        | 600.033s  | 600.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |   4.740s  |   4.740s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |   2.806s  |   2.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   4.666s  |   4.666s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        |  71.184s  |  71.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  22.993s  |  22.993s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  13.540s  |  13.540s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  18.530s  |  18.530s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |   2.584s  |   2.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  21.898s  |  21.898s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              | 110.783s  | 110.783s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  33.029s  |  33.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  |  52.302s  |  52.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  |  38.845s  |  38.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |   4.533s  |   4.533s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |   5.409s  |   5.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   1.174s  |   1.174s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |  33.583s  |  33.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |   6.150s  |   6.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   1.704s  |   1.704s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |   2.692s  |   2.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        |  76.340s  |  76.340s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   0.911s  |   0.911s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |   2.541s  |   2.541s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |   1.857s  |   1.857s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   | 600.033s  | 600.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     |  21.281s  |  21.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   1.275s  |   1.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   0.863s  |   0.863s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     |   2.763s  |   2.763s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                |  28.156s  |  28.156s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      |  31.393s  |  31.393s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   1.324s  |   1.324s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      | 600.052s  | 600.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   1.844s  |   1.844s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      |  94.705s  |  94.705s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   0.712s  |   0.712s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   3.444s  |   3.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |   1.975s  |   1.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |   8.719s  |   8.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |   9.973s  |   9.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |  17.035s  |  17.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   3.819s  |   3.819s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                |   3.392s  |   3.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |   1.709s  |   1.709s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   0.772s  |   0.772s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   1.009s  |   1.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   1.882s  |   1.882s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   1.577s  |   1.577s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              | 600.057s  | 600.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   2.868s  |   2.868s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   1.988s  |   1.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   1.286s  |   1.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  10.364s  |  10.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |   2.339s  |   2.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |   8.150s  |   8.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |   9.975s  |   9.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   1.740s  |   1.740s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            |   2.466s  |   2.466s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   1.332s  |   1.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |   1.447s  |   1.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |   1.840s  |   1.840s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            |   2.439s  |   2.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   1.009s  |   1.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |   0.834s  |   0.834s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |  10.987s  |  10.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   3.316s  |   3.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |   7.426s  |   7.426s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   3.474s  |   3.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   2.747s  |   2.747s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |   1.976s  |   1.976s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |  62.830s  |  62.830s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   0.797s  |   0.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   0.922s  |   0.922s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |   6.480s  |   6.480s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           |   2.051s  |   2.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   1.416s  |   1.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |  11.142s  |  11.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |   0.814s  |   0.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  23.177s  |  23.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |   0.626s  |   0.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |   3.044s  |   3.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |   1.919s  |   1.919s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |  50.730s  |  50.730s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   2.297s  |   2.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |   6.403s  |   6.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   1.619s  |   1.619s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  26.317s  |  26.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   1.287s  |   1.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   1.068s  |   1.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   1.305s  |   1.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |  13.542s  |  13.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   2.135s  |   2.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |   2.194s  |   2.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           | 600.035s  | 600.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  13.679s  |  13.679s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   2.180s  |   2.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     | 600.208s  | 600.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |  12.155s  |  12.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |  19.571s  |  19.571s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   2.099s  |   2.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   2.049s  |   2.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     | 600.037s  | 600.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |   6.627s  |   6.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |   7.085s  |   7.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |   8.244s  |   8.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   6.105s  |   6.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   0.869s  |   0.869s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   1.405s  |   1.405s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   1.395s  |   1.395s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   1.731s  |   1.731s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     | 600.052s  | 600.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |  22.718s  |  22.718s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |  23.201s  |  23.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     | 600.051s  | 600.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |   0.702s  |   0.702s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |  18.735s  |  18.735s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   0.915s  |   0.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |  26.898s  |  26.898s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   0.572s  |   0.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   2.576s  |   2.576s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |   8.750s  |   8.750s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |  12.110s  |  12.110s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |   7.427s  |   7.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     |   5.575s  |   5.575s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     | 600.032s  | 600.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |   9.151s  |   9.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   0.728s  |   0.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               | 600.043s  | 600.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   7.705s  |   7.705s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |  52.485s  |  52.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |  28.745s  |  28.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |   3.382s  |   3.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               | 600.053s  | 600.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |   2.051s  |   2.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |  58.946s  |  58.946s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               |   2.052s  |   2.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               | 600.201s  | 600.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |  11.947s  |  11.947s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   1.319s  |   1.319s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   2.112s  |   2.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  22.928s  |  22.928s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               |   6.256s  |   6.256s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   1.329s  |   1.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |   5.895s  |   5.895s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               | 600.039s  | 600.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |   2.056s  |   2.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   1.284s  |   1.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   5.766s  |   5.766s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   0.813s  |   0.813s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               | 600.043s  | 600.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               | 600.043s  | 600.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   5.663s  |   5.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   2.135s  |   2.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |   4.029s  |   4.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |  12.510s  |  12.510s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   1.243s  |   1.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |  14.207s  |  14.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |   5.309s  |   5.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   2.137s  |   2.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |  14.283s  |  14.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   1.210s  |   1.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             | 600.032s  | 600.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |   6.242s  |   6.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   0.905s  |   0.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   0.642s  |   0.642s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   0.918s  |   0.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |   0.559s  |   0.559s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   5.553s  |   5.553s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |   7.888s  |   7.888s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   1.482s  |   1.482s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             |   2.064s  |   2.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |   1.203s  |   1.203s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |  10.736s  |  10.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   2.128s  |   2.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             | 600.036s  | 600.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   2.209s  |   2.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |  18.712s  |  18.712s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |   2.588s  |   2.588s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |   2.109s  |   2.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |   2.081s  |   2.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |   1.158s  |   1.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   1.465s  |   1.465s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |  15.024s  |  15.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             | 600.038s  | 600.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   9.666s  |   9.666s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |   2.993s  |   2.993s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |   9.493s  |   9.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               |  23.901s  |  23.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |   1.241s  |   1.241s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |   0.624s  |   0.624s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         | 173.862s  | 173.862s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   5.623s  |   5.623s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              |  20.420s  |  20.420s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   2.105s  |   2.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |   5.244s  |   5.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |   5.346s  |   5.346s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |  12.322s  |  12.322s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   1.478s  |   1.478s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   2.292s  |   2.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |   6.246s  |   6.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    | 600.051s  | 600.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   2.007s  |   2.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |  13.709s  |  13.709s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   3.060s  |   3.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    | 600.027s  | 600.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    | 600.039s  | 600.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    | 600.041s  | 600.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   1.249s  |   1.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   0.979s  |   0.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |   5.974s  |   5.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    | 600.052s  | 600.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |   5.781s  |   5.781s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   1.422s  |   1.422s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  39.412s  |  39.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  82.233s  |  82.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   1.180s  |   1.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    |   2.050s  |   2.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |   7.838s  |   7.838s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |  17.697s  |  17.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   2.135s  |   2.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    | 600.051s  | 600.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   1.570s  |   1.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   6.007s  |   6.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   0.766s  |   0.766s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   6.256s  |   6.256s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |   1.291s  |   1.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   1.352s  |   1.352s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |   4.552s  |   4.552s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   2.710s  |   2.710s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   2.385s  |   2.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  10.707s  |  10.707s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |  59.634s  |  59.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |   6.499s  |   6.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          | 600.039s  | 600.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          | 600.046s  | 600.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |  14.192s  |  14.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |   5.719s  |   5.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   2.099s  |   2.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          | 600.042s  | 600.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   4.128s  |   4.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   5.640s  |   5.640s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |   5.974s  |   5.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |   2.067s  |   2.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |  22.054s  |  22.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |  74.053s  |  74.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |   1.675s  |   1.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |   3.796s  |   3.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |   5.648s  |   5.648s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |  10.305s  |  10.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   5.192s  |   5.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        | 137.536s  | 137.536s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |  20.709s  |  20.709s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   1.634s  |   1.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |   4.696s  |   4.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   2.226s  |   2.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   2.495s  |   2.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        | 600.055s  | 600.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   0.793s  |   0.793s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |   8.671s  |   8.671s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |   1.065s  |   1.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |   2.887s  |   2.887s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   2.264s  |   2.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        | 600.027s  | 600.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |   8.347s  |   8.347s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        |   2.076s  |   2.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |  10.475s  |  10.475s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   1.140s  |   1.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        | 600.046s  | 600.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        | 493.182s  | 493.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |   2.072s  |   2.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   7.348s  |   7.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   7.200s  |   7.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  | 600.196s  | 600.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   2.094s  |   2.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   1.060s  |   1.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |   2.103s  |   2.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   1.347s  |   1.347s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   1.816s  |   1.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     |   2.062s  |   2.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |   8.761s  |   8.761s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   2.096s  |   2.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     | 600.040s  | 600.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   1.142s  |   1.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |   1.454s  |   1.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       | 600.033s  | 600.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |  36.101s  |  36.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |  38.736s  |  38.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |  34.469s  |  34.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |   1.954s  |   1.954s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       | 600.041s  | 600.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   1.366s  |   1.366s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   1.283s  |   1.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |  12.211s  |  12.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       | 600.036s  | 600.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   0.604s  |   0.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   1.103s  |   1.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   0.613s  |   0.613s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       |   2.058s  |   2.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |   6.183s  |   6.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 | 600.201s  | 600.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |   2.692s  |   2.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |   2.282s  |   2.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  11.788s  |  11.788s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |  10.429s  |  10.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  16.201s  |  16.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  27.258s  |  27.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  14.354s  |  14.354s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   1.685s  |   1.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |  31.672s  |  31.672s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |   2.757s  |   2.757s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   1.001s  |   1.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |  12.252s  |  12.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            | 172.006s  | 172.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   2.522s  |   2.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   0.975s  |   0.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   1.420s  |   1.420s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   6.602s  |   6.602s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   0.808s  |   0.808s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   0.803s  |   0.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |   2.810s  |   2.810s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   0.880s  |   0.880s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   1.320s  |   1.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |   6.855s  |   6.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   0.961s  |   0.961s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   5.980s  |   5.980s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   1.728s  |   1.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   1.624s  |   1.624s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |   9.667s  |   9.667s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |   1.179s  |   1.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |   7.672s  |   7.672s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   0.955s  |   0.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   1.600s  |   1.600s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   5.928s  |   5.928s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   0.956s  |   0.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   1.441s  |   1.441s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  11.390s  |  11.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   1.623s  |   1.623s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  10.659s  |  10.659s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |  13.691s  |  13.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   1.411s  |   1.411s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   0.850s  |   0.850s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  18.441s  |  18.441s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   6.007s  |   6.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   2.861s  |   2.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   0.965s  |   0.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |   8.441s  |   8.441s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   0.677s  |   0.677s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   1.235s  |   1.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   1.334s  |   1.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   5.924s  |   5.924s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   1.134s  |   1.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   1.630s  |   1.630s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   1.367s  |   1.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   1.753s  |   1.753s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   2.759s  |   2.759s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   1.357s  |   1.357s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   1.015s  |   1.015s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   0.989s  |   0.989s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  12.360s  |  12.360s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   0.915s  |   0.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                | 600.521s  | 600.521s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   0.801s  |   0.801s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |   7.576s  |   7.576s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   1.195s  |   1.195s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   1.063s  |   1.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   2.469s  |   2.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |   9.145s  |   9.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |   1.507s  |   1.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   2.879s  |   2.879s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   0.728s  |   0.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  46.757s  |  46.757s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   1.415s  |   1.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   1.267s  |   1.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |  21.599s  |  21.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   2.145s  |   2.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   6.718s  |   6.718s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   2.401s  |   2.401s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |   7.388s  |   7.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |   8.679s  |   8.679s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   1.275s  |   1.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   1.127s  |   1.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   1.716s  |   1.716s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   1.816s  |   1.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   6.048s  |   6.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                | 135.854s  | 135.854s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |   2.650s  |   2.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |   8.205s  |   8.205s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |  28.964s  |  28.964s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  13.222s  |  13.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   0.997s  |   0.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   0.917s  |   0.917s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   0.886s  |   0.886s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |   2.712s  |   2.712s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |   8.503s  |   8.503s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   1.015s  |   1.015s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |   3.377s  |   3.377s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |  12.972s  |  12.972s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   0.901s  |   0.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   5.932s  |   5.932s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   0.950s  |   0.950s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   2.068s  |   2.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   1.404s  |   1.404s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   0.823s  |   0.823s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   1.210s  |   1.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   6.239s  |   6.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |   2.510s  |   2.510s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   8.699s  |   8.699s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   0.721s  |   0.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   1.131s  |   1.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   1.705s  |   1.705s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          |  18.767s  |  18.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          |  21.035s  |  21.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          |  32.169s  |  32.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   1.741s  |   1.741s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   1.236s  |   1.236s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             | 308.848s  | 308.848s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            |  54.982s  |  54.982s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            |  61.085s  |  61.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   0.917s  |   0.917s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   5.560s  |   5.560s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    | 187.603s  | 187.603s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   1.104s  |   1.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |  62.942s  |  62.942s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   2.965s  |   2.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      | 600.023s  | 600.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   1.605s  |   1.605s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   3.124s  |   3.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   2.764s  |   2.764s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   1.286s  |   1.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   0.922s  |   0.922s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   |   2.875s  |   2.875s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |  16.491s  |  16.491s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |   8.713s  |   8.713s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |  29.366s  |  29.366s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               | 173.994s  | 173.994s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |   2.720s  |   2.720s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   1.159s  |   1.159s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          |  99.572s  |  99.572s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  17.965s  |  17.965s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               | 600.189s  | 600.189s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   2.538s  |   2.538s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         |  91.388s  |  91.388s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |   5.016s  |   5.016s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               | 600.456s  | 600.456s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  19.087s  |  19.087s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   1.547s  |   1.547s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |   4.522s  |   4.522s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         | 600.290s  | 600.290s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |   2.213s  |   2.213s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         | 354.950s  | 354.950s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |   9.121s  |   9.121s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  16.177s  |  16.177s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    | 600.300s  | 600.300s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  25.346s  |  25.346s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    | 474.990s  | 474.990s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |   8.887s  |   8.887s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  17.125s  |  17.125s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   0.812s  |   0.812s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  21.877s  |  21.877s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   3.830s  |   3.830s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   4.797s  |   4.797s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |   6.336s  |   6.336s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |   7.675s  |   7.675s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |   2.550s  |   2.550s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   3.993s  |   3.993s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |   3.432s  |   3.432s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   5.807s  |   5.807s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  | 434.815s  | 434.815s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   0.847s  |   0.847s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  27.109s  |  27.109s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |   5.728s  |   5.728s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 | 206.357s  | 206.357s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |   8.163s  |   8.163s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           | 600.396s  | 600.396s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |   1.464s  |   1.464s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |  19.665s  |  19.665s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              | 600.032s  | 600.032s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   2.192s  |   2.192s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              | 600.045s  | 600.045s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              | 600.033s  | 600.033s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  17.806s  |  17.806s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              | 600.046s  | 600.046s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              | 600.046s  | 600.046s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |  14.529s  |  14.529s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   0.974s  |   0.974s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |   7.711s  |   7.711s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  15.944s  |  15.944s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |   1.560s  |   1.560s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |  40.861s  |  40.861s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  20.270s  |  20.270s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  24.751s  |  24.751s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  13.254s  |  13.254s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  22.962s  |  22.962s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            | 203.601s  | 203.601s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   2.524s  |   2.524s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   0.938s  |   0.938s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             |   2.567s  |   2.567s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   1.851s  |   1.851s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             | 600.040s  | 600.040s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   0.891s  |   0.891s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 | 600.046s  | 600.046s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  | 600.051s  | 600.051s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |   2.349s  |   2.349s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   2.502s  |   2.502s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             | 600.034s  | 600.034s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   0.800s  |   0.800s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   1.698s  |   1.698s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |   1.185s  |   1.185s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   0.910s  |   0.910s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |   1.814s  |   1.814s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   0.898s  |   0.898s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   0.982s  |   0.982s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   1.876s  |   1.876s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   0.762s  |   0.762s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           | 550.806s  | 550.806s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   1.015s  |   1.015s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   2.948s  |   2.948s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               | 600.275s  | 600.275s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            | 600.157s  | 600.157s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   0.723s  |   0.723s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 | 600.292s  | 600.292s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |   2.282s  |   2.282s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  13.466s  |  13.466s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |   1.910s  |   1.910s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           | 600.036s  | 600.036s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |   2.043s  |   2.043s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |   2.042s  |   2.042s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 | 175.708s  | 175.708s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      | 111.607s  | 111.607s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |   1.679s  |   1.679s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |   2.594s  |   2.594s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  10.036s  |  10.036s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |   2.083s  |   2.083s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  11.894s  |  11.894s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |   3.702s  |   3.702s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   0.769s  |   0.769s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      | 176.389s  | 176.389s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               | 600.052s  | 600.052s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   1.023s  |   1.023s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |   2.794s  |   2.794s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       |   2.480s  |   2.480s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       | 600.046s  | 600.046s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |   2.751s  |   2.751s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   1.524s  |   1.524s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       | 116.316s  | 116.316s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |   7.793s  |   7.793s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |  28.690s  |  28.690s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       | 600.052s  | 600.052s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |  23.198s  |  23.198s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   0.822s  |   0.822s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       | 600.040s  | 600.040s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |  11.118s  |  11.118s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   2.746s  |   2.746s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       | 304.683s  | 304.683s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   2.522s  |   2.522s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   1.075s  |   1.075s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   0.863s  |   0.863s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   1.393s  |   1.393s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   0.835s  |   0.835s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |   7.084s  |   7.084s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |   6.936s  |   6.936s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |   2.121s  |   2.121s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   8.338s  |   8.338s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   2.744s  |   2.744s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                | 600.025s  | 600.025s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   0.889s  |   0.889s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                | 600.167s  | 600.167s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   3.656s  |   3.656s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      | 600.046s  | 600.046s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   0.546s  |   0.546s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |  13.531s  |  13.531s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   2.465s  |   2.465s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   6.407s  |   6.407s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   0.916s  |   0.916s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   5.813s  |   5.813s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |   6.479s  |   6.479s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   5.878s  |   5.878s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   2.543s  |   2.543s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      | 600.046s  | 600.046s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   2.611s  |   2.611s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   1.567s  |   1.567s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   0.982s  |   0.982s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   2.031s  |   2.031s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   6.363s  |   6.363s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   0.877s  |   0.877s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   1.244s  |   1.244s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |   3.189s  |   3.189s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   0.969s  |   0.969s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      | 600.033s  | 600.033s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   6.022s  |   6.022s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   1.263s  |   1.263s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   1.050s  |   1.050s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   1.259s  |   1.259s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   6.133s  |   6.133s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      | 378.819s  | 378.819s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |   6.237s  |   6.237s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   0.752s  |   0.752s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   0.968s  |   0.968s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   6.032s  |   6.032s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      | 600.052s  | 600.052s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      | 600.034s  | 600.034s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   0.752s  |   0.752s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   0.997s  |   0.997s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |   1.692s  |   1.692s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      | 600.043s  | 600.043s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   0.912s  |   0.912s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   1.085s  |   1.085s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |   2.882s  |   2.882s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      | 108.953s  | 108.953s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   2.727s  |   2.727s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   0.647s  |   0.647s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   1.472s  |   1.472s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   1.370s  |   1.370s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   6.752s  |   6.752s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   0.944s  |   0.944s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   0.685s  |   0.685s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   1.918s  |   1.918s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   2.139s  |   2.139s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   1.147s  |   1.147s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   1.844s  |   1.844s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   2.451s  |   2.451s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   1.394s  |   1.394s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |   2.352s  |   2.352s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            | 600.254s  | 600.254s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |   9.645s  |   9.645s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  16.969s  |  16.969s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |   8.263s  |   8.263s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  12.893s  |  12.893s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |  16.000s  |  16.000s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        |   2.813s  |   2.813s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        | 600.464s  | 600.464s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  13.829s  |  13.829s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       | 403.170s  | 403.170s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   3.115s  |   3.115s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   1.197s  |   1.197s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     | 174.437s  | 174.437s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     | 239.878s  | 239.878s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     |  99.072s  |  99.072s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |   8.916s  |   8.916s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         | 600.424s  | 600.424s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         | 600.577s  | 600.577s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               | 471.745s  | 471.745s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   0.859s  |   0.859s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |   1.914s  |   1.914s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               | 600.419s  | 600.419s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  | 211.915s  | 211.915s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |  55.540s  |  55.540s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     |  43.399s  |  43.399s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |   2.816s  |   2.816s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  11.070s  |  11.070s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            |  31.563s  |  31.563s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            | 378.264s  | 378.264s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   1.378s  |   1.378s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  40.366s  |  40.366s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 | 250.540s  | 250.540s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  29.826s  |  29.826s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 | 110.439s  | 110.439s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |   9.134s  |   9.134s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |   2.294s  |   2.294s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           |  39.732s  |  39.732s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           | 370.803s  | 370.803s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           |   2.726s  |   2.726s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |   8.341s  |   8.341s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  16.137s  |  16.137s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |  11.107s  |  11.107s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   1.740s  |   1.740s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  48.098s  |  48.098s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 | 520.357s  | 520.357s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  11.181s  |  11.181s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   1.504s  |   1.504s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 |  15.094s  |  15.094s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 | 600.223s  | 600.223s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |  49.172s  |  49.172s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  15.158s  |  15.158s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 | 130.458s  | 130.458s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   1.464s  |   1.464s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 |  26.100s  |  26.100s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |   2.702s  |   2.702s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  14.630s  |  14.630s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |  16.354s  |  16.354s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   3.055s  |   3.055s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   2.259s  |   2.259s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 | 322.129s  | 322.129s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  28.778s  |  28.778s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |   2.239s  |   2.239s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 |   1.584s  |   1.584s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 |  31.382s  |  31.382s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   1.324s  |   1.324s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |   5.113s  |   5.113s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 | 253.030s  | 253.030s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   2.637s  |   2.637s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |  24.640s  |  24.640s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   0.950s  |   0.950s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |  24.014s  |  24.014s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |   1.780s  |   1.780s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |   4.277s  |   4.277s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   1.240s  |   1.240s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   0.633s  |   0.633s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |   1.850s  |   1.850s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 |  25.126s  |  25.126s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  21.735s  |  21.735s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 |  32.125s  |  32.125s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |   9.056s  |   9.056s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        | 600.187s  | 600.187s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  16.350s  |  16.350s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  11.400s  |  11.400s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |  44.721s  |  44.721s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           |  56.475s  |  56.475s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    | 392.806s  | 392.806s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    | 600.188s  | 600.188s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       |  35.684s  |  35.684s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       |  69.650s  |  69.650s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  17.406s  |  17.406s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  36.275s  |  36.275s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |   2.076s  |   2.076s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              | 338.116s  | 338.116s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  48.203s  |  48.203s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |   7.269s  |   7.269s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  42.729s  |  42.729s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  22.555s  |  22.555s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  13.296s  |  13.296s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  |  14.452s  |  14.452s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  41.253s  |  41.253s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  12.342s  |  12.342s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   3.412s  |   3.412s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  19.783s  |  19.783s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |  45.364s  |  45.364s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  33.928s  |  33.928s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            | 174.528s  | 174.528s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          |  58.754s  |  58.754s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  22.871s  |  22.871s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  34.044s  |  34.044s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  44.645s  |  44.645s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  25.424s  |  25.424s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   1.118s  |   1.118s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   2.292s  |   2.292s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        | 513.140s  | 513.140s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        | 299.068s  | 299.068s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |   2.706s  |   2.706s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        |   2.631s  |   2.631s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        |  12.004s  |  12.004s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        |  25.936s  |  25.936s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        |   2.526s  |   2.526s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        | 333.068s  | 333.068s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        |  38.963s  |  38.963s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |  87.367s  |  87.367s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   0.754s  |   0.754s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   4.019s  |   4.019s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  12.297s  |  12.297s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |   1.200s  |   1.200s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |   2.106s  |   2.106s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   1.779s  |   1.779s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   2.741s  |   2.741s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   1.174s  |   1.174s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |   1.297s  |   1.297s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             |  91.606s  |  91.606s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             |   2.617s  |   2.617s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   1.756s  |   1.756s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             |  87.181s  |  87.181s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             | 205.239s  | 205.239s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   2.188s  |   2.188s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |  26.446s  |  26.446s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             | 600.180s  | 600.180s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |   2.371s  |   2.371s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             |   2.648s  |   2.648s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             | 176.696s  | 176.696s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   0.900s  |   0.900s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             | 168.654s  | 168.654s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             | 600.194s  | 600.194s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   2.193s  |   2.193s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   2.741s  |   2.741s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   1.245s  |   1.245s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                |   2.476s  |   2.476s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |   7.940s  |   7.940s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           | 600.042s  | 600.042s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 | 600.033s  | 600.033s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   0.889s  |   0.889s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 | 303.979s  | 303.979s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 | 600.038s  | 600.038s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   0.939s  |   0.939s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 | 600.024s  | 600.024s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   1.196s  |   1.196s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   1.886s  |   1.886s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  | 175.020s  | 175.020s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |   0.677s  |   0.677s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |   2.917s  |   2.917s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 | 600.045s  | 600.045s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   1.126s  |   1.126s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 | 374.591s  | 374.591s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 | 600.036s  | 600.036s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 | 370.143s  | 370.143s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   1.759s  |   1.759s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   3.791s  |   3.791s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   0.924s  |   0.924s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |   7.581s  |   7.581s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            | 600.041s  | 600.041s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  40.897s  |  40.897s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  |  12.614s  |  12.614s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  | 600.036s  | 600.036s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            | 600.038s  | 600.038s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 | 600.042s  | 600.042s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |   2.678s  |   2.678s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  |  13.837s  |  13.837s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   0.959s  |   0.959s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  | 600.041s  | 600.041s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  | 600.035s  | 600.035s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  | 600.038s  | 600.038s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  | 600.041s  | 600.041s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |   8.180s  |   8.180s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            | 600.033s  | 600.033s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |   7.882s  |   7.882s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   0.489s  |   0.489s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |   1.764s  |   1.764s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           |   2.780s  |   2.780s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  10.325s  |  10.325s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               |   2.705s  |   2.705s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               |  54.745s  |  54.745s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               |  92.186s  |  92.186s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               | 600.237s  | 600.237s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               | 600.259s  | 600.259s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |   1.347s  |   1.347s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |  12.225s  |  12.225s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  21.712s  |  21.712s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |   7.520s  |   7.520s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   2.263s  |   2.263s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   0.586s  |   0.586s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             | 600.035s  | 600.035s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |   2.292s  |   2.292s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   1.277s  |   1.277s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |   1.737s  |   1.737s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |   1.327s  |   1.327s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   3.134s  |   3.134s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  12.094s  |  12.094s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  10.362s  |  10.362s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    | 287.470s  | 287.470s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   2.443s  |   2.443s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   1.586s  |   1.586s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             |   2.444s  |   2.444s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   1.438s  |   1.438s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             |   2.439s  |   2.439s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  10.019s  |  10.019s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |   0.842s  |   0.842s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               | 600.299s  | 600.299s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         | 600.169s  | 600.169s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |   1.846s  |   1.846s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |   8.566s  |   8.566s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |   8.922s  |   8.922s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |   1.971s  |   1.971s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  11.916s  |  11.916s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        | 219.443s  | 219.443s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            | 600.039s  | 600.039s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   1.103s  |   1.103s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |   2.893s  |   2.893s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            | 515.318s  | 515.318s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   0.812s  |   0.812s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  10.463s  |  10.463s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              | 600.038s  | 600.038s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  21.743s  |  21.743s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              | 600.042s  | 600.042s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  10.155s  |  10.155s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          | 600.055s  | 600.055s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   1.175s  |   1.175s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          | 600.033s  | 600.033s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |   9.631s  |   9.631s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       | 600.040s  | 600.040s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   2.068s  |   2.068s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   1.282s  |   1.282s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   6.244s  |   6.244s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         |  47.763s  |  47.763s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           | 600.052s  | 600.052s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |  10.859s  |  10.859s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  | 600.037s  | 600.037s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            | 600.036s  | 600.036s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   1.098s  |   1.098s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   0.770s  |   0.770s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |   1.142s  |   1.142s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          |   2.776s  |   2.776s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          | 600.310s  | 600.310s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |   1.900s  |   1.900s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          | 600.220s  | 600.220s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          | 600.348s  | 600.348s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |   1.943s  |   1.943s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          |   2.123s  |   2.123s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          | 600.356s  | 600.356s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |   1.549s  |   1.549s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                | 600.279s  | 600.279s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                | 600.413s  | 600.413s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   1.210s  |   1.210s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                | 600.305s  | 600.305s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                | 600.339s  | 600.339s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |   7.968s  |   7.968s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                | 600.280s  | 600.280s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                | 600.271s  | 600.271s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |   7.915s  |   7.915s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                | 600.209s  | 600.209s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                | 600.249s  | 600.249s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          | 600.174s  | 600.174s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |   9.326s  |   9.326s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          | 600.309s  | 600.309s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   6.173s  |   6.173s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |   3.262s  |   3.262s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          |  39.017s  |  39.017s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                | 600.055s  | 600.055s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                | 600.036s  | 600.036s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   1.299s  |   1.299s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   1.346s  |   1.346s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |   2.540s  |   2.540s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   1.542s  |   1.542s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   1.718s  |   1.718s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                | 600.055s  | 600.055s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                | 600.038s  | 600.038s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |   8.743s  |   8.743s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                | 600.036s  | 600.036s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                | 363.260s  | 363.260s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                | 600.052s  | 600.052s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                | 600.034s  | 600.034s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   1.511s  |   1.511s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                | 600.057s  | 600.057s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   1.535s  |   1.535s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   1.893s  |   1.893s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   1.455s  |   1.455s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |   8.682s  |   8.682s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |  36.012s  |  36.012s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   1.661s  |   1.661s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                | 600.057s  | 600.057s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   1.863s  |   1.863s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                | 600.045s  | 600.045s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   0.880s  |   0.880s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |   1.466s  |   1.466s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                | 600.030s  | 600.030s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                | 600.015s  | 600.015s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |   7.388s  |   7.388s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   1.887s  |   1.887s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   1.542s  |   1.542s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          | 600.055s  | 600.055s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          | 600.026s  | 600.026s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          | 600.040s  | 600.040s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   0.976s  |   0.976s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |  64.263s  |  64.263s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   1.870s  |   1.870s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |   1.170s  |   1.170s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          | 600.027s  | 600.027s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   0.480s  |   0.480s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   1.180s  |   1.180s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   6.412s  |   6.412s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          | 600.031s  | 600.031s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   1.562s  |   1.562s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   1.832s  |   1.832s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          | 353.447s  | 353.447s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   1.608s  |   1.608s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |   1.681s  |   1.681s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          | 600.032s  | 600.032s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          | 600.041s  | 600.041s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          | 600.028s  | 600.028s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          | 600.039s  | 600.039s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |   1.435s  |   1.435s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          |  28.121s  |  28.121s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |   1.174s  |   1.174s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |  25.544s  |  25.544s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           | 132.956s  | 132.956s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           | 600.027s  | 600.027s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           | 600.017s  | 600.017s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   1.082s  |   1.082s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |   1.620s  |   1.620s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   1.236s  |   1.236s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        | 600.036s  | 600.036s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   1.217s  |   1.217s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |   2.463s  |   2.463s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |   3.172s  |   3.172s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   1.307s  |   1.307s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |   5.990s  |   5.990s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |  11.880s  |  11.880s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        | 600.036s  | 600.036s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |   2.064s  |   2.064s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   1.247s  |   1.247s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        | 134.912s  | 134.912s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |   1.793s  |   1.793s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |  26.664s  |  26.664s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   1.851s  |   1.851s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   1.449s  |   1.449s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   1.706s  |   1.706s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |  36.276s  |  36.276s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        | 600.037s  | 600.037s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   1.634s  |   1.634s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        | 600.043s  | 600.043s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        | 298.131s  | 298.131s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   0.713s  |   0.713s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   1.325s  |   1.325s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        | 600.045s  | 600.045s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        | 600.026s  | 600.026s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   1.114s  |   1.114s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        | 121.181s  | 121.181s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |   3.733s  |   3.733s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            | 121.545s  | 121.545s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  | 600.030s  | 600.030s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  | 600.052s  | 600.052s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |  51.532s  |  51.532s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  | 600.028s  | 600.028s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  | 600.035s  | 600.035s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   0.978s  |   0.978s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   2.290s  |   2.290s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   1.334s  |   1.334s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  | 110.723s  | 110.723s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   1.457s  |   1.457s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  | 600.045s  | 600.045s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |   2.979s  |   2.979s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                | 600.331s  | 600.331s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  17.203s  |  17.203s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   2.398s  |   2.398s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              |  40.720s  |  40.720s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        | 600.458s  | 600.458s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   0.912s  |   0.912s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |   1.152s  |   1.152s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |   1.134s  |   1.134s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   | 600.055s  | 600.055s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         |  56.277s  |  56.277s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   0.769s  |   0.769s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   1.106s  |   1.106s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |   5.968s  |   5.968s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        | 600.264s  | 600.264s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   1.025s  |   1.025s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        | 600.203s  | 600.203s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |   1.010s  |   1.010s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   0.980s  |   0.980s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   2.261s  |   2.261s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  10.074s  |  10.074s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   1.206s  |   1.206s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |   1.391s  |   1.391s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |   7.766s  |   7.766s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |   8.438s  |   8.438s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |   1.077s  |   1.077s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            |   2.224s  |   2.224s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |   0.890s  |   0.890s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            | 600.299s  | 600.299s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   0.969s  |   0.969s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   1.403s  |   1.403s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   0.810s  |   0.810s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |   9.227s  |   9.227s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  11.429s  |  11.429s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |   8.022s  |   8.022s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |   2.474s  |   2.474s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   1.083s  |   1.083s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         | 600.046s  | 600.046s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |  49.660s  |  49.660s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         | 600.045s  | 600.045s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |   5.962s  |   5.962s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |   1.363s  |   1.363s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   1.456s  |   1.456s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         |  20.133s  |  20.133s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   1.634s  |   1.634s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   1.901s  |   1.901s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   2.039s  |   2.039s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   1.002s  |   1.002s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   0.723s  |   0.723s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   3.428s  |   3.428s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   1.119s  |   1.119s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   | 600.042s  | 600.042s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           | 209.803s  | 209.803s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           | 600.051s  | 600.051s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           | 600.042s  | 600.042s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   0.520s  |   0.520s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |   8.082s  |   8.082s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           |   3.068s  |   3.068s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           | 191.826s  | 191.826s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           | 243.659s  | 243.659s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  |  84.355s  |  84.355s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   0.853s  |   0.853s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   6.126s  |   6.126s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   0.995s  |   0.995s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   1.131s  |   1.131s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   0.689s  |   0.689s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   1.214s  |   1.214s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   1.221s  |   1.221s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             | 117.100s  | 117.100s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             | 600.034s  | 600.034s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |  73.730s  |  73.730s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   1.653s  |   1.653s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |   2.500s  |   2.500s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             | 600.034s  | 600.034s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   1.409s  |   1.409s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |   3.337s  |   3.337s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             | 600.029s  | 600.029s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |  16.863s  |  16.863s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             | 600.035s  | 600.035s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   2.044s  |   2.044s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |   7.912s  |   7.912s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   0.888s  |   0.888s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          | 600.181s  | 600.181s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                | 363.335s  | 363.335s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                | 112.985s  | 112.985s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |   8.346s  |   8.346s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |   9.694s  |   9.694s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                | 600.222s  | 600.222s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  11.646s  |  11.646s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  20.675s  |  20.675s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |   2.636s  |   2.636s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   0.933s  |   0.933s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   0.987s  |   0.987s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              | 600.484s  | 600.484s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       | 600.486s  | 600.486s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       | 600.174s  | 600.174s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   2.322s  |   2.322s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |   9.083s  |   9.083s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  17.138s  |  17.138s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  25.591s  |  25.591s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           |  15.141s  |  15.141s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  10.131s  |  10.131s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  13.037s  |  13.037s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   1.698s  |   1.698s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  17.438s  |  17.438s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |  11.236s  |  11.236s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |   8.630s  |   8.630s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  10.560s  |  10.560s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  14.346s  |  14.346s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |   9.587s  |   9.587s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  21.745s  |  21.745s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  14.410s  |  14.410s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           | 600.375s  | 600.375s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           | 600.371s  | 600.371s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |  51.730s  |  51.730s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |   7.669s  |   7.669s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 | 600.480s  | 600.480s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 | 600.234s  | 600.234s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   1.702s  |   1.702s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |   2.052s  |   2.052s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                | 600.541s  | 600.541s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                | 151.020s  | 151.020s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |   2.439s  |   2.439s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  12.976s  |  12.976s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          | 600.230s  | 600.230s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          |  89.325s  |  89.325s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |   2.577s  |   2.577s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  15.880s  |  15.880s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     | 284.263s  | 284.263s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                | 149.271s  | 149.271s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   1.895s  |   1.895s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            |   7.827s  |   7.827s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |  10.966s  |  10.966s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   1.077s  |   1.077s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  16.509s  |  16.509s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   1.598s  |   1.598s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |  30.998s  |  30.998s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |   1.115s  |   1.115s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            | 600.045s  | 600.045s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      |  28.498s  |  28.498s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   0.656s  |   0.656s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      |  70.772s  |  70.772s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   0.559s  |   0.559s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  28.838s  |  28.838s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |  65.478s  |  65.478s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   0.620s  |   0.620s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  28.575s  |  28.575s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   1.029s  |   1.029s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |   2.322s  |   2.322s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |  16.041s  |  16.041s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   6.481s  |   6.481s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |   7.336s  |   7.336s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  | 600.036s  | 600.036s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  | 155.466s  | 155.466s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   1.558s  |   1.558s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           | 600.043s  | 600.043s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           |  82.461s  |  82.461s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        | 600.042s  | 600.042s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   2.448s  |   2.448s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   2.451s  |   2.451s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |  25.769s  |  25.769s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   1.612s  |   1.612s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   2.004s  |   2.004s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |   6.391s  |   6.391s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   2.835s  |   2.835s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   0.613s  |   0.613s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |   7.298s  |   7.298s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |   3.775s  |   3.775s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   2.288s  |   2.288s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   1.180s  |   1.180s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   0.980s  |   0.980s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   0.557s  |   0.557s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |  42.300s  |  42.300s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  49.677s  |  49.677s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |   1.169s  |   1.169s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   1.201s  |   1.201s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |   9.423s  |   9.423s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  15.712s  |  15.712s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   1.011s  |   1.011s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |   3.460s  |   3.460s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   1.707s  |   1.707s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |   2.520s  |   2.520s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                | 600.032s  | 600.032s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                | 600.038s  | 600.038s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   3.663s  |   3.663s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          |  10.639s  |  10.639s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   2.712s  |   2.712s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   0.664s  |   0.664s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |   7.083s  |   7.083s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |   2.866s  |   2.866s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |  34.662s  |  34.662s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |   7.493s  |   7.493s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |  10.828s  |  10.828s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   1.313s  |   1.313s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |   1.538s  |   1.538s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   2.868s  |   2.868s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |   2.601s  |   2.601s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   2.510s  |   2.510s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   3.119s  |   3.119s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   2.081s  |   2.081s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   2.694s  |   2.694s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  25.275s  |  25.275s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   2.074s  |   2.074s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       |   2.865s  |   2.865s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |   2.054s  |   2.054s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   1.661s  |   1.661s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       | 600.029s  | 600.029s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   1.280s  |   1.280s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       |   2.630s  |   2.630s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     | 600.039s  | 600.039s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   0.784s  |   0.784s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  19.110s  |  19.110s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |  10.757s  |  10.757s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   1.175s  |   1.175s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |   0.743s  |   0.743s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   1.642s  |   1.642s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   1.071s  |   1.071s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   1.025s  |   1.025s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |  25.329s  |  25.329s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        | 600.027s  | 600.027s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        | 600.028s  | 600.028s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |  16.342s  |  16.342s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  24.162s  |  24.162s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  | 600.037s  | 600.037s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  | 600.027s  | 600.027s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |   2.695s  |   2.695s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |   2.193s  |   2.193s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   0.961s  |   0.961s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           | 600.057s  | 600.057s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           | 429.628s  | 429.628s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   1.489s  |   1.489s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   2.030s  |   2.030s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   2.908s  |   2.908s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   2.237s  |   2.237s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           | 105.594s  | 105.594s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   1.531s  |   1.531s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           | 408.055s  | 408.055s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   0.546s  |   0.546s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   0.936s  |   0.936s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   2.637s  |   2.637s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   0.674s  |   0.674s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   1.678s  |   1.678s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   0.764s  |   0.764s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   1.291s  |   1.291s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |   2.800s  |   2.800s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   2.925s  |   2.925s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   2.681s  |   2.681s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           |  20.115s  |  20.115s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   1.351s  |   1.351s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           |   2.796s  |   2.796s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   2.121s  |   2.121s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   2.802s  |   2.802s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |   2.844s  |   2.844s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           |  41.318s  |  41.318s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   1.648s  |   1.648s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   1.308s  |   1.308s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   3.332s  |   3.332s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   1.584s  |   1.584s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   0.966s  |   0.966s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |   2.758s  |   2.758s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   1.470s  |   1.470s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   2.860s  |   2.860s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |  13.327s  |  13.327s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |   2.211s  |   2.211s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  23.223s  |  23.223s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   2.589s  |   2.589s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |   2.503s  |   2.503s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            | 558.666s  | 558.666s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |   2.999s  |   2.999s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   2.231s  |   2.231s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   1.171s  |   1.171s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  34.395s  |  34.395s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           | 121.553s  | 121.553s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   2.172s  |   2.172s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   2.311s  |   2.311s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  13.010s  |  13.010s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   1.625s  |   1.625s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   1.028s  |   1.028s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   0.754s  |   0.754s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   2.613s  |   2.613s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |   3.043s  |   3.043s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   2.910s  |   2.910s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   2.199s  |   2.199s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   2.329s  |   2.329s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   3.788s  |   3.788s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   2.864s  |   2.864s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           | 600.035s  | 600.035s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   2.744s  |   2.744s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   3.393s  |   3.393s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           |  71.533s  |  71.533s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   1.984s  |   1.984s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           | 600.028s  | 600.028s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   2.174s  |   2.174s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   1.228s  |   1.228s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   3.749s  |   3.749s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   1.455s  |   1.455s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   3.185s  |   3.185s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   1.084s  |   1.084s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           | 600.035s  | 600.035s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  15.139s  |  15.139s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   0.746s  |   0.746s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   0.851s  |   0.851s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   1.891s  |   1.891s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   1.386s  |   1.386s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   3.648s  |   3.648s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   3.237s  |   3.237s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |   2.721s  |   2.721s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |  14.160s  |  14.160s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.184s  |   1.184s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   1.749s  |   1.749s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   1.383s  |   1.383s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            | 600.055s  | 600.055s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            | 600.041s  | 600.041s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            | 600.042s  | 600.042s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            | 600.045s  | 600.045s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            | 600.045s  | 600.045s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            | 142.663s  | 142.663s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            | 600.047s  | 600.047s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.064s  |   0.064s  |   0.000s  | 0.0%|
</details>
