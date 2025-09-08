Comparing data and data


# SUMMARY
- LHS tests = 2313
- RHS tests = 2313
- LHS success = 2310  (99.87029831387808%)
- RHS success = 2310  (99.87029831387808%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-parallel-searchtree
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 96bb3caa9ec54a27c36be74f4cb38b17fd5d2cc6
Z3 branch: 
Z3 options: "-T:30 tactic.default_tactic=smt smt.threads=4 smt_parallel.searchtree=true"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: fix messup with closing nodes

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-parallel-searchtree
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 96bb3caa9ec54a27c36be74f4cb38b17fd5d2cc6
Z3 branch: 
Z3 options: "-T:30 tactic.default_tactic=smt smt.threads=4 smt_parallel.searchtree=true"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: fix messup with closing nodes

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.180s  |  30.180s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.329s  |  30.329s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.813s  |   1.813s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   1.016s  |   1.016s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   1.087s  |   1.087s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.916s  |   0.916s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.653s  |  30.653s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.810s  |   0.810s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.717s  |   0.717s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.180s  |  30.180s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.329s  |  30.329s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.813s  |   1.813s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   1.016s  |   1.016s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   1.087s  |   1.087s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.916s  |   0.916s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.653s  |  30.653s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.810s  |   0.810s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.717s  |   0.717s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.180s  |  30.180s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.329s  |  30.329s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.813s  |   1.813s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   1.016s  |   1.016s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   1.087s  |   1.087s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.916s  |   0.916s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.653s  |  30.653s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.810s  |   0.810s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.717s  |   0.717s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.180s  |  30.180s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.329s  |  30.329s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.813s  |   1.813s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   1.016s  |   1.016s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   1.087s  |   1.087s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.916s  |   0.916s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.653s  |  30.653s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.810s  |   0.810s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.717s  |   0.717s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                     |  31.324s |198.0MiB|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                         |  31.267s |139.0MiB|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                    |  31.213s |122.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  31.101s |1803.0MiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2              |  31.023s |189.0MiB|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                            |  31.022s |163.0MiB|
|185.smt2                                                                                   |  31.018s |2822.0MiB|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                |  31.018s |156.0MiB|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                  |  30.998s |168.0MiB|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                              |  30.998s |170.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.992s |1925.0MiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       |  30.990s |207.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                      |  30.990s |173.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                          |  30.986s |158.0MiB|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                       |  30.956s |166.0MiB|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2               |  30.948s |141.0MiB|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                       |  30.936s |283.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               |  30.916s |139.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  30.913s |591.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                         |  30.910s |160.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                     |  31.324s |198.0MiB|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                         |  31.267s |139.0MiB|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                    |  31.213s |122.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  31.101s |1803.0MiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2              |  31.023s |189.0MiB|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                            |  31.022s |163.0MiB|
|185.smt2                                                                                   |  31.018s |2822.0MiB|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                |  31.018s |156.0MiB|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                  |  30.998s |168.0MiB|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                              |  30.998s |170.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.992s |1925.0MiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       |  30.990s |207.0MiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                      |  30.990s |173.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                          |  30.986s |158.0MiB|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                       |  30.956s |166.0MiB|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2               |  30.948s |141.0MiB|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                       |  30.936s |283.0MiB|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                               |  30.916s |139.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  30.913s |591.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                         |  30.910s |160.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |152.0MiB|152.0MiB|0B| 0.0%|
|04.smt2                                                                                     |149.0MiB|149.0MiB|0B| 0.0%|
|1.smt2                                                                                      |119.0MiB|119.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |118.0MiB|118.0MiB|0B| 0.0%|
|1010.smt2                                                                                   |121.0MiB|121.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |98.592MiB|98.592MiB|0B| 0.0%|
|1021.smt2                                                                                   |97.0MiB|97.0MiB|0B| 0.0%|
|1034.smt2                                                                                   |100.0MiB|100.0MiB|0B| 0.0%|
|1063.smt2                                                                                   |102.0MiB|102.0MiB|0B| 0.0%|
|107.smt2                                                                                    |96.292MiB|96.292MiB|0B| 0.0%|
|1082.smt2                                                                                   |109.0MiB|109.0MiB|0B| 0.0%|
|1085.smt2                                                                                   |98.828MiB|98.828MiB|0B| 0.0%|
|1089.smt2                                                                                   |98.5MiB|98.5MiB|0B| 0.0%|
|1090.smt2                                                                                   |98.168MiB|98.168MiB|0B| 0.0%|
|1092.smt2                                                                                   |98.688MiB|98.688MiB|0B| 0.0%|
|11.smt2                                                                                     |160.0MiB|160.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |98.4MiB|98.4MiB|0B| 0.0%|
|1112.smt2                                                                                   |99.796MiB|99.796MiB|0B| 0.0%|
|1113.smt2                                                                                   |99.18MiB|99.18MiB|0B| 0.0%|
|1126.smt2                                                                                   |97.0MiB|97.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |152.0MiB|152.0MiB|0B| 0.0%|
|04.smt2                                                                                     |149.0MiB|149.0MiB|0B| 0.0%|
|1.smt2                                                                                      |119.0MiB|119.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |118.0MiB|118.0MiB|0B| 0.0%|
|1010.smt2                                                                                   |121.0MiB|121.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |98.592MiB|98.592MiB|0B| 0.0%|
|1021.smt2                                                                                   |97.0MiB|97.0MiB|0B| 0.0%|
|1034.smt2                                                                                   |100.0MiB|100.0MiB|0B| 0.0%|
|1063.smt2                                                                                   |102.0MiB|102.0MiB|0B| 0.0%|
|107.smt2                                                                                    |96.292MiB|96.292MiB|0B| 0.0%|
|1082.smt2                                                                                   |109.0MiB|109.0MiB|0B| 0.0%|
|1085.smt2                                                                                   |98.828MiB|98.828MiB|0B| 0.0%|
|1089.smt2                                                                                   |98.5MiB|98.5MiB|0B| 0.0%|
|1090.smt2                                                                                   |98.168MiB|98.168MiB|0B| 0.0%|
|1092.smt2                                                                                   |98.688MiB|98.688MiB|0B| 0.0%|
|11.smt2                                                                                     |160.0MiB|160.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |98.4MiB|98.4MiB|0B| 0.0%|
|1112.smt2                                                                                   |99.796MiB|99.796MiB|0B| 0.0%|
|1113.smt2                                                                                   |99.18MiB|99.18MiB|0B| 0.0%|
|1126.smt2                                                                                   |97.0MiB|97.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |152.0MiB|152.0MiB|0B| 0.0%|
|04.smt2                                                                                     |149.0MiB|149.0MiB|0B| 0.0%|
|1.smt2                                                                                      |119.0MiB|119.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |118.0MiB|118.0MiB|0B| 0.0%|
|1010.smt2                                                                                   |121.0MiB|121.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |98.592MiB|98.592MiB|0B| 0.0%|
|1021.smt2                                                                                   |97.0MiB|97.0MiB|0B| 0.0%|
|1034.smt2                                                                                   |100.0MiB|100.0MiB|0B| 0.0%|
|1063.smt2                                                                                   |102.0MiB|102.0MiB|0B| 0.0%|
|107.smt2                                                                                    |96.292MiB|96.292MiB|0B| 0.0%|
|1082.smt2                                                                                   |109.0MiB|109.0MiB|0B| 0.0%|
|1085.smt2                                                                                   |98.828MiB|98.828MiB|0B| 0.0%|
|1089.smt2                                                                                   |98.5MiB|98.5MiB|0B| 0.0%|
|1090.smt2                                                                                   |98.168MiB|98.168MiB|0B| 0.0%|
|1092.smt2                                                                                   |98.688MiB|98.688MiB|0B| 0.0%|
|11.smt2                                                                                     |160.0MiB|160.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |98.4MiB|98.4MiB|0B| 0.0%|
|1112.smt2                                                                                   |99.796MiB|99.796MiB|0B| 0.0%|
|1113.smt2                                                                                   |99.18MiB|99.18MiB|0B| 0.0%|
|1126.smt2                                                                                   |97.0MiB|97.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |152.0MiB|152.0MiB|0B| 0.0%|
|04.smt2                                                                                     |149.0MiB|149.0MiB|0B| 0.0%|
|1.smt2                                                                                      |119.0MiB|119.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |118.0MiB|118.0MiB|0B| 0.0%|
|1010.smt2                                                                                   |121.0MiB|121.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |98.592MiB|98.592MiB|0B| 0.0%|
|1021.smt2                                                                                   |97.0MiB|97.0MiB|0B| 0.0%|
|1034.smt2                                                                                   |100.0MiB|100.0MiB|0B| 0.0%|
|1063.smt2                                                                                   |102.0MiB|102.0MiB|0B| 0.0%|
|107.smt2                                                                                    |96.292MiB|96.292MiB|0B| 0.0%|
|1082.smt2                                                                                   |109.0MiB|109.0MiB|0B| 0.0%|
|1085.smt2                                                                                   |98.828MiB|98.828MiB|0B| 0.0%|
|1089.smt2                                                                                   |98.5MiB|98.5MiB|0B| 0.0%|
|1090.smt2                                                                                   |98.168MiB|98.168MiB|0B| 0.0%|
|1092.smt2                                                                                   |98.688MiB|98.688MiB|0B| 0.0%|
|11.smt2                                                                                     |160.0MiB|160.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |98.4MiB|98.4MiB|0B| 0.0%|
|1112.smt2                                                                                   |99.796MiB|99.796MiB|0B| 0.0%|
|1113.smt2                                                                                   |99.18MiB|99.18MiB|0B| 0.0%|
|1126.smt2                                                                                   |97.0MiB|97.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  30.501s |3164.0MiB|
|185.smt2                                                                                   |  31.018s |2822.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  30.302s |1989.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.992s |1925.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  31.101s |1803.0MiB|
|182.smt2                                                                                   |  30.768s |1648.0MiB|
|183.smt2                                                                                   |  30.673s |1647.0MiB|
|181.smt2                                                                                   |  30.560s |935.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  30.730s |929.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   |  30.357s |806.0MiB|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                |  30.383s |782.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          |  30.337s |748.0MiB|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                 |  30.391s |728.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  30.348s |698.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                    |  30.556s |689.0MiB|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                           |  30.359s |686.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  30.402s |660.0MiB|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                 |  30.519s |653.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                        |  30.519s |630.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  30.403s |628.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  30.501s |3164.0MiB|
|185.smt2                                                                                   |  31.018s |2822.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  30.302s |1989.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.992s |1925.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  31.101s |1803.0MiB|
|182.smt2                                                                                   |  30.768s |1648.0MiB|
|183.smt2                                                                                   |  30.673s |1647.0MiB|
|181.smt2                                                                                   |  30.560s |935.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  30.730s |929.0MiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   |  30.357s |806.0MiB|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                |  30.383s |782.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          |  30.337s |748.0MiB|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                 |  30.391s |728.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  30.348s |698.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                    |  30.556s |689.0MiB|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                           |  30.359s |686.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  30.402s |660.0MiB|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                 |  30.519s |653.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                        |  30.519s |630.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  30.403s |628.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  30.180s  |  30.180s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  30.329s  |  30.329s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.813s  |   1.813s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   1.016s  |   1.016s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   1.087s  |   1.087s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.916s  |   0.916s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  30.653s  |  30.653s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.810s  |   0.810s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.772s  |   0.772s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   1.118s  |   1.118s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.908s  |   0.908s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.773s  |   0.773s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.779s  |   0.779s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |  30.181s  |  30.181s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.781s  |   0.781s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   1.068s  |   1.068s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.510s  |   0.510s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   1.253s  |   1.253s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   1.148s  |   1.148s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.760s  |   0.760s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   1.279s  |   1.279s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.949s  |   0.949s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.704s  |   0.704s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |  30.446s  |  30.446s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.670s  |   0.670s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.945s  |   0.945s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.914s  |   0.914s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.671s  |   0.671s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.934s  |   0.934s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   1.362s  |   1.362s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   1.228s  |   1.228s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   1.688s  |   1.688s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   1.123s  |   1.123s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   1.432s  |   1.432s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   1.574s  |   1.574s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.683s  |   0.683s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   1.076s  |   1.076s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.998s  |   0.998s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.844s  |   0.844s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |  30.254s  |  30.254s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.900s  |   0.900s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.683s  |   0.683s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  30.560s  |  30.560s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  30.768s  |  30.768s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  30.673s  |  30.673s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  31.018s  |  31.018s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   1.398s  |   1.398s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   0.767s  |   0.767s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   0.813s  |   0.813s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   1.487s  |   1.487s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.816s  |   0.816s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.773s  |   0.773s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   0.797s  |   0.797s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   1.093s  |   1.093s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.617s  |   0.617s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   0.907s  |   0.907s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   1.245s  |   1.245s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.670s  |   0.670s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |  30.290s  |  30.290s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.997s  |   0.997s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.648s  |   0.648s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.604s  |   0.604s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |  30.337s  |  30.337s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.768s  |   0.768s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.964s  |   0.964s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   1.080s  |   1.080s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.558s  |   0.558s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.848s  |   0.848s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   1.769s  |   1.769s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   2.055s  |   2.055s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   1.817s  |   1.817s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |  30.189s  |  30.189s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |  17.822s  |  17.822s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |  13.625s  |  13.625s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   1.220s  |   1.220s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |  30.520s  |  30.520s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   0.617s  |   0.617s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.706s  |   0.706s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.876s  |   0.876s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.674s  |   0.674s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |  30.682s  |  30.682s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.698s  |   0.698s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.619s  |   0.619s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.769s  |   0.769s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.849s  |   0.849s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   1.013s  |   1.013s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.885s  |   0.885s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.905s  |   0.905s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.847s  |   0.847s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   1.007s  |   1.007s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   1.155s  |   1.155s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   1.036s  |   1.036s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   0.761s  |   0.761s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.642s  |   0.642s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|966.smt2                                                                                    |   1.681s  |   1.681s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  30.303s  |  30.303s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   1.013s  |   1.013s  |   0.000s  | 0.0%|
|99.smt2                                                                                     |  30.382s  |  30.382s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.751s  |   0.751s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |  30.235s  |  30.235s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.986s  |   0.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   1.209s  |   1.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          |  30.397s  |  30.397s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |  19.044s  |  19.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   2.037s  |   2.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |  30.501s  |  30.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.510s  |   0.510s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          |  30.313s  |  30.313s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   3.289s  |   3.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   1.716s  |   1.716s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            |  30.185s  |  30.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |  29.046s  |  29.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   1.899s  |   1.899s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       |  30.183s  |  30.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   1.406s  |   1.406s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  30.390s  |  30.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |  10.786s  |  10.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |  30.256s  |  30.256s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   1.835s  |   1.835s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   0.803s  |   0.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           |  30.510s  |  30.510s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           |  30.432s  |  30.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |  30.650s  |  30.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |  23.714s  |  23.714s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  30.629s  |  30.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   7.273s  |   7.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |  15.692s  |  15.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         |  21.492s  |  21.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             |  30.453s  |  30.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |  30.227s  |  30.227s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  30.537s  |  30.537s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             |  30.547s  |  30.547s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 |  30.559s  |  30.559s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   1.327s  |   1.327s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   1.893s  |   1.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              |   1.017s  |   1.017s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |  22.133s  |  22.133s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |   8.610s  |   8.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               |  30.220s  |  30.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         |  30.862s  |  30.862s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |  30.171s  |  30.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |   5.984s  |   5.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |  30.161s  |  30.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 |  30.529s  |  30.529s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      |  30.157s  |  30.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   7.124s  |   7.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   4.529s  |   4.529s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              |  30.493s  |  30.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   7.271s  |   7.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |  30.249s  |  30.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          |  30.431s  |  30.431s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          |  30.185s  |  30.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   5.997s  |   5.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         |  30.314s  |  30.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   4.143s  |   4.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      |  30.254s  |  30.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |  12.816s  |  12.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   6.481s  |   6.481s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |  14.010s  |  14.010s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         |  30.228s  |  30.228s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      |  30.317s  |  30.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               |  30.643s  |  30.643s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  30.308s  |  30.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |  23.135s  |  23.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           |  30.119s  |  30.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               |  30.190s  |  30.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   0.908s  |   0.908s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               |  30.373s  |  30.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |  30.197s  |  30.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   1.703s  |   1.703s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |  30.169s  |  30.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   9.014s  |   9.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   |  30.183s  |  30.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   |  30.290s  |  30.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   |  30.268s  |  30.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             |  30.857s  |  30.857s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  31.022s  |  31.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   2.022s  |   2.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    |  30.215s  |  30.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |  25.251s  |  25.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        |  30.200s  |  30.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  30.219s  |  30.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  30.177s  |  30.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     |  30.391s  |  30.391s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               |  30.325s  |  30.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               |  30.253s  |  30.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   0.958s  |   0.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   0.808s  |   0.808s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |  24.240s  |  24.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |  30.498s  |  30.498s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               |  30.474s  |  30.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   0.996s  |   0.996s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   1.750s  |   1.750s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   2.362s  |   2.362s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   1.320s  |   1.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   1.337s  |   1.337s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   1.196s  |   1.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                |  30.217s  |  30.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   1.358s  |   1.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              |  30.180s  |  30.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |  30.574s  |  30.574s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   1.865s  |   1.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |  30.269s  |  30.269s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  30.272s  |  30.272s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  30.866s  |  30.866s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   1.163s  |   1.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  30.660s  |  30.660s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          |  30.152s  |  30.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          |  30.211s  |  30.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          |  30.315s  |  30.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |  26.642s  |  26.642s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          |  30.508s  |  30.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          |  30.152s  |  30.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  30.680s  |  30.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   6.211s  |   6.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  17.411s  |  17.411s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   2.287s  |   2.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    |  30.641s  |  30.641s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   8.860s  |   8.860s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |  30.254s  |  30.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    |  30.162s  |  30.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |  16.193s  |  16.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |  15.593s  |  15.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |   7.479s  |   7.479s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |   5.653s  |   5.653s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        |  30.189s  |  30.189s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |  30.364s  |  30.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |  24.531s  |  24.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   2.587s  |   2.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        |  30.215s  |  30.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   0.558s  |   0.558s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  30.261s  |  30.261s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  30.471s  |  30.471s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  30.327s  |  30.327s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  23.736s  |  23.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  30.212s  |  30.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              |  30.357s  |  30.357s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  30.452s  |  30.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  |  30.179s  |  30.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |  21.177s  |  21.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |  30.164s  |  30.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.796s  |   0.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              |  30.221s  |  30.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |  13.362s  |  13.362s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |  30.359s  |  30.359s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |   9.022s  |   9.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |  20.434s  |  20.434s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  30.646s  |  30.646s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        |  30.492s  |  30.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |  30.844s  |  30.844s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |   5.792s  |   5.792s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   |  30.300s  |  30.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   |  30.183s  |  30.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     |  30.282s  |  30.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   7.549s  |   7.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   1.021s  |   1.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   1.342s  |   1.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     |  30.597s  |  30.597s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 |  30.663s  |  30.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                |  30.182s  |  30.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   6.665s  |   6.665s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                |  30.948s  |  30.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      |  30.226s  |  30.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   5.867s  |   5.867s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      |  30.596s  |  30.596s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      |  30.281s  |  30.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   8.634s  |   8.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      |  31.324s  |  31.324s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |   5.371s  |   5.371s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   1.335s  |   1.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   3.427s  |   3.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |  13.938s  |  13.938s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |   3.229s  |   3.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   2.025s  |   2.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |  30.447s  |  30.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  30.836s  |  30.836s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |  10.129s  |  10.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |  25.955s  |  25.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          |  30.302s  |  30.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               |  30.301s  |  30.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                |  30.410s  |  30.410s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   9.413s  |   9.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |  12.008s  |  12.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   2.270s  |   2.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   2.229s  |   2.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |  10.265s  |  10.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   1.334s  |   1.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   1.118s  |   1.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              |  30.271s  |  30.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   2.594s  |   2.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   0.958s  |   0.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |  30.296s  |  30.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   5.819s  |   5.819s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  30.165s  |  30.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          |  30.822s  |  30.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |   9.221s  |   9.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          |  30.215s  |  30.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          |  30.181s  |  30.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |  23.918s  |  23.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          |  30.224s  |  30.224s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          |  30.755s  |  30.755s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |  25.692s  |  25.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          |  30.223s  |  30.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            |  30.441s  |  30.441s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   1.110s  |   1.110s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |  13.376s  |  13.376s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |   8.395s  |   8.395s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            |  30.191s  |  30.191s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   7.850s  |   7.850s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   1.315s  |   1.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |  24.467s  |  24.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   1.113s  |   1.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   3.244s  |   3.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |   5.587s  |   5.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   1.054s  |   1.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   0.996s  |   0.996s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |   1.172s  |   1.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           |  30.374s  |  30.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           |  30.247s  |  30.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |   1.102s  |   1.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   4.072s  |   4.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   3.418s  |   3.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           |  30.301s  |  30.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   2.373s  |   2.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |  30.153s  |  30.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   0.974s  |   0.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |   6.820s  |   6.820s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   1.380s  |   1.380s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           |  30.461s  |  30.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |  30.192s  |  30.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   1.305s  |   1.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |   3.347s  |   3.347s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  10.805s  |  10.805s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |   2.845s  |   2.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |  22.595s  |  22.595s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |   6.979s  |   6.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           |   0.648s  |   0.648s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |  30.671s  |  30.671s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   3.469s  |   3.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |   6.692s  |   6.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |  17.627s  |  17.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  13.412s  |  13.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   1.016s  |   1.016s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   0.901s  |   0.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |  30.251s  |  30.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   2.061s  |   2.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |   4.116s  |   4.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |  18.543s  |  18.543s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |   4.176s  |   4.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           |  30.162s  |  30.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  13.961s  |  13.961s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           |  30.281s  |  30.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   4.889s  |   4.889s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           |  30.986s  |  30.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     |  30.556s  |  30.556s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   1.621s  |   1.621s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   6.689s  |   6.689s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |   1.292s  |   1.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |  11.820s  |  11.820s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |  30.420s  |  30.420s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   4.158s  |   4.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   2.067s  |   2.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     |  30.231s  |  30.231s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |   5.847s  |   5.847s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.914s  |   0.914s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |  11.469s  |  11.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |  30.517s  |  30.517s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   7.073s  |   7.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |  30.295s  |  30.295s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   6.025s  |   6.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   3.333s  |   3.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   9.220s  |   9.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   7.211s  |   7.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   5.864s  |   5.864s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   6.173s  |   6.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   1.770s  |   1.770s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     |  30.260s  |  30.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |   5.400s  |   5.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |   6.965s  |   6.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   0.905s  |   0.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   3.055s  |   3.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |   2.308s  |   2.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               |  30.212s  |  30.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |   1.442s  |   1.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   4.788s  |   4.788s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     |  30.221s  |  30.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |   1.289s  |   1.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |   2.080s  |   2.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   1.135s  |   1.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |   1.147s  |   1.147s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |  11.575s  |  11.575s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |  12.025s  |  12.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   1.677s  |   1.677s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |   1.349s  |   1.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     |   2.571s  |   2.571s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     |  30.659s  |  30.659s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  30.576s  |  30.576s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   0.776s  |   0.776s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               |  30.175s  |  30.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   0.766s  |   0.766s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   4.355s  |   4.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |   1.201s  |   1.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               |  30.784s  |  30.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |   9.795s  |   9.795s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   1.791s  |   1.791s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |  30.355s  |  30.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               |  30.212s  |  30.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |   2.818s  |   2.818s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |   4.652s  |   4.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               |  30.476s  |  30.476s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               |  30.280s  |  30.280s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               |  31.023s  |  31.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               |  30.134s  |  30.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |   1.339s  |   1.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   1.542s  |   1.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |  11.474s  |  11.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   1.036s  |   1.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  30.255s  |  30.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               |   2.165s  |   2.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   0.769s  |   0.769s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               |  30.466s  |  30.466s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   1.150s  |   1.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |   2.069s  |   2.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               |  30.279s  |  30.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |   2.054s  |   2.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   1.629s  |   1.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   5.594s  |   5.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   3.190s  |   3.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |  10.179s  |  10.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   6.484s  |   6.484s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   1.837s  |   1.837s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   6.200s  |   6.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   2.489s  |   2.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               |  30.898s  |  30.898s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   2.178s  |   2.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               |  30.449s  |  30.449s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               |  30.489s  |  30.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |  16.281s  |  16.281s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |  28.752s  |  28.752s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |  30.152s  |  30.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |   9.482s  |   9.482s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   7.161s  |   7.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |   3.897s  |   3.897s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |  30.219s  |  30.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   1.626s  |   1.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |   2.934s  |   2.934s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   4.707s  |   4.707s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             |  30.240s  |  30.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |  30.146s  |  30.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |  12.537s  |  12.537s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   1.314s  |   1.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   6.734s  |   6.734s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   0.572s  |   0.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |  10.185s  |  10.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |   4.150s  |   4.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   2.245s  |   2.245s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |   1.746s  |   1.746s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   7.585s  |   7.585s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             |  30.536s  |  30.536s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |   7.755s  |   7.755s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |   3.370s  |   3.370s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.998s  |   0.998s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |  25.100s  |  25.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             |  30.420s  |  30.420s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   7.071s  |   7.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             |  30.253s  |  30.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |  26.688s  |  26.688s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |   2.255s  |   2.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |   4.654s  |   4.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |   2.685s  |   2.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   1.353s  |   1.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |   2.550s  |   2.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |   4.144s  |   4.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             |  30.406s  |  30.406s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   4.527s  |   4.527s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.606s  |   0.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   1.602s  |   1.602s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             |  30.708s  |  30.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |   1.018s  |   1.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             |  30.287s  |  30.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   1.743s  |   1.743s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             |  30.182s  |  30.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   0.953s  |   0.953s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             |  30.379s  |  30.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |  30.683s  |  30.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |  30.339s  |  30.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               |   8.894s  |   8.894s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |   7.116s  |   7.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |   6.900s  |   6.900s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         |  30.184s  |  30.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              |   5.187s  |   5.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   6.323s  |   6.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |  25.246s  |  25.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |   2.040s  |   2.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   4.088s  |   4.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    |  30.824s  |  30.824s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |   0.810s  |   0.810s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |   4.158s  |   4.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   8.370s  |   8.370s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |  30.332s  |  30.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   6.291s  |   6.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |  30.277s  |  30.277s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    |  30.270s  |  30.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   1.786s  |   1.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    |  30.243s  |  30.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   0.846s  |   0.846s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   8.673s  |   8.673s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |  30.506s  |  30.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    |  30.226s  |  30.226s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    |  30.390s  |  30.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    |  30.270s  |  30.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   6.570s  |   6.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   5.627s  |   5.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |   1.382s  |   1.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   8.877s  |   8.877s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    |  30.329s  |  30.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    |  30.581s  |  30.581s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  30.500s  |  30.500s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  30.284s  |  30.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |  30.355s  |  30.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |  10.146s  |  10.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    |  30.229s  |  30.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |  27.595s  |  27.595s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |  26.048s  |  26.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   2.958s  |   2.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    |  30.278s  |  30.278s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |  11.025s  |  11.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    |  30.495s  |  30.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |   2.692s  |   2.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   1.847s  |   1.847s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.751s  |   0.751s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |  13.695s  |  13.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |  30.459s  |  30.459s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |   1.048s  |   1.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |  10.477s  |  10.477s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |  10.104s  |  10.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |  30.253s  |  30.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          |  30.230s  |  30.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   1.775s  |   1.775s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.633s  |   0.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          |  30.845s  |  30.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   7.391s  |   7.391s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |  13.487s  |  13.487s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |   1.021s  |   1.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          |  30.160s  |  30.160s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |   1.262s  |   1.262s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          |  30.551s  |  30.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   1.237s  |   1.237s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          |  30.439s  |  30.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   2.569s  |   2.569s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |   1.022s  |   1.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   2.722s  |   2.722s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   0.783s  |   0.783s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          |  30.502s  |  30.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          |  30.266s  |  30.266s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.969s  |   0.969s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   0.839s  |   0.839s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          |  30.213s  |  30.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   6.926s  |   6.926s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |  11.291s  |  11.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   0.761s  |   0.761s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        |  30.479s  |  30.479s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   1.212s  |   1.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        |  30.956s  |  30.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   1.091s  |   1.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |   1.303s  |   1.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |  17.825s  |  17.825s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |   2.831s  |   2.831s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |  20.705s  |  20.705s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |  14.283s  |  14.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   1.114s  |   1.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |   1.889s  |   1.889s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   1.645s  |   1.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   2.336s  |   2.336s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.666s  |   0.666s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |   3.497s  |   3.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.628s  |   0.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |  10.458s  |  10.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   9.779s  |   9.779s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   5.745s  |   5.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |  14.200s  |  14.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   2.404s  |   2.404s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   2.089s  |   2.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   3.250s  |   3.250s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        |  30.235s  |  30.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   6.210s  |   6.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |  13.620s  |  13.620s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |   2.930s  |   2.930s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |   5.402s  |   5.402s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   5.206s  |   5.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |  11.028s  |  11.028s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |  30.430s  |  30.430s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        |  30.485s  |  30.485s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |   3.572s  |   3.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        |  30.338s  |  30.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |  22.046s  |  22.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |  10.962s  |  10.962s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |   1.253s  |   1.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   3.891s  |   3.891s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |   5.063s  |   5.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |  30.284s  |  30.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   0.738s  |   0.738s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        |  30.251s  |  30.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |  20.352s  |  20.352s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  |  30.615s  |  30.615s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   1.575s  |   1.575s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   2.523s  |   2.523s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   5.155s  |   5.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   8.952s  |   8.952s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |   6.753s  |   6.753s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |  17.475s  |  17.475s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   4.663s  |   4.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   0.991s  |   0.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     |   1.447s  |   1.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  30.282s  |  30.282s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   7.800s  |   7.800s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |  30.265s  |  30.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |  15.080s  |  15.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   4.029s  |   4.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     |  30.757s  |  30.757s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     |  30.194s  |  30.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     |  30.196s  |  30.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |  11.724s  |  11.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |   6.243s  |   6.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   2.002s  |   2.002s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       |  30.460s  |  30.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |  30.314s  |  30.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |   6.051s  |   6.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |  30.502s  |  30.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |   2.415s  |   2.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |   9.440s  |   9.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       |  30.390s  |  30.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   1.122s  |   1.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |  30.814s  |  30.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       |  30.542s  |  30.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |  30.175s  |  30.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |  30.275s  |  30.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   0.728s  |   0.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |  30.259s  |  30.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       |  30.153s  |  30.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   4.999s  |   4.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |  30.276s  |  30.276s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   7.692s  |   7.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   0.578s  |   0.578s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   1.122s  |   1.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   6.052s  |   6.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       |  30.339s  |  30.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       |  30.990s  |  30.990s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |  16.116s  |  16.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 |  30.396s  |  30.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |   9.342s  |   9.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |   3.023s  |   3.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  13.941s  |  13.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   7.329s  |   7.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |   6.357s  |   6.357s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  15.332s  |  15.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   1.371s  |   1.371s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |   5.808s  |   5.808s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  30.413s  |  30.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   2.965s  |   2.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |  17.074s  |  17.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  30.229s  |  30.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   1.534s  |   1.534s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |  12.795s  |  12.795s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            |  10.056s  |  10.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   6.700s  |   6.700s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   2.037s  |   2.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   1.329s  |   1.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   0.899s  |   0.899s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   1.727s  |   1.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   1.421s  |   1.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   6.177s  |   6.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |  30.279s  |  30.279s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   2.621s  |   2.621s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   1.253s  |   1.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   4.974s  |   4.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   1.776s  |   1.776s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |   8.492s  |   8.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   4.179s  |   4.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |  12.831s  |  12.831s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |   8.167s  |   8.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |   8.865s  |   8.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |   6.713s  |   6.713s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   8.991s  |   8.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   5.814s  |   5.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   0.745s  |   0.745s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   1.878s  |   1.878s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   0.676s  |   0.676s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  27.238s  |  27.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   2.342s  |   2.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |   6.390s  |   6.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |   2.886s  |   2.886s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   4.126s  |   4.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |  12.011s  |  12.011s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  30.475s  |  30.475s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   1.176s  |   1.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   1.469s  |   1.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   1.310s  |   1.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |  30.832s  |  30.832s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   1.670s  |   1.670s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   1.893s  |   1.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   8.698s  |   8.698s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   1.410s  |   1.410s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   7.803s  |   7.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   2.773s  |   2.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   5.401s  |   5.401s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   1.420s  |   1.420s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   5.748s  |   5.748s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |  13.147s  |  13.147s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   2.213s  |   2.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   2.156s  |   2.156s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   3.072s  |   3.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   1.258s  |   1.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   3.693s  |   3.693s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   8.969s  |   8.969s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   2.115s  |   2.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |   3.801s  |   3.801s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   4.126s  |   4.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   3.434s  |   3.434s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  30.296s  |  30.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |  10.232s  |  10.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |   5.379s  |   5.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   2.315s  |   2.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   3.050s  |   3.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   3.976s  |   3.976s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  20.185s  |  20.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |   7.022s  |   7.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   1.930s  |   1.930s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   4.113s  |   4.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  30.456s  |  30.456s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   2.344s  |   2.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   2.998s  |   2.998s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |  11.466s  |  11.466s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   5.020s  |   5.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   4.739s  |   4.739s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   4.719s  |   4.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |   3.253s  |   3.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |   5.394s  |   5.394s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   3.108s  |   3.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   0.763s  |   0.763s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   6.724s  |   6.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   2.598s  |   2.598s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   6.699s  |   6.699s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                |  30.449s  |  30.449s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |   2.525s  |   2.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  30.254s  |  30.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   1.954s  |   1.954s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |  30.406s  |  30.406s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  30.781s  |  30.781s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   3.224s  |   3.224s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   2.473s  |   2.473s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |  14.733s  |  14.733s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   1.807s  |   1.807s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   3.457s  |   3.457s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   2.558s  |   2.558s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  30.565s  |  30.565s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   5.711s  |   5.711s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |  14.448s  |  14.448s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   1.991s  |   1.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   2.161s  |   2.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   0.821s  |   0.821s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |   9.430s  |   9.430s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   1.385s  |   1.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |   7.341s  |   7.341s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   1.091s  |   1.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   0.773s  |   0.773s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   2.181s  |   2.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |  12.071s  |  12.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   4.149s  |   4.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   0.727s  |   0.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   7.096s  |   7.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   7.905s  |   7.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   5.749s  |   5.749s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   1.799s  |   1.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |   4.350s  |   4.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   3.068s  |   3.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   3.330s  |   3.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   4.451s  |   4.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   1.372s  |   1.372s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          |  30.726s  |  30.726s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          |  30.497s  |  30.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          |  30.712s  |  30.712s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   6.592s  |   6.592s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   1.783s  |   1.783s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             |  30.718s  |  30.718s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            |  30.479s  |  30.479s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            |  30.219s  |  30.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   1.790s  |   1.790s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   2.911s  |   2.911s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |  23.814s  |  23.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |  13.300s  |  13.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |  11.234s  |  11.234s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   1.249s  |   1.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |  30.167s  |  30.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |  23.958s  |  23.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      |  30.154s  |  30.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   1.058s  |   1.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |  12.423s  |  12.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |  30.560s  |  30.560s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   2.937s  |   2.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       |  30.633s  |  30.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   4.593s  |   4.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   1.504s  |   1.504s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   2.984s  |   2.984s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   |  30.197s  |  30.197s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |   9.873s  |   9.873s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |  11.886s  |  11.886s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |  10.448s  |  10.448s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |  30.166s  |  30.166s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |  19.406s  |  19.406s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   2.943s  |   2.943s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.859s  |   0.859s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   8.468s  |   8.468s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          |  30.282s  |  30.282s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          |  30.356s  |  30.356s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   1.599s  |   1.599s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   1.195s  |   1.195s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               |  30.642s  |  30.642s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               |  30.263s  |  30.263s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  23.519s  |  23.519s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               |  30.679s  |  30.679s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               |  30.194s  |  30.194s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   1.798s  |   1.798s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         |  30.207s  |  30.207s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         |  30.188s  |  30.188s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         |  30.218s  |  30.218s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |  30.273s  |  30.273s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               |  30.675s  |  30.675s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  30.185s  |  30.185s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   5.522s  |   5.522s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |  30.472s  |  30.472s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         |  30.519s  |  30.519s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |  10.535s  |  10.535s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   1.614s  |   1.614s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         |  30.730s  |  30.730s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  30.411s  |  30.411s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  30.202s  |  30.202s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    |  30.357s  |  30.357s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  30.389s  |  30.389s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    |  30.557s  |  30.557s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  22.723s  |  22.723s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  30.369s  |  30.369s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   8.955s  |   8.955s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              |  30.501s  |  30.501s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  30.229s  |  30.229s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |  30.694s  |  30.694s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |  30.442s  |  30.442s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  30.301s  |  30.301s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   1.692s  |   1.692s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |  10.567s  |  10.567s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |   8.471s  |   8.471s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |  30.795s  |  30.795s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   8.850s  |   8.850s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |  30.329s  |  30.329s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |  15.813s  |  15.813s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.647s  |   0.647s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  |  30.719s  |  30.719s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   2.201s  |   2.201s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  30.310s  |  30.310s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |  30.432s  |  30.432s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 |  30.383s  |  30.383s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  30.271s  |  30.271s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           |  30.408s  |  30.408s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |   6.549s  |   6.549s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |  30.154s  |  30.154s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              |  30.509s  |  30.509s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |  15.780s  |  15.780s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              |  30.295s  |  30.295s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              |  30.157s  |  30.157s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  30.898s  |  30.898s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              |  30.307s  |  30.307s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              |  30.273s  |  30.273s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |  30.318s  |  30.318s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              |  30.144s  |  30.144s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              |  30.521s  |  30.521s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |  30.576s  |  30.576s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  30.455s  |  30.455s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |  30.391s  |  30.391s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |  30.557s  |  30.557s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  30.193s  |  30.193s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  30.262s  |  30.262s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  30.458s  |  30.458s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  30.356s  |  30.356s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            |  30.284s  |  30.284s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |  30.281s  |  30.281s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             |  30.159s  |  30.159s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             |  30.195s  |  30.195s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             |  30.274s  |  30.274s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   2.009s  |   2.009s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             |  30.199s  |  30.199s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             |  30.218s  |  30.218s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   1.589s  |   1.589s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 |  30.548s  |  30.548s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   1.573s  |   1.573s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  |  30.341s  |  30.341s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |  11.463s  |  11.463s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |  30.184s  |  30.184s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             |  30.169s  |  30.169s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   0.773s  |   0.773s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |  11.417s  |  11.417s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |  13.006s  |  13.006s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   0.461s  |   0.461s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             |  30.177s  |  30.177s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   0.915s  |   0.915s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   0.976s  |   0.976s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   1.753s  |   1.753s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |  14.818s  |  14.818s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |  31.213s  |  31.213s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               |  31.101s  |  31.101s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   3.936s  |   3.936s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            |  30.438s  |  30.438s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |  30.170s  |  30.170s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 |  30.348s  |  30.348s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |   9.947s  |   9.947s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  30.250s  |  30.250s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |  14.747s  |  14.747s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           |  30.477s  |  30.477s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |  11.902s  |  11.902s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |  20.493s  |  20.493s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 |  30.223s  |  30.223s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      |  30.178s  |  30.178s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |   7.323s  |   7.323s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |  14.244s  |  14.244s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           |  30.291s  |  30.291s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  30.236s  |  30.236s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |  12.131s  |  12.131s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  30.533s  |  30.533s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              |  30.208s  |  30.208s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |  30.436s  |  30.436s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   2.260s  |   2.260s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   0.849s  |   0.849s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      |  30.471s  |  30.471s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               |  30.190s  |  30.190s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              |  30.332s  |  30.332s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   4.321s  |   4.321s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.704s  |   0.704s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       |  30.488s  |  30.488s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |   6.914s  |   6.914s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   1.134s  |   1.134s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       |  30.174s  |  30.174s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   1.096s  |   1.096s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       |  30.357s  |  30.357s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |   5.887s  |   5.887s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.809s  |   0.809s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       |  30.494s  |  30.494s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   1.495s  |   1.495s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |  30.557s  |  30.557s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |  20.854s  |  20.854s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.713s  |   0.713s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       |  30.324s  |  30.324s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |   2.189s  |   2.189s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       |  30.732s  |  30.732s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |  26.191s  |  26.191s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   1.661s  |   1.661s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       |  30.388s  |  30.388s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |   4.863s  |   4.863s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   1.451s  |   1.451s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   1.003s  |   1.003s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       |  30.482s  |  30.482s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       |  30.427s  |  30.427s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   5.240s  |   5.240s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |  16.965s  |  16.965s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       |  30.172s  |  30.172s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   5.338s  |   5.338s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   0.864s  |   0.864s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.745s  |   0.745s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               |  30.525s  |  30.525s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         |  30.161s  |  30.161s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   4.613s  |   4.613s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.821s  |   0.821s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |  15.095s  |  15.095s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   3.694s  |   3.694s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |   8.113s  |   8.113s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |   9.150s  |   9.150s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |   4.712s  |   4.712s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   6.048s  |   6.048s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   2.105s  |   2.105s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   2.365s  |   2.365s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                |  30.405s  |  30.405s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   1.523s  |   1.523s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   3.718s  |   3.718s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      |  30.635s  |  30.635s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   4.767s  |   4.767s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |  21.877s  |  21.877s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   3.188s  |   3.188s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   1.290s  |   1.290s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |  20.915s  |  20.915s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   0.813s  |   0.813s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |   1.958s  |   1.958s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.824s  |   0.824s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   2.442s  |   2.442s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      |  30.343s  |  30.343s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      |  30.175s  |  30.175s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   3.038s  |   3.038s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   0.752s  |   0.752s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   0.727s  |   0.727s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   2.110s  |   2.110s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |  28.296s  |  28.296s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |   7.644s  |   7.644s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   0.923s  |   0.923s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   0.953s  |   0.953s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   9.370s  |   9.370s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   0.671s  |   0.671s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   1.233s  |   1.233s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   2.080s  |   2.080s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |   1.154s  |   1.154s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   1.622s  |   1.622s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   6.648s  |   6.648s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      |  30.119s  |  30.119s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   2.186s  |   2.186s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      |  30.236s  |  30.236s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   1.002s  |   1.002s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   6.400s  |   6.400s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |  16.936s  |  16.936s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   1.562s  |   1.562s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      |  30.261s  |  30.261s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   3.189s  |   3.189s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |  10.409s  |  10.409s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |   2.122s  |   2.122s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   6.629s  |   6.629s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.748s  |   0.748s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   3.263s  |   3.263s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   1.168s  |   1.168s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   0.489s  |   0.489s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   4.863s  |   4.863s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   2.490s  |   2.490s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   2.810s  |   2.810s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   1.010s  |   1.010s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   1.641s  |   1.641s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   0.738s  |   0.738s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   0.853s  |   0.853s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |  30.287s  |  30.287s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            |  30.489s  |  30.489s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |  13.847s  |  13.847s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  30.270s  |  30.270s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |   9.859s  |   9.859s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  30.633s  |  30.633s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |  19.431s  |  19.431s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        |  30.990s  |  30.990s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        |  30.144s  |  30.144s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  30.345s  |  30.345s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       |  30.554s  |  30.554s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   4.943s  |   4.943s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   2.807s  |   2.807s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     |  30.423s  |  30.423s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     |  30.913s  |  30.913s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     |  30.316s  |  30.316s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |  15.305s  |  15.305s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         |  30.307s  |  30.307s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               |  30.716s  |  30.716s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         |  30.223s  |  30.223s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               |  30.498s  |  30.498s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |  14.650s  |  14.650s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               |  30.388s  |  30.388s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  |  30.519s  |  30.519s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |  30.430s  |  30.430s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     |  30.380s  |  30.380s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  30.399s  |  30.399s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  14.151s  |  14.151s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            |  30.253s  |  30.253s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            |  30.404s  |  30.404s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   5.698s  |   5.698s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   0.968s  |   0.968s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                |  30.648s  |  30.648s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  30.528s  |  30.528s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 |  30.894s  |  30.894s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 |  30.402s  |  30.402s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  30.827s  |  30.827s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 |  30.332s  |  30.332s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  20.262s  |  20.262s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |  10.743s  |  10.743s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           |  30.444s  |  30.444s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           |  30.246s  |  30.246s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           |  30.266s  |  30.266s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |  19.755s  |  19.755s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  30.119s  |  30.119s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |  30.290s  |  30.290s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   1.136s  |   1.136s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  30.159s  |  30.159s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  30.400s  |  30.400s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   4.065s  |   4.065s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 |  30.895s  |  30.895s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 |  30.394s  |  30.394s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |  23.310s  |  23.310s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  30.336s  |  30.336s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 |  30.288s  |  30.288s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   1.540s  |   1.540s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 |  30.202s  |  30.202s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |   2.385s  |   2.385s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  30.218s  |  30.218s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |  30.153s  |  30.153s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   2.492s  |   2.492s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   1.162s  |   1.162s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 |  30.313s  |  30.313s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  30.583s  |  30.583s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |   2.307s  |   2.307s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 |  31.018s  |  31.018s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 |  30.228s  |  30.228s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   9.139s  |   9.139s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |  30.339s  |  30.339s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 |  30.376s  |  30.376s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |  30.236s  |  30.236s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |  30.239s  |  30.239s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |  20.924s  |  20.924s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |  30.347s  |  30.347s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |   0.945s  |   0.945s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |  30.292s  |  30.292s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   4.387s  |   4.387s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   0.655s  |   0.655s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              |  30.508s  |  30.508s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  30.224s  |  30.224s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 |  30.290s  |  30.290s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  30.201s  |  30.201s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 |  30.159s  |  30.159s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  23.025s  |  23.025s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        |  30.389s  |  30.389s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  30.261s  |  30.261s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  30.696s  |  30.696s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |  30.165s  |  30.165s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           |  30.223s  |  30.223s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    |  30.798s  |  30.798s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    |  30.322s  |  30.322s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       |  30.177s  |  30.177s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       |  30.843s  |  30.843s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  30.451s  |  30.451s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  30.236s  |  30.236s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |  10.613s  |  10.613s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              |  30.618s  |  30.618s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  30.191s  |  30.191s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  30.624s  |  30.624s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  30.247s  |  30.247s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  30.212s  |  30.212s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  30.174s  |  30.174s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  |  30.391s  |  30.391s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  30.419s  |  30.419s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  30.200s  |  30.200s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |  30.505s  |  30.505s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  30.205s  |  30.205s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |  30.285s  |  30.285s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  30.187s  |  30.187s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            |  30.359s  |  30.359s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          |  30.216s  |  30.216s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  30.295s  |  30.295s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  30.998s  |  30.998s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  30.182s  |  30.182s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   8.185s  |   8.185s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        |  30.173s  |  30.173s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        |  30.184s  |  30.184s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |  30.194s  |  30.194s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        |  30.171s  |  30.171s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        |  30.328s  |  30.328s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        |  30.483s  |  30.483s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        |  23.177s  |  23.177s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        |  30.282s  |  30.282s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        |  30.461s  |  30.461s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  |  30.343s  |  30.343s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   0.964s  |   0.964s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |  30.400s  |  30.400s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.633s  |   0.633s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   1.359s  |   1.359s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |  30.706s  |  30.706s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |   7.943s  |   7.943s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 |  30.487s  |  30.487s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |  19.579s  |  19.579s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 |  30.810s  |  30.810s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 |  30.793s  |  30.793s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |   7.831s  |   7.831s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 |  30.188s  |  30.188s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 |  30.425s  |  30.425s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |  13.847s  |  13.847s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   2.991s  |   2.991s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |  30.188s  |  30.188s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   3.130s  |   3.130s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |   6.045s  |   6.045s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             |  30.243s  |  30.243s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             |  30.185s  |  30.185s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   9.226s  |   9.226s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             |  30.321s  |  30.321s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             |  30.248s  |  30.248s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   6.663s  |   6.663s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |  30.309s  |  30.309s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             |  30.367s  |  30.367s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |  29.653s  |  29.653s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             |  30.703s  |  30.703s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             |  30.283s  |  30.283s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   6.223s  |   6.223s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             |  30.240s  |  30.240s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             |  30.308s  |  30.308s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |  10.328s  |  10.328s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |  30.358s  |  30.358s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  |  30.311s  |  30.311s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   0.844s  |   0.844s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.586s  |   0.586s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   6.602s  |   6.602s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                |  30.543s  |  30.543s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   0.902s  |   0.902s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  30.302s  |  30.302s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           |  30.223s  |  30.223s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 |  30.412s  |  30.412s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   1.388s  |   1.388s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 |  30.190s  |  30.190s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 |  30.480s  |  30.480s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   0.870s  |   0.870s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 |  30.159s  |  30.159s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   4.310s  |   4.310s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           |  30.146s  |  30.146s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   6.898s  |   6.898s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 |  30.349s  |  30.349s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 |  30.230s  |  30.230s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           |  30.177s  |  30.177s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  |  30.551s  |  30.551s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |   4.208s  |   4.208s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 |  30.687s  |  30.687s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 |  30.323s  |  30.323s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   1.260s  |   1.260s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   3.880s  |   3.880s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |  30.855s  |  30.855s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 |  30.108s  |  30.108s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   6.753s  |   6.753s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 |  30.340s  |  30.340s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 |  30.507s  |  30.507s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   3.551s  |   3.551s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 |  30.239s  |  30.239s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   8.728s  |   8.728s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |  30.546s  |  30.546s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  |  30.598s  |  30.598s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   8.819s  |   8.819s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |   7.558s  |   7.558s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            |  30.181s  |  30.181s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  30.552s  |  30.552s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   1.553s  |   1.553s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  |  30.388s  |  30.388s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  |  30.478s  |  30.478s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            |  30.182s  |  30.182s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   1.975s  |   1.975s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 |  30.213s  |  30.213s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |  30.254s  |  30.254s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  |  30.207s  |  30.207s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   3.620s  |   3.620s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  |  30.087s  |  30.087s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  |  30.642s  |  30.642s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   3.835s  |   3.835s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  |  30.410s  |  30.410s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  |  30.236s  |  30.236s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   2.485s  |   2.485s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  |  30.831s  |  30.831s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  |  30.477s  |  30.477s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.984s  |   0.984s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |  23.689s  |  23.689s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            |  30.254s  |  30.254s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   2.410s  |   2.410s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |  30.183s  |  30.183s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   0.736s  |   0.736s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |   7.133s  |   7.133s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           |  30.890s  |  30.890s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           |  30.351s  |  30.351s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           |  30.588s  |  30.588s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  30.297s  |  30.297s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               |  30.353s  |  30.353s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               |  30.608s  |  30.608s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               |  30.756s  |  30.756s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               |  30.358s  |  30.358s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               |  30.403s  |  30.403s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |  30.248s  |  30.248s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |  30.998s  |  30.998s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  30.618s  |  30.618s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |  16.307s  |  16.307s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   8.030s  |   8.030s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   4.340s  |   4.340s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             |  30.410s  |  30.410s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |   9.881s  |   9.881s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |   9.325s  |   9.325s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |  10.259s  |  10.259s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  30.486s  |  30.486s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  30.440s  |  30.440s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    |  30.243s  |  30.243s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   4.618s  |   4.618s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               |  30.168s  |  30.168s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             |  30.229s  |  30.229s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   6.899s  |   6.899s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             |  30.222s  |  30.222s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             |  30.202s  |  30.202s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   5.275s  |   5.275s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             |  30.255s  |  30.255s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             |  30.769s  |  30.769s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  28.834s  |  28.834s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |   7.259s  |   7.259s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               |  30.221s  |  30.221s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         |  30.992s  |  30.992s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  26.593s  |  26.593s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  30.216s  |  30.216s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  30.537s  |  30.537s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  15.175s  |  15.175s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  30.148s  |  30.148s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        |  30.281s  |  30.281s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            |  13.054s  |  13.054s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            |  30.613s  |  30.613s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   1.404s  |   1.404s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |  30.174s  |  30.174s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   0.947s  |   0.947s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            |   3.447s  |   3.447s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   1.123s  |   1.123s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  30.121s  |  30.121s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              |  30.230s  |  30.230s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  30.230s  |  30.230s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              |  25.205s  |  25.205s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   1.401s  |   1.401s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  30.303s  |  30.303s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          |  30.446s  |  30.446s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   0.575s  |   0.575s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |   2.397s  |   2.397s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  30.572s  |  30.572s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       |  30.319s  |  30.319s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   1.012s  |   1.012s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       |   3.178s  |   3.178s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |  13.355s  |  13.355s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |  30.229s  |  30.229s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |  10.967s  |  10.967s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |   7.824s  |   7.824s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  |  30.199s  |  30.199s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            |  30.260s  |  30.260s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              |  21.132s  |  21.132s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   0.885s  |   0.885s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   1.490s  |   1.490s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |   8.837s  |   8.837s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          |  30.441s  |  30.441s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          |  30.496s  |  30.496s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |  12.452s  |  12.452s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          |  30.252s  |  30.252s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          |  30.910s  |  30.910s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |  14.445s  |  14.445s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          |  30.217s  |  30.217s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          |  30.158s  |  30.158s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |  16.010s  |  16.010s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                |  30.391s  |  30.391s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                |  30.916s  |  30.916s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   7.100s  |   7.100s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                |  30.281s  |  30.281s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                |  30.196s  |  30.196s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |  10.145s  |  10.145s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                |  30.279s  |  30.279s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                |  30.514s  |  30.514s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |  18.281s  |  18.281s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                |  30.524s  |  30.524s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                |  30.408s  |  30.408s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          |  30.240s  |  30.240s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |  25.036s  |  25.036s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          |  30.301s  |  30.301s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   5.936s  |   5.936s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |  30.223s  |  30.223s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          |  30.363s  |  30.363s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |  30.747s  |  30.747s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                |  30.865s  |  30.865s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   2.112s  |   2.112s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   1.218s  |   1.218s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |   4.417s  |   4.417s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |   3.804s  |   3.804s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |   6.667s  |   6.667s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   1.170s  |   1.170s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                |  30.320s  |  30.320s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   1.813s  |   1.813s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |  10.495s  |  10.495s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                |  30.391s  |  30.391s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                |   5.554s  |   5.554s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |   6.852s  |   6.852s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |   7.322s  |   7.322s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   1.360s  |   1.360s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                |  30.246s  |  30.246s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   1.079s  |   1.079s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   5.058s  |   5.058s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                |  30.306s  |  30.306s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   0.766s  |   0.766s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |  12.005s  |  12.005s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   2.039s  |   2.039s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |   8.097s  |   8.097s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |   9.984s  |   9.984s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   0.872s  |   0.872s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                |  30.393s  |  30.393s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   7.783s  |   7.783s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   1.244s  |   1.244s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |  11.499s  |  11.499s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                |  30.353s  |  30.353s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                |  30.333s  |  30.333s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |  19.871s  |  19.871s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   8.211s  |   8.211s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   2.548s  |   2.548s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |  10.578s  |  10.578s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          |  30.286s  |  30.286s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |   2.531s  |   2.531s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   0.669s  |   0.669s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |   7.340s  |   7.340s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |  27.512s  |  27.512s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |  13.115s  |  13.115s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   6.520s  |   6.520s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   1.410s  |   1.410s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   8.566s  |   8.566s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          |  30.201s  |  30.201s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   0.865s  |   0.865s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   4.814s  |   4.814s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   5.166s  |   5.166s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   9.140s  |   9.140s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |   3.611s  |   3.611s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |   2.279s  |   2.279s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          |  30.155s  |  30.155s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          |  30.362s  |  30.362s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          |  31.267s  |  31.267s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          |  30.164s  |  30.164s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |   8.293s  |   8.293s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   1.755s  |   1.755s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          |   2.080s  |   2.080s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  30.236s  |  30.236s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |  30.437s  |  30.437s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |   5.874s  |   5.874s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           |  30.381s  |  30.381s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           |  30.261s  |  30.261s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |  17.928s  |  17.928s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   1.974s  |   1.974s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        |  30.526s  |  30.526s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |   2.573s  |   2.573s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |   7.843s  |   7.843s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   1.569s  |   1.569s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |   4.712s  |   4.712s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   3.040s  |   3.040s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |  14.534s  |  14.534s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        |  30.352s  |  30.352s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   1.928s  |   1.928s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |   3.596s  |   3.596s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |   8.406s  |   8.406s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   1.072s  |   1.072s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |   6.905s  |   6.905s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |   1.034s  |   1.034s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   5.525s  |   5.525s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |  12.385s  |  12.385s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   0.841s  |   0.841s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   1.432s  |   1.432s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |  11.100s  |  11.100s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        |  30.208s  |  30.208s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   2.266s  |   2.266s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   1.096s  |   1.096s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |  10.217s  |  10.217s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   1.593s  |   1.593s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |  11.854s  |  11.854s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        |  30.149s  |  30.149s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   1.617s  |   1.617s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        |  30.447s  |  30.447s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |   7.002s  |   7.002s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   8.819s  |   8.819s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.902s  |   0.902s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   0.703s  |   0.703s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        |  30.370s  |  30.370s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        |  30.289s  |  30.289s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   1.482s  |   1.482s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |   2.502s  |   2.502s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        |   9.273s  |   9.273s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |  30.425s  |  30.425s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            |  30.362s  |  30.362s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  |  30.428s  |  30.428s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  |  30.243s  |  30.243s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |  28.167s  |  28.167s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  |  30.600s  |  30.600s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  |  30.178s  |  30.178s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   5.813s  |   5.813s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   6.857s  |   6.857s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   8.911s  |   8.911s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   1.604s  |   1.604s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  |  30.259s  |  30.259s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |   5.202s  |   5.202s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  |  30.764s  |  30.764s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  |  30.322s  |  30.322s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   3.293s  |   3.293s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |   5.744s  |   5.744s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                |  30.235s  |  30.235s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  30.212s  |  30.212s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   3.548s  |   3.548s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              |   2.871s  |   2.871s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        |  30.647s  |  30.647s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   |  30.336s  |  30.336s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   |  30.263s  |  30.263s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |  25.939s  |  25.939s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   |  30.290s  |  30.290s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   |  30.307s  |  30.307s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |  30.147s  |  30.147s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   |  30.251s  |  30.251s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   |  30.267s  |  30.267s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |  30.813s  |  30.813s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   |  30.157s  |  30.157s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         |  30.203s  |  30.203s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |  18.975s  |  18.975s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   0.843s  |   0.843s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |  23.581s  |  23.581s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         |  30.299s  |  30.299s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |  18.127s  |  18.127s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        |  30.718s  |  30.718s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        |  30.936s  |  30.936s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |  22.761s  |  22.761s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        |  30.298s  |  30.298s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        |  30.492s  |  30.492s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |  24.027s  |  24.027s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        |  30.471s  |  30.471s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   1.923s  |   1.923s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   2.961s  |   2.961s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  30.269s  |  30.269s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   1.331s  |   1.331s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |  18.547s  |  18.547s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  30.395s  |  30.395s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |  30.389s  |  30.389s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |  15.270s  |  15.270s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            |  30.313s  |  30.313s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            |  30.689s  |  30.689s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |  17.195s  |  17.195s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            |  30.523s  |  30.523s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            |  30.194s  |  30.194s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |  29.435s  |  29.435s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            |  30.162s  |  30.162s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  |  30.247s  |  30.247s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   1.229s  |   1.229s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  |  30.246s  |  30.246s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   1.015s  |   1.015s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            |  30.523s  |  30.523s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  16.929s  |  16.929s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  30.436s  |  30.436s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  30.238s  |  30.238s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  30.466s  |  30.466s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   1.790s  |   1.790s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |  30.355s  |  30.355s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         |  30.730s  |  30.730s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   4.093s  |   4.093s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         |  30.176s  |  30.176s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |   6.143s  |   6.143s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |  18.652s  |  18.652s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |  13.594s  |  13.594s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   2.856s  |   2.856s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         |  30.376s  |  30.376s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   6.073s  |   6.073s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   3.499s  |   3.499s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   4.721s  |   4.721s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   2.686s  |   2.686s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   3.932s  |   3.932s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   1.684s  |   1.684s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |  12.355s  |  12.355s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   |  30.389s  |  30.389s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           |  30.546s  |  30.546s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           |  30.196s  |  30.196s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           |  30.375s  |  30.375s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   1.742s  |   1.742s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |  30.476s  |  30.476s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           |   7.834s  |   7.834s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           |  30.375s  |  30.375s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           |  23.695s  |  23.695s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  |  30.255s  |  30.255s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   9.420s  |   9.420s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   2.381s  |   2.381s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   1.208s  |   1.208s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   1.205s  |   1.205s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   1.228s  |   1.228s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             |  30.211s  |  30.211s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   0.835s  |   0.835s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   3.986s  |   3.986s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   2.819s  |   2.819s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |  30.383s  |  30.383s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             |  30.293s  |  30.293s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   0.996s  |   0.996s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |  30.148s  |  30.148s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             |  30.428s  |  30.428s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   0.692s  |   0.692s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   1.329s  |   1.329s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |  14.263s  |  14.263s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             |  30.212s  |  30.212s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   1.864s  |   1.864s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |  30.320s  |  30.320s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             |  30.287s  |  30.287s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   6.862s  |   6.862s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |  16.709s  |  16.709s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              |  30.321s  |  30.321s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      |  30.217s  |  30.217s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   5.641s  |   5.641s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          |  30.302s  |  30.302s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                |  30.562s  |  30.562s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |  30.319s  |  30.319s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |  24.396s  |  24.396s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                |  30.175s  |  30.175s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                |  30.307s  |  30.307s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                |  30.301s  |  30.301s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                |  30.236s  |  30.236s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  30.432s  |  30.432s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  30.431s  |  30.431s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          |  30.293s  |  30.293s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |  30.530s  |  30.530s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   4.619s  |   4.619s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   2.756s  |   2.756s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              |  30.716s  |  30.716s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       |  30.477s  |  30.477s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       |  30.477s  |  30.477s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  30.191s  |  30.191s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  30.182s  |  30.182s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  30.248s  |  30.248s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  30.173s  |  30.173s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           |  30.315s  |  30.315s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  30.187s  |  30.187s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  18.663s  |  18.663s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             |  30.198s  |  30.198s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  30.153s  |  30.153s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |  30.408s  |  30.408s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  25.693s  |  25.693s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  30.352s  |  30.352s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  30.486s  |  30.486s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |  30.269s  |  30.269s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  30.220s  |  30.220s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  30.179s  |  30.179s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           |  30.300s  |  30.300s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           |  30.337s  |  30.337s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |  30.188s  |  30.188s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  30.200s  |  30.200s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 |  30.478s  |  30.478s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 |  30.263s  |  30.263s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   5.691s  |   5.691s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |  30.889s  |  30.889s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                |  30.372s  |  30.372s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                |  30.280s  |  30.280s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  30.260s  |  30.260s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  30.282s  |  30.282s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          |  30.315s  |  30.315s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          |  30.309s  |  30.309s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          |  30.620s  |  30.620s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |  30.245s  |  30.245s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  30.233s  |  30.233s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     |  30.081s  |  30.081s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   2.488s  |   2.488s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                |  30.626s  |  30.626s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                |  30.700s  |  30.700s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   1.822s  |   1.822s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |  28.450s  |  28.450s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            |   5.021s  |   5.021s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |  30.560s  |  30.560s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   0.742s  |   0.742s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.762s  |   0.762s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  30.161s  |  30.161s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   4.601s  |   4.601s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |   0.976s  |   0.976s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   0.690s  |   0.690s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   0.618s  |   0.618s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |  30.604s  |  30.604s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   1.723s  |   1.723s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            |  30.508s  |  30.508s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      |  30.296s  |  30.296s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   0.842s  |   0.842s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      |  30.625s  |  30.625s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   3.343s  |   3.343s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   1.893s  |   1.893s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  13.562s  |  13.562s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |  30.185s  |  30.185s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  30.218s  |  30.218s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   3.048s  |   3.048s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |  30.236s  |  30.236s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |   7.975s  |   7.975s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.756s  |   0.756s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.613s  |   0.613s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  30.287s  |  30.287s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  30.346s  |  30.346s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |   6.713s  |   6.713s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  |  30.596s  |  30.596s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |   7.596s  |   7.596s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           |  30.450s  |  30.450s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      |  30.152s  |  30.152s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |  10.413s  |  10.413s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      |  30.214s  |  30.214s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           |  30.227s  |  30.227s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           |  30.506s  |  30.506s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        |  30.363s  |  30.363s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   9.749s  |   9.749s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   2.535s  |   2.535s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   1.378s  |   1.378s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |  30.735s  |  30.735s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   1.418s  |   1.418s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   1.336s  |   1.336s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   7.587s  |   7.587s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  15.114s  |  15.114s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |  17.035s  |  17.035s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   2.292s  |   2.292s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        |  30.290s  |  30.290s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   0.753s  |   0.753s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   1.618s  |   1.618s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |  30.486s  |  30.486s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   2.157s  |   2.157s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |  30.219s  |  30.219s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   5.654s  |   5.654s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   0.981s  |   0.981s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.723s  |   0.723s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   0.545s  |   0.545s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |  30.445s  |  30.445s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  11.847s  |  11.847s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |   5.258s  |   5.258s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.593s  |   0.593s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   8.512s  |   8.512s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  30.383s  |  30.383s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  30.154s  |  30.154s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   2.582s  |   2.582s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |  30.163s  |  30.163s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   1.022s  |   1.022s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   0.746s  |   0.746s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |  19.019s  |  19.019s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                |  30.166s  |  30.166s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                |  30.357s  |  30.357s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   2.125s  |   2.125s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          |  30.259s  |  30.259s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   3.162s  |   3.162s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   1.227s  |   1.227s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |   2.177s  |   2.177s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |  30.285s  |  30.285s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |  30.203s  |  30.203s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.617s  |   0.617s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  15.977s  |  15.977s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                |  30.216s  |  30.216s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |   0.638s  |   0.638s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  16.135s  |  16.135s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   1.825s  |   1.825s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |  30.453s  |  30.453s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  26.217s  |  26.217s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |  30.163s  |  30.163s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |  30.396s  |  30.396s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   1.678s  |   1.678s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   6.454s  |   6.454s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  23.624s  |  23.624s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       |  30.150s  |  30.150s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       |  30.518s  |  30.518s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |  15.040s  |  15.040s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       |  30.534s  |  30.534s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       |  30.256s  |  30.256s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       |  30.302s  |  30.302s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       |  30.472s  |  30.472s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |  18.312s  |  18.312s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   1.541s  |   1.541s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   0.992s  |   0.992s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       |  30.287s  |  30.287s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       |  30.431s  |  30.431s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     |  30.190s  |  30.190s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   5.420s  |   5.420s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  30.181s  |  30.181s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   1.533s  |   1.533s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |  11.828s  |  11.828s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   0.753s  |   0.753s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |   7.147s  |   7.147s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   1.361s  |   1.361s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |  30.211s  |  30.211s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   9.892s  |   9.892s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        |  30.134s  |  30.134s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        |  30.548s  |  30.548s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |  30.210s  |  30.210s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  30.135s  |  30.135s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  |  30.343s  |  30.343s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  |  30.405s  |  30.405s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   1.288s  |   1.288s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.841s  |   0.841s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   1.170s  |   1.170s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  30.148s  |  30.148s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   1.541s  |   1.541s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.753s  |   0.753s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |  19.797s  |  19.797s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   3.843s  |   3.843s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           |  30.718s  |  30.718s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           |  30.276s  |  30.276s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   0.910s  |   0.910s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |  16.380s  |  16.380s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |  16.364s  |  16.364s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   1.088s  |   1.088s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.462s  |   0.462s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |  30.554s  |  30.554s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.593s  |   0.593s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   1.976s  |   1.976s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           |  30.257s  |  30.257s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   1.543s  |   1.543s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   2.997s  |   2.997s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           |  30.674s  |  30.674s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.632s  |   0.632s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.904s  |   0.904s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           |  30.188s  |  30.188s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   2.757s  |   2.757s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   6.023s  |   6.023s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   0.784s  |   0.784s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.462s  |   0.462s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   2.873s  |   2.873s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   0.810s  |   0.810s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   1.157s  |   1.157s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.852s  |   0.852s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |  30.716s  |  30.716s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.618s  |   0.618s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.706s  |   0.706s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.721s  |   0.721s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |  30.515s  |  30.515s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.753s  |   0.753s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   1.530s  |   1.530s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   2.111s  |   2.111s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.866s  |   0.866s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |  30.895s  |  30.895s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |  30.280s  |  30.280s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   8.374s  |   8.374s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           |  30.451s  |  30.451s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.562s  |   0.562s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           |  30.487s  |  30.487s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   5.482s  |   5.482s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |  30.252s  |  30.252s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   1.212s  |   1.212s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   1.505s  |   1.505s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   1.071s  |   1.071s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   1.723s  |   1.723s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |  18.134s  |  18.134s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   0.692s  |   0.692s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           |  30.207s  |  30.207s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   2.787s  |   2.787s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   2.327s  |   2.327s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |  30.249s  |  30.249s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.951s  |   0.951s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.790s  |   0.790s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.908s  |   0.908s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   1.263s  |   1.263s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |  19.467s  |  19.467s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |  21.700s  |  21.700s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.924s  |   0.924s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.796s  |   0.796s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   1.219s  |   1.219s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.462s  |   0.462s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.666s  |   0.666s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   3.474s  |   3.474s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   7.306s  |   7.306s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |  30.364s  |  30.364s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   2.462s  |   2.462s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |   1.453s  |   1.453s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.803s  |   0.803s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   1.025s  |   1.025s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   1.131s  |   1.131s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |  30.734s  |  30.734s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.960s  |   0.960s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   1.007s  |   1.007s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   0.792s  |   0.792s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   1.354s  |   1.354s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  30.263s  |  30.263s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |  30.610s  |  30.610s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |  30.206s  |  30.206s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   2.455s  |   2.455s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.815s  |   0.815s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   1.151s  |   1.151s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   1.135s  |   1.135s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.762s  |   0.762s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   6.037s  |   6.037s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |  30.279s  |  30.279s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   1.474s  |   1.474s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |  21.734s  |  21.734s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  30.250s  |  30.250s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           |  30.176s  |  30.176s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |  30.178s  |  30.178s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   1.006s  |   1.006s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  30.273s  |  30.273s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   1.516s  |   1.516s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   1.049s  |   1.049s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   3.421s  |   3.421s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |  30.179s  |  30.179s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   1.215s  |   1.215s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   4.255s  |   4.255s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   3.208s  |   3.208s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   8.448s  |   8.448s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |  30.745s  |  30.745s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |  30.774s  |  30.774s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.763s  |   0.763s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |  30.234s  |  30.234s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   1.681s  |   1.681s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   5.727s  |   5.727s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   6.672s  |   6.672s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           |  30.150s  |  30.150s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |  30.277s  |  30.277s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   1.431s  |   1.431s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |  30.128s  |  30.128s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.633s  |   0.633s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           |  30.325s  |  30.325s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.768s  |   0.768s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   1.548s  |   1.548s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   3.813s  |   3.813s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |  21.077s  |  21.077s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.843s  |   0.843s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           |  30.692s  |  30.692s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |  12.793s  |  12.793s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |  30.420s  |  30.420s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |  16.731s  |  16.731s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |  20.380s  |  20.380s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.768s  |   0.768s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   8.030s  |   8.030s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |  24.051s  |  24.051s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   4.244s  |   4.244s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.706s  |   0.706s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           |  30.212s  |  30.212s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.737s  |   0.737s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  30.156s  |  30.156s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.778s  |   0.778s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.822s  |   0.822s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.563s  |   0.563s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.850s  |   0.850s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   1.578s  |   1.578s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   1.048s  |   1.048s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   2.759s  |   2.759s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |  26.631s  |  26.631s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |  19.575s  |  19.575s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   1.479s  |   1.479s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   3.184s  |   3.184s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.713s  |   0.713s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |  20.890s  |  20.890s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |  30.471s  |  30.471s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |  30.384s  |  30.384s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.869s  |   0.869s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   1.427s  |   1.427s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   2.040s  |   2.040s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   1.159s  |   1.159s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   0.674s  |   0.674s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.925s  |   0.925s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   1.537s  |   1.537s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.770s  |   0.770s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.924s  |   0.924s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   0.545s  |   0.545s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   1.256s  |   1.256s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.859s  |   0.859s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.603s  |   0.603s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.890s  |   0.890s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            |  30.617s  |  30.617s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.674s  |   0.674s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |   4.837s  |   4.837s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   1.073s  |   1.073s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            |  30.143s  |  30.143s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.648s  |   0.648s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            |  30.262s  |  30.262s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            |  30.894s  |  30.894s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.563s  |   0.563s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            |   4.523s  |   4.523s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            |  30.262s  |  30.262s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.918s  |   0.918s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.422s  |   0.422s  |   0.000s  | 0.0%|
</details>
