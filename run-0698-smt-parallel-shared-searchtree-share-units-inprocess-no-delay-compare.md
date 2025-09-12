Comparing data and data


# SUMMARY
- LHS tests = 2313
- RHS tests = 2313
- LHS success = 2112  (91.30998702983139%)
- RHS success = 2112  (91.30998702983139%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-parallel-shared-searchtree-share-units-inprocess-no-delay
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: ea4bec9d039a2b61ad7102c7b62038a4178a1ba8
Z3 branch: ilana
Z3 options: "-T:30 tactic.default_tactic=smt smt.threads=4 smt_parallel.searchtree=true smt_parallel.share_conflicts=false smt_parallel.share_units=true smt_parallel.cube_initial_only=true smt_parallel.inprocessing=true smt_parallel.inprocessing_delay=0"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: internalize assertions during simplify

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-parallel-shared-searchtree-share-units-inprocess-no-delay
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: ea4bec9d039a2b61ad7102c7b62038a4178a1ba8
Z3 branch: ilana
Z3 options: "-T:30 tactic.default_tactic=smt smt.threads=4 smt_parallel.searchtree=true smt_parallel.share_conflicts=false smt_parallel.share_units=true smt_parallel.cube_initial_only=true smt_parallel.inprocessing=true smt_parallel.inprocessing_delay=0"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: internalize assertions during simplify

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  30.553s |3257.0MiB|
|185.smt2                                                                                   |  30.507s |3732.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  30.469s |3286.0MiB|
|183.smt2                                                                                   |  30.327s |2164.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.304s |2167.0MiB|
|182.smt2                                                                                   |  30.302s |2074.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  30.270s |1476.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  30.257s |1823.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  30.255s |2172.0MiB|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                |  30.228s |1522.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                        |  30.217s |1334.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                    |  30.207s |1559.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  30.199s |1344.0MiB|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                 |  30.193s |1298.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          |  30.161s |1162.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              |  30.156s |1032.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  30.144s |1050.0MiB|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                 |  30.142s |855.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2             |  30.115s |696.0MiB|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                           |  30.115s |737.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  30.553s |3257.0MiB|
|185.smt2                                                                                   |  30.507s |3732.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  30.469s |3286.0MiB|
|183.smt2                                                                                   |  30.327s |2164.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.304s |2167.0MiB|
|182.smt2                                                                                   |  30.302s |2074.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  30.270s |1476.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  30.257s |1823.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  30.255s |2172.0MiB|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                |  30.228s |1522.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                        |  30.217s |1334.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                    |  30.207s |1559.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  30.199s |1344.0MiB|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                 |  30.193s |1298.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          |  30.161s |1162.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              |  30.156s |1032.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  30.144s |1050.0MiB|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                 |  30.142s |855.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2             |  30.115s |696.0MiB|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                           |  30.115s |737.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |119.0MiB|119.0MiB|0B| 0.0%|
|04.smt2                                                                                     |113.0MiB|113.0MiB|0B| 0.0%|
|1.smt2                                                                                      |123.0MiB|123.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |116.0MiB|116.0MiB|0B| 0.0%|
|1010.smt2                                                                                   |115.0MiB|115.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1021.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1034.smt2                                                                                   |100.0MiB|100.0MiB|0B| 0.0%|
|1063.smt2                                                                                   |105.0MiB|105.0MiB|0B| 0.0%|
|107.smt2                                                                                    |97.048MiB|97.048MiB|0B| 0.0%|
|1082.smt2                                                                                   |109.0MiB|109.0MiB|0B| 0.0%|
|1085.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |99.016MiB|99.016MiB|0B| 0.0%|
|1090.smt2                                                                                   |99.168MiB|99.168MiB|0B| 0.0%|
|1092.smt2                                                                                   |98.848MiB|98.848MiB|0B| 0.0%|
|11.smt2                                                                                     |109.0MiB|109.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |99.612MiB|99.612MiB|0B| 0.0%|
|1112.smt2                                                                                   |97.0MiB|97.0MiB|0B| 0.0%|
|1113.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1126.smt2                                                                                   |99.0MiB|99.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |119.0MiB|119.0MiB|0B| 0.0%|
|04.smt2                                                                                     |113.0MiB|113.0MiB|0B| 0.0%|
|1.smt2                                                                                      |123.0MiB|123.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |116.0MiB|116.0MiB|0B| 0.0%|
|1010.smt2                                                                                   |115.0MiB|115.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1021.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1034.smt2                                                                                   |100.0MiB|100.0MiB|0B| 0.0%|
|1063.smt2                                                                                   |105.0MiB|105.0MiB|0B| 0.0%|
|107.smt2                                                                                    |97.048MiB|97.048MiB|0B| 0.0%|
|1082.smt2                                                                                   |109.0MiB|109.0MiB|0B| 0.0%|
|1085.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |99.016MiB|99.016MiB|0B| 0.0%|
|1090.smt2                                                                                   |99.168MiB|99.168MiB|0B| 0.0%|
|1092.smt2                                                                                   |98.848MiB|98.848MiB|0B| 0.0%|
|11.smt2                                                                                     |109.0MiB|109.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |99.612MiB|99.612MiB|0B| 0.0%|
|1112.smt2                                                                                   |97.0MiB|97.0MiB|0B| 0.0%|
|1113.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1126.smt2                                                                                   |99.0MiB|99.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |119.0MiB|119.0MiB|0B| 0.0%|
|04.smt2                                                                                     |113.0MiB|113.0MiB|0B| 0.0%|
|1.smt2                                                                                      |123.0MiB|123.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |116.0MiB|116.0MiB|0B| 0.0%|
|1010.smt2                                                                                   |115.0MiB|115.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1021.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1034.smt2                                                                                   |100.0MiB|100.0MiB|0B| 0.0%|
|1063.smt2                                                                                   |105.0MiB|105.0MiB|0B| 0.0%|
|107.smt2                                                                                    |97.048MiB|97.048MiB|0B| 0.0%|
|1082.smt2                                                                                   |109.0MiB|109.0MiB|0B| 0.0%|
|1085.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |99.016MiB|99.016MiB|0B| 0.0%|
|1090.smt2                                                                                   |99.168MiB|99.168MiB|0B| 0.0%|
|1092.smt2                                                                                   |98.848MiB|98.848MiB|0B| 0.0%|
|11.smt2                                                                                     |109.0MiB|109.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |99.612MiB|99.612MiB|0B| 0.0%|
|1112.smt2                                                                                   |97.0MiB|97.0MiB|0B| 0.0%|
|1113.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1126.smt2                                                                                   |99.0MiB|99.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |119.0MiB|119.0MiB|0B| 0.0%|
|04.smt2                                                                                     |113.0MiB|113.0MiB|0B| 0.0%|
|1.smt2                                                                                      |123.0MiB|123.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |116.0MiB|116.0MiB|0B| 0.0%|
|1010.smt2                                                                                   |115.0MiB|115.0MiB|0B| 0.0%|
|1018.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1021.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1034.smt2                                                                                   |100.0MiB|100.0MiB|0B| 0.0%|
|1063.smt2                                                                                   |105.0MiB|105.0MiB|0B| 0.0%|
|107.smt2                                                                                    |97.048MiB|97.048MiB|0B| 0.0%|
|1082.smt2                                                                                   |109.0MiB|109.0MiB|0B| 0.0%|
|1085.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1089.smt2                                                                                   |99.016MiB|99.016MiB|0B| 0.0%|
|1090.smt2                                                                                   |99.168MiB|99.168MiB|0B| 0.0%|
|1092.smt2                                                                                   |98.848MiB|98.848MiB|0B| 0.0%|
|11.smt2                                                                                     |109.0MiB|109.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |99.612MiB|99.612MiB|0B| 0.0%|
|1112.smt2                                                                                   |97.0MiB|97.0MiB|0B| 0.0%|
|1113.smt2                                                                                   |98.0MiB|98.0MiB|0B| 0.0%|
|1126.smt2                                                                                   |99.0MiB|99.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|185.smt2                                                                                   |  30.507s |3732.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  30.469s |3286.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  30.553s |3257.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  30.255s |2172.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.304s |2167.0MiB|
|183.smt2                                                                                   |  30.327s |2164.0MiB|
|182.smt2                                                                                   |  30.302s |2074.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  30.257s |1823.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                    |  30.207s |1559.0MiB|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                |  30.228s |1522.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  30.270s |1476.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  30.199s |1344.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                        |  30.217s |1334.0MiB|
|181.smt2                                                                                   |  28.708s |1320.0MiB|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                 |  30.193s |1298.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          |  30.161s |1162.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  30.144s |1050.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  20.322s |1035.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              |  30.156s |1032.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  19.752s |1010.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|185.smt2                                                                                   |  30.507s |3732.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  30.469s |3286.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  30.553s |3257.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  30.255s |2172.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  30.304s |2167.0MiB|
|183.smt2                                                                                   |  30.327s |2164.0MiB|
|182.smt2                                                                                   |  30.302s |2074.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  30.257s |1823.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                    |  30.207s |1559.0MiB|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                |  30.228s |1522.0MiB|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                              |  30.270s |1476.0MiB|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                |  30.199s |1344.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                        |  30.217s |1334.0MiB|
|181.smt2                                                                                   |  28.708s |1320.0MiB|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                 |  30.193s |1298.0MiB|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                          |  30.161s |1162.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  30.144s |1050.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  20.322s |1035.0MiB|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                              |  30.156s |1032.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  19.752s |1010.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |   1.043s  |   1.043s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |   2.724s  |   2.724s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |   4.331s  |   4.331s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  28.708s  |  28.708s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  30.302s  |  30.302s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  30.327s  |  30.327s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  30.507s  |  30.507s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   1.466s  |   1.466s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   2.268s  |   2.268s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|966.smt2                                                                                    |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          |   3.837s  |   3.837s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |   3.997s  |   3.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |   1.415s  |   1.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   0.546s  |   0.546s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            |   5.124s  |   5.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       |   1.507s  |   1.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |   4.952s  |   4.952s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   1.275s  |   1.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           |   3.445s  |   3.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           |   3.901s  |   3.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |   7.626s  |   7.626s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   3.169s  |   3.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |   1.586s  |   1.586s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   1.315s  |   1.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |   1.631s  |   1.631s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         |   3.064s  |   3.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             |  13.244s  |  13.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             |   0.951s  |   0.951s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 |   1.361s  |   1.361s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   0.770s  |   0.770s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |   1.757s  |   1.757s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               |   1.463s  |   1.463s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         |   1.180s  |   1.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   2.035s  |   2.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |   0.951s  |   0.951s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 |   1.390s  |   1.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   1.622s  |   1.622s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              |   2.248s  |   2.248s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   1.421s  |   1.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   1.028s  |   1.028s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          |   2.531s  |   2.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   0.824s  |   0.824s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         |   1.444s  |   1.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      |   5.762s  |   5.762s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   1.394s  |   1.394s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   1.088s  |   1.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         |   1.005s  |   1.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      |   1.440s  |   1.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |   2.966s  |   2.966s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |   4.168s  |   4.168s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           |   1.386s  |   1.386s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               |   2.572s  |   2.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               |   2.146s  |   2.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |   1.102s  |   1.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   |   1.424s  |   1.424s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   |   0.814s  |   0.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   |   2.073s  |   2.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             |   2.099s  |   2.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |   1.544s  |   1.544s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    |   4.499s  |   4.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |   3.876s  |   3.876s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        |   1.162s  |   1.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     |   1.080s  |   1.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               |   1.097s  |   1.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   1.000s  |   1.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   0.703s  |   0.703s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                |   3.315s  |   3.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              |   3.599s  |   3.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |   1.007s  |   1.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   1.584s  |   1.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |   1.303s  |   1.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |   1.879s  |   1.879s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          |   1.690s  |   1.690s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          |   3.533s  |   3.533s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          |   4.315s  |   4.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |   2.645s  |   2.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          |   4.136s  |   4.136s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          |  11.025s  |  11.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |   1.959s  |   1.959s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    |   7.806s  |   7.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   1.115s  |   1.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   1.852s  |   1.852s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    |   4.726s  |   4.726s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   1.986s  |   1.986s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   2.108s  |   2.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |   1.750s  |   1.750s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        |   1.522s  |   1.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |   1.162s  |   1.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        |   1.186s  |   1.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |   2.069s  |   2.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |   1.705s  |   1.705s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |   3.786s  |   3.786s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              |   1.487s  |   1.487s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |   1.240s  |   1.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |   1.432s  |   1.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   0.865s  |   0.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |   1.587s  |   1.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |   0.913s  |   0.913s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   |   1.368s  |   1.368s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   |   1.975s  |   1.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     |   0.821s  |   0.821s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   1.074s  |   1.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     |   1.459s  |   1.459s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 |   0.987s  |   0.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                |   1.364s  |   1.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                |   2.031s  |   2.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      |   1.076s  |   1.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   1.172s  |   1.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      |   2.030s  |   2.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      |   2.102s  |   2.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      |   2.959s  |   2.959s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |   0.888s  |   0.888s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   1.123s  |   1.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |   1.157s  |   1.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |   1.009s  |   1.009s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |   2.098s  |   2.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |   2.392s  |   2.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               |   1.534s  |   1.534s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |   2.283s  |   2.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   1.896s  |   1.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              |   1.454s  |   1.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   1.423s  |   1.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   0.461s  |   0.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   0.752s  |   0.752s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          |   1.461s  |   1.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          |   1.320s  |   1.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          |   1.195s  |   1.195s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |   1.458s  |   1.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          |   1.775s  |   1.775s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          |   1.698s  |   1.698s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |   0.865s  |   0.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          |   1.987s  |   1.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            |   0.945s  |   0.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |   2.502s  |   2.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            |   0.953s  |   0.953s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   0.835s  |   0.835s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   0.624s  |   0.624s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |   1.254s  |   1.254s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           |   1.301s  |   1.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           |   1.451s  |   1.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   1.220s  |   1.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           |   1.193s  |   1.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   1.620s  |   1.620s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           |   1.623s  |   1.623s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |   1.363s  |   1.363s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |   2.043s  |   2.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |   1.642s  |   1.642s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |   1.261s  |   1.261s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   0.921s  |   0.921s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |   0.698s  |   0.698s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   0.941s  |   0.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           |   1.918s  |   1.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           |   1.670s  |   1.670s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   0.580s  |   0.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           |   1.560s  |   1.560s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     |  30.207s  |  30.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   1.053s  |   1.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |   1.564s  |   1.564s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     |   3.338s  |   3.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     |   1.407s  |   1.407s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |   1.250s  |   1.250s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   0.721s  |   0.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   0.754s  |   0.754s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   1.177s  |   1.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   1.078s  |   1.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     |   1.050s  |   1.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |   1.377s  |   1.377s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               |   4.251s  |   4.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     |   1.172s  |   1.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |   1.651s  |   1.651s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     |   1.355s  |   1.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     |   1.316s  |   1.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               |   1.298s  |   1.298s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               |   1.599s  |   1.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |   0.967s  |   0.967s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |   0.860s  |   0.860s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               |   0.859s  |   0.859s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               |   1.044s  |   1.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               |   0.885s  |   0.885s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               |   1.015s  |   1.015s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               |   1.224s  |   1.224s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |   0.548s  |   0.548s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |   1.473s  |   1.473s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               |   0.891s  |   0.891s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               |   1.219s  |   1.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               |   0.808s  |   0.808s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   1.375s  |   1.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   0.940s  |   0.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               |   1.131s  |   1.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   1.399s  |   1.399s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   1.723s  |   1.723s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               |   1.119s  |   1.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   1.239s  |   1.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               |   0.887s  |   0.887s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               |   0.727s  |   0.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   2.531s  |   2.531s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |   1.064s  |   1.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |   1.437s  |   1.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   1.044s  |   1.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |   1.066s  |   1.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             |   1.137s  |   1.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |   1.973s  |   1.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |   0.625s  |   0.625s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             |   1.050s  |   1.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |   1.481s  |   1.481s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             |   1.268s  |   1.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   0.765s  |   0.765s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             |   1.956s  |   1.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |   1.350s  |   1.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |   0.775s  |   0.775s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |   1.648s  |   1.648s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |   1.299s  |   1.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             |   1.504s  |   1.504s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   1.193s  |   1.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   1.122s  |   1.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             |   1.030s  |   1.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |   1.076s  |   1.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             |   1.635s  |   1.635s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             |   1.370s  |   1.370s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             |   1.472s  |   1.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |   5.278s  |   5.278s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |   1.129s  |   1.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               |   1.621s  |   1.621s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         |   5.163s  |   5.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              |   1.956s  |   1.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   0.807s  |   0.807s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   0.580s  |   0.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    |   1.434s  |   1.434s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   1.418s  |   1.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   1.993s  |   1.993s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |   3.290s  |   3.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    |   1.465s  |   1.465s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    |   0.975s  |   0.975s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   1.079s  |   1.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    |   1.548s  |   1.548s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    |   1.509s  |   1.509s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    |   1.259s  |   1.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   1.121s  |   1.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |   0.566s  |   0.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   0.906s  |   0.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    |   1.673s  |   1.673s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |   1.343s  |   1.343s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |   1.086s  |   1.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |   2.062s  |   2.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |   1.308s  |   1.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    |   1.765s  |   1.765s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |   1.266s  |   1.266s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |   0.839s  |   0.839s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    |   1.498s  |   1.498s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   1.449s  |   1.449s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    |   1.469s  |   1.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |   1.423s  |   1.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          |   1.303s  |   1.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   0.867s  |   0.867s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          |   0.998s  |   0.998s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   0.703s  |   0.703s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          |   0.957s  |   0.957s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          |   1.942s  |   1.942s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          |   0.996s  |   0.996s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   0.822s  |   0.822s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          |   1.299s  |   1.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          |   1.081s  |   1.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          |   1.203s  |   1.203s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   1.050s  |   1.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        |   1.204s  |   1.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   0.761s  |   0.761s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        |   1.129s  |   1.129s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |   1.492s  |   1.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |   0.816s  |   0.816s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |   1.030s  |   1.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   1.320s  |   1.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   1.032s  |   1.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |   1.363s  |   1.363s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   1.230s  |   1.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        |   0.952s  |   0.952s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   0.903s  |   0.903s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |   1.208s  |   1.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |   0.778s  |   0.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   0.821s  |   0.821s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        |   1.234s  |   1.234s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        |   1.170s  |   1.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        |   1.278s  |   1.278s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |   1.200s  |   1.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        |   0.767s  |   0.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        |   1.513s  |   1.513s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   1.079s  |   1.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  |   4.931s  |   4.931s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   1.094s  |   1.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   1.939s  |   1.939s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   1.508s  |   1.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |   1.175s  |   1.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |   3.438s  |   3.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |   1.234s  |   1.234s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   1.001s  |   1.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   0.618s  |   0.618s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     |   1.309s  |   1.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     |   0.982s  |   0.982s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |   1.288s  |   1.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       |   1.823s  |   1.823s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |   2.212s  |   2.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |   1.565s  |   1.565s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       |   1.017s  |   1.017s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |   1.083s  |   1.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       |   1.255s  |   1.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   0.628s  |   0.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |   2.096s  |   2.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       |   1.372s  |   1.372s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |   2.193s  |   2.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 |  11.578s  |  11.578s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |   3.022s  |   3.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |   1.212s  |   1.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |   0.706s  |   0.706s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   1.082s  |   1.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |   1.132s  |   1.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |   0.933s  |   0.933s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |   1.883s  |   1.883s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |   4.627s  |   4.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |   1.928s  |   1.928s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |   5.173s  |   5.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  |   1.458s  |   1.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            |   2.722s  |   2.722s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   1.104s  |   1.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |   2.447s  |   2.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   0.793s  |   0.793s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |   0.959s  |   0.959s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   0.869s  |   0.869s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |   1.194s  |   1.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |   0.951s  |   0.951s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |   0.664s  |   0.664s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   1.290s  |   1.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   0.927s  |   0.927s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |   1.154s  |   1.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |   0.999s  |   0.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   0.894s  |   0.894s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |   1.464s  |   1.464s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |   2.627s  |   2.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   1.136s  |   1.136s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   1.117s  |   1.117s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   1.202s  |   1.202s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   1.162s  |   1.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   0.612s  |   0.612s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   1.020s  |   1.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |   3.112s  |   3.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   1.032s  |   1.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |   0.738s  |   0.738s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |   1.829s  |   1.829s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |   0.664s  |   0.664s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |   3.074s  |   3.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |   1.350s  |   1.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   0.736s  |   0.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   0.647s  |   0.647s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   1.268s  |   1.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                |   3.983s  |   3.983s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |   7.299s  |   7.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |   5.310s  |   5.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |   9.884s  |   9.884s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   0.968s  |   0.968s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   1.714s  |   1.714s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   0.849s  |   0.849s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   1.185s  |   1.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |   5.645s  |   5.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |   0.704s  |   0.704s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |   1.003s  |   1.003s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   1.520s  |   1.520s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   1.091s  |   1.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   1.067s  |   1.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   0.566s  |   0.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   1.186s  |   1.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   0.633s  |   0.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   1.869s  |   1.869s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |   1.315s  |   1.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |   2.777s  |   2.777s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      |   1.436s  |   1.436s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   0.802s  |   0.802s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   1.497s  |   1.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       |   3.042s  |   3.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   |   0.749s  |   0.749s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |   1.312s  |   1.312s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |   0.884s  |   0.884s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |   1.082s  |   1.082s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |   1.613s  |   1.613s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |   1.593s  |   1.593s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   1.130s  |   1.130s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          |   1.656s  |   1.656s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          |   1.326s  |   1.326s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               |   2.167s  |   2.167s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               |   2.009s  |   2.009s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |   1.099s  |   1.099s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               |   4.728s  |   4.728s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               |  18.403s  |  18.403s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         |   1.144s  |   1.144s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         |   4.955s  |   4.955s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         |  20.836s  |  20.836s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |   9.348s  |   9.348s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               |  30.156s  |  30.156s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |   5.297s  |   5.297s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   0.689s  |   0.689s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |  19.867s  |  19.867s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         |  30.217s  |  30.217s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |   0.620s  |   0.620s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         |  30.257s  |  30.257s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |   3.421s  |   3.421s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    |  13.954s  |  13.954s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |   4.147s  |   4.147s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    |  11.770s  |  11.770s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |   2.887s  |   2.887s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |   4.970s  |   4.970s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   0.706s  |   0.706s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              |  30.553s  |  30.553s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |  12.364s  |  12.364s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |  25.278s  |  25.278s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |   2.327s  |   2.327s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |   0.793s  |   0.793s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |  14.046s  |  14.046s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |  18.323s  |  18.323s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   1.439s  |   1.439s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  |  11.112s  |  11.112s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |   4.746s  |   4.746s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |  19.359s  |  19.359s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 |  30.228s  |  30.228s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           |  30.161s  |  30.161s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |   1.565s  |   1.565s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              |   0.982s  |   0.982s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   0.952s  |   0.952s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              |   1.609s  |   1.609s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              |   3.889s  |   3.889s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              |   2.116s  |   2.116s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              |   2.152s  |   2.152s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              |   2.022s  |   2.022s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |   3.701s  |   3.701s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |   1.835s  |   1.835s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |   4.732s  |   4.732s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |   4.847s  |   4.847s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   0.960s  |   0.960s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             |   1.024s  |   1.024s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             |   0.960s  |   0.960s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             |   1.278s  |   1.278s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             |   1.987s  |   1.987s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             |   1.664s  |   1.664s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |   0.818s  |   0.818s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   1.278s  |   1.278s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |   0.718s  |   0.718s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |   0.936s  |   0.936s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             |   1.487s  |   1.487s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   1.103s  |   1.103s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               |  30.469s  |  30.469s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            |   6.222s  |   6.222s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 |  30.144s  |  30.144s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |   0.809s  |   0.809s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |   1.021s  |   1.021s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           |  15.264s  |  15.264s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 |  13.000s  |  13.000s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |   0.982s  |   0.982s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           |  17.809s  |  17.809s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              |   1.614s  |   1.614s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   0.569s  |   0.569s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      |   4.181s  |   4.181s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               |   2.269s  |   2.269s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              |   4.694s  |   4.694s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       |   0.842s  |   0.842s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |   0.766s  |   0.766s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       |   1.545s  |   1.545s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |   0.822s  |   0.822s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       |   0.779s  |   0.779s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   1.205s  |   1.205s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |   0.995s  |   0.995s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |   1.050s  |   1.050s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       |   0.857s  |   0.857s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   1.399s  |   1.399s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |   1.173s  |   1.173s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   0.619s  |   0.619s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       |   1.121s  |   1.121s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   0.874s  |   0.874s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       |   1.010s  |   1.010s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   1.193s  |   1.193s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               |   1.706s  |   1.706s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         |   1.343s  |   1.343s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   0.663s  |   0.663s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 |   0.626s  |   0.626s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |   1.088s  |   1.088s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |   0.886s  |   0.886s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   0.944s  |   0.944s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   1.304s  |   1.304s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                |   1.285s  |   1.285s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                |   2.148s  |   2.148s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      |   1.404s  |   1.404s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |   1.555s  |   1.555s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      |   1.239s  |   1.239s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   0.462s  |   0.462s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   0.721s  |   0.721s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |   0.899s  |   0.899s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   1.317s  |   1.317s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      |   1.267s  |   1.267s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      |   0.768s  |   0.768s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |   1.309s  |   1.309s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   0.876s  |   0.876s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      |   1.505s  |   1.505s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |   0.976s  |   0.976s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   0.751s  |   0.751s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   0.914s  |   0.914s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   1.502s  |   1.502s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            |   3.563s  |   3.563s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |   1.719s  |   1.719s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |   1.652s  |   1.652s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |   1.596s  |   1.596s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        |   2.613s  |   2.613s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        |   2.928s  |   2.928s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       |   2.298s  |   2.298s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   0.913s  |   0.913s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     |  25.372s  |  25.372s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     |  29.606s  |  29.606s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         |   5.295s  |   5.295s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               |   1.060s  |   1.060s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         |   3.765s  |   3.765s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               |   4.332s  |   4.332s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               |   2.786s  |   2.786s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  |  30.193s  |  30.193s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |   7.342s  |   7.342s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |   4.484s  |   4.484s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |   2.102s  |   2.102s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            |   4.599s  |   4.599s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            |   8.809s  |   8.809s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |   7.015s  |   7.015s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 |   8.643s  |   8.643s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 |  30.199s  |  30.199s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |   8.514s  |   8.514s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 |  10.489s  |  10.489s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |   2.357s  |   2.357s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |   3.112s  |   3.112s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           |   4.020s  |   4.020s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           |   7.810s  |   7.810s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |   1.536s  |   1.536s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |   2.262s  |   2.262s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 |   4.184s  |   4.184s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |   1.305s  |   1.305s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 |   2.378s  |   2.378s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 |   7.113s  |   7.113s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 |   3.381s  |   3.381s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |   1.808s  |   1.808s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |   1.033s  |   1.033s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 |   3.739s  |   3.739s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 |   2.495s  |   2.495s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |   1.412s  |   1.412s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |   4.054s  |   4.054s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 |   1.718s  |   1.718s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |   1.806s  |   1.806s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 |   2.557s  |   2.557s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 |   5.225s  |   5.225s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   2.528s  |   2.528s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |   2.449s  |   2.449s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 |   6.234s  |   6.234s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   3.486s  |   3.486s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |   3.768s  |   3.768s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   2.008s  |   2.008s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 |   4.061s  |   4.061s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |   0.987s  |   0.987s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              |  18.600s  |  18.600s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |   1.932s  |   1.932s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        |  26.795s  |  26.795s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    |  17.168s  |  17.168s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    |  27.769s  |  27.769s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              |  30.115s  |  30.115s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  |  30.142s  |  30.142s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            |  30.115s  |  30.115s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          |   2.799s  |   2.799s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |   0.650s  |   0.650s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        |   1.506s  |   1.506s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        |   2.848s  |   2.848s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |   1.489s  |   1.489s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        |   2.571s  |   2.571s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        |   2.546s  |   2.546s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        |   1.567s  |   1.567s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        |   2.216s  |   2.216s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        |   2.812s  |   2.812s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        |   3.061s  |   3.061s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  |   1.791s  |   1.791s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |   1.611s  |   1.611s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   1.261s  |   1.261s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |   2.621s  |   2.621s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 |   1.743s  |   1.743s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   0.964s  |   0.964s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 |   1.598s  |   1.598s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 |   1.836s  |   1.836s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 |   1.670s  |   1.670s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 |   2.233s  |   2.233s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   0.980s  |   0.980s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             |  13.142s  |  13.142s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             |   8.190s  |   8.190s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   3.484s  |   3.484s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             |   6.790s  |   6.790s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             |   6.283s  |   6.283s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   1.131s  |   1.131s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |  10.476s  |  10.476s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             |   7.676s  |   7.676s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |   1.796s  |   1.796s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             |   7.305s  |   7.305s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             |   6.398s  |   6.398s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   1.287s  |   1.287s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             |   9.557s  |   9.557s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             |   9.166s  |   9.166s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   2.551s  |   2.551s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   2.820s  |   2.820s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  |   0.652s  |   0.652s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   1.214s  |   1.214s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                |   1.882s  |   1.882s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |   1.502s  |   1.502s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 |   1.378s  |   1.378s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 |   1.375s  |   1.375s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 |   1.187s  |   1.187s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 |   2.144s  |   2.144s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 |   1.536s  |   1.536s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   0.473s  |   0.473s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           |   1.637s  |   1.637s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 |   1.476s  |   1.476s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 |   0.852s  |   0.852s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           |   1.361s  |   1.361s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  |   4.312s  |   4.312s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 |   1.312s  |   1.312s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 |   1.819s  |   1.819s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   0.739s  |   0.739s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |   1.885s  |   1.885s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 |   0.841s  |   0.841s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 |   1.767s  |   1.767s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 |   1.871s  |   1.871s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 |   2.238s  |   2.238s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   0.764s  |   0.764s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   1.383s  |   1.383s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  |   1.511s  |   1.511s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   1.603s  |   1.603s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |   1.611s  |   1.611s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            |   1.293s  |   1.293s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |   3.461s  |   3.461s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  |   0.928s  |   0.928s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  |   1.191s  |   1.191s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  |   1.018s  |   1.018s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            |   1.060s  |   1.060s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 |   1.439s  |   1.439s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |   1.164s  |   1.164s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  |   1.206s  |   1.206s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  |   1.495s  |   1.495s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  |   2.228s  |   2.228s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   0.515s  |   0.515s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  |   2.479s  |   2.479s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  |   2.441s  |   2.441s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  |   3.511s  |   3.511s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  |   3.416s  |   3.416s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |   1.035s  |   1.035s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            |   1.939s  |   1.939s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |   1.300s  |   1.300s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |   0.642s  |   0.642s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           |   4.704s  |   4.704s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           |   3.173s  |   3.173s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           |   2.684s  |   2.684s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |   2.155s  |   2.155s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               |   6.847s  |   6.847s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               |   6.506s  |   6.506s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               |   5.055s  |   5.055s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               |  30.270s  |  30.270s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |   9.844s  |   9.844s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |   4.195s  |   4.195s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   0.768s  |   0.768s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             |   1.218s  |   1.218s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |   1.834s  |   1.834s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   2.840s  |   2.840s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |   1.109s  |   1.109s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |   2.703s  |   2.703s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    |   9.824s  |   9.824s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   0.812s  |   0.812s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               |   4.206s  |   4.206s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             |   1.505s  |   1.505s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             |   0.921s  |   0.921s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             |   1.910s  |   1.910s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             |   1.423s  |   1.423s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             |   2.140s  |   2.140s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             |   1.587s  |   1.587s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |   1.370s  |   1.370s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               |  10.651s  |  10.651s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         |  30.304s  |  30.304s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |   2.905s  |   2.905s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |   2.424s  |   2.424s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |   1.213s  |   1.213s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        |   7.284s  |   7.284s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            |   2.389s  |   2.389s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            |   2.328s  |   2.328s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |   0.968s  |   0.968s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            |   1.284s  |   1.284s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |   0.889s  |   0.889s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              |   1.194s  |   1.194s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |   0.960s  |   0.960s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              |   1.884s  |   1.884s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |   0.765s  |   0.765s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |   0.776s  |   0.776s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   0.903s  |   0.903s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   2.753s  |   2.753s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         |   5.238s  |   5.238s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           |   1.761s  |   1.761s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |   1.070s  |   1.070s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  |   1.481s  |   1.481s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            |   1.397s  |   1.397s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              |   0.915s  |   0.915s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          |   2.484s  |   2.484s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          |   4.251s  |   4.251s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |   1.118s  |   1.118s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          |   2.198s  |   2.198s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          |   4.246s  |   4.246s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          |   2.448s  |   2.448s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          |   3.538s  |   3.538s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                |   1.683s  |   1.683s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                |   3.554s  |   3.554s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                |   2.237s  |   2.237s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                |   3.036s  |   3.036s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |   1.205s  |   1.205s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                |   2.039s  |   2.039s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                |   4.917s  |   4.917s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |   1.320s  |   1.320s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                |   2.170s  |   2.170s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                |   5.624s  |   5.624s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          |   5.667s  |   5.667s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |   1.835s  |   1.835s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          |   2.367s  |   2.367s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |   2.751s  |   2.751s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          |   8.765s  |   8.765s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |   1.712s  |   1.712s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                |   0.793s  |   0.793s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |   0.738s  |   0.738s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |   0.887s  |   0.887s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |   1.282s  |   1.282s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |   1.149s  |   1.149s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |   1.105s  |   1.105s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                |   1.311s  |   1.311s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                |   0.982s  |   0.982s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |   1.351s  |   1.351s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |   0.728s  |   0.728s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |   1.865s  |   1.865s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                |   1.200s  |   1.200s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                |   1.287s  |   1.287s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |   1.766s  |   1.766s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   1.582s  |   1.582s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |   0.887s  |   0.887s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          |   1.558s  |   1.558s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |   1.131s  |   1.131s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |   0.797s  |   0.797s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |   1.672s  |   1.672s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |   1.109s  |   1.109s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          |   1.807s  |   1.807s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          |   1.314s  |   1.314s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          |   1.138s  |   1.138s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          |   1.215s  |   1.215s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |   6.228s  |   6.228s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |   9.210s  |   9.210s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |   1.033s  |   1.033s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           |   1.623s  |   1.623s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           |   1.445s  |   1.445s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |   2.499s  |   2.499s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |   0.890s  |   0.890s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        |   1.035s  |   1.035s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |   1.175s  |   1.175s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |   1.754s  |   1.754s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        |   0.870s  |   0.870s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |   2.105s  |   2.105s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        |   0.722s  |   0.722s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        |   1.192s  |   1.192s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |   1.383s  |   1.383s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        |   1.289s  |   1.289s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        |   0.989s  |   0.989s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |   0.915s  |   0.915s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        |   2.000s  |   2.000s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |   4.493s  |   4.493s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            |   7.828s  |   7.828s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  |   1.660s  |   1.660s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  |   1.552s  |   1.552s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |   0.575s  |   0.575s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  |   0.613s  |   0.613s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  |   1.188s  |   1.188s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  |   1.598s  |   1.598s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |   1.327s  |   1.327s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                |   5.108s  |   5.108s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |   1.679s  |   1.679s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   2.500s  |   2.500s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        |   7.161s  |   7.161s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   |   1.758s  |   1.758s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   |   2.061s  |   2.061s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   |   1.536s  |   1.536s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   |   2.728s  |   2.728s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   |   2.606s  |   2.606s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   |   2.667s  |   2.667s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   |   1.545s  |   1.545s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         |   0.961s  |   0.961s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         |   1.974s  |   1.974s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        |   4.950s  |   4.950s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        |   7.027s  |   7.027s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   1.209s  |   1.209s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        |   4.363s  |   4.363s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        |   7.447s  |   7.447s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        |   4.724s  |   4.724s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   3.428s  |   3.428s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |   6.805s  |   6.805s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            |   4.793s  |   4.793s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            |   7.092s  |   7.092s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            |   6.650s  |   6.650s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            |   7.861s  |   7.861s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   1.208s  |   1.208s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            |   5.075s  |   5.075s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  |   2.253s  |   2.253s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  |   1.772s  |   1.772s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |   1.978s  |   1.978s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         |   1.210s  |   1.210s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |   4.320s  |   4.320s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         |   1.495s  |   1.495s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         |   1.461s  |   1.461s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |   1.294s  |   1.294s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   0.971s  |   0.971s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         |   2.774s  |   2.774s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   1.670s  |   1.670s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   1.280s  |   1.280s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   1.016s  |   1.016s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   1.818s  |   1.818s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   1.091s  |   1.091s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           |   1.439s  |   1.439s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           |   0.852s  |   0.852s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |   0.964s  |   0.964s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           |   1.416s  |   1.416s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           |   1.344s  |   1.344s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  |   1.160s  |   1.160s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   0.484s  |   0.484s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             |   1.111s  |   1.111s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |   0.910s  |   0.910s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             |   0.825s  |   0.825s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |   1.133s  |   1.133s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |   1.250s  |   1.250s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             |   1.688s  |   1.688s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |   0.767s  |   0.767s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             |   1.007s  |   1.007s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |   1.106s  |   1.106s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             |   1.793s  |   1.793s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   0.586s  |   0.586s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |   1.196s  |   1.196s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              |   3.349s  |   3.349s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      |   1.703s  |   1.703s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   1.177s  |   1.177s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          |  30.255s  |  30.255s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                |  13.255s  |  13.255s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |   1.487s  |   1.487s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |   1.020s  |   1.020s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                |   2.228s  |   2.228s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                |   4.407s  |   4.407s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |   0.760s  |   0.760s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                |   2.071s  |   2.071s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                |   2.799s  |   2.799s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |   1.132s  |   1.132s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |   1.145s  |   1.145s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          |   3.933s  |   3.933s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              |   4.163s  |   4.163s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       |  12.648s  |  12.648s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       |   6.404s  |   6.404s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   2.190s  |   2.190s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |   1.267s  |   1.267s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             |   6.574s  |   6.574s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |   2.228s  |   2.228s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |   1.661s  |   1.661s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           |   6.809s  |   6.809s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           |  14.371s  |  14.371s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |   2.497s  |   2.497s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 |   7.445s  |   7.445s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 |   7.507s  |   7.507s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   0.801s  |   0.801s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |   2.849s  |   2.849s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                |  16.788s  |  16.788s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                |   4.279s  |   4.279s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |   3.762s  |   3.762s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |   2.651s  |   2.651s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          |   4.217s  |   4.217s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          |   9.151s  |   9.151s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          |   3.252s  |   3.252s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |   2.868s  |   2.868s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |   1.751s  |   1.751s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     |   1.014s  |   1.014s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                |   1.360s  |   1.360s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                |   1.847s  |   1.847s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   0.603s  |   0.603s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   0.604s  |   0.604s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |   2.866s  |   2.866s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |   1.093s  |   1.093s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   0.680s  |   0.680s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |   0.751s  |   0.751s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      |   2.479s  |   2.479s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      |   1.248s  |   1.248s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   0.772s  |   0.772s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |   1.338s  |   1.338s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |   1.832s  |   1.832s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |   1.663s  |   1.663s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |   1.185s  |   1.185s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |   1.390s  |   1.390s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |   2.860s  |   2.860s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |   1.717s  |   1.717s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  |  15.541s  |  15.541s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |   1.751s  |   1.751s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           |   1.242s  |   1.242s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      |   1.774s  |   1.774s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   1.256s  |   1.256s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      |   1.947s  |   1.947s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           |   1.694s  |   1.694s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   1.313s  |   1.313s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   0.809s  |   0.809s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |   2.379s  |   2.379s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   2.966s  |   2.966s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        |   1.160s  |   1.160s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |   1.790s  |   1.790s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   1.197s  |   1.197s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |   0.835s  |   0.835s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |   1.955s  |   1.955s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |   1.399s  |   1.399s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                |   1.840s  |   1.840s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                |   1.236s  |   1.236s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   0.955s  |   0.955s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |   0.987s  |   0.987s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                |   1.589s  |   1.589s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   3.223s  |   3.223s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |   4.781s  |   4.781s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   2.365s  |   2.365s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   3.190s  |   3.190s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   1.110s  |   1.110s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |   2.354s  |   2.354s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       |   2.400s  |   2.400s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       |   1.506s  |   1.506s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   1.294s  |   1.294s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       |   2.952s  |   2.952s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       |   2.365s  |   2.365s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       |   2.349s  |   2.349s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       |   1.237s  |   1.237s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.461s  |   0.461s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       |   1.432s  |   1.432s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       |   1.287s  |   1.287s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     |   0.648s  |   0.648s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |   2.268s  |   2.268s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |   0.926s  |   0.926s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |   2.233s  |   2.233s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        |   4.106s  |   4.106s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        |   1.433s  |   1.433s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   1.313s  |   1.313s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |   0.985s  |   0.985s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  |   3.908s  |   3.908s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  |   3.871s  |   3.871s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |   1.712s  |   1.712s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   0.656s  |   0.656s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           |   6.572s  |   6.572s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   5.312s  |   5.312s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   5.106s  |   5.106s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   5.409s  |   5.409s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           |   2.781s  |   2.781s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           |   3.479s  |   3.479s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   4.330s  |   4.330s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   2.225s  |   2.225s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   4.337s  |   4.337s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   4.142s  |   4.142s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           |   9.604s  |   9.604s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   3.042s  |   3.042s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   3.125s  |   3.125s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   2.894s  |   2.894s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   4.741s  |   4.741s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |   3.661s  |   3.661s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   1.620s  |   1.620s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |   1.837s  |   1.837s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |  28.784s  |  28.784s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |   3.896s  |   3.896s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   6.691s  |   6.691s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |   2.883s  |   2.883s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   1.333s  |   1.333s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            |   3.196s  |   3.196s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   1.171s  |   1.171s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |   4.065s  |   4.065s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           |   2.518s  |   2.518s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   1.806s  |   1.806s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |   4.190s  |   4.190s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   1.570s  |   1.570s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   0.575s  |   0.575s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   0.731s  |   0.731s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   1.735s  |   1.735s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |   6.128s  |   6.128s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   9.380s  |   9.380s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   3.951s  |   3.951s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   3.868s  |   3.868s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   0.802s  |   0.802s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   3.296s  |   3.296s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   4.264s  |   4.264s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           |   6.144s  |   6.144s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           |   4.006s  |   4.006s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   1.185s  |   1.185s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   3.049s  |   3.049s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   5.443s  |   5.443s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   1.859s  |   1.859s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           |   4.975s  |   4.975s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |   7.256s  |   7.256s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   2.028s  |   2.028s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   2.458s  |   2.458s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   1.596s  |   1.596s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |   1.419s  |   1.419s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   0.822s  |   0.822s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |   1.195s  |   1.195s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            |   0.839s  |   0.839s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            |   2.396s  |   2.396s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            |   1.283s  |   1.283s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            |   1.680s  |   1.680s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
</details>
