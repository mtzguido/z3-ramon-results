Comparing data and data


# SUMMARY
- LHS tests = 2313
- RHS tests = 2313
- LHS success = 1403  (60.65715520968439%)
- RHS success = 1403  (60.65715520968439%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-reassert-all-units
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 4d61c199170c539e5a4b3d477627d3e030d77502
Z3 branch: reassert-all-units
Z3 options: "-T:20 -v:2"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: add code path to reassert units

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-reassert-all-units
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 4d61c199170c539e5a4b3d477627d3e030d77502
Z3 branch: reassert-all-units
Z3 options: "-T:20 -v:2"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: add code path to reassert units

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.828s  |  19.828s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.828s  |  19.828s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.828s  |  19.828s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.828s  |  19.828s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  20.084s |2676.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  20.081s |2094.0MiB|
|185.smt2                                                                                   |  20.031s |706.0MiB|
|182.smt2                                                                                   |  20.023s |421.0MiB|
|181.smt2                                                                                   |  20.019s |315.0MiB|
|183.smt2                                                                                   |  20.011s |429.0MiB|
|58.smt2                                                                                    |  20.009s |163.0MiB|
|40.smt2                                                                                    |  20.008s |116.0MiB|
|73.smt2                                                                                    |  20.005s |120.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  20.005s |602.0MiB|
|54.smt2                                                                                    |  20.003s |138.0MiB|
|124.smt2                                                                                   |  20.003s |77.66MiB|
|140.smt2                                                                                   |  20.003s |115.0MiB|
|65.smt2                                                                                    |  20.001s |119.0MiB|
|35.smt2                                                                                    |  20.001s |121.0MiB|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                       |  20.000s |41.38MiB|
|99.smt2                                                                                    |  19.999s |145.0MiB|
|02.smt2                                                                                    |  19.999s |118.0MiB|
|177.smt2                                                                                   |  19.991s |121.0MiB|
|98.smt2                                                                                    |  19.984s |127.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  20.084s |2676.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  20.081s |2094.0MiB|
|185.smt2                                                                                   |  20.031s |706.0MiB|
|182.smt2                                                                                   |  20.023s |421.0MiB|
|181.smt2                                                                                   |  20.019s |315.0MiB|
|183.smt2                                                                                   |  20.011s |429.0MiB|
|58.smt2                                                                                    |  20.009s |163.0MiB|
|40.smt2                                                                                    |  20.008s |116.0MiB|
|73.smt2                                                                                    |  20.005s |120.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  20.005s |602.0MiB|
|54.smt2                                                                                    |  20.003s |138.0MiB|
|124.smt2                                                                                   |  20.003s |77.66MiB|
|140.smt2                                                                                   |  20.003s |115.0MiB|
|65.smt2                                                                                    |  20.001s |119.0MiB|
|35.smt2                                                                                    |  20.001s |121.0MiB|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                       |  20.000s |41.38MiB|
|99.smt2                                                                                    |  19.999s |145.0MiB|
|02.smt2                                                                                    |  19.999s |118.0MiB|
|177.smt2                                                                                   |  19.991s |121.0MiB|
|98.smt2                                                                                    |  19.984s |127.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |118.0MiB|118.0MiB|0B| 0.0%|
|04.smt2                                                                                     |108.0MiB|108.0MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |29.944MiB|29.944MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.124MiB|30.124MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.1MiB|23.1MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.236MiB|23.236MiB|0B| 0.0%|
|1034.smt2                                                                                   |23.976MiB|23.976MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.164MiB|24.164MiB|0B| 0.0%|
|107.smt2                                                                                    |21.76MiB|21.76MiB|0B| 0.0%|
|1082.smt2                                                                                   |26.928MiB|26.928MiB|0B| 0.0%|
|1085.smt2                                                                                   |79.804MiB|79.804MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.396MiB|22.396MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.344MiB|22.344MiB|0B| 0.0%|
|1092.smt2                                                                                   |22.4MiB|22.4MiB|0B| 0.0%|
|11.smt2                                                                                     |110.0MiB|110.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.396MiB|23.396MiB|0B| 0.0%|
|1112.smt2                                                                                   |22.972MiB|22.972MiB|0B| 0.0%|
|1113.smt2                                                                                   |22.764MiB|22.764MiB|0B| 0.0%|
|1126.smt2                                                                                   |24.388MiB|24.388MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |118.0MiB|118.0MiB|0B| 0.0%|
|04.smt2                                                                                     |108.0MiB|108.0MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |29.944MiB|29.944MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.124MiB|30.124MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.1MiB|23.1MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.236MiB|23.236MiB|0B| 0.0%|
|1034.smt2                                                                                   |23.976MiB|23.976MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.164MiB|24.164MiB|0B| 0.0%|
|107.smt2                                                                                    |21.76MiB|21.76MiB|0B| 0.0%|
|1082.smt2                                                                                   |26.928MiB|26.928MiB|0B| 0.0%|
|1085.smt2                                                                                   |79.804MiB|79.804MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.396MiB|22.396MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.344MiB|22.344MiB|0B| 0.0%|
|1092.smt2                                                                                   |22.4MiB|22.4MiB|0B| 0.0%|
|11.smt2                                                                                     |110.0MiB|110.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.396MiB|23.396MiB|0B| 0.0%|
|1112.smt2                                                                                   |22.972MiB|22.972MiB|0B| 0.0%|
|1113.smt2                                                                                   |22.764MiB|22.764MiB|0B| 0.0%|
|1126.smt2                                                                                   |24.388MiB|24.388MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |118.0MiB|118.0MiB|0B| 0.0%|
|04.smt2                                                                                     |108.0MiB|108.0MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |29.944MiB|29.944MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.124MiB|30.124MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.1MiB|23.1MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.236MiB|23.236MiB|0B| 0.0%|
|1034.smt2                                                                                   |23.976MiB|23.976MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.164MiB|24.164MiB|0B| 0.0%|
|107.smt2                                                                                    |21.76MiB|21.76MiB|0B| 0.0%|
|1082.smt2                                                                                   |26.928MiB|26.928MiB|0B| 0.0%|
|1085.smt2                                                                                   |79.804MiB|79.804MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.396MiB|22.396MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.344MiB|22.344MiB|0B| 0.0%|
|1092.smt2                                                                                   |22.4MiB|22.4MiB|0B| 0.0%|
|11.smt2                                                                                     |110.0MiB|110.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.396MiB|23.396MiB|0B| 0.0%|
|1112.smt2                                                                                   |22.972MiB|22.972MiB|0B| 0.0%|
|1113.smt2                                                                                   |22.764MiB|22.764MiB|0B| 0.0%|
|1126.smt2                                                                                   |24.388MiB|24.388MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |118.0MiB|118.0MiB|0B| 0.0%|
|04.smt2                                                                                     |108.0MiB|108.0MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |29.944MiB|29.944MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.124MiB|30.124MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.1MiB|23.1MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.236MiB|23.236MiB|0B| 0.0%|
|1034.smt2                                                                                   |23.976MiB|23.976MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.164MiB|24.164MiB|0B| 0.0%|
|107.smt2                                                                                    |21.76MiB|21.76MiB|0B| 0.0%|
|1082.smt2                                                                                   |26.928MiB|26.928MiB|0B| 0.0%|
|1085.smt2                                                                                   |79.804MiB|79.804MiB|0B| 0.0%|
|1089.smt2                                                                                   |22.396MiB|22.396MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.344MiB|22.344MiB|0B| 0.0%|
|1092.smt2                                                                                   |22.4MiB|22.4MiB|0B| 0.0%|
|11.smt2                                                                                     |110.0MiB|110.0MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.396MiB|23.396MiB|0B| 0.0%|
|1112.smt2                                                                                   |22.972MiB|22.972MiB|0B| 0.0%|
|1113.smt2                                                                                   |22.764MiB|22.764MiB|0B| 0.0%|
|1126.smt2                                                                                   |24.388MiB|24.388MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  20.084s |2676.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  20.081s |2094.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  19.901s |988.0MiB|
|185.smt2                                                                                   |  20.031s |706.0MiB|
|From_T2__foo.t2__terminationS_12_0.smt2                                                    |  12.073s |637.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  13.843s |628.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  10.266s |628.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  13.452s |625.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  20.005s |602.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  11.923s |487.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           |  13.341s |485.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  13.196s |478.0MiB|
|183.smt2                                                                                   |  20.011s |429.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  18.204s |424.0MiB|
|182.smt2                                                                                   |  20.023s |421.0MiB|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                |  11.721s |340.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2         |   7.061s |320.0MiB|
|181.smt2                                                                                   |  20.019s |315.0MiB|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                          |   1.985s |311.0MiB|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                     |   1.911s |311.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         |  20.084s |2676.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              |  20.081s |2094.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        |  19.901s |988.0MiB|
|185.smt2                                                                                   |  20.031s |706.0MiB|
|From_T2__foo.t2__terminationS_12_0.smt2                                                    |  12.073s |637.0MiB|
|From_T2__foo.t2__terminationS_21_0.smt2                                                    |  13.843s |628.0MiB|
|From_T2__foo.t2__terminationS_30_0.smt2                                                    |  10.266s |628.0MiB|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                        |  13.452s |625.0MiB|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                             |  20.005s |602.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2           |  11.923s |487.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2           |  13.341s |485.0MiB|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2            |  13.196s |478.0MiB|
|183.smt2                                                                                   |  20.011s |429.0MiB|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                |  18.204s |424.0MiB|
|182.smt2                                                                                   |  20.023s |421.0MiB|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                |  11.721s |340.0MiB|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2         |   7.061s |320.0MiB|
|181.smt2                                                                                   |  20.019s |315.0MiB|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                          |   1.985s |311.0MiB|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                     |   1.911s |311.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.828s  |  19.828s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   1.377s  |   1.377s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   0.964s  |   0.964s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   0.942s  |   0.942s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   1.449s  |   1.449s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   1.714s  |   1.714s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   0.585s  |   0.585s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   0.983s  |   0.983s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|966.smt2                                                                                    |   1.346s  |   1.346s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|99.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |   1.036s  |   1.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   0.639s  |   0.639s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   0.580s  |   0.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            |   7.905s  |   7.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   0.671s  |   0.671s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   0.775s  |   0.775s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   0.859s  |   0.859s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   0.675s  |   0.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   0.753s  |   0.753s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |   0.614s  |   0.614s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   0.617s  |   0.617s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         |   1.644s  |   1.644s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 |   1.056s  |   1.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      |   1.324s  |   1.324s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          |   0.814s  |   0.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          |   0.946s  |   0.946s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      |   1.803s  |   1.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      |   5.775s  |   5.775s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             |   0.670s  |   0.670s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    |   1.194s  |   1.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |   1.058s  |   1.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |   0.530s  |   0.530s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               |   0.965s  |   0.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   1.206s  |   1.206s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   1.140s  |   1.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   1.035s  |   1.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   1.644s  |   1.644s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                |   1.144s  |   1.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |   1.777s  |   1.777s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          |   0.663s  |   0.663s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |   0.671s  |   0.671s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    |   0.772s  |   0.772s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |   0.825s  |   0.825s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |   0.701s  |   0.701s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |   1.132s  |   1.132s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |   0.849s  |   0.849s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |   0.807s  |   0.807s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  |   1.110s  |   1.110s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |   1.594s  |   1.594s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |   1.314s  |   1.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |   1.185s  |   1.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |   0.860s  |   0.860s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   |   5.544s  |   5.544s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                |   0.585s  |   0.585s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   1.002s  |   1.002s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   1.436s  |   1.436s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          |   1.007s  |   1.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               |   1.315s  |   1.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                |   1.389s  |   1.389s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   1.112s  |   1.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   1.459s  |   1.459s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          |   0.809s  |   0.809s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |   0.766s  |   0.766s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   1.577s  |   1.577s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   1.182s  |   1.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |   0.813s  |   0.813s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     |   2.763s  |   2.763s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   0.803s  |   0.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   0.903s  |   0.903s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |   0.837s  |   0.837s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   0.489s  |   0.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   0.818s  |   0.818s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   1.277s  |   1.277s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   0.652s  |   0.652s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   0.648s  |   0.648s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   1.460s  |   1.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   1.237s  |   1.237s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   1.006s  |   1.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   1.005s  |   1.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   0.802s  |   0.802s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   0.545s  |   0.545s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   0.991s  |   0.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   0.800s  |   0.800s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   0.675s  |   0.675s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   0.800s  |   0.800s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   1.264s  |   1.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   1.249s  |   1.249s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   1.019s  |   1.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   1.458s  |   1.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   0.838s  |   0.838s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   0.701s  |   0.701s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   1.446s  |   1.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   1.057s  |   1.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   1.035s  |   1.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   0.982s  |   0.982s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   1.313s  |   1.313s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          |   2.799s  |   2.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          |   7.061s  |   7.061s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          |   1.969s  |   1.969s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   0.807s  |   0.807s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             |  13.196s  |  13.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            |  13.341s  |  13.341s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            |  11.923s  |  11.923s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   1.082s  |   1.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   1.063s  |   1.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   1.402s  |   1.402s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   0.966s  |   0.966s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   |   1.236s  |   1.236s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               |   0.666s  |   0.666s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         |   0.944s  |   0.944s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         |   5.678s  |   5.678s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         |  13.452s  |  13.452s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |   2.157s  |   2.157s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |   1.699s  |   1.699s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |   1.744s  |   1.744s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |   0.949s  |   0.949s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   0.763s  |   0.763s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 |  11.721s  |  11.721s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |   0.626s  |   0.626s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |   1.180s  |   1.180s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |   0.692s  |   0.692s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   1.068s  |   1.068s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |   1.255s  |   1.255s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |   0.585s  |   0.585s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |   0.569s  |   0.569s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             |   0.608s  |   0.608s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             |   0.569s  |   0.569s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   0.868s  |   0.868s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 |   0.803s  |   0.803s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  |   0.904s  |   0.904s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |   0.822s  |   0.822s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   1.449s  |   1.449s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   0.762s  |   0.762s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |   0.638s  |   0.638s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   0.913s  |   0.913s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   0.876s  |   0.876s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   0.823s  |   0.823s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   0.934s  |   0.934s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 |  18.204s  |  18.204s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |   1.491s  |   1.491s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |   1.258s  |   1.258s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |   1.211s  |   1.211s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           |   8.034s  |   8.034s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      |   9.755s  |   9.755s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |   1.420s  |   1.420s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |   0.894s  |   0.894s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           |   7.617s  |   7.617s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |   0.765s  |   0.765s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   0.652s  |   0.652s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   1.075s  |   1.075s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       |   0.698s  |   0.698s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       |   0.632s  |   0.632s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   0.706s  |   0.706s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |   0.820s  |   0.820s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |   0.885s  |   0.885s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      |   5.630s  |   5.630s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   0.484s  |   0.484s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      |   0.582s  |   0.582s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   0.588s  |   0.588s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   0.563s  |   0.563s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      |   0.737s  |   0.737s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   0.839s  |   0.839s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      |   0.784s  |   0.784s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   1.371s  |   1.371s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   0.767s  |   0.767s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   1.787s  |   1.787s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            |   0.670s  |   0.670s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |   0.588s  |   0.588s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   1.007s  |   1.007s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     |  12.073s  |  12.073s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     |  10.266s  |  10.266s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               |   0.820s  |   0.820s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  |  19.800s  |  19.800s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     |   1.463s  |   1.463s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |   1.014s  |   1.014s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   0.530s  |   0.530s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                |   1.071s  |   1.071s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |   1.363s  |   1.363s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           |   0.953s  |   0.953s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |   7.575s  |   7.575s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   1.423s  |   1.423s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   1.257s  |   1.257s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |   1.476s  |   1.476s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |   0.620s  |   0.620s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 |   1.196s  |   1.196s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 |   0.739s  |   0.739s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |   0.762s  |   0.762s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           |   0.815s  |   0.815s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    |   9.314s  |   9.314s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       |   1.751s  |   1.751s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       |   1.550s  |   1.550s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |   1.002s  |   1.002s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |   1.405s  |   1.405s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |   0.652s  |   0.652s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              |  12.519s  |  12.519s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |   0.632s  |   0.632s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |   0.585s  |   0.585s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |   1.001s  |   1.001s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  |  11.918s  |  11.918s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   0.565s  |   0.565s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |   0.767s  |   0.767s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |   0.732s  |   0.732s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            |   8.240s  |   8.240s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |   0.623s  |   0.623s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  |   0.612s  |   0.612s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 |   0.543s  |   0.543s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             |   0.727s  |   0.727s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             |   1.067s  |   1.067s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           |   1.002s  |   1.002s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   0.546s  |   0.546s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           |   0.704s  |   0.704s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 |   1.550s  |   1.550s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           |   0.859s  |   0.859s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 |   0.575s  |   0.575s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 |   0.617s  |   0.617s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 |   0.898s  |   0.898s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  |   0.557s  |   0.557s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            |   0.489s  |   0.489s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   0.773s  |   0.773s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |   0.619s  |   0.619s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |   0.732s  |   0.732s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   0.546s  |   0.546s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             |   0.664s  |   0.664s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   1.188s  |   1.188s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   0.924s  |   0.924s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |   0.811s  |   0.811s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            |   0.850s  |   0.850s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   1.688s  |   1.688s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               |   1.071s  |   1.071s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             |   1.736s  |   1.736s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   0.808s  |   0.808s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             |   0.546s  |   0.546s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |   1.578s  |   1.578s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         |  19.901s  |  19.901s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |   0.956s  |   0.956s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |   1.191s  |   1.191s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |   1.754s  |   1.754s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |   1.251s  |   1.251s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              |   0.706s  |   0.706s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   0.655s  |   0.655s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |   1.013s  |   1.013s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                |   0.515s  |   0.515s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   1.304s  |   1.304s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |   1.283s  |   1.283s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   1.352s  |   1.352s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |   1.314s  |   1.314s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   0.916s  |   0.916s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   0.881s  |   0.881s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   0.831s  |   0.831s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  |   7.279s  |   7.279s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                |   0.702s  |   0.702s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        |   0.695s  |   0.695s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   |   0.947s  |   0.947s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   |   0.767s  |   0.767s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   |   0.618s  |   0.618s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   |   0.905s  |   0.905s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   1.007s  |   1.007s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        |   1.757s  |   1.757s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   1.653s  |   1.653s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   1.131s  |   1.131s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |   0.739s  |   0.739s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |   1.805s  |   1.805s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |   1.749s  |   1.749s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            |   1.043s  |   1.043s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            |   1.898s  |   1.898s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  |   7.049s  |   7.049s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  |   0.620s  |   0.620s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   0.852s  |   0.852s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            |   1.367s  |   1.367s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |   0.914s  |   0.914s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |   5.933s  |   5.933s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |   0.832s  |   0.832s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         |   1.799s  |   1.799s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   1.010s  |   1.010s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   1.436s  |   1.436s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   1.082s  |   1.082s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   1.105s  |   1.105s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   0.763s  |   0.763s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   0.913s  |   0.913s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   1.003s  |   1.003s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   1.339s  |   1.339s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             |   0.834s  |   0.834s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   1.419s  |   1.419s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             |   0.548s  |   0.548s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      |   1.467s  |   1.467s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                |   0.749s  |   0.749s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                |   1.433s  |   1.433s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                |   0.861s  |   0.861s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |   0.575s  |   0.575s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |   1.758s  |   1.758s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   0.877s  |   0.877s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |   0.678s  |   0.678s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |   0.624s  |   0.624s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |   0.957s  |   0.957s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           |   0.671s  |   0.671s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |   0.813s  |   0.813s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   1.649s  |   1.649s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |   0.635s  |   0.635s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |   1.784s  |   1.784s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          |   0.899s  |   0.899s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          |   1.723s  |   1.723s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   0.546s  |   0.546s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                |   0.588s  |   0.588s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   1.201s  |   1.201s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           |   0.674s  |   0.674s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      |   0.939s  |   0.939s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      |   0.484s  |   0.484s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           |   1.043s  |   1.043s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   1.289s  |   1.289s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   0.663s  |   0.663s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        |   0.484s  |   0.484s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |   1.603s  |   1.603s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   1.013s  |   1.013s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   0.626s  |   0.626s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |   1.379s  |   1.379s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   1.662s  |   1.662s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                |   0.796s  |   0.796s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |   0.860s  |   0.860s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |   1.437s  |   1.437s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |   0.698s  |   0.698s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   1.123s  |   1.123s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   1.708s  |   1.708s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       |   0.585s  |   0.585s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       |   0.478s  |   0.478s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       |   0.971s  |   0.971s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       |   0.633s  |   0.633s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   1.312s  |   1.312s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   1.132s  |   1.132s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   1.379s  |   1.379s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  |   0.480s  |   0.480s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           |   2.333s  |   2.333s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   0.939s  |   0.939s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |   1.314s  |   1.314s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           |   2.011s  |   2.011s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   1.545s  |   1.545s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |   2.671s  |   2.671s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   1.753s  |   1.753s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           |   1.052s  |   1.052s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           |   1.779s  |   1.779s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   1.467s  |   1.467s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   0.763s  |   0.763s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |   0.625s  |   0.625s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
</details>
