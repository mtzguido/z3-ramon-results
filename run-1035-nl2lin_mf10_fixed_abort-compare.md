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
Job description: nl2lin max_fail=10 alwais abort_on_fail on QF_NIA_small
Job tag: nl2lin_mf10_fixed_abort
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 9f4e1f57059b931bf2e9d27d3fbeefc43101dff2
Z3 branch: nl2lin
Z3 options: "-T:200 smt.random_seed=6 smt.arith.nl.nra_check_assignment_max_fail=10"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: abort nla check_assignment after a set number of allowed failures

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: nl2lin max_fail=10 alwais abort_on_fail on QF_NIA_small
Job tag: nl2lin_mf10_fixed_abort
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 9f4e1f57059b931bf2e9d27d3fbeefc43101dff2
Z3 branch: nl2lin
Z3 options: "-T:200 smt.random_seed=6 smt.arith.nl.nra_check_assignment_max_fail=10"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: abort nla check_assignment after a set number of allowed failures

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 200.040s  | 200.040s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 200.040s  | 200.040s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.750s  |   2.750s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.632s  |   1.632s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 200.053s  | 200.053s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 200.040s  | 200.040s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 200.040s  | 200.040s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.750s  |   2.750s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.632s  |   1.632s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 200.053s  | 200.053s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 200.040s  | 200.040s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 200.040s  | 200.040s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.750s  |   2.750s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.632s  |   1.632s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 200.053s  | 200.053s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 200.040s  | 200.040s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 200.040s  | 200.040s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.750s  |   2.750s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.632s  |   1.632s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 200.053s  | 200.053s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 200.400s |2072.0MiB|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                       | 200.358s |813.0MiB|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                         | 200.329s |629.0MiB|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                         | 200.316s |685.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 200.296s |2611.0MiB|
|185.smt2                                                                                   | 200.257s |1139.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 200.256s |1255.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                    | 200.256s |463.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 200.255s |929.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 200.255s |1761.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 200.248s |804.0MiB|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                               | 200.247s |337.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 200.239s |1900.0MiB|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                   | 200.236s |786.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 200.233s |729.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 200.233s |1148.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                        | 200.232s |551.0MiB|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                | 200.223s |386.0MiB|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                           | 200.216s |429.0MiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                   | 200.216s |208.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 200.400s |2072.0MiB|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                       | 200.358s |813.0MiB|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                         | 200.329s |629.0MiB|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                         | 200.316s |685.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 200.296s |2611.0MiB|
|185.smt2                                                                                   | 200.257s |1139.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 200.256s |1255.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                    | 200.256s |463.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 200.255s |929.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 200.255s |1761.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 200.248s |804.0MiB|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                               | 200.247s |337.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 200.239s |1900.0MiB|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                   | 200.236s |786.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 200.233s |729.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 200.233s |1148.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                        | 200.232s |551.0MiB|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                | 200.223s |386.0MiB|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                           | 200.216s |429.0MiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                   | 200.216s |208.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |83.456MiB|83.456MiB|0B| 0.0%|
|04.smt2                                                                                     |74.684MiB|74.684MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |27.268MiB|27.268MiB|0B| 0.0%|
|1010.smt2                                                                                   |27.224MiB|27.224MiB|0B| 0.0%|
|1018.smt2                                                                                   |24.096MiB|24.096MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.492MiB|24.492MiB|0B| 0.0%|
|1034.smt2                                                                                   |25.06MiB|25.06MiB|0B| 0.0%|
|1063.smt2                                                                                   |26.712MiB|26.712MiB|0B| 0.0%|
|107.smt2                                                                                    |22.332MiB|22.332MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.54MiB|27.54MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.112MiB|80.112MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.912MiB|22.912MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.948MiB|22.948MiB|0B| 0.0%|
|1092.smt2                                                                                   |28.712MiB|28.712MiB|0B| 0.0%|
|11.smt2                                                                                     |70.724MiB|70.724MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.228MiB|23.228MiB|0B| 0.0%|
|1112.smt2                                                                                   |28.4MiB|28.4MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.228MiB|23.228MiB|0B| 0.0%|
|1126.smt2                                                                                   |23.86MiB|23.86MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |83.456MiB|83.456MiB|0B| 0.0%|
|04.smt2                                                                                     |74.684MiB|74.684MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |27.268MiB|27.268MiB|0B| 0.0%|
|1010.smt2                                                                                   |27.224MiB|27.224MiB|0B| 0.0%|
|1018.smt2                                                                                   |24.096MiB|24.096MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.492MiB|24.492MiB|0B| 0.0%|
|1034.smt2                                                                                   |25.06MiB|25.06MiB|0B| 0.0%|
|1063.smt2                                                                                   |26.712MiB|26.712MiB|0B| 0.0%|
|107.smt2                                                                                    |22.332MiB|22.332MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.54MiB|27.54MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.112MiB|80.112MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.912MiB|22.912MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.948MiB|22.948MiB|0B| 0.0%|
|1092.smt2                                                                                   |28.712MiB|28.712MiB|0B| 0.0%|
|11.smt2                                                                                     |70.724MiB|70.724MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.228MiB|23.228MiB|0B| 0.0%|
|1112.smt2                                                                                   |28.4MiB|28.4MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.228MiB|23.228MiB|0B| 0.0%|
|1126.smt2                                                                                   |23.86MiB|23.86MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |83.456MiB|83.456MiB|0B| 0.0%|
|04.smt2                                                                                     |74.684MiB|74.684MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |27.268MiB|27.268MiB|0B| 0.0%|
|1010.smt2                                                                                   |27.224MiB|27.224MiB|0B| 0.0%|
|1018.smt2                                                                                   |24.096MiB|24.096MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.492MiB|24.492MiB|0B| 0.0%|
|1034.smt2                                                                                   |25.06MiB|25.06MiB|0B| 0.0%|
|1063.smt2                                                                                   |26.712MiB|26.712MiB|0B| 0.0%|
|107.smt2                                                                                    |22.332MiB|22.332MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.54MiB|27.54MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.112MiB|80.112MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.912MiB|22.912MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.948MiB|22.948MiB|0B| 0.0%|
|1092.smt2                                                                                   |28.712MiB|28.712MiB|0B| 0.0%|
|11.smt2                                                                                     |70.724MiB|70.724MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.228MiB|23.228MiB|0B| 0.0%|
|1112.smt2                                                                                   |28.4MiB|28.4MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.228MiB|23.228MiB|0B| 0.0%|
|1126.smt2                                                                                   |23.86MiB|23.86MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |83.456MiB|83.456MiB|0B| 0.0%|
|04.smt2                                                                                     |74.684MiB|74.684MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |27.268MiB|27.268MiB|0B| 0.0%|
|1010.smt2                                                                                   |27.224MiB|27.224MiB|0B| 0.0%|
|1018.smt2                                                                                   |24.096MiB|24.096MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.492MiB|24.492MiB|0B| 0.0%|
|1034.smt2                                                                                   |25.06MiB|25.06MiB|0B| 0.0%|
|1063.smt2                                                                                   |26.712MiB|26.712MiB|0B| 0.0%|
|107.smt2                                                                                    |22.332MiB|22.332MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.54MiB|27.54MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.112MiB|80.112MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.912MiB|22.912MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.948MiB|22.948MiB|0B| 0.0%|
|1092.smt2                                                                                   |28.712MiB|28.712MiB|0B| 0.0%|
|11.smt2                                                                                     |70.724MiB|70.724MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.228MiB|23.228MiB|0B| 0.0%|
|1112.smt2                                                                                   |28.4MiB|28.4MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.228MiB|23.228MiB|0B| 0.0%|
|1126.smt2                                                                                   |23.86MiB|23.86MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 200.296s |2611.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 200.400s |2072.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 200.239s |1900.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 200.255s |1761.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 200.194s |1356.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               | 200.213s |1284.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 200.256s |1255.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 200.233s |1148.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              | 200.174s |1141.0MiB|
|185.smt2                                                                                   | 200.257s |1139.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 200.166s |1108.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                         | 200.138s |1060.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                         | 200.194s |1040.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                         | 200.178s |1040.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 200.174s |1016.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 200.192s |999.0MiB|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                              | 200.189s |966.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 200.255s |929.0MiB|
|From_T2__select.t2__p21345_terminationG_0.smt2                                             | 160.671s |906.0MiB|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                             | 200.136s |900.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 200.296s |2611.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 200.400s |2072.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 200.239s |1900.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 200.255s |1761.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 200.194s |1356.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               | 200.213s |1284.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 200.256s |1255.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             | 200.233s |1148.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              | 200.174s |1141.0MiB|
|185.smt2                                                                                   | 200.257s |1139.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 200.166s |1108.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                         | 200.138s |1060.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                         | 200.194s |1040.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                         | 200.178s |1040.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                        | 200.174s |1016.0MiB|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                               | 200.192s |999.0MiB|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                              | 200.189s |966.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 200.255s |929.0MiB|
|From_T2__select.t2__p21345_terminationG_0.smt2                                             | 160.671s |906.0MiB|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                             | 200.136s |900.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 200.040s  | 200.040s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 200.040s  | 200.040s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   2.750s  |   2.750s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.632s  |   1.632s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 200.053s  | 200.053s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|124.smt2                                                                                    | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   1.099s  |   1.099s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   1.653s  |   1.653s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|140.smt2                                                                                    | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   1.542s  |   1.542s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.608s  |   0.608s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   1.841s  |   1.841s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   8.549s  |   8.549s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   4.470s  |   4.470s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   1.676s  |   1.676s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|177.smt2                                                                                    | 200.075s  | 200.075s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   0.808s  |   0.808s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   1.847s  |   1.847s  |   0.000s  | 0.0%|
|181.smt2                                                                                    | 200.100s  | 200.100s  |   0.000s  | 0.0%|
|182.smt2                                                                                    | 200.083s  | 200.083s  |   0.000s  | 0.0%|
|183.smt2                                                                                    | 200.145s  | 200.145s  |   0.000s  | 0.0%|
|185.smt2                                                                                    | 200.257s  | 200.257s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   1.232s  |   1.232s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   2.073s  |   2.073s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   1.236s  |   1.236s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   2.777s  |   2.777s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   4.485s  |   4.485s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   5.085s  |   5.085s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   2.071s  |   2.071s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   3.200s  |   3.200s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   1.049s  |   1.049s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   2.173s  |   2.173s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   2.365s  |   2.365s  |   0.000s  | 0.0%|
|35.smt2                                                                                     | 200.048s  | 200.048s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|40.smt2                                                                                     | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   1.810s  |   1.810s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   1.549s  |   1.549s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|54.smt2                                                                                     | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   2.400s  |   2.400s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   1.792s  |   1.792s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   2.968s  |   2.968s  |   0.000s  | 0.0%|
|58.smt2                                                                                     | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   1.847s  |   1.847s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   2.337s  |   2.337s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   3.872s  |   3.872s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|65.smt2                                                                                     | 200.069s  | 200.069s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   1.200s  |   1.200s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|73.smt2                                                                                     | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   3.113s  |   3.113s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   2.134s  |   2.134s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   1.151s  |   1.151s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   3.324s  |   3.324s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|966.smt2                                                                                    | 200.114s  | 200.114s  |   0.000s  | 0.0%|
|98.smt2                                                                                     | 200.035s  | 200.035s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|99.smt2                                                                                     | 200.040s  | 200.040s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |  13.758s  |  13.758s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   4.573s  |   4.573s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          |   4.155s  |   4.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |  12.229s  |  12.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |  14.394s  |  14.394s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          |  29.168s  |  29.168s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   2.023s  |   2.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   1.798s  |   1.798s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            | 200.159s  | 200.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   4.413s  |   4.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   4.275s  |   4.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       |  17.993s  |  17.993s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               | 200.052s  | 200.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  97.443s  |  97.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   3.062s  |   3.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |  10.221s  |  10.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |  11.180s  |  11.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   1.233s  |   1.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           |   3.918s  |   3.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           |  52.143s  |  52.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         | 166.961s  | 166.961s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   6.226s  |   6.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |   4.116s  |   4.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   2.780s  |   2.780s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |   9.744s  |   9.744s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         | 200.057s  | 200.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             | 200.206s  | 200.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |  10.537s  |  10.537s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  11.779s  |  11.779s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 |   5.937s  |   5.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   1.936s  |   1.936s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   4.283s  |   4.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   8.897s  |   8.897s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   3.102s  |   3.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              | 101.010s  | 101.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |   4.499s  |   4.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   1.333s  |   1.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |   6.606s  |   6.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               | 200.074s  | 200.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         | 200.120s  | 200.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   9.515s  |   9.515s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |   2.841s  |   2.841s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       | 200.118s  | 200.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 |  21.400s  |  21.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      |   6.117s  |   6.117s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   2.006s  |   2.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   5.910s  |   5.910s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              |  85.485s  |  85.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   2.654s  |   2.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   5.062s  |   5.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   1.491s  |   1.491s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          |  28.917s  |  28.917s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   3.288s  |   3.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         | 200.074s  | 200.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   3.275s  |   3.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      | 200.122s  | 200.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |   2.833s  |   2.833s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   3.937s  |   3.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   5.215s  |   5.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      | 200.030s  | 200.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               | 200.102s  | 200.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  12.507s  |  12.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |  22.677s  |  22.677s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   6.627s  |   6.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               | 200.034s  | 200.034s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   3.476s  |   3.476s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               |  15.681s  |  15.681s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |   3.106s  |   3.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   3.879s  |   3.879s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |   3.320s  |   3.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            | 200.154s  | 200.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   6.955s  |   6.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   | 200.048s  | 200.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   | 200.152s  | 200.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             | 200.137s  | 200.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |   2.245s  |   2.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   1.616s  |   1.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    | 200.186s  | 200.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |  13.009s  |  13.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        | 200.051s  | 200.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  43.265s  |  43.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  34.371s  |  34.371s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     | 200.046s  | 200.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               |  48.068s  |  48.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   4.399s  |   4.399s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   5.213s  |   5.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   3.069s  |   3.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |   6.225s  |   6.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               |   3.734s  |   3.734s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   0.982s  |   0.982s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   5.841s  |   5.841s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   3.230s  |   3.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   6.793s  |   6.793s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   2.919s  |   2.919s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   5.683s  |   5.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                | 200.247s  | 200.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   0.940s  |   0.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              | 169.888s  | 169.888s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |  22.382s  |  22.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   1.566s  |   1.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   9.094s  |   9.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  13.283s  |  13.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  31.653s  |  31.653s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   7.784s  |   7.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  63.571s  |  63.571s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          | 200.103s  | 200.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          | 200.139s  | 200.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |   9.019s  |   9.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          | 200.165s  | 200.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          | 200.082s  | 200.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |   4.311s  |   4.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   2.417s  |   2.417s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  13.084s  |  13.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   4.273s  |   4.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   3.243s  |   3.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   2.213s  |   2.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    | 200.113s  | 200.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   2.086s  |   2.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   3.158s  |   3.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        | 200.198s  | 200.198s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |   4.693s  |   4.693s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |   5.720s  |   5.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   3.545s  |   3.545s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        | 200.039s  | 200.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   0.984s  |   0.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  80.681s  |  80.681s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  41.975s  |  41.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  41.649s  |  41.649s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  25.808s  |  25.808s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  57.505s  |  57.505s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  45.639s  |  45.639s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  |  97.049s  |  97.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  |  51.075s  |  51.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |   5.413s  |   5.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |  91.913s  |  91.913s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   3.500s  |   3.500s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              | 200.046s  | 200.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   1.894s  |   1.894s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             | 200.053s  | 200.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |   5.074s  |   5.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   2.013s  |   2.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  13.464s  |  13.464s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        | 200.055s  | 200.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   3.232s  |   3.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |   9.682s  |   9.682s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |   4.531s  |   4.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     |  18.154s  |  18.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   3.578s  |   3.578s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   2.767s  |   2.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   1.547s  |   1.547s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     | 200.114s  | 200.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 | 200.069s  | 200.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                | 200.177s  | 200.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                |   6.048s  |   6.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      | 200.072s  | 200.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   2.467s  |   2.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |  14.946s  |  14.946s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      |   3.713s  |   3.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |   2.573s  |   2.573s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   0.798s  |   0.798s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   2.109s  |   2.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   4.426s  |   4.426s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   2.693s  |   2.693s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |  11.084s  |  11.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   4.111s  |   4.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |   3.828s  |   3.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |   1.826s  |   1.826s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   6.094s  |   6.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          | 200.077s  | 200.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               |   7.184s  |   7.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                | 114.924s  | 114.924s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   6.338s  |   6.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |   3.940s  |   3.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   2.030s  |   2.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   5.690s  |   5.690s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   2.121s  |   2.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   5.276s  |   5.276s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   0.728s  |   0.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              | 200.043s  | 200.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   2.279s  |   2.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   4.753s  |   4.753s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   8.906s  |   8.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   3.260s  |   3.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  15.745s  |  15.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          | 200.132s  | 200.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |   5.229s  |   5.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          | 200.096s  | 200.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          | 200.129s  | 200.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |  11.836s  |  11.836s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          | 200.094s  | 200.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          | 200.069s  | 200.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |  13.002s  |  13.002s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   9.014s  |   9.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            | 200.056s  | 200.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   4.896s  |   4.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |   3.151s  |   3.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |   4.226s  |   4.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |  57.481s  |  57.481s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |   5.323s  |   5.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |  10.191s  |  10.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |   2.274s  |   2.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   2.833s  |   2.833s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |  23.729s  |  23.729s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           | 200.117s  | 200.117s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |   8.411s  |   8.411s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   2.791s  |   2.791s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   0.462s  |   0.462s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           | 200.103s  | 200.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   2.601s  |   2.601s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   1.937s  |   1.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |  17.159s  |  17.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           | 200.075s  | 200.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   1.965s  |   1.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   2.218s  |   2.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |   2.161s  |   2.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           | 200.074s  | 200.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |  24.047s  |  24.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   2.291s  |   2.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |   3.075s  |   3.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   2.200s  |   2.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  14.261s  |  14.261s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   1.865s  |   1.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   0.850s  |   0.850s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |  55.157s  |  55.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.634s  |   0.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           | 200.046s  | 200.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           | 200.035s  | 200.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           | 200.074s  | 200.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   2.251s  |   2.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     | 200.256s  | 200.256s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |   1.137s  |   1.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |  24.841s  |  24.841s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |  14.260s  |  14.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   2.141s  |   2.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   7.255s  |   7.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     | 200.052s  | 200.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |  24.630s  |  24.630s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |   1.927s  |   1.927s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   1.879s  |   1.879s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   2.172s  |   2.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   1.985s  |   1.985s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   1.472s  |   1.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   1.478s  |   1.478s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   1.369s  |   1.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   3.395s  |   3.395s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   0.652s  |   0.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     | 200.068s  | 200.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |  23.637s  |  23.637s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   2.112s  |   2.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     | 200.061s  | 200.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               |  80.222s  |  80.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   2.569s  |   2.569s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     | 200.084s  | 200.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |  21.655s  |  21.655s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |  15.357s  |  15.357s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   2.260s  |   2.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   5.751s  |   5.751s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |  11.892s  |  11.892s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   0.872s  |   0.872s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   2.179s  |   2.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |   8.484s  |   8.484s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   7.121s  |   7.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |  51.045s  |  51.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     |  14.786s  |  14.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  10.715s  |  10.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |  38.871s  |  38.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   2.151s  |   2.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   1.113s  |   1.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               | 200.102s  | 200.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               | 200.052s  | 200.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |   9.404s  |   9.404s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |   3.600s  |   3.600s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               | 200.085s  | 200.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               | 114.661s  | 114.661s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               | 200.076s  | 200.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               | 200.100s  | 200.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               | 200.070s  | 200.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |  12.250s  |  12.250s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   1.329s  |   1.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   2.250s  |   2.250s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  32.509s  |  32.509s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               |   2.219s  |   2.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   0.751s  |   0.751s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               | 200.038s  | 200.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   1.154s  |   1.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   2.384s  |   2.384s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |   5.660s  |   5.660s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |   5.336s  |   5.336s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   9.532s  |   9.532s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   1.871s  |   1.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   2.720s  |   2.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   0.991s  |   0.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   2.761s  |   2.761s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   5.332s  |   5.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               | 200.096s  | 200.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               | 200.114s  | 200.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   2.512s  |   2.512s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |   4.403s  |   4.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |  75.047s  |  75.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |  14.945s  |  14.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   2.731s  |   2.731s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |  69.052s  |  69.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |   0.619s  |   0.619s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |   6.755s  |   6.755s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   2.800s  |   2.800s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             | 200.074s  | 200.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |  15.843s  |  15.843s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   2.764s  |   2.764s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   1.655s  |   1.655s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   2.241s  |   2.241s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   1.713s  |   1.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |   1.285s  |   1.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   9.267s  |   9.267s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |   2.149s  |   2.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   0.947s  |   0.947s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             | 200.078s  | 200.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |  18.238s  |  18.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |   3.715s  |   3.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   1.553s  |   1.553s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             | 200.056s  | 200.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   2.662s  |   2.662s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             | 200.083s  | 200.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |   6.095s  |   6.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |   2.164s  |   2.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             | 200.045s  | 200.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |   6.577s  |   6.577s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |   1.363s  |   1.363s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             | 200.092s  | 200.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |  10.882s  |  10.882s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   1.396s  |   1.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             | 200.083s  | 200.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             | 200.053s  | 200.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   8.007s  |   8.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             | 200.171s  | 200.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |   3.214s  |   3.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |   2.139s  |   2.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               |   8.200s  |   8.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |   1.665s  |   1.665s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         | 128.090s  | 128.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   5.570s  |   5.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              |   2.333s  |   2.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   2.213s  |   2.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |  39.431s  |  39.431s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   1.525s  |   1.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    | 200.057s  | 200.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |   1.293s  |   1.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              | 200.085s  | 200.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   2.196s  |   2.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   2.794s  |   2.794s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   0.865s  |   0.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |  23.090s  |  23.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    | 200.100s  | 200.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   2.269s  |   2.269s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    | 200.216s  | 200.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   2.915s  |   2.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    | 200.069s  | 200.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   1.572s  |   1.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   1.082s  |   1.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |   1.087s  |   1.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   6.639s  |   6.639s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    | 200.048s  | 200.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |   7.289s  |   7.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    |   2.149s  |   2.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   0.771s  |   0.771s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |   8.290s  |   8.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  84.300s  |  84.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |   6.134s  |   6.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   1.365s  |   1.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    | 200.070s  | 200.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |  50.989s  |  50.989s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |  16.435s  |  16.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   2.275s  |   2.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    | 200.082s  | 200.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   3.456s  |   3.456s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    | 200.046s  | 200.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |   0.603s  |   0.603s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    | 200.061s  | 200.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   1.445s  |   1.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |  21.087s  |  21.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |   5.635s  |   5.635s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   1.549s  |   1.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |  17.622s  |  17.622s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   2.548s  |   2.548s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          | 200.214s  | 200.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   1.773s  |   1.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          | 200.078s  | 200.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   2.242s  |   2.242s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  11.839s  |  11.839s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |   7.501s  |   7.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          | 200.084s  | 200.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |  51.550s  |  51.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          | 200.069s  | 200.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          | 200.050s  | 200.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |   6.460s  |   6.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   1.852s  |   1.852s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   1.763s  |   1.763s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          | 200.084s  | 200.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          | 200.095s  | 200.095s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   6.468s  |   6.468s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   1.156s  |   1.156s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |  21.316s  |  21.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        | 200.064s  | 200.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   2.195s  |   2.195s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |  48.143s  |  48.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |  39.101s  |  39.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |  13.219s  |  13.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |   1.811s  |   1.811s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |   0.721s  |   0.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |   8.154s  |   8.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |   3.195s  |   3.195s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |   2.151s  |   2.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |  11.333s  |  11.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        | 149.058s  | 149.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   1.063s  |   1.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |  14.108s  |  14.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   2.474s  |   2.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   3.384s  |   3.384s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |   4.607s  |   4.607s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   1.000s  |   1.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   2.235s  |   2.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        | 200.112s  | 200.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   2.180s  |   2.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |   2.249s  |   2.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |  11.125s  |  11.125s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   2.326s  |   2.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |   1.946s  |   1.946s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   2.365s  |   2.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        | 200.110s  | 200.110s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        | 200.034s  | 200.034s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        | 200.085s  | 200.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |  34.166s  |  34.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   2.102s  |   2.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   1.494s  |   1.494s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |  28.245s  |  28.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |   2.163s  |   2.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   1.407s  |   1.407s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        | 200.055s  | 200.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   9.379s  |   9.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  | 200.111s  | 200.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   2.178s  |   2.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   6.535s  |   6.535s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   1.818s  |   1.818s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |  10.160s  |  10.160s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |   8.079s  |   8.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   2.305s  |   2.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   0.784s  |   0.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     | 200.064s  | 200.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  25.680s  |  25.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   2.196s  |   2.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |  10.976s  |  10.976s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   2.152s  |   2.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   5.401s  |   5.401s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     | 200.080s  | 200.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     | 200.049s  | 200.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |  10.298s  |  10.298s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |   2.988s  |   2.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       |   2.258s  |   2.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |   1.887s  |   1.887s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |  17.187s  |  17.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   2.167s  |   2.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |   8.299s  |   8.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |   7.316s  |   7.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       |   2.182s  |   2.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   0.901s  |   0.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |   1.350s  |   1.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       | 200.057s  | 200.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   1.445s  |   1.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   1.020s  |   1.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   2.129s  |   2.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   2.173s  |   2.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   2.295s  |   2.295s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       | 200.044s  | 200.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |  34.024s  |  34.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   1.681s  |   1.681s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   0.939s  |   0.939s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       | 200.043s  | 200.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       | 200.049s  | 200.049s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |  16.680s  |  16.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 | 200.133s  | 200.133s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  45.698s  |  45.698s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |   8.854s  |   8.854s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  23.713s  |  23.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   2.210s  |   2.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |   3.958s  |   3.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  17.022s  |  17.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   2.130s  |   2.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  14.182s  |  14.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  45.714s  |  45.714s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   2.479s  |   2.479s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |  76.039s  |  76.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   1.585s  |   1.585s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |   4.292s  |   4.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            |   3.752s  |   3.752s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   1.994s  |   1.994s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   7.566s  |   7.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   7.897s  |   7.897s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   3.864s  |   3.864s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   2.912s  |   2.912s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   5.330s  |   5.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   2.958s  |   2.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |  15.201s  |  15.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |  49.009s  |  49.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   5.465s  |   5.465s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   1.936s  |   1.936s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   2.555s  |   2.555s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |  10.122s  |  10.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   3.652s  |   3.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   4.618s  |   4.618s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   8.621s  |   8.621s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   3.938s  |   3.938s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |  11.652s  |  11.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |   2.828s  |   2.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |  54.961s  |  54.961s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   9.320s  |   9.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |  29.208s  |  29.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   3.415s  |   3.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   8.217s  |   8.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   4.618s  |   4.618s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  25.465s  |  25.465s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   9.383s  |   9.383s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  11.074s  |  11.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |   3.157s  |   3.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   2.738s  |   2.738s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   2.022s  |   2.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  25.447s  |  25.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   5.155s  |   5.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   2.051s  |   2.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   4.866s  |   4.866s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |  27.412s  |  27.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   4.941s  |   4.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   2.190s  |   2.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   2.201s  |   2.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   3.469s  |   3.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   7.490s  |   7.490s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   2.967s  |   2.967s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   1.874s  |   1.874s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   7.700s  |   7.700s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   3.533s  |   3.533s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   3.661s  |   3.661s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   4.266s  |   4.266s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |  14.254s  |  14.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |  12.616s  |  12.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   3.776s  |   3.776s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   4.455s  |   4.455s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   2.344s  |   2.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   2.082s  |   2.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  23.786s  |  23.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   2.300s  |   2.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   2.011s  |   2.011s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  19.337s  |  19.337s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   1.299s  |   1.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |  15.219s  |  15.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   2.516s  |   2.516s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |  14.887s  |  14.887s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |  22.403s  |  22.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  10.055s  |  10.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |  10.014s  |  10.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   1.713s  |   1.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   4.043s  |   4.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  21.608s  |  21.608s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   3.156s  |   3.156s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   2.769s  |   2.769s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   5.146s  |   5.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   1.964s  |   1.964s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |  11.265s  |  11.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   9.750s  |   9.750s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   7.210s  |   7.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   4.003s  |   4.003s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  11.929s  |  11.929s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |   1.674s  |   1.674s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   9.865s  |   9.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   3.483s  |   3.483s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   2.902s  |   2.902s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   1.692s  |   1.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   2.086s  |   2.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                | 157.525s  | 157.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |   7.812s  |   7.812s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  10.935s  |  10.935s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   2.561s  |   2.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |  28.760s  |  28.760s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  20.508s  |  20.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   4.499s  |   4.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   1.474s  |   1.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   2.078s  |   2.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   3.188s  |   3.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   3.195s  |   3.195s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   1.941s  |   1.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  21.512s  |  21.512s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   3.112s  |   3.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |   9.502s  |   9.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   2.581s  |   2.581s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   1.784s  |   1.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   3.127s  |   3.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   2.904s  |   2.904s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |   3.941s  |   3.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   1.302s  |   1.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |   2.779s  |   2.779s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   1.230s  |   1.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   3.075s  |   3.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   2.615s  |   2.615s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   3.150s  |   3.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |  41.143s  |  41.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   3.846s  |   3.846s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   2.528s  |   2.528s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |  25.078s  |  25.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |  10.568s  |  10.568s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   1.374s  |   1.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |   9.914s  |   9.914s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |  12.449s  |  12.449s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   2.692s  |   2.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   3.213s  |   3.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   7.043s  |   7.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          |  61.270s  |  61.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          |  53.001s  |  53.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          | 101.186s  | 101.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   3.325s  |   3.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   4.673s  |   4.673s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             | 200.175s  | 200.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            | 200.172s  | 200.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            | 120.199s  | 120.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   2.964s  |   2.964s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   3.353s  |   3.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   7.223s  |   7.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   3.165s  |   3.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |  75.849s  |  75.849s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   3.037s  |   3.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       | 200.057s  | 200.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   4.332s  |   4.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      | 200.058s  | 200.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   5.902s  |   5.902s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   4.374s  |   4.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   1.332s  |   1.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   5.552s  |   5.552s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   4.977s  |   4.977s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   4.026s  |   4.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   1.122s  |   1.122s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   1.965s  |   1.965s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   2.583s  |   2.583s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |   8.888s  |   8.888s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |  47.794s  |  47.794s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |  84.532s  |  84.532s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |   3.389s  |   3.389s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |  30.975s  |  30.975s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   3.874s  |   3.874s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   1.690s  |   1.690s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          | 170.637s  | 170.637s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          | 200.068s  | 200.068s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   2.819s  |   2.819s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   1.278s  |   1.278s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               | 200.114s  | 200.114s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               | 200.104s  | 200.104s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  23.956s  |  23.956s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               | 200.073s  | 200.073s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   2.809s  |   2.809s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         | 200.078s  | 200.078s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         | 200.103s  | 200.103s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         |  53.753s  |  53.753s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               | 200.175s  | 200.175s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               | 200.176s  | 200.176s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  15.991s  |  15.991s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   9.554s  |   9.554s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |   8.079s  |   8.079s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         | 200.128s  | 200.128s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |   8.127s  |   8.127s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.981s  |   0.981s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         | 200.176s  | 200.176s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  33.068s  |  33.068s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  24.698s  |  24.698s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    | 200.194s  | 200.194s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  97.831s  |  97.831s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    | 200.236s  | 200.236s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  23.347s  |  23.347s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  10.945s  |  10.945s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   4.050s  |   4.050s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              | 200.233s  | 200.233s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  53.942s  |  53.942s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   5.900s  |   5.900s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   5.816s  |   5.816s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  26.759s  |  26.759s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.752s  |   0.752s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |  13.330s  |  13.330s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |   2.539s  |   2.539s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   5.134s  |   5.134s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   1.143s  |   1.143s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |   4.432s  |   4.432s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   7.733s  |   7.733s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  | 200.154s  | 200.154s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   2.698s  |   2.698s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  28.365s  |  28.365s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 | 200.210s  | 200.210s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 | 200.128s  | 200.128s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  12.942s  |  12.942s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           | 200.172s  | 200.172s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |   4.913s  |   4.913s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              | 200.045s  | 200.045s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   3.641s  |   3.641s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              | 200.110s  | 200.110s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              |   4.212s  |   4.212s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  12.671s  |  12.671s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              | 200.070s  | 200.070s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              | 200.070s  | 200.070s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |  98.888s  |  98.888s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              | 200.049s  | 200.049s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   3.821s  |   3.821s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |   8.714s  |   8.714s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  18.161s  |  18.161s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |   8.115s  |   8.115s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |  61.506s  |  61.506s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  44.443s  |  44.443s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  33.296s  |  33.296s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  18.027s  |  18.027s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  80.355s  |  80.355s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            | 119.559s  | 119.559s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   4.961s  |   4.961s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             | 200.042s  | 200.042s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   5.409s  |   5.409s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             | 200.078s  | 200.078s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             | 200.128s  | 200.128s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   1.996s  |   1.996s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             |   4.692s  |   4.692s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             | 200.145s  | 200.145s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   2.811s  |   2.811s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 | 200.058s  | 200.058s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  | 200.075s  | 200.075s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |   4.463s  |   4.463s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   4.703s  |   4.703s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   3.891s  |   3.891s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   4.685s  |   4.685s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |   1.459s  |   1.459s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   3.519s  |   3.519s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |   4.710s  |   4.710s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   2.531s  |   2.531s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   3.577s  |   3.577s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   4.901s  |   4.901s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   3.506s  |   3.506s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   1.430s  |   1.430s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   1.328s  |   1.328s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |   5.479s  |   5.479s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   1.971s  |   1.971s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   3.947s  |   3.947s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               | 200.400s  | 200.400s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   1.205s  |   1.205s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            | 200.116s  | 200.116s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   1.632s  |   1.632s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 | 200.158s  | 200.158s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |   5.551s  |   5.551s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  25.438s  |  25.438s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |   3.469s  |   3.469s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           | 200.112s  | 200.112s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |  12.020s  |  12.020s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |  10.016s  |  10.016s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 | 197.595s  | 197.595s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      | 200.140s  | 200.140s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |  12.279s  |  12.279s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |  13.884s  |  13.884s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           | 200.068s  | 200.068s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  45.356s  |  45.356s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |   4.126s  |   4.126s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  25.629s  |  25.629s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              | 200.038s  | 200.038s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |   5.334s  |   5.334s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   2.016s  |   2.016s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   5.217s  |   5.217s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      | 200.137s  | 200.137s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               | 200.048s  | 200.048s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              |   4.443s  |   4.443s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   2.836s  |   2.836s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       | 200.048s  | 200.048s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |  22.335s  |  22.335s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   1.093s  |   1.093s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       | 200.092s  | 200.092s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |  17.931s  |  17.931s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.748s  |   0.748s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   2.059s  |   2.059s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   4.546s  |   4.546s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |  20.715s  |  20.715s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |   8.141s  |   8.141s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       | 200.082s  | 200.082s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   6.644s  |   6.644s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |  10.525s  |  10.525s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       |  22.041s  |  22.041s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |   4.128s  |   4.128s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   1.460s  |   1.460s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   4.221s  |   4.221s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       | 200.088s  | 200.088s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   8.954s  |   8.954s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       | 200.086s  | 200.086s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   6.534s  |   6.534s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   0.783s  |   0.783s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               | 200.076s  | 200.076s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         | 200.194s  | 200.194s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   2.987s  |   2.987s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   2.265s  |   2.265s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 | 200.037s  | 200.037s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   0.731s  |   0.731s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |   8.591s  |   8.591s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |   3.651s  |   3.651s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |  10.009s  |  10.009s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   2.477s  |   2.477s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   4.428s  |   4.428s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                | 200.117s  | 200.117s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   1.217s  |   1.217s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   3.098s  |   3.098s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                | 200.147s  | 200.147s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   1.772s  |   1.772s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   4.031s  |   4.031s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      | 200.053s  | 200.053s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   3.793s  |   3.793s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   1.827s  |   1.827s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |   3.746s  |   3.746s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   4.560s  |   4.560s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   2.184s  |   2.184s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   1.490s  |   1.490s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   3.310s  |   3.310s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   1.155s  |   1.155s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   6.705s  |   6.705s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   3.476s  |   3.476s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   2.890s  |   2.890s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   1.053s  |   1.053s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |   3.983s  |   3.983s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |  41.366s  |  41.366s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      | 200.072s  | 200.072s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   1.962s  |   1.962s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      | 200.036s  | 200.036s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   2.579s  |   2.579s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   3.556s  |   3.556s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   3.461s  |   3.461s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   1.946s  |   1.946s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   2.940s  |   2.940s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   2.684s  |   2.684s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   3.590s  |   3.590s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |  29.445s  |  29.445s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   2.897s  |   2.897s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   1.955s  |   1.955s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |   3.773s  |   3.773s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   2.685s  |   2.685s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      | 200.108s  | 200.108s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   1.684s  |   1.684s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   5.308s  |   5.308s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   4.097s  |   4.097s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   8.044s  |   8.044s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   4.449s  |   4.449s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   4.614s  |   4.614s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |   3.603s  |   3.603s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   2.363s  |   2.363s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   2.749s  |   2.749s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   1.539s  |   1.539s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      | 200.074s  | 200.074s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   1.228s  |   1.228s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   3.243s  |   3.243s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   4.868s  |   4.868s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      | 200.057s  | 200.057s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   1.347s  |   1.347s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      | 200.080s  | 200.080s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   6.400s  |   6.400s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   2.113s  |   2.113s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |   4.235s  |   4.235s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |   3.879s  |   3.879s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   2.158s  |   2.158s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.718s  |   0.718s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   4.071s  |   4.071s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   2.056s  |   2.056s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   4.376s  |   4.376s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   3.788s  |   3.788s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   2.722s  |   2.722s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   4.602s  |   4.602s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   3.991s  |   3.991s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   4.088s  |   4.088s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   2.133s  |   2.133s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   2.227s  |   2.227s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   2.484s  |   2.484s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |  11.342s  |  11.342s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   6.320s  |   6.320s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   3.391s  |   3.391s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   7.590s  |   7.590s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   1.824s  |   1.824s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   4.952s  |   4.952s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   6.611s  |   6.611s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   6.425s  |   6.425s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   7.301s  |   7.301s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |   9.476s  |   9.476s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            | 200.143s  | 200.143s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |  18.613s  |  18.613s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  41.229s  |  41.229s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |  15.087s  |  15.087s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  26.413s  |  26.413s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |   9.887s  |   9.887s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        | 200.201s  | 200.201s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        |   3.623s  |   3.623s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  26.755s  |  26.755s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |  27.042s  |  27.042s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   3.454s  |   3.454s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     |  66.167s  |  66.167s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     | 200.203s  | 200.203s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     | 200.159s  | 200.159s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |  12.276s  |  12.276s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         | 200.174s  | 200.174s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               | 200.038s  | 200.038s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         | 200.232s  | 200.232s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               | 200.167s  | 200.167s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   1.142s  |   1.142s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |   4.554s  |   4.554s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               | 200.149s  | 200.149s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  | 200.144s  | 200.144s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |  41.663s  |  41.663s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     | 107.617s  | 107.617s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  48.695s  |  48.695s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  32.398s  |  32.398s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            | 200.099s  | 200.099s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            | 200.119s  | 200.119s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   3.622s  |   3.622s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   1.278s  |   1.278s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                | 200.069s  | 200.069s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   4.364s  |   4.364s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  47.439s  |  47.439s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 | 200.096s  | 200.096s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 | 200.138s  | 200.138s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  45.950s  |  45.950s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 | 200.223s  | 200.223s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |   3.671s  |   3.671s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |   2.066s  |   2.066s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           | 200.124s  | 200.124s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           | 200.102s  | 200.102s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           | 175.834s  | 175.834s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |  10.952s  |  10.952s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  17.608s  |  17.608s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |  14.855s  |  14.855s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   3.329s  |   3.329s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  26.483s  |  26.483s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 | 200.138s  | 200.138s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  16.920s  |  16.920s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 | 200.124s  | 200.124s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   4.189s  |   4.189s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 |  38.603s  |  38.603s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 | 200.133s  | 200.133s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |  15.956s  |  15.956s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  18.314s  |  18.314s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 | 200.119s  | 200.119s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   7.153s  |   7.153s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 |  50.600s  |  50.600s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |   8.867s  |   8.867s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 | 200.193s  | 200.193s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |  45.208s  |  45.208s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   7.819s  |   7.819s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   9.261s  |   9.261s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 | 200.085s  | 200.085s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  28.205s  |  28.205s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |  10.318s  |  10.318s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 | 200.069s  | 200.069s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 | 164.547s  | 164.547s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   4.844s  |   4.844s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |  77.551s  |  77.551s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 |  86.779s  |  86.779s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   4.010s  |   4.010s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |  34.724s  |  34.724s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   5.545s  |   5.545s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 | 103.921s  | 103.921s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |  17.938s  |  17.938s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |   9.552s  |   9.552s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   3.136s  |   3.136s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   3.147s  |   3.147s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              | 200.073s  | 200.073s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  19.471s  |  19.471s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 | 123.875s  | 123.875s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  65.399s  |  65.399s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 | 134.286s  | 134.286s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  20.759s  |  20.759s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        | 200.100s  | 200.100s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  32.883s  |  32.883s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  28.558s  |  28.558s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |  46.397s  |  46.397s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           | 136.304s  | 136.304s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    | 200.090s  | 200.090s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       |  18.927s  |  18.927s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       |  65.891s  |  65.891s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  52.858s  |  52.858s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  36.604s  |  36.604s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |  13.235s  |  13.235s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              | 200.115s  | 200.115s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 | 158.398s  | 158.398s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  15.748s  |  15.748s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  86.809s  |  86.809s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  35.584s  |  35.584s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  44.541s  |  44.541s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  |  84.103s  |  84.103s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  69.972s  |  69.972s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  31.842s  |  31.842s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   5.657s  |   5.657s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  43.626s  |  43.626s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |  32.254s  |  32.254s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  24.554s  |  24.554s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            | 200.119s  | 200.119s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          | 171.220s  | 171.220s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  30.631s  |  30.631s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  37.393s  |  37.393s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  56.084s  |  56.084s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  66.208s  |  66.208s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   3.031s  |   3.031s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   6.926s  |   6.926s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        | 110.442s  | 110.442s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        | 200.358s  | 200.358s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |  31.744s  |  31.744s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        | 200.096s  | 200.096s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        |   4.155s  |   4.155s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        |  51.764s  |  51.764s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        | 200.088s  | 200.088s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        | 200.052s  | 200.052s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        |  47.153s  |  47.153s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  | 200.073s  | 200.073s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   1.895s  |   1.895s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     | 200.078s  | 200.078s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.664s  |   0.664s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   2.324s  |   2.324s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   9.602s  |   9.602s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  84.152s  |  84.152s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 | 200.064s  | 200.064s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   2.514s  |   2.514s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 | 200.090s  | 200.090s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 | 200.095s  | 200.095s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |   3.546s  |   3.546s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 | 200.052s  | 200.052s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 | 200.104s  | 200.104s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |   3.856s  |   3.856s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   6.267s  |   6.267s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   3.640s  |   3.640s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   5.006s  |   5.006s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |   2.795s  |   2.795s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             |  79.819s  |  79.819s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             |   3.901s  |   3.901s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   8.585s  |   8.585s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             |  99.193s  |  99.193s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             | 171.594s  | 171.594s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   3.317s  |   3.317s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |  85.648s  |  85.648s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             | 200.150s  | 200.150s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |   3.537s  |   3.537s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             | 128.724s  | 128.724s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             | 200.148s  | 200.148s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   2.163s  |   2.163s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             | 200.147s  | 200.147s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             | 200.197s  | 200.197s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   7.906s  |   7.906s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   4.278s  |   4.278s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  |  87.321s  |  87.321s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   6.654s  |   6.654s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                | 200.036s  | 200.036s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  14.166s  |  14.166s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           | 200.061s  | 200.061s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   2.533s  |   2.533s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 |   4.938s  |   4.938s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   1.579s  |   1.579s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 | 200.099s  | 200.099s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 | 200.068s  | 200.068s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   2.813s  |   2.813s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           | 200.049s  | 200.049s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   5.335s  |   5.335s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 | 200.077s  | 200.077s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 | 200.058s  | 200.058s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           | 200.046s  | 200.046s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  |   3.462s  |   3.462s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |   2.580s  |   2.580s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 |   3.380s  |   3.380s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 | 200.150s  | 200.150s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   1.533s  |   1.533s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   3.602s  |   3.602s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |   5.513s  |   5.513s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 | 200.035s  | 200.035s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   3.023s  |   3.023s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 |  70.777s  |  70.777s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   1.604s  |   1.604s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 |  57.957s  |  57.957s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   5.006s  |   5.006s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   5.912s  |   5.912s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   1.302s  |   1.302s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |   6.574s  |   6.574s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  28.402s  |  28.402s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   3.153s  |   3.153s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  |   4.145s  |   4.145s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   1.834s  |   1.834s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  |  15.713s  |  15.713s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  | 200.083s  | 200.083s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            |   3.879s  |   3.879s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   2.186s  |   2.186s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |  15.376s  |  15.376s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  | 200.056s  | 200.056s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   3.784s  |   3.784s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  |   3.312s  |   3.312s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   1.988s  |   1.988s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  | 200.069s  | 200.069s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   2.115s  |   2.115s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  | 200.049s  | 200.049s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  | 200.047s  | 200.047s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   1.040s  |   1.040s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |   4.805s  |   4.805s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            | 200.051s  | 200.051s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   3.725s  |   3.725s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |  11.977s  |  11.977s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   1.483s  |   1.483s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |   2.680s  |   2.680s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           | 200.159s  | 200.159s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           | 200.125s  | 200.125s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |   4.281s  |   4.281s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               |  23.741s  |  23.741s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               | 200.189s  | 200.189s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               | 125.020s  | 125.020s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               | 200.185s  | 200.185s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               | 200.163s  | 200.163s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |   8.504s  |   8.504s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |   3.314s  |   3.314s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  24.242s  |  24.242s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |   7.114s  |   7.114s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   4.254s  |   4.254s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   1.229s  |   1.229s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             | 200.070s  | 200.070s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |   3.454s  |   3.454s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   4.542s  |   4.542s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |  10.977s  |  10.977s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |   2.308s  |   2.308s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   3.095s  |   3.095s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   4.626s  |   4.626s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  13.887s  |  13.887s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  26.327s  |  26.327s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            | 200.048s  | 200.048s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    | 200.133s  | 200.133s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   7.368s  |   7.368s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               | 200.116s  | 200.116s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             | 200.097s  | 200.097s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             | 200.084s  | 200.084s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             | 200.058s  | 200.058s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   4.875s  |   4.875s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             |   5.689s  |   5.689s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   6.402s  |   6.402s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  15.785s  |  15.785s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |   9.005s  |   9.005s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               | 200.174s  | 200.174s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         | 200.166s  | 200.166s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  13.454s  |  13.454s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  12.818s  |  12.818s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  12.545s  |  12.545s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  19.384s  |  19.384s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  19.657s  |  19.657s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        | 200.233s  | 200.233s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            | 200.044s  | 200.044s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            | 200.045s  | 200.045s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   3.190s  |   3.190s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |   5.428s  |   5.428s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   2.508s  |   2.508s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            | 200.061s  | 200.061s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   2.453s  |   2.453s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  12.343s  |  12.343s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              | 200.057s  | 200.057s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  12.643s  |  12.643s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  10.892s  |  10.892s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          | 200.053s  | 200.053s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   2.925s  |   2.925s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |   4.053s  |   4.053s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  11.475s  |  11.475s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   3.128s  |   3.128s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       | 200.090s  | 200.090s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   5.736s  |   5.736s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   4.345s  |   4.345s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   3.358s  |   3.358s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         |  60.358s  |  60.358s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |   5.259s  |   5.259s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |   6.839s  |   6.839s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  | 200.050s  | 200.050s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   5.857s  |   5.857s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   2.726s  |   2.726s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |   3.020s  |   3.020s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          | 200.178s  | 200.178s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          | 200.212s  | 200.212s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |   2.695s  |   2.695s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          | 200.194s  | 200.194s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          | 200.168s  | 200.168s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |   9.424s  |   9.424s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          | 200.138s  | 200.138s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          | 200.239s  | 200.239s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |   1.879s  |   1.879s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                | 200.132s  | 200.132s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                | 200.213s  | 200.213s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                |   3.400s  |   3.400s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                | 200.256s  | 200.256s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |  11.206s  |  11.206s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                | 200.141s  | 200.141s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                | 200.192s  | 200.192s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |   2.166s  |   2.166s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                | 200.159s  | 200.159s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                | 200.248s  | 200.248s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          | 200.144s  | 200.144s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |   3.738s  |   3.738s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          | 200.112s  | 200.112s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   8.107s  |   8.107s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |   4.318s  |   4.318s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          | 152.273s  | 152.273s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                |   2.835s  |   2.835s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   5.064s  |   5.064s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   4.277s  |   4.277s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |  14.889s  |  14.889s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   5.406s  |   5.406s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   4.251s  |   4.251s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |  17.223s  |  17.223s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                | 200.113s  | 200.113s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.575s  |   0.575s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                | 200.047s  | 200.047s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                |   9.780s  |   9.780s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |  31.937s  |  31.937s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |  29.897s  |  29.897s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   7.325s  |   7.325s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                | 200.074s  | 200.074s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   5.635s  |   5.635s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   5.591s  |   5.591s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   0.946s  |   0.946s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   9.802s  |   9.802s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |   4.086s  |   4.086s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |  10.898s  |  10.898s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                | 186.347s  | 186.347s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   4.507s  |   4.507s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |  82.643s  |  82.643s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   7.046s  |   7.046s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                |   2.552s  |   2.552s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   1.228s  |   1.228s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |   5.242s  |   5.242s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                | 200.061s  | 200.061s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                | 200.042s  | 200.042s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   8.002s  |   8.002s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   4.058s  |   4.058s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          | 200.048s  | 200.048s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          | 200.055s  | 200.055s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   2.942s  |   2.942s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |  12.516s  |  12.516s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |  51.395s  |  51.395s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   5.420s  |   5.420s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |  56.748s  |  56.748s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |   3.073s  |   3.073s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   1.285s  |   1.285s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   1.349s  |   1.349s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   2.803s  |   2.803s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          | 200.064s  | 200.064s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   4.490s  |   4.490s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   1.205s  |   1.205s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   7.909s  |   7.909s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   1.596s  |   1.596s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   1.235s  |   1.235s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |  18.309s  |  18.309s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   4.707s  |   4.707s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |   4.059s  |   4.059s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          | 200.050s  | 200.050s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          | 200.157s  | 200.157s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          | 200.076s  | 200.076s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          | 200.043s  | 200.043s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |   5.458s  |   5.458s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          | 200.115s  | 200.115s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |   7.988s  |   7.988s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |  53.531s  |  53.531s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |   6.945s  |   6.945s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           | 200.044s  | 200.044s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   3.026s  |   3.026s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |  67.602s  |  67.602s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   3.450s  |   3.450s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        | 200.052s  | 200.052s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   4.508s  |   4.508s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        | 200.084s  | 200.084s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   7.168s  |   7.168s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |   3.723s  |   3.723s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |   3.012s  |   3.012s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        | 200.068s  | 200.068s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |   8.665s  |   8.665s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        | 200.112s  | 200.112s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   5.289s  |   5.289s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |   4.846s  |   4.846s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   1.001s  |   1.001s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |   8.865s  |   8.865s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   5.699s  |   5.699s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   4.633s  |   4.633s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   0.800s  |   0.800s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        | 200.039s  | 200.039s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   3.095s  |   3.095s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   6.358s  |   6.358s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   1.028s  |   1.028s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   8.903s  |   8.903s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |  17.153s  |  17.153s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   8.025s  |   8.025s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        | 200.044s  | 200.044s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  37.551s  |  37.551s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   0.966s  |   0.966s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   3.682s  |   3.682s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        | 200.056s  | 200.056s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        | 200.056s  | 200.056s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   6.565s  |   6.565s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        |  42.101s  |  42.101s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            | 171.141s  | 171.141s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            |   4.684s  |   4.684s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  |   2.641s  |   2.641s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |  19.195s  |  19.195s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  | 200.075s  | 200.075s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  | 200.051s  | 200.051s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   3.249s  |   3.249s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   1.115s  |   1.115s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   6.625s  |   6.625s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  | 200.043s  | 200.043s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   2.863s  |   2.863s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   2.933s  |   2.933s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  | 200.170s  | 200.170s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   6.385s  |   6.385s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  | 200.069s  | 200.069s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   0.555s  |   0.555s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |   3.769s  |   3.769s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                | 200.255s  | 200.255s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  65.294s  |  65.294s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   8.466s  |   8.466s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              | 160.671s  | 160.671s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        | 200.203s  | 200.203s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   | 200.084s  | 200.084s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   | 200.135s  | 200.135s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   1.679s  |   1.679s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   | 200.191s  | 200.191s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |   2.495s  |   2.495s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   | 200.076s  | 200.076s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   | 200.118s  | 200.118s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |   2.923s  |   2.923s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   |   2.366s  |   2.366s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         | 125.441s  | 125.441s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   7.683s  |   7.683s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   2.994s  |   2.994s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         | 200.072s  | 200.072s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         | 200.101s  | 200.101s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   1.564s  |   1.564s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        | 200.115s  | 200.115s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        |   2.429s  |   2.429s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   7.346s  |   7.346s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        | 200.202s  | 200.202s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        |   2.567s  |   2.567s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |   7.099s  |   7.099s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        | 200.095s  | 200.095s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   3.566s  |   3.566s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   6.222s  |   6.222s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  20.949s  |  20.949s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |  13.040s  |  13.040s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |   9.414s  |   9.414s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  16.376s  |  16.376s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |  21.030s  |  21.030s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |  10.183s  |  10.183s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            | 200.072s  | 200.072s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            | 200.151s  | 200.151s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |   9.235s  |   9.235s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            | 200.122s  | 200.122s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            | 200.216s  | 200.216s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   8.962s  |   8.962s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            | 200.171s  | 200.171s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  |   3.713s  |   3.713s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   6.523s  |   6.523s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  | 200.098s  | 200.098s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   4.508s  |   4.508s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            | 200.074s  | 200.074s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  17.134s  |  17.134s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  21.891s  |  21.891s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  16.541s  |  16.541s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  15.590s  |  15.590s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   4.004s  |   4.004s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         | 200.064s  | 200.064s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   | 200.142s  | 200.142s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         | 200.056s  | 200.056s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   3.179s  |   3.179s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         | 200.102s  | 200.102s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |  11.291s  |  11.291s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |   3.231s  |   3.231s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   4.153s  |   4.153s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   8.264s  |   8.264s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         |  72.089s  |  72.089s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   4.166s  |   4.166s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   4.222s  |   4.222s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   4.376s  |   4.376s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   5.424s  |   5.424s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   3.989s  |   3.989s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   2.871s  |   2.871s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   4.153s  |   4.153s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   2.850s  |   2.850s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   |   5.640s  |   5.640s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           | 200.075s  | 200.075s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           | 200.080s  | 200.080s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   1.318s  |   1.318s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |  10.239s  |  10.239s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           | 160.447s  | 160.447s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           |   6.702s  |   6.702s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           | 121.428s  | 121.428s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  |  66.985s  |  66.985s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   2.721s  |   2.721s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   2.482s  |   2.482s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   8.137s  |   8.137s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   4.073s  |   4.073s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   8.812s  |   8.812s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             |  63.829s  |  63.829s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   3.584s  |   3.584s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   1.918s  |   1.918s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   3.573s  |   3.573s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   2.534s  |   2.534s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |   3.108s  |   3.108s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             | 200.040s  | 200.040s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   1.133s  |   1.133s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |  29.409s  |  29.409s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   4.433s  |   4.433s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |   5.495s  |   5.495s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             | 200.042s  | 200.042s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   7.837s  |   7.837s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   0.906s  |   0.906s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |   3.138s  |   3.138s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   2.971s  |   2.971s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |   3.216s  |   3.216s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             | 200.080s  | 200.080s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   7.349s  |   7.349s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |   9.219s  |   9.219s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              | 200.069s  | 200.069s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   3.878s  |   3.878s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          | 200.296s  | 200.296s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                | 200.155s  | 200.155s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |  72.398s  |  72.398s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |  17.703s  |  17.703s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                | 200.160s  | 200.160s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                | 200.097s  | 200.097s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  13.124s  |  13.124s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                | 200.122s  | 200.122s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                | 200.213s  | 200.213s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  15.819s  |  15.819s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  26.105s  |  26.105s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          | 200.045s  | 200.045s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |  10.352s  |  10.352s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   3.475s  |   3.475s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   3.614s  |   3.614s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              | 200.136s  | 200.136s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       | 200.189s  | 200.189s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       | 200.094s  | 200.094s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  15.003s  |  15.003s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  23.084s  |  23.084s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  25.640s  |  25.640s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  39.712s  |  39.712s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           |  47.530s  |  47.530s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  29.687s  |  29.687s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  18.615s  |  18.615s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   5.453s  |   5.453s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             | 200.118s  | 200.118s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  50.909s  |  50.909s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |  30.500s  |  30.500s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  20.324s  |  20.324s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  18.603s  |  18.603s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  50.346s  |  50.346s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |  41.075s  |  41.075s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  43.089s  |  43.089s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  12.466s  |  12.466s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           | 200.183s  | 200.183s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           | 200.255s  | 200.255s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           | 200.121s  | 200.121s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  13.274s  |  13.274s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 | 200.164s  | 200.164s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 | 200.106s  | 200.106s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   8.948s  |   8.948s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |  10.464s  |  10.464s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                | 200.143s  | 200.143s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                | 200.094s  | 200.094s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  15.362s  |  15.362s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  20.953s  |  20.953s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          | 200.329s  | 200.329s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          | 200.316s  | 200.316s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |   3.138s  |   3.138s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |   5.181s  |   5.181s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     | 101.159s  | 101.159s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   3.094s  |   3.094s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                | 150.185s  | 150.185s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                | 200.078s  | 200.078s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   2.071s  |   2.071s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   4.063s  |   4.063s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            | 200.101s  | 200.101s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |  13.204s  |  13.204s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   5.506s  |   5.506s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  33.927s  |  33.927s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   2.624s  |   2.624s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |  23.297s  |  23.297s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   2.022s  |   2.022s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   1.477s  |   1.477s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |   1.321s  |   1.321s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            | 200.051s  | 200.051s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      | 200.162s  | 200.162s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   4.999s  |   4.999s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   1.590s  |   1.590s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      | 200.115s  | 200.115s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   1.236s  |   1.236s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   1.876s  |   1.876s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       | 196.522s  | 196.522s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   2.163s  |   2.163s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  68.943s  |  68.943s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   5.722s  |   5.722s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |  20.658s  |  20.658s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |   1.968s  |   1.968s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.666s  |   0.666s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   2.086s  |   2.086s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           | 200.050s  | 200.050s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  12.377s  |  12.377s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |   9.453s  |   9.453s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  | 200.058s  | 200.058s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |  76.512s  |  76.512s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           | 200.075s  | 200.075s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   3.211s  |   3.211s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           | 200.052s  | 200.052s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           |  84.392s  |  84.392s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        | 200.048s  | 200.048s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   8.021s  |   8.021s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   2.303s  |   2.303s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   1.490s  |   1.490s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |  24.868s  |  24.868s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   1.551s  |   1.551s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   6.825s  |   6.825s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   4.921s  |   4.921s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |   3.662s  |   3.662s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   5.103s  |   5.103s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   1.197s  |   1.197s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   2.052s  |   2.052s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   3.033s  |   3.033s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              | 200.078s  | 200.078s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   4.114s  |   4.114s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  | 200.068s  | 200.068s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   6.977s  |   6.977s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   6.140s  |   6.140s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   2.252s  |   2.252s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   2.556s  |   2.556s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   2.439s  |   2.439s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |  50.339s  |  50.339s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  16.071s  |  16.071s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |   3.576s  |   3.576s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   3.069s  |   3.069s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  13.346s  |  13.346s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |   3.540s  |   3.540s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   2.678s  |   2.678s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |  15.955s  |  15.955s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   7.789s  |   7.789s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |  19.218s  |  19.218s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                | 200.044s  | 200.044s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          |   3.089s  |   3.089s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   1.530s  |   1.530s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   0.973s  |   0.973s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   0.983s  |   0.983s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   1.063s  |   1.063s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  12.365s  |  12.365s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |  26.763s  |  26.763s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |  35.352s  |  35.352s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |   4.516s  |   4.516s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                | 200.119s  | 200.119s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |   7.199s  |   7.199s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   3.428s  |   3.428s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  12.964s  |  12.964s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   2.163s  |   2.163s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   4.644s  |   4.644s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   4.571s  |   4.571s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   3.928s  |   3.928s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |  18.466s  |  18.466s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |  12.269s  |  12.269s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       | 109.728s  | 109.728s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       | 200.147s  | 200.147s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       | 200.140s  | 200.140s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   2.655s  |   2.655s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       | 200.084s  | 200.084s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       |   4.033s  |   4.033s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |   8.451s  |   8.451s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   4.462s  |   4.462s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       | 200.045s  | 200.045s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   3.893s  |   3.893s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       | 200.055s  | 200.055s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     |   3.282s  |   3.282s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   1.249s  |   1.249s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  35.661s  |  35.661s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   1.304s  |   1.304s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   7.191s  |   7.191s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   4.730s  |   4.730s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |   9.558s  |   9.558s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   7.316s  |   7.316s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   2.531s  |   2.531s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   1.620s  |   1.620s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   2.661s  |   2.661s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |   3.670s  |   3.670s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        | 200.042s  | 200.042s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   7.323s  |   7.323s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  27.052s  |  27.052s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  | 200.057s  | 200.057s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.814s  |   0.814s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   2.136s  |   2.136s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  18.860s  |  18.860s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.638s  |   0.638s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |  14.780s  |  14.780s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   5.822s  |   5.822s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           |   7.131s  |   7.131s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           | 200.046s  | 200.046s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   1.190s  |   1.190s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   4.069s  |   4.069s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   5.936s  |   5.936s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   4.666s  |   4.666s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   4.198s  |   4.198s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   0.756s  |   0.756s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           |  27.641s  |  27.641s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   3.198s  |   3.198s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           | 200.050s  | 200.050s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   0.566s  |   0.566s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.727s  |   0.727s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           | 180.362s  | 180.362s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   1.825s  |   1.825s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   5.760s  |   5.760s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   2.169s  |   2.169s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   1.207s  |   1.207s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   3.955s  |   3.955s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   3.395s  |   3.395s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   6.786s  |   6.786s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.864s  |   0.864s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |   5.154s  |   5.154s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   4.188s  |   4.188s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   3.843s  |   3.843s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           |   6.563s  |   6.563s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   3.087s  |   3.087s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           |   3.169s  |   3.169s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   2.641s  |   2.641s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   4.615s  |   4.615s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.834s  |   0.834s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   2.040s  |   2.040s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   1.272s  |   1.272s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |   3.468s  |   3.468s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   2.315s  |   2.315s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           | 173.169s  | 173.169s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   1.596s  |   1.596s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   2.025s  |   2.025s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   7.338s  |   7.338s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   2.635s  |   2.635s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   2.788s  |   2.788s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |   5.215s  |   5.215s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   4.421s  |   4.421s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   4.877s  |   4.877s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   2.795s  |   2.795s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   3.212s  |   3.212s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |  24.644s  |  24.644s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |   2.578s  |   2.578s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   1.189s  |   1.189s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   2.369s  |   2.369s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.761s  |   0.761s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  22.771s  |  22.771s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   3.527s  |   3.527s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |   3.416s  |   3.416s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            | 200.120s  | 200.120s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   2.589s  |   2.589s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |   5.636s  |   5.636s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   5.266s  |   5.266s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   2.372s  |   2.372s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   1.483s  |   1.483s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  69.321s  |  69.321s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           |   7.036s  |   7.036s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   3.214s  |   3.214s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   5.598s  |   5.598s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  21.157s  |  21.157s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   0.961s  |   0.961s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   2.896s  |   2.896s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   3.903s  |   3.903s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   3.125s  |   3.125s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   3.634s  |   3.634s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |   4.464s  |   4.464s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   4.172s  |   4.172s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   2.459s  |   2.459s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   4.194s  |   4.194s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   7.971s  |   7.971s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   5.023s  |   5.023s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   3.191s  |   3.191s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   2.073s  |   2.073s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   5.750s  |   5.750s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           | 115.459s  | 115.459s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.768s  |   0.768s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   1.158s  |   1.158s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   5.217s  |   5.217s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           | 200.061s  | 200.061s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   7.084s  |   7.084s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   4.094s  |   4.094s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   7.665s  |   7.665s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   4.570s  |   4.570s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   6.071s  |   6.071s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   3.407s  |   3.407s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           | 200.078s  | 200.078s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  85.717s  |  85.717s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   1.814s  |   1.814s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   3.110s  |   3.110s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   7.258s  |   7.258s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   4.517s  |   4.517s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |  10.816s  |  10.816s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   4.474s  |   4.474s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           | 137.652s  | 137.652s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.560s  |   0.560s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |  12.131s  |  12.131s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   1.099s  |   1.099s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.603s  |   1.603s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   1.257s  |   1.257s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   2.184s  |   2.184s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   1.415s  |   1.415s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            | 200.105s  | 200.105s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            | 146.690s  | 146.690s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            | 200.057s  | 200.057s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            | 200.056s  | 200.056s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.546s  |   0.546s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            | 200.042s  | 200.042s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            |  30.697s  |  30.697s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.101s  |   0.101s  |   0.000s  | 0.0%|
</details>
