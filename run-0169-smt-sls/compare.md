Comparing data and data


# SUMMARY
- LHS tests = 186
- RHS tests = 186
- LHS success = 186  (100.0%)
- RHS success = 186  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 9770c005926e2085d4ede18f03d56cb67d762d84
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: adjust heuristic in random-inc-dec for finite domains

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 9770c005926e2085d4ede18f03d56cb67d762d84
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: adjust heuristic in random-inc-dec for finite domains

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.884s  |  19.884s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.693s  |  19.693s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.904s  |  19.904s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |  19.901s  |  19.901s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |  18.488s  |  18.488s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.593s  |  19.593s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.884s  |  19.884s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.693s  |  19.693s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.904s  |  19.904s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |  19.901s  |  19.901s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |  18.488s  |  18.488s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.593s  |  19.593s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.884s  |  19.884s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.693s  |  19.693s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.904s  |  19.904s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |  19.901s  |  19.901s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |  18.488s  |  18.488s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.593s  |  19.593s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.884s  |  19.884s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.693s  |  19.693s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.904s  |  19.904s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |  19.901s  |  19.901s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |  18.488s  |  18.488s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.593s  |  19.593s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|76.smt2                                                                                    |  20.080s |23.864MiB|
|166.smt2                                                                                   |  20.012s |25.9MiB|
|126.smt2                                                                                   |  20.011s |36.096MiB|
|15.smt2                                                                                    |  20.010s |21.268MiB|
|95.smt2                                                                                    |  20.010s |22.776MiB|
|178.smt2                                                                                   |  20.010s |152.0MiB|
|173.smt2                                                                                   |  20.010s |138.0MiB|
|171.smt2                                                                                   |  20.010s |61.08MiB|
|106.smt2                                                                                   |  20.008s |34.152MiB|
|66.smt2                                                                                    |  20.007s |23.864MiB|
|125.smt2                                                                                   |  20.007s |38.288MiB|
|55.smt2                                                                                    |  20.007s |21.94MiB|
|05.smt2                                                                                    |  20.007s |22.176MiB|
|163.smt2                                                                                   |  20.006s |73.996MiB|
|59.smt2                                                                                    |  20.006s |22.784MiB|
|43.smt2                                                                                    |  20.006s |21.188MiB|
|75.smt2                                                                                    |  20.006s |22.772MiB|
|151.smt2                                                                                   |  20.005s |33.964MiB|
|53.smt2                                                                                    |  20.005s |23.032MiB|
|92.smt2                                                                                    |  20.005s |21.848MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|76.smt2                                                                                    |  20.080s |23.864MiB|
|166.smt2                                                                                   |  20.012s |25.9MiB|
|126.smt2                                                                                   |  20.011s |36.096MiB|
|15.smt2                                                                                    |  20.010s |21.268MiB|
|95.smt2                                                                                    |  20.010s |22.776MiB|
|178.smt2                                                                                   |  20.010s |152.0MiB|
|173.smt2                                                                                   |  20.010s |138.0MiB|
|171.smt2                                                                                   |  20.010s |61.08MiB|
|106.smt2                                                                                   |  20.008s |34.152MiB|
|66.smt2                                                                                    |  20.007s |23.864MiB|
|125.smt2                                                                                   |  20.007s |38.288MiB|
|55.smt2                                                                                    |  20.007s |21.94MiB|
|05.smt2                                                                                    |  20.007s |22.176MiB|
|163.smt2                                                                                   |  20.006s |73.996MiB|
|59.smt2                                                                                    |  20.006s |22.784MiB|
|43.smt2                                                                                    |  20.006s |21.188MiB|
|75.smt2                                                                                    |  20.006s |22.772MiB|
|151.smt2                                                                                   |  20.005s |33.964MiB|
|53.smt2                                                                                    |  20.005s |23.032MiB|
|92.smt2                                                                                    |  20.005s |21.848MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.192MiB|22.192MiB|0B| 0.0%|
|02.smt2                                                                                     |21.724MiB|21.724MiB|0B| 0.0%|
|03.smt2                                                                                     |21.836MiB|21.836MiB|0B| 0.0%|
|04.smt2                                                                                     |21.036MiB|21.036MiB|0B| 0.0%|
|05.smt2                                                                                     |22.176MiB|22.176MiB|0B| 0.0%|
|06.smt2                                                                                     |19.748MiB|19.748MiB|0B| 0.0%|
|07.smt2                                                                                     |21.488MiB|21.488MiB|0B| 0.0%|
|08.smt2                                                                                     |20.524MiB|20.524MiB|0B| 0.0%|
|09.smt2                                                                                     |20.86MiB|20.86MiB|0B| 0.0%|
|10.smt2                                                                                     |21.552MiB|21.552MiB|0B| 0.0%|
|100.smt2                                                                                    |22.78MiB|22.78MiB|0B| 0.0%|
|101.smt2                                                                                    |21.968MiB|21.968MiB|0B| 0.0%|
|102.smt2                                                                                    |23.916MiB|23.916MiB|0B| 0.0%|
|103.smt2                                                                                    |22.8MiB|22.8MiB|0B| 0.0%|
|104.smt2                                                                                    |23.724MiB|23.724MiB|0B| 0.0%|
|105.smt2                                                                                    |31.816MiB|31.816MiB|0B| 0.0%|
|106.smt2                                                                                    |34.152MiB|34.152MiB|0B| 0.0%|
|107.smt2                                                                                    |21.956MiB|21.956MiB|0B| 0.0%|
|108.smt2                                                                                    |31.904MiB|31.904MiB|0B| 0.0%|
|109.smt2                                                                                    |22.168MiB|22.168MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.192MiB|22.192MiB|0B| 0.0%|
|02.smt2                                                                                     |21.724MiB|21.724MiB|0B| 0.0%|
|03.smt2                                                                                     |21.836MiB|21.836MiB|0B| 0.0%|
|04.smt2                                                                                     |21.036MiB|21.036MiB|0B| 0.0%|
|05.smt2                                                                                     |22.176MiB|22.176MiB|0B| 0.0%|
|06.smt2                                                                                     |19.748MiB|19.748MiB|0B| 0.0%|
|07.smt2                                                                                     |21.488MiB|21.488MiB|0B| 0.0%|
|08.smt2                                                                                     |20.524MiB|20.524MiB|0B| 0.0%|
|09.smt2                                                                                     |20.86MiB|20.86MiB|0B| 0.0%|
|10.smt2                                                                                     |21.552MiB|21.552MiB|0B| 0.0%|
|100.smt2                                                                                    |22.78MiB|22.78MiB|0B| 0.0%|
|101.smt2                                                                                    |21.968MiB|21.968MiB|0B| 0.0%|
|102.smt2                                                                                    |23.916MiB|23.916MiB|0B| 0.0%|
|103.smt2                                                                                    |22.8MiB|22.8MiB|0B| 0.0%|
|104.smt2                                                                                    |23.724MiB|23.724MiB|0B| 0.0%|
|105.smt2                                                                                    |31.816MiB|31.816MiB|0B| 0.0%|
|106.smt2                                                                                    |34.152MiB|34.152MiB|0B| 0.0%|
|107.smt2                                                                                    |21.956MiB|21.956MiB|0B| 0.0%|
|108.smt2                                                                                    |31.904MiB|31.904MiB|0B| 0.0%|
|109.smt2                                                                                    |22.168MiB|22.168MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.192MiB|22.192MiB|0B| 0.0%|
|02.smt2                                                                                     |21.724MiB|21.724MiB|0B| 0.0%|
|03.smt2                                                                                     |21.836MiB|21.836MiB|0B| 0.0%|
|04.smt2                                                                                     |21.036MiB|21.036MiB|0B| 0.0%|
|05.smt2                                                                                     |22.176MiB|22.176MiB|0B| 0.0%|
|06.smt2                                                                                     |19.748MiB|19.748MiB|0B| 0.0%|
|07.smt2                                                                                     |21.488MiB|21.488MiB|0B| 0.0%|
|08.smt2                                                                                     |20.524MiB|20.524MiB|0B| 0.0%|
|09.smt2                                                                                     |20.86MiB|20.86MiB|0B| 0.0%|
|10.smt2                                                                                     |21.552MiB|21.552MiB|0B| 0.0%|
|100.smt2                                                                                    |22.78MiB|22.78MiB|0B| 0.0%|
|101.smt2                                                                                    |21.968MiB|21.968MiB|0B| 0.0%|
|102.smt2                                                                                    |23.916MiB|23.916MiB|0B| 0.0%|
|103.smt2                                                                                    |22.8MiB|22.8MiB|0B| 0.0%|
|104.smt2                                                                                    |23.724MiB|23.724MiB|0B| 0.0%|
|105.smt2                                                                                    |31.816MiB|31.816MiB|0B| 0.0%|
|106.smt2                                                                                    |34.152MiB|34.152MiB|0B| 0.0%|
|107.smt2                                                                                    |21.956MiB|21.956MiB|0B| 0.0%|
|108.smt2                                                                                    |31.904MiB|31.904MiB|0B| 0.0%|
|109.smt2                                                                                    |22.168MiB|22.168MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.192MiB|22.192MiB|0B| 0.0%|
|02.smt2                                                                                     |21.724MiB|21.724MiB|0B| 0.0%|
|03.smt2                                                                                     |21.836MiB|21.836MiB|0B| 0.0%|
|04.smt2                                                                                     |21.036MiB|21.036MiB|0B| 0.0%|
|05.smt2                                                                                     |22.176MiB|22.176MiB|0B| 0.0%|
|06.smt2                                                                                     |19.748MiB|19.748MiB|0B| 0.0%|
|07.smt2                                                                                     |21.488MiB|21.488MiB|0B| 0.0%|
|08.smt2                                                                                     |20.524MiB|20.524MiB|0B| 0.0%|
|09.smt2                                                                                     |20.86MiB|20.86MiB|0B| 0.0%|
|10.smt2                                                                                     |21.552MiB|21.552MiB|0B| 0.0%|
|100.smt2                                                                                    |22.78MiB|22.78MiB|0B| 0.0%|
|101.smt2                                                                                    |21.968MiB|21.968MiB|0B| 0.0%|
|102.smt2                                                                                    |23.916MiB|23.916MiB|0B| 0.0%|
|103.smt2                                                                                    |22.8MiB|22.8MiB|0B| 0.0%|
|104.smt2                                                                                    |23.724MiB|23.724MiB|0B| 0.0%|
|105.smt2                                                                                    |31.816MiB|31.816MiB|0B| 0.0%|
|106.smt2                                                                                    |34.152MiB|34.152MiB|0B| 0.0%|
|107.smt2                                                                                    |21.956MiB|21.956MiB|0B| 0.0%|
|108.smt2                                                                                    |31.904MiB|31.904MiB|0B| 0.0%|
|109.smt2                                                                                    |22.168MiB|22.168MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|182.smt2                                                                                   |  19.868s |274.0MiB|
|183.smt2                                                                                   |  19.929s |273.0MiB|
|185.smt2                                                                                   |  20.000s |245.0MiB|
|186.smt2                                                                                   |  19.939s |245.0MiB|
|181.smt2                                                                                   |  19.972s |155.0MiB|
|178.smt2                                                                                   |  20.010s |152.0MiB|
|179.smt2                                                                                   |  20.004s |146.0MiB|
|180.smt2                                                                                   |  19.952s |146.0MiB|
|172.smt2                                                                                   |  19.879s |144.0MiB|
|176.smt2                                                                                   |  19.909s |143.0MiB|
|173.smt2                                                                                   |  20.010s |138.0MiB|
|184.smt2                                                                                   |  19.951s |136.0MiB|
|174.smt2                                                                                   |  19.994s |132.0MiB|
|175.smt2                                                                                   |  19.465s |132.0MiB|
|169.smt2                                                                                   |  20.001s |78.576MiB|
|165.smt2                                                                                   |  19.989s |76.476MiB|
|163.smt2                                                                                   |  20.006s |73.996MiB|
|161.smt2                                                                                   |  20.002s |73.5MiB|
|168.smt2                                                                                   |  20.001s |67.428MiB|
|171.smt2                                                                                   |  20.010s |61.08MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|182.smt2                                                                                   |  19.868s |274.0MiB|
|183.smt2                                                                                   |  19.929s |273.0MiB|
|185.smt2                                                                                   |  20.000s |245.0MiB|
|186.smt2                                                                                   |  19.939s |245.0MiB|
|181.smt2                                                                                   |  19.972s |155.0MiB|
|178.smt2                                                                                   |  20.010s |152.0MiB|
|179.smt2                                                                                   |  20.004s |146.0MiB|
|180.smt2                                                                                   |  19.952s |146.0MiB|
|172.smt2                                                                                   |  19.879s |144.0MiB|
|176.smt2                                                                                   |  19.909s |143.0MiB|
|173.smt2                                                                                   |  20.010s |138.0MiB|
|184.smt2                                                                                   |  19.951s |136.0MiB|
|174.smt2                                                                                   |  19.994s |132.0MiB|
|175.smt2                                                                                   |  19.465s |132.0MiB|
|169.smt2                                                                                   |  20.001s |78.576MiB|
|165.smt2                                                                                   |  19.989s |76.476MiB|
|163.smt2                                                                                   |  20.006s |73.996MiB|
|161.smt2                                                                                   |  20.002s |73.5MiB|
|168.smt2                                                                                   |  20.001s |67.428MiB|
|171.smt2                                                                                   |  20.010s |61.08MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.884s  |  19.884s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.693s  |  19.693s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.904s  |  19.904s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |  19.901s  |  19.901s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |  18.488s  |  18.488s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.593s  |  19.593s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  19.933s  |  19.933s  |   0.000s  | 0.0%|
|110.smt2                                                                                    |  19.785s  |  19.785s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  19.644s  |  19.644s  |   0.000s  | 0.0%|
|112.smt2                                                                                    |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|114.smt2                                                                                    |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |  19.490s  |  19.490s  |   0.000s  | 0.0%|
|116.smt2                                                                                    |  19.914s  |  19.914s  |   0.000s  | 0.0%|
|117.smt2                                                                                    |  19.580s  |  19.580s  |   0.000s  | 0.0%|
|118.smt2                                                                                    |  19.871s  |  19.871s  |   0.000s  | 0.0%|
|119.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|12.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|120.smt2                                                                                    |  19.875s  |  19.875s  |   0.000s  | 0.0%|
|121.smt2                                                                                    |  19.802s  |  19.802s  |   0.000s  | 0.0%|
|122.smt2                                                                                    |  19.776s  |  19.776s  |   0.000s  | 0.0%|
|123.smt2                                                                                    |  19.820s  |  19.820s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|125.smt2                                                                                    |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|126.smt2                                                                                    |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|128.smt2                                                                                    |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|129.smt2                                                                                    |  19.854s  |  19.854s  |   0.000s  | 0.0%|
|13.smt2                                                                                     |  19.907s  |  19.907s  |   0.000s  | 0.0%|
|130.smt2                                                                                    |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|131.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|132.smt2                                                                                    |  19.658s  |  19.658s  |   0.000s  | 0.0%|
|133.smt2                                                                                    |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|134.smt2                                                                                    |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|135.smt2                                                                                    |  19.825s  |  19.825s  |   0.000s  | 0.0%|
|136.smt2                                                                                    |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|137.smt2                                                                                    |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|138.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|139.smt2                                                                                    |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|14.smt2                                                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |  19.897s  |  19.897s  |   0.000s  | 0.0%|
|141.smt2                                                                                    |  19.953s  |  19.953s  |   0.000s  | 0.0%|
|142.smt2                                                                                    |  19.588s  |  19.588s  |   0.000s  | 0.0%|
|143.smt2                                                                                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|144.smt2                                                                                    |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|145.smt2                                                                                    |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|146.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|147.smt2                                                                                    |  19.747s  |  19.747s  |   0.000s  | 0.0%|
|148.smt2                                                                                    |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |  19.904s  |  19.904s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|150.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|151.smt2                                                                                    |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|152.smt2                                                                                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|153.smt2                                                                                    |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|154.smt2                                                                                    |  19.853s  |  19.853s  |   0.000s  | 0.0%|
|155.smt2                                                                                    |  19.953s  |  19.953s  |   0.000s  | 0.0%|
|156.smt2                                                                                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|157.smt2                                                                                    |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|158.smt2                                                                                    |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|159.smt2                                                                                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|16.smt2                                                                                     |  19.817s  |  19.817s  |   0.000s  | 0.0%|
|160.smt2                                                                                    |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|161.smt2                                                                                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  19.653s  |  19.653s  |   0.000s  | 0.0%|
|163.smt2                                                                                    |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|164.smt2                                                                                    |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|165.smt2                                                                                    |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|166.smt2                                                                                    |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|168.smt2                                                                                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|169.smt2                                                                                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|17.smt2                                                                                     |  19.725s  |  19.725s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|171.smt2                                                                                    |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|172.smt2                                                                                    |  19.879s  |  19.879s  |   0.000s  | 0.0%|
|173.smt2                                                                                    |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|174.smt2                                                                                    |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|175.smt2                                                                                    |  19.465s  |  19.465s  |   0.000s  | 0.0%|
|176.smt2                                                                                    |  19.909s  |  19.909s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|178.smt2                                                                                    |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|18.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|180.smt2                                                                                    |  19.952s  |  19.952s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  19.868s  |  19.868s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  19.929s  |  19.929s  |   0.000s  | 0.0%|
|184.smt2                                                                                    |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|186.smt2                                                                                    |  19.939s  |  19.939s  |   0.000s  | 0.0%|
|19.smt2                                                                                     |  19.872s  |  19.872s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.949s  |  19.949s  |   0.000s  | 0.0%|
|21.smt2                                                                                     |  19.880s  |  19.880s  |   0.000s  | 0.0%|
|22.smt2                                                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|24.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|25.smt2                                                                                     |  19.618s  |  19.618s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|27.smt2                                                                                     |  19.923s  |  19.923s  |   0.000s  | 0.0%|
|28.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  19.887s  |  19.887s  |   0.000s  | 0.0%|
|30.smt2                                                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|31.smt2                                                                                     |  19.814s  |  19.814s  |   0.000s  | 0.0%|
|32.smt2                                                                                     |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|36.smt2                                                                                     |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|37.smt2                                                                                     |  19.870s  |  19.870s  |   0.000s  | 0.0%|
|38.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|39.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|42.smt2                                                                                     |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|43.smt2                                                                                     |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|44.smt2                                                                                     |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|45.smt2                                                                                     |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|46.smt2                                                                                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|47.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|48.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|49.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|50.smt2                                                                                     |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|51.smt2                                                                                     |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|52.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|53.smt2                                                                                     |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|55.smt2                                                                                     |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|56.smt2                                                                                     |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|57.smt2                                                                                     |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|59.smt2                                                                                     |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|60.smt2                                                                                     |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|61.smt2                                                                                     |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|62.smt2                                                                                     |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|63.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  19.829s  |  19.829s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|66.smt2                                                                                     |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|67.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|68.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|69.smt2                                                                                     |  19.898s  |  19.898s  |   0.000s  | 0.0%|
|70.smt2                                                                                     |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|71.smt2                                                                                     |  19.826s  |  19.826s  |   0.000s  | 0.0%|
|72.smt2                                                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|76.smt2                                                                                     |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|77.smt2                                                                                     |  19.943s  |  19.943s  |   0.000s  | 0.0%|
|78.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|79.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  19.828s  |  19.828s  |   0.000s  | 0.0%|
|81.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|82.smt2                                                                                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |  19.952s  |  19.952s  |   0.000s  | 0.0%|
|84.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|85.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|86.smt2                                                                                     |  19.864s  |  19.864s  |   0.000s  | 0.0%|
|87.smt2                                                                                     |  19.740s  |  19.740s  |   0.000s  | 0.0%|
|88.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|89.smt2                                                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  19.768s  |  19.768s  |   0.000s  | 0.0%|
|91.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|92.smt2                                                                                     |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |  19.769s  |  19.769s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|95.smt2                                                                                     |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|96.smt2                                                                                     |  19.688s  |  19.688s  |   0.000s  | 0.0%|
|97.smt2                                                                                     |  19.785s  |  19.785s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  19.922s  |  19.922s  |   0.000s  | 0.0%|
</details>
