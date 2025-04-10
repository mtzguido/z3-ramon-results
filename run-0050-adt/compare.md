Comparing data and data


# SUMMARY
- LHS tests = 2000
- RHS tests = 2000
- LHS success = 1995  (99.75%)
- RHS success = 1995  (99.75%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: adt
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: aa2292d5c4582de9e3454437851165fcfa04a7b7
Z3 branch: sls
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_DT_SAT
Z3 commit message: fixes to occurs check

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: adt
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: aa2292d5c4582de9e3454437851165fcfa04a7b7
Z3 branch: sls
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_DT_SAT
Z3 commit message: fixes to occurs check

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|blocksworld_from_0_2_0_to_2_0_0_negated_goal_bmc_3.smt2                                     |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|blocksworld_from_1_0_1_to_0_1_1_negated_goal_bmc_3.smt2                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|blocksworld_from_1_1_0_to_1_0_1_negated_goal_bmc_1.smt2                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|blocksworld_from_3_0_0_to_1_1_1_negated_goal_bmc_4.smt2                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|typed_v10l20001.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20005.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20007.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20008.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20010.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20011.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20014.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l20015.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20018.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20021.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l20023.cvc.smt2                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v10l20024.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20026.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20027.cvc.smt2                                                                    |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|typed_v10l20029.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20031.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|blocksworld_from_0_2_0_to_2_0_0_negated_goal_bmc_3.smt2                                     |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|blocksworld_from_1_0_1_to_0_1_1_negated_goal_bmc_3.smt2                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|blocksworld_from_1_1_0_to_1_0_1_negated_goal_bmc_1.smt2                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|blocksworld_from_3_0_0_to_1_1_1_negated_goal_bmc_4.smt2                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|typed_v10l20001.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20005.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20007.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20008.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20010.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20011.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20014.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l20015.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20018.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20021.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l20023.cvc.smt2                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v10l20024.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20026.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20027.cvc.smt2                                                                    |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|typed_v10l20029.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20031.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|blocksworld_from_0_2_0_to_2_0_0_negated_goal_bmc_3.smt2                                     |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|blocksworld_from_1_0_1_to_0_1_1_negated_goal_bmc_3.smt2                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|blocksworld_from_1_1_0_to_1_0_1_negated_goal_bmc_1.smt2                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|blocksworld_from_3_0_0_to_1_1_1_negated_goal_bmc_4.smt2                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|typed_v10l20001.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20005.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20007.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20008.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20010.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20011.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20014.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l20015.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20018.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20021.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l20023.cvc.smt2                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v10l20024.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20026.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20027.cvc.smt2                                                                    |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|typed_v10l20029.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20031.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|blocksworld_from_0_2_0_to_2_0_0_negated_goal_bmc_3.smt2                                     |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|blocksworld_from_1_0_1_to_0_1_1_negated_goal_bmc_3.smt2                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|blocksworld_from_1_1_0_to_1_0_1_negated_goal_bmc_1.smt2                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|blocksworld_from_3_0_0_to_1_1_1_negated_goal_bmc_4.smt2                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|typed_v10l20001.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20005.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20007.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20008.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20010.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20011.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20014.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l20015.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20018.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20021.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l20023.cvc.smt2                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v10l20024.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20026.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20027.cvc.smt2                                                                    |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|typed_v10l20029.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20031.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|vlsat3_h84.smt2                                                                            |  20.004s |177.0MiB|
|vlsat3_h03.smt2                                                                            |  20.002s |346.0MiB|
|vlsat3_h32.smt2                                                                            |  20.002s |117.0MiB|
|v1l30081.cvc.smt2                                                                          |  20.000s |18.496MiB|
|v5l30043.cvc.smt2                                                                          |  19.999s |18.756MiB|
|v3l20085.cvc.smt2                                                                          |  19.999s |18.48MiB|
|vlsat3_h30.smt2                                                                            |  19.998s |82.772MiB|
|vlsat3_h16.smt2                                                                            |  19.996s |80.516MiB|
|v1l50005.cvc.smt2                                                                          |  19.996s |18.54MiB|
|v5l70066.cvc.smt2                                                                          |  19.995s |18.52MiB|
|vlsat3_h26.smt2                                                                            |  19.995s |108.0MiB|
|vlsat3_h40.smt2                                                                            |  19.995s |244.0MiB|
|vlsat3_h13.smt2                                                                            |  19.994s |114.0MiB|
|v1l20040.cvc.smt2                                                                          |  19.991s |18.488MiB|
|v3l60061.cvc.smt2                                                                          |  19.990s |18.576MiB|
|v5l60033.cvc.smt2                                                                          |  19.990s |18.508MiB|
|v3l80041.cvc.smt2                                                                          |  19.988s |18.536MiB|
|vlsat3_h54.smt2                                                                            |  19.987s |112.0MiB|
|vlsat3_h24.smt2                                                                            |  19.985s |113.0MiB|
|v1l50022.cvc.smt2                                                                          |  19.985s |18.732MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|vlsat3_h84.smt2                                                                            |  20.004s |177.0MiB|
|vlsat3_h03.smt2                                                                            |  20.002s |346.0MiB|
|vlsat3_h32.smt2                                                                            |  20.002s |117.0MiB|
|v1l30081.cvc.smt2                                                                          |  20.000s |18.496MiB|
|v5l30043.cvc.smt2                                                                          |  19.999s |18.756MiB|
|v3l20085.cvc.smt2                                                                          |  19.999s |18.48MiB|
|vlsat3_h30.smt2                                                                            |  19.998s |82.772MiB|
|vlsat3_h16.smt2                                                                            |  19.996s |80.516MiB|
|v1l50005.cvc.smt2                                                                          |  19.996s |18.54MiB|
|v5l70066.cvc.smt2                                                                          |  19.995s |18.52MiB|
|vlsat3_h26.smt2                                                                            |  19.995s |108.0MiB|
|vlsat3_h40.smt2                                                                            |  19.995s |244.0MiB|
|vlsat3_h13.smt2                                                                            |  19.994s |114.0MiB|
|v1l20040.cvc.smt2                                                                          |  19.991s |18.488MiB|
|v3l60061.cvc.smt2                                                                          |  19.990s |18.576MiB|
|v5l60033.cvc.smt2                                                                          |  19.990s |18.508MiB|
|v3l80041.cvc.smt2                                                                          |  19.988s |18.536MiB|
|vlsat3_h54.smt2                                                                            |  19.987s |112.0MiB|
|vlsat3_h24.smt2                                                                            |  19.985s |113.0MiB|
|v1l50022.cvc.smt2                                                                          |  19.985s |18.732MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|blocksworld_from_0_2_0_to_2_0_0_negated_goal_bmc_3.smt2                                     |19.292MiB|19.292MiB|0B| 0.0%|
|blocksworld_from_1_0_1_to_0_1_1_negated_goal_bmc_3.smt2                                     |19.28MiB|19.28MiB|0B| 0.0%|
|blocksworld_from_1_1_0_to_1_0_1_negated_goal_bmc_1.smt2                                     |18.768MiB|18.768MiB|0B| 0.0%|
|blocksworld_from_3_0_0_to_1_1_1_negated_goal_bmc_4.smt2                                     |19.824MiB|19.824MiB|0B| 0.0%|
|typed_v10l20001.cvc.smt2                                                                    |18.252MiB|18.252MiB|0B| 0.0%|
|typed_v10l20005.cvc.smt2                                                                    |18.24MiB|18.24MiB|0B| 0.0%|
|typed_v10l20007.cvc.smt2                                                                    |18.344MiB|18.344MiB|0B| 0.0%|
|typed_v10l20008.cvc.smt2                                                                    |18.256MiB|18.256MiB|0B| 0.0%|
|typed_v10l20010.cvc.smt2                                                                    |18.512MiB|18.512MiB|0B| 0.0%|
|typed_v10l20011.cvc.smt2                                                                    |18.468MiB|18.468MiB|0B| 0.0%|
|typed_v10l20014.cvc.smt2                                                                    |18.32MiB|18.32MiB|0B| 0.0%|
|typed_v10l20015.cvc.smt2                                                                    |18.512MiB|18.512MiB|0B| 0.0%|
|typed_v10l20018.cvc.smt2                                                                    |18.276MiB|18.276MiB|0B| 0.0%|
|typed_v10l20021.cvc.smt2                                                                    |18.488MiB|18.488MiB|0B| 0.0%|
|typed_v10l20023.cvc.smt2                                                                    |18.372MiB|18.372MiB|0B| 0.0%|
|typed_v10l20024.cvc.smt2                                                                    |18.256MiB|18.256MiB|0B| 0.0%|
|typed_v10l20026.cvc.smt2                                                                    |18.272MiB|18.272MiB|0B| 0.0%|
|typed_v10l20027.cvc.smt2                                                                    |18.46MiB|18.46MiB|0B| 0.0%|
|typed_v10l20029.cvc.smt2                                                                    |18.512MiB|18.512MiB|0B| 0.0%|
|typed_v10l20031.cvc.smt2                                                                    |18.516MiB|18.516MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|blocksworld_from_0_2_0_to_2_0_0_negated_goal_bmc_3.smt2                                     |19.292MiB|19.292MiB|0B| 0.0%|
|blocksworld_from_1_0_1_to_0_1_1_negated_goal_bmc_3.smt2                                     |19.28MiB|19.28MiB|0B| 0.0%|
|blocksworld_from_1_1_0_to_1_0_1_negated_goal_bmc_1.smt2                                     |18.768MiB|18.768MiB|0B| 0.0%|
|blocksworld_from_3_0_0_to_1_1_1_negated_goal_bmc_4.smt2                                     |19.824MiB|19.824MiB|0B| 0.0%|
|typed_v10l20001.cvc.smt2                                                                    |18.252MiB|18.252MiB|0B| 0.0%|
|typed_v10l20005.cvc.smt2                                                                    |18.24MiB|18.24MiB|0B| 0.0%|
|typed_v10l20007.cvc.smt2                                                                    |18.344MiB|18.344MiB|0B| 0.0%|
|typed_v10l20008.cvc.smt2                                                                    |18.256MiB|18.256MiB|0B| 0.0%|
|typed_v10l20010.cvc.smt2                                                                    |18.512MiB|18.512MiB|0B| 0.0%|
|typed_v10l20011.cvc.smt2                                                                    |18.468MiB|18.468MiB|0B| 0.0%|
|typed_v10l20014.cvc.smt2                                                                    |18.32MiB|18.32MiB|0B| 0.0%|
|typed_v10l20015.cvc.smt2                                                                    |18.512MiB|18.512MiB|0B| 0.0%|
|typed_v10l20018.cvc.smt2                                                                    |18.276MiB|18.276MiB|0B| 0.0%|
|typed_v10l20021.cvc.smt2                                                                    |18.488MiB|18.488MiB|0B| 0.0%|
|typed_v10l20023.cvc.smt2                                                                    |18.372MiB|18.372MiB|0B| 0.0%|
|typed_v10l20024.cvc.smt2                                                                    |18.256MiB|18.256MiB|0B| 0.0%|
|typed_v10l20026.cvc.smt2                                                                    |18.272MiB|18.272MiB|0B| 0.0%|
|typed_v10l20027.cvc.smt2                                                                    |18.46MiB|18.46MiB|0B| 0.0%|
|typed_v10l20029.cvc.smt2                                                                    |18.512MiB|18.512MiB|0B| 0.0%|
|typed_v10l20031.cvc.smt2                                                                    |18.516MiB|18.516MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|blocksworld_from_0_2_0_to_2_0_0_negated_goal_bmc_3.smt2                                     |19.292MiB|19.292MiB|0B| 0.0%|
|blocksworld_from_1_0_1_to_0_1_1_negated_goal_bmc_3.smt2                                     |19.28MiB|19.28MiB|0B| 0.0%|
|blocksworld_from_1_1_0_to_1_0_1_negated_goal_bmc_1.smt2                                     |18.768MiB|18.768MiB|0B| 0.0%|
|blocksworld_from_3_0_0_to_1_1_1_negated_goal_bmc_4.smt2                                     |19.824MiB|19.824MiB|0B| 0.0%|
|typed_v10l20001.cvc.smt2                                                                    |18.252MiB|18.252MiB|0B| 0.0%|
|typed_v10l20005.cvc.smt2                                                                    |18.24MiB|18.24MiB|0B| 0.0%|
|typed_v10l20007.cvc.smt2                                                                    |18.344MiB|18.344MiB|0B| 0.0%|
|typed_v10l20008.cvc.smt2                                                                    |18.256MiB|18.256MiB|0B| 0.0%|
|typed_v10l20010.cvc.smt2                                                                    |18.512MiB|18.512MiB|0B| 0.0%|
|typed_v10l20011.cvc.smt2                                                                    |18.468MiB|18.468MiB|0B| 0.0%|
|typed_v10l20014.cvc.smt2                                                                    |18.32MiB|18.32MiB|0B| 0.0%|
|typed_v10l20015.cvc.smt2                                                                    |18.512MiB|18.512MiB|0B| 0.0%|
|typed_v10l20018.cvc.smt2                                                                    |18.276MiB|18.276MiB|0B| 0.0%|
|typed_v10l20021.cvc.smt2                                                                    |18.488MiB|18.488MiB|0B| 0.0%|
|typed_v10l20023.cvc.smt2                                                                    |18.372MiB|18.372MiB|0B| 0.0%|
|typed_v10l20024.cvc.smt2                                                                    |18.256MiB|18.256MiB|0B| 0.0%|
|typed_v10l20026.cvc.smt2                                                                    |18.272MiB|18.272MiB|0B| 0.0%|
|typed_v10l20027.cvc.smt2                                                                    |18.46MiB|18.46MiB|0B| 0.0%|
|typed_v10l20029.cvc.smt2                                                                    |18.512MiB|18.512MiB|0B| 0.0%|
|typed_v10l20031.cvc.smt2                                                                    |18.516MiB|18.516MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|blocksworld_from_0_2_0_to_2_0_0_negated_goal_bmc_3.smt2                                     |19.292MiB|19.292MiB|0B| 0.0%|
|blocksworld_from_1_0_1_to_0_1_1_negated_goal_bmc_3.smt2                                     |19.28MiB|19.28MiB|0B| 0.0%|
|blocksworld_from_1_1_0_to_1_0_1_negated_goal_bmc_1.smt2                                     |18.768MiB|18.768MiB|0B| 0.0%|
|blocksworld_from_3_0_0_to_1_1_1_negated_goal_bmc_4.smt2                                     |19.824MiB|19.824MiB|0B| 0.0%|
|typed_v10l20001.cvc.smt2                                                                    |18.252MiB|18.252MiB|0B| 0.0%|
|typed_v10l20005.cvc.smt2                                                                    |18.24MiB|18.24MiB|0B| 0.0%|
|typed_v10l20007.cvc.smt2                                                                    |18.344MiB|18.344MiB|0B| 0.0%|
|typed_v10l20008.cvc.smt2                                                                    |18.256MiB|18.256MiB|0B| 0.0%|
|typed_v10l20010.cvc.smt2                                                                    |18.512MiB|18.512MiB|0B| 0.0%|
|typed_v10l20011.cvc.smt2                                                                    |18.468MiB|18.468MiB|0B| 0.0%|
|typed_v10l20014.cvc.smt2                                                                    |18.32MiB|18.32MiB|0B| 0.0%|
|typed_v10l20015.cvc.smt2                                                                    |18.512MiB|18.512MiB|0B| 0.0%|
|typed_v10l20018.cvc.smt2                                                                    |18.276MiB|18.276MiB|0B| 0.0%|
|typed_v10l20021.cvc.smt2                                                                    |18.488MiB|18.488MiB|0B| 0.0%|
|typed_v10l20023.cvc.smt2                                                                    |18.372MiB|18.372MiB|0B| 0.0%|
|typed_v10l20024.cvc.smt2                                                                    |18.256MiB|18.256MiB|0B| 0.0%|
|typed_v10l20026.cvc.smt2                                                                    |18.272MiB|18.272MiB|0B| 0.0%|
|typed_v10l20027.cvc.smt2                                                                    |18.46MiB|18.46MiB|0B| 0.0%|
|typed_v10l20029.cvc.smt2                                                                    |18.512MiB|18.512MiB|0B| 0.0%|
|typed_v10l20031.cvc.smt2                                                                    |18.516MiB|18.516MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|vlsat3_h03.smt2                                                                            |  20.002s |346.0MiB|
|vlsat3_h40.smt2                                                                            |  19.995s |244.0MiB|
|vlsat3_h00.smt2                                                                            |  14.805s |187.0MiB|
|vlsat3_h84.smt2                                                                            |  20.004s |177.0MiB|
|vlsat3_h33.smt2                                                                            |  19.982s |131.0MiB|
|vlsat3_h32.smt2                                                                            |  20.002s |117.0MiB|
|vlsat3_h13.smt2                                                                            |  19.994s |114.0MiB|
|vlsat3_h24.smt2                                                                            |  19.985s |113.0MiB|
|vlsat3_h54.smt2                                                                            |  19.987s |112.0MiB|
|vlsat3_h26.smt2                                                                            |  19.995s |108.0MiB|
|vlsat3_h30.smt2                                                                            |  19.998s |82.772MiB|
|vlsat3_h16.smt2                                                                            |  19.996s |80.516MiB|
|blocksworld_from_3_0_0_to_1_1_1_negated_goal_bmc_4.smt2                                    |   0.028s |19.824MiB|
|blocksworld_from_0_2_0_to_2_0_0_negated_goal_bmc_3.smt2                                    |   0.021s |19.292MiB|
|blocksworld_from_1_0_1_to_0_1_1_negated_goal_bmc_3.smt2                                    |   0.014s |19.28MiB|
|typed_v5l60038.cvc.smt2                                                                    |   0.013s |19.116MiB|
|v5l60008.cvc.smt2                                                                          |   0.008s |19.016MiB|
|typed_v10l70038.cvc.smt2                                                                   |   0.007s |18.816MiB|
|typed_v10l40024.cvc.smt2                                                                   |   0.006s |18.796MiB|
|v1l80100.cvc.smt2                                                                          |  19.981s |18.792MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|vlsat3_h03.smt2                                                                            |  20.002s |346.0MiB|
|vlsat3_h40.smt2                                                                            |  19.995s |244.0MiB|
|vlsat3_h00.smt2                                                                            |  14.805s |187.0MiB|
|vlsat3_h84.smt2                                                                            |  20.004s |177.0MiB|
|vlsat3_h33.smt2                                                                            |  19.982s |131.0MiB|
|vlsat3_h32.smt2                                                                            |  20.002s |117.0MiB|
|vlsat3_h13.smt2                                                                            |  19.994s |114.0MiB|
|vlsat3_h24.smt2                                                                            |  19.985s |113.0MiB|
|vlsat3_h54.smt2                                                                            |  19.987s |112.0MiB|
|vlsat3_h26.smt2                                                                            |  19.995s |108.0MiB|
|vlsat3_h30.smt2                                                                            |  19.998s |82.772MiB|
|vlsat3_h16.smt2                                                                            |  19.996s |80.516MiB|
|blocksworld_from_3_0_0_to_1_1_1_negated_goal_bmc_4.smt2                                    |   0.028s |19.824MiB|
|blocksworld_from_0_2_0_to_2_0_0_negated_goal_bmc_3.smt2                                    |   0.021s |19.292MiB|
|blocksworld_from_1_0_1_to_0_1_1_negated_goal_bmc_3.smt2                                    |   0.014s |19.28MiB|
|typed_v5l60038.cvc.smt2                                                                    |   0.013s |19.116MiB|
|v5l60008.cvc.smt2                                                                          |   0.008s |19.016MiB|
|typed_v10l70038.cvc.smt2                                                                   |   0.007s |18.816MiB|
|typed_v10l40024.cvc.smt2                                                                   |   0.006s |18.796MiB|
|v1l80100.cvc.smt2                                                                          |  19.981s |18.792MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|blocksworld_from_0_2_0_to_2_0_0_negated_goal_bmc_3.smt2                                     |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|blocksworld_from_1_0_1_to_0_1_1_negated_goal_bmc_3.smt2                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|blocksworld_from_1_1_0_to_1_0_1_negated_goal_bmc_1.smt2                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|blocksworld_from_3_0_0_to_1_1_1_negated_goal_bmc_4.smt2                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|typed_v10l20001.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20005.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20007.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20008.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20010.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20011.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20014.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l20015.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20018.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20021.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l20023.cvc.smt2                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v10l20024.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20026.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20027.cvc.smt2                                                                    |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|typed_v10l20029.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20031.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20035.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20037.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20038.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20039.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20043.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20048.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l20050.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20064.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20065.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l20067.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20069.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20071.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l20073.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20075.cvc.smt2                                                                    |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v10l20077.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l20079.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20081.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l20082.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l20084.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20085.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l20087.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20091.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l20092.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20093.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20094.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l20098.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l20099.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l30001.cvc.smt2                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v10l30002.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30003.cvc.smt2                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v10l30004.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l30006.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l30007.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l30008.cvc.smt2                                                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|typed_v10l30016.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l30017.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30018.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l30019.cvc.smt2                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v10l30021.cvc.smt2                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v10l30022.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l30025.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30026.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l30027.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30029.cvc.smt2                                                                    |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|typed_v10l30032.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l30034.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30035.cvc.smt2                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v10l30036.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l30040.cvc.smt2                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v10l30041.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l30044.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l30045.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30046.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l30047.cvc.smt2                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v10l30048.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l30049.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l30051.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l30052.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l30053.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30055.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l30056.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l30057.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l30058.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30059.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30063.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l30064.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30066.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30067.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30072.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l30073.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l30074.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30075.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l30076.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30078.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30080.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30082.cvc.smt2                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v10l30086.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30087.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30090.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l30092.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30094.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30095.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30096.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l30099.cvc.smt2                                                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|typed_v10l40011.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l40022.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l40023.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l40024.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l40025.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l40029.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l40037.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l40039.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l40040.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l40042.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l40043.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l40045.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l40046.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l40047.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l40049.cvc.smt2                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v10l40054.cvc.smt2                                                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|typed_v10l40057.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l40059.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l40061.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l40068.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l40069.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l40073.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l40075.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l40076.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l40079.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l40080.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l40083.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l40086.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l40087.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l40089.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l40090.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l40091.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l40097.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l40098.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l40099.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50002.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50003.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l50008.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50010.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l50012.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50013.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50020.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l50025.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50026.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l50029.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l50030.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l50042.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l50043.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50044.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l50045.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50046.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50049.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50050.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l50059.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l50062.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l50063.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l50064.cvc.smt2                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v10l50066.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l50067.cvc.smt2                                                                    |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|typed_v10l50070.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l50075.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l50078.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50079.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50080.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50081.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l50083.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l50086.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50094.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l50097.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l50098.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l60002.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l60004.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l60005.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l60007.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60010.cvc.smt2                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v10l60011.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60017.cvc.smt2                                                                    |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v10l60018.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60020.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l60022.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60027.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60028.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l60029.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l60031.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60033.cvc.smt2                                                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|typed_v10l60036.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60037.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60038.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60042.cvc.smt2                                                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|typed_v10l60043.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60046.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l60050.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60051.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l60055.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60061.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l60066.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60071.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l60075.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60078.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60079.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l60084.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l60090.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l60093.cvc.smt2                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v10l60098.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l70002.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70006.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l70008.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70011.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70012.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l70015.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70016.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l70024.cvc.smt2                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v10l70025.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70027.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l70028.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70029.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70032.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l70038.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70039.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l70043.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70047.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70048.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70053.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l70054.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70055.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70060.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70061.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l70066.cvc.smt2                                                                    |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v10l70067.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70069.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l70070.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l70075.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l70078.cvc.smt2                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v10l70079.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l70087.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l70094.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l70099.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l70100.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l80008.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l80012.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l80014.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l80020.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l80023.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l80025.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l80026.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l80031.cvc.smt2                                                                    |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v10l80039.cvc.smt2                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v10l80042.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l80045.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l80046.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l80048.cvc.smt2                                                                    |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v10l80049.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l80050.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l80056.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l80057.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l80059.cvc.smt2                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v10l80060.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l80071.cvc.smt2                                                                    |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v10l80072.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l80078.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l80081.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l80085.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l80091.cvc.smt2                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v10l80096.cvc.smt2                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v10l90001.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l90003.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l90005.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l90006.cvc.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v10l90011.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l90019.cvc.smt2                                                                    |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v10l90024.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l90027.cvc.smt2                                                                    |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|typed_v10l90035.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l90036.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l90039.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l90040.cvc.smt2                                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v10l90041.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l90044.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l90051.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l90055.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l90059.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l90068.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l90070.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l90072.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l90074.cvc.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v10l90078.cvc.smt2                                                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|typed_v10l90080.cvc.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v10l90089.cvc.smt2                                                                    |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v10l90091.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l90092.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l90097.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v10l90100.cvc.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l20001.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v1l20002.cvc.smt2                                                                     |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|typed_v1l20004.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l20008.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v1l20010.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l20011.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l20012.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v1l20014.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l20015.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l20017.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v1l20022.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l20023.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l20027.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v1l20029.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l20031.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v1l20039.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v1l20044.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v1l20049.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l20054.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l20057.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l20064.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l20066.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v1l20067.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v1l20068.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l20069.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v1l20072.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v1l20073.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l20074.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v1l20075.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l20076.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l20077.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l20080.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l20083.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l20086.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v1l20093.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l30022.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v1l30042.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l30061.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v1l30063.cvc.smt2                                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|typed_v1l30074.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l30076.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v1l30078.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l30081.cvc.smt2                                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|typed_v1l30082.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l30083.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l30091.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v1l30092.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v1l30093.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v1l30095.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v1l30100.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l40010.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l40022.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v1l40038.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v1l40048.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l40069.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v1l40077.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l40078.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l40095.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v1l40098.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l50029.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l50071.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l50072.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l50076.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v1l50090.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l50093.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v1l60029.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v1l60046.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l60048.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v1l60061.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v1l60066.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v1l60088.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l60094.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l70007.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l70087.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v1l80032.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l80073.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v1l80093.cvc.smt2                                                                     |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|typed_v1l90027.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v1l90060.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l20002.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20004.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20005.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20011.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20013.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20018.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v2l20019.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20023.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l20029.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l20030.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l20031.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l20033.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l20034.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l20038.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20039.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v2l20046.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20047.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l20048.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20052.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l20053.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20054.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l20055.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l20056.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l20057.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20058.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l20060.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l20064.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l20066.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20067.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l20068.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l20070.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v2l20071.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20073.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20074.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l20079.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20082.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20084.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20091.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l20093.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l20095.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l20096.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v2l20097.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l20100.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l30003.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l30010.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l30011.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l30015.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l30024.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v2l30025.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l30026.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l30028.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l30032.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l30035.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l30039.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v2l30045.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l30047.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v2l30048.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v2l30054.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l30055.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l30058.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l30060.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l30067.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l30068.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l30077.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l30080.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l30081.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l30087.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v2l30088.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l30094.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l40002.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l40003.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v2l40012.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l40014.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l40018.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v2l40019.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l40023.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l40032.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l40037.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l40039.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l40042.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l40049.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l40053.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l40057.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l40066.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v2l40080.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v2l40088.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l40089.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l40100.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l50010.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l50014.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l50029.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l50036.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l50037.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l50040.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l50046.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l50056.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l50062.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v2l50064.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l50066.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l50067.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l50076.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l50078.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v2l50084.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l50095.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l50098.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l60016.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l60022.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l60032.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l60035.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l60039.cvc.smt2                                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|typed_v2l60053.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l60073.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l60081.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l60086.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l60096.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l60098.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v2l60099.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l60100.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l70013.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l70019.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l70024.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l70029.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l70032.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v2l70040.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l70059.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l70061.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l70091.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l70096.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v2l80013.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l80031.cvc.smt2                                                                     |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|typed_v2l90007.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v2l90012.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l90021.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v2l90029.cvc.smt2                                                                     |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|typed_v2l90064.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v3l20003.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l20006.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l20007.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l20009.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l20013.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l20015.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l20016.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l20019.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v3l20023.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l20029.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l20031.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l20039.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l20040.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l20043.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l20044.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l20045.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l20048.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l20049.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l20051.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l20054.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l20056.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l20058.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l20060.cvc.smt2                                                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|typed_v3l20063.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l20064.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v3l20067.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l20074.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l20076.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l20078.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l20079.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v3l20080.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l20081.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l20083.cvc.smt2                                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|typed_v3l20085.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l20087.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l20088.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l20093.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l20094.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l20097.cvc.smt2                                                                     |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|typed_v3l20098.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l20099.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l30003.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l30004.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v3l30008.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l30011.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l30013.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l30019.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l30021.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l30024.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l30030.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l30032.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l30033.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l30037.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l30043.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l30045.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v3l30048.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l30049.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l30050.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l30055.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l30056.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l30058.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l30059.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v3l30060.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v3l30062.cvc.smt2                                                                     |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|typed_v3l30064.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l30065.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l30069.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l30071.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v3l30078.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l30084.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v3l30085.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l30086.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l30093.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l40004.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l40017.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l40020.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l40021.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l40031.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l40035.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l40036.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l40038.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l40044.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l40048.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v3l40049.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l40050.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l40054.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l40057.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l40059.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l40073.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l40076.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l40077.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l40080.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l40090.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v3l40092.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l40093.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l40097.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v3l40099.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l50004.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l50005.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l50006.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l50007.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l50011.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l50012.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v3l50017.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l50026.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l50040.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l50048.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l50052.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l50057.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l50058.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l50062.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l50063.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v3l50065.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l50066.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l50068.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l50070.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v3l50076.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l50077.cvc.smt2                                                                     |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|typed_v3l50082.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l50088.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v3l50090.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l50091.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l50098.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l60005.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v3l60029.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l60032.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l60039.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v3l60053.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l60061.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l60062.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l60063.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l60065.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v3l60067.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l60071.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l60074.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l60078.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v3l60093.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l70002.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l70009.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l70014.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v3l70018.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l70020.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l70046.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l70053.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l70056.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l70061.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l70072.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v3l70086.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v3l70088.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l70089.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l70090.cvc.smt2                                                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|typed_v3l70093.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l70094.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l70096.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v3l70097.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l80001.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l80003.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l80005.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v3l80007.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v3l80014.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l80040.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l80050.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v3l80057.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l80060.cvc.smt2                                                                     |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|typed_v3l80075.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v3l80082.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v3l80091.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l90004.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v3l90017.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v3l90022.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v3l90032.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v3l90034.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l90051.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v3l90057.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v3l90066.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v3l90098.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l20004.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l20007.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l20009.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l20010.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v5l20011.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l20013.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l20017.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l20018.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l20019.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l20021.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l20025.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l20029.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l20030.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l20031.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l20035.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l20036.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l20038.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l20039.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l20044.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l20046.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l20048.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v5l20051.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l20052.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l20053.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l20057.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l20058.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l20062.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l20066.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l20067.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l20069.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l20071.cvc.smt2                                                                     |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|typed_v5l20073.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l20074.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l20078.cvc.smt2                                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|typed_v5l20079.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l20083.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l20084.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v5l20090.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l20095.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v5l20096.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l20100.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l30002.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l30009.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l30012.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l30016.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l30025.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l30026.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v5l30027.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l30029.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l30034.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l30037.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l30038.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l30040.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l30044.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l30050.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l30052.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l30054.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l30055.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l30056.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l30057.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l30060.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v5l30066.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l30071.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l30073.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l30077.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v5l30078.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l30079.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l30082.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l30083.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l30086.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l30089.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l30095.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l30096.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l30097.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l30098.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l30099.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v5l30100.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l40003.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l40007.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l40010.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v5l40011.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l40013.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v5l40016.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v5l40017.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l40020.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l40025.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l40029.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l40030.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l40032.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l40037.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l40040.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l40043.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l40044.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l40045.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l40049.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v5l40056.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l40059.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l40060.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l40061.cvc.smt2                                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|typed_v5l40072.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l40073.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l40074.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l40077.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l40080.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l40081.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l40083.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v5l40088.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l40089.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l40090.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v5l40091.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v5l40093.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l40097.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l40098.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l50003.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v5l50004.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l50008.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l50013.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l50014.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l50015.cvc.smt2                                                                     |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|typed_v5l50017.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l50018.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l50020.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l50026.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l50032.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l50035.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v5l50047.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l50048.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l50053.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l50056.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l50057.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l50058.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l50063.cvc.smt2                                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|typed_v5l50064.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v5l50068.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l50074.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l50075.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l50082.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l50084.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l50087.cvc.smt2                                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|typed_v5l50092.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v5l50095.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l50096.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v5l60007.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l60009.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l60021.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l60024.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l60025.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l60030.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l60031.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v5l60032.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l60033.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l60038.cvc.smt2                                                                     |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|typed_v5l60043.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l60051.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l60057.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l60061.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l60066.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l60068.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l60076.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v5l60079.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l60085.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l60093.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l70001.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l70006.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l70007.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l70008.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l70016.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l70022.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l70024.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l70025.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l70026.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l70028.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v5l70031.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l70036.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l70046.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l70051.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l70052.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l70064.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v5l70071.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l70078.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l70085.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l70089.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l70093.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l70094.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l70095.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l80006.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v5l80007.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l80009.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l80010.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l80011.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l80017.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l80019.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l80028.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l80029.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l80036.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l80040.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l80044.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l80047.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v5l80048.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l80049.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l80063.cvc.smt2                                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|typed_v5l80067.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l80068.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l80070.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l80086.cvc.smt2                                                                     |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|typed_v5l80087.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l90002.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l90003.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l90025.cvc.smt2                                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|typed_v5l90027.cvc.smt2                                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|typed_v5l90028.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l90031.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l90041.cvc.smt2                                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|typed_v5l90051.cvc.smt2                                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|typed_v5l90052.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l90057.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l90058.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l90059.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|typed_v5l90072.cvc.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|typed_v5l90074.cvc.smt2                                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l20001.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l20004.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l20007.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l20008.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l20009.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l20016.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20017.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l20019.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l20022.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l20024.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l20025.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20026.cvc.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v10l20032.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l20033.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20035.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20036.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l20038.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l20041.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20042.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l20043.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l20044.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l20045.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20046.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l20047.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l20052.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20054.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l20055.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l20056.cvc.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v10l20059.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20060.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20063.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l20069.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20070.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l20073.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20075.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20076.cvc.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v10l20077.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20078.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l20079.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l20082.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l20083.cvc.smt2                                                                          |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|v10l20085.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20086.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20088.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20091.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l20092.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l20094.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l20095.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l20096.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l30002.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l30007.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l30008.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l30010.cvc.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v10l30011.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l30013.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l30014.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l30016.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l30017.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l30018.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l30019.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l30020.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l30021.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l30024.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l30026.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l30028.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l30032.cvc.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|v10l30033.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l30035.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l30037.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l30040.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l30043.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l30045.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l30046.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l30048.cvc.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v10l30052.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l30054.cvc.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v10l30057.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l30059.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l30062.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l30065.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l30067.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l30070.cvc.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v10l30072.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l30074.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l30078.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l30080.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l30083.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l30084.cvc.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v10l30085.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l30087.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l30091.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l30097.cvc.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v10l30100.cvc.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v10l40010.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40011.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40014.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40015.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40017.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l40024.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l40026.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l40029.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40030.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40033.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l40037.cvc.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v10l40038.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40039.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40043.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40044.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l40046.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l40047.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40052.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l40053.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l40054.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40055.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l40061.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40066.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40068.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l40071.cvc.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v10l40072.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l40073.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l40074.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l40076.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l40078.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40081.cvc.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v10l40083.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l40086.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40088.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40089.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40091.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l40092.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l40094.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l40095.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l40096.cvc.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v10l50001.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50002.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50007.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l50010.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50014.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50023.cvc.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v10l50024.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50029.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50030.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l50031.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50033.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l50035.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50037.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l50038.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l50041.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50043.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l50049.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50050.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50052.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50054.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l50058.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50060.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l50062.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l50064.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50066.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l50068.cvc.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v10l50070.cvc.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v10l50071.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50072.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l50073.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50079.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l50081.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50082.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l50083.cvc.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v10l50086.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l50091.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l50092.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l50093.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l50097.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50098.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l50099.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l60005.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60014.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l60016.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l60018.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60022.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l60024.cvc.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v10l60027.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60028.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60029.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60030.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60031.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l60034.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60035.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l60037.cvc.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|v10l60044.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l60046.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l60048.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60050.cvc.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v10l60052.cvc.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v10l60053.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60055.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l60062.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l60063.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60066.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l60067.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l60068.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l60069.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l60070.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l60071.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60072.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l60081.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l60082.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l60083.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l60084.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60086.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l60087.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l60088.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l60089.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60092.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60095.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l60096.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l60097.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l60099.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l60100.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l70005.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l70008.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l70009.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l70014.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l70015.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l70017.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l70022.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l70023.cvc.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v10l70026.cvc.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v10l70029.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l70032.cvc.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v10l70035.cvc.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v10l70036.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l70038.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l70040.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l70041.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l70052.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l70054.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l70059.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l70063.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l70065.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l70069.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l70071.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l70072.cvc.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v10l70076.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l70079.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l70080.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l70081.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l70087.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l70093.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l70095.cvc.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v10l70100.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l80002.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l80003.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l80004.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l80010.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l80014.cvc.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v10l80016.cvc.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v10l80022.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l80025.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l80032.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l80033.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l80038.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l80039.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l80043.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l80050.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l80053.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l80055.cvc.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v10l80056.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l80057.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l80065.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l80068.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l80073.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l80074.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l80079.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l80084.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l80088.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l80090.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l80092.cvc.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v10l80096.cvc.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v10l80098.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l90008.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l90013.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l90022.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l90023.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l90025.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l90027.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l90038.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l90039.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l90041.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l90042.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l90044.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l90047.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l90052.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l90054.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l90055.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l90057.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l90059.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l90061.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l90067.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l90069.cvc.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v10l90071.cvc.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v10l90075.cvc.smt2                                                                          |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|v10l90077.cvc.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v10l90081.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l90089.cvc.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v10l90091.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v10l90094.cvc.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l20001.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l20003.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l20004.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v1l20006.cvc.smt2                                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|v1l20008.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l20010.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l20011.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v1l20014.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l20015.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v1l20017.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l20022.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l20026.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l20027.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l20032.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l20033.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l20035.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v1l20036.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l20038.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l20039.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v1l20040.cvc.smt2                                                                           |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|v1l20046.cvc.smt2                                                                           |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|v1l20049.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l20052.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v1l20053.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l20054.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v1l20058.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l20060.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v1l20061.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l20062.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l20069.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l20070.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l20077.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l20080.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v1l20081.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l20087.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l20090.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l20095.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l20096.cvc.smt2                                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|v1l20097.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l20098.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v1l20099.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l30003.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l30013.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l30019.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l30020.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l30024.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l30025.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v1l30026.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v1l30043.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l30045.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l30047.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l30050.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l30052.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l30053.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l30058.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l30069.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l30073.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v1l30077.cvc.smt2                                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|v1l30080.cvc.smt2                                                                           |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|v1l30081.cvc.smt2                                                                           |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|v1l30085.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l30086.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l30088.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l30090.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l30095.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l30098.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l40003.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l40005.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l40010.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v1l40020.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v1l40024.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l40025.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l40027.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l40028.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v1l40032.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l40036.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l40046.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l40055.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v1l40056.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l40058.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v1l40063.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v1l40064.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l40067.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l40071.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l40074.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l40078.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l40082.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l40091.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l40095.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l40096.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l50003.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l50005.cvc.smt2                                                                           |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|v1l50012.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l50022.cvc.smt2                                                                           |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|v1l50025.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l50030.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l50045.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l50047.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l50065.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l50066.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l50071.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l50072.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l50075.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l50078.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l50081.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l50093.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l50100.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l60008.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l60024.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l60038.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l60040.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l60049.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l60064.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l60066.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l60075.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v1l60079.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l60081.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l60099.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l70003.cvc.smt2                                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|v1l70006.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l70007.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l70021.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l70035.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l70059.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l70062.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l70068.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l70098.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l80004.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l80021.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v1l80028.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l80035.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l80044.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l80056.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v1l80063.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v1l80072.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v1l80100.cvc.smt2                                                                           |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|v1l90004.cvc.smt2                                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|v1l90025.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v1l90035.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v2l20001.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v2l20002.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l20005.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l20007.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l20009.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l20010.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l20011.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l20020.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l20021.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l20022.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l20023.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l20024.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l20030.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l20033.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l20034.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l20035.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l20038.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l20040.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l20041.cvc.smt2                                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|v2l20043.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l20044.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l20045.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l20048.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l20049.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l20053.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l20059.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v2l20061.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l20062.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l20063.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l20065.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l20068.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l20070.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l20072.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l20073.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l20075.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l20076.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l20079.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l20080.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l20094.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v2l20097.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l20100.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l30001.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l30004.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l30006.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l30007.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l30009.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l30010.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l30016.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v2l30017.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l30018.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l30019.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l30021.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l30022.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l30023.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l30032.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l30033.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l30034.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l30043.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l30046.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l30047.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l30051.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l30052.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v2l30061.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l30062.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v2l30068.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l30069.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l30070.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l30072.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l30073.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l30078.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l30079.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l30081.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l30086.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l30090.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l30091.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l30093.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l30096.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v2l40006.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l40009.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l40012.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l40014.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l40020.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l40023.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l40030.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l40036.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l40038.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l40039.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l40043.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v2l40052.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l40053.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l40061.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v2l40063.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l40069.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l40075.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l40076.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l40077.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l40078.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l40080.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l40081.cvc.smt2                                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|v2l40082.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l40090.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l50004.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l50012.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l50015.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l50027.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l50030.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l50033.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l50035.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l50037.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l50042.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l50047.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l50050.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l50052.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l50056.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l50059.cvc.smt2                                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|v2l50060.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l50064.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l50073.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l50074.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l50079.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l50081.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l50088.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l50090.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l50096.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l50097.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l50100.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l60004.cvc.smt2                                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|v2l60007.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l60012.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v2l60017.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l60027.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l60031.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l60033.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l60037.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l60045.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l60054.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l60057.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v2l60072.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l60075.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l60076.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v2l60080.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l60088.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l60096.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l60097.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l60098.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v2l70005.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l70009.cvc.smt2                                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|v2l70010.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v2l70014.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l70020.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l70030.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l70038.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l70046.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l70047.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v2l70055.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v2l70058.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v2l70066.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l70070.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l70072.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l70073.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v2l70081.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l70083.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l80020.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l80032.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v2l80061.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v2l80070.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l80083.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v2l80098.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v2l90007.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v2l90044.cvc.smt2                                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|v2l90059.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v2l90065.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v2l90070.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v2l90079.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v2l90086.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20003.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l20004.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l20005.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v3l20009.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l20010.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v3l20011.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20012.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20013.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v3l20022.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20024.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20025.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20026.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v3l20030.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l20033.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l20035.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l20038.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l20039.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20042.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l20044.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l20045.cvc.smt2                                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|v3l20046.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l20047.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v3l20050.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l20056.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20057.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l20059.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20061.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l20064.cvc.smt2                                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|v3l20065.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l20067.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l20068.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l20070.cvc.smt2                                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|v3l20071.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20074.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20082.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l20083.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20084.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20085.cvc.smt2                                                                           |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|v3l20086.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20088.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l20089.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l20091.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l20092.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l20093.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20096.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20097.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l20098.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v3l30001.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30003.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l30004.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l30006.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30007.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30008.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30010.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l30011.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l30012.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l30015.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30016.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v3l30017.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30018.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l30021.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l30028.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30030.cvc.smt2                                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|v3l30034.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30036.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l30042.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30044.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30047.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l30048.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30049.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30050.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l30052.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30059.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v3l30064.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30070.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30072.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v3l30074.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30079.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30082.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30085.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v3l30086.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l30093.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l30094.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v3l30096.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v3l30098.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v3l30100.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l40003.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l40004.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v3l40005.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40010.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v3l40011.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40012.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v3l40013.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40024.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l40025.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40026.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40029.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l40032.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40036.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40047.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v3l40050.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l40056.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40057.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40059.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v3l40062.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40065.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v3l40068.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40072.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40073.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40075.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l40076.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v3l40079.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40080.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40081.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l40087.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v3l40095.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v3l40096.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l40097.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l50003.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l50005.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l50015.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l50023.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l50026.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l50037.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v3l50039.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v3l50040.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l50042.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l50044.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v3l50046.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l50049.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l50053.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l50063.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l50067.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l50069.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l50071.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l50079.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l50081.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l50084.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l50085.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v3l50091.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l50099.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l60003.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v3l60011.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l60018.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l60020.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v3l60028.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l60029.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l60037.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l60040.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l60045.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v3l60046.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l60057.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l60061.cvc.smt2                                                                           |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|v3l60066.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l60068.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l60071.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l60076.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l60077.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l60081.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l60088.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l60089.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l60090.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l60093.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v3l60094.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l70006.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l70007.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l70012.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l70015.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l70016.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l70022.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l70023.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l70030.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v3l70034.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l70035.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l70041.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l70046.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l70058.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l70059.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l70062.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l70066.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l70068.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v3l70073.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l70075.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l70093.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l70100.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l80002.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l80011.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l80015.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l80018.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l80019.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l80027.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l80041.cvc.smt2                                                                           |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|v3l80048.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l80049.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l80055.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l80056.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l80059.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v3l80070.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l80073.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l80079.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l80080.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l80082.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l80087.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l80088.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v3l80091.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l80095.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l80098.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v3l90024.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l90042.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l90047.cvc.smt2                                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|v3l90055.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v3l90064.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v3l90073.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l90077.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v3l90084.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l90086.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v3l90098.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v3l90100.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20004.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20008.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l20009.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l20011.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l20013.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20023.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20024.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l20025.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l20026.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l20031.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20032.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l20034.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l20036.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20037.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l20039.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20040.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l20043.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l20044.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l20045.cvc.smt2                                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|v5l20046.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20047.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l20055.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v5l20056.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20059.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20060.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20061.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l20063.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l20064.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l20067.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l20068.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l20072.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20073.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l20074.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20077.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l20078.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20079.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20082.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l20087.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l20090.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l20097.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l20098.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l30009.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l30010.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l30013.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l30019.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v5l30022.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l30023.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l30024.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l30028.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l30029.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l30030.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l30033.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l30035.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l30036.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l30037.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l30038.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l30040.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l30043.cvc.smt2                                                                           |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|v5l30048.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l30049.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v5l30056.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l30059.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l30061.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v5l30062.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l30064.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l30068.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l30069.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v5l30071.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l30072.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l30073.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l30075.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l30076.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l30079.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l30081.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l30082.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l30085.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l30089.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l30090.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l30094.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l30097.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l30098.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l30100.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40002.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40003.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40005.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l40006.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40008.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l40012.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40014.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40015.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l40016.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40017.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l40022.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40024.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40028.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l40029.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l40030.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40031.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l40032.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40033.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l40034.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l40040.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40043.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v5l40044.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40045.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l40048.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v5l40052.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40060.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l40061.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40064.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l40069.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l40075.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40081.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l40083.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l40085.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40089.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l40097.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l50002.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l50003.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l50006.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l50008.cvc.smt2                                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|v5l50016.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l50020.cvc.smt2                                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|v5l50021.cvc.smt2                                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|v5l50022.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l50026.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l50038.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l50041.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l50055.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v5l50060.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l50061.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l50063.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v5l50064.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v5l50066.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l50071.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l50073.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v5l50074.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l50076.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l50077.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l50081.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l50083.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l50085.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l50087.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l50090.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l50092.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l50093.cvc.smt2                                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|v5l50094.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l50096.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l60002.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l60006.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l60008.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l60011.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l60012.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l60013.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l60016.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l60022.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l60031.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l60033.cvc.smt2                                                                           |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|v5l60035.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l60036.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v5l60041.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l60042.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l60048.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v5l60049.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l60056.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l60059.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l60060.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v5l60072.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l60073.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l60076.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l60078.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l60079.cvc.smt2                                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|v5l60081.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l60083.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l60086.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l60089.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l60090.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l60095.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l70002.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v5l70013.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l70024.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l70027.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l70028.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l70029.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l70034.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l70036.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l70042.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v5l70050.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l70053.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l70057.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l70059.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l70066.cvc.smt2                                                                           |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|v5l70071.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l70083.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l70085.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v5l70095.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v5l70096.cvc.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|v5l70097.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l70098.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l80006.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l80008.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l80013.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l80018.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l80019.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l80022.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l80025.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l80028.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l80030.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l80035.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l80037.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v5l80040.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v5l80042.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l80044.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l80048.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l80049.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l80053.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l80066.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v5l80068.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l80074.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l80086.cvc.smt2                                                                           |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|v5l80087.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l80088.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l80097.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l80098.cvc.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|v5l80100.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l90016.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l90020.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l90025.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l90028.cvc.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|v5l90029.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l90041.cvc.smt2                                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|v5l90045.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l90056.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l90058.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|v5l90067.cvc.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|v5l90068.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l90075.cvc.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|v5l90081.cvc.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|v5l90099.cvc.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|vlsat3_h00.smt2                                                                             |  14.805s  |  14.805s  |   0.000s  | 0.0%|
|vlsat3_h03.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|vlsat3_h13.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|vlsat3_h16.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|vlsat3_h24.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|vlsat3_h26.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|vlsat3_h30.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|vlsat3_h32.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|vlsat3_h33.smt2                                                                             |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|vlsat3_h40.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|vlsat3_h54.smt2                                                                             |  19.987s  |  19.987s  |   0.000s  | 0.0%|
</details>
