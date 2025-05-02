Comparing data and data


# SUMMARY
- LHS tests = 294
- RHS tests = 294
- LHS success = 294  (100.0%)
- RHS success = 294  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: rings_with_dio
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: dd211bade9ecb681c2714d6de997f4c91bdf7a2e
Z3 branch: 
Z3 options: "-T:600 -st"
Z3 inputs: inputs/rings
Z3 commit message: filter out terms that are not solved

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: rings_with_dio
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: dd211bade9ecb681c2714d6de997f4c91bdf7a2e
Z3 branch: 
Z3 options: "-T:600 -st"
Z3 inputs: inputs/rings
Z3 commit message: filter out terms that are not solved

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |   1.487s  |   1.487s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |   2.625s  |   2.625s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |  18.283s  |  18.283s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |   0.211s  |   0.211s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |   1.487s  |   1.487s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |   2.625s  |   2.625s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |  18.283s  |  18.283s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |   0.211s  |   0.211s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |   1.487s  |   1.487s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |   2.625s  |   2.625s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |  18.283s  |  18.283s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |   0.211s  |   0.211s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |   1.487s  |   1.487s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |   2.625s  |   2.625s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |  18.283s  |  18.283s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |   0.211s  |   0.211s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp4_9vars_8ite_unsat.smt2                                                           | 599.973s |37.996MiB|
|ring_2exp6_9vars_7ite_unsat.smt2                                                           | 599.971s |46.96MiB|
|ring_2exp8_9vars_8ite_unsat.smt2                                                           | 599.971s |46.404MiB|
|ring_2exp16_9vars_8ite_unsat.smt2                                                          | 599.967s |43.064MiB|
|ring_2exp6_9vars_8ite_unsat.smt2                                                           | 599.964s |42.08MiB|
|ring_2exp6_8vars_7ite_unsat.smt2                                                           | 599.961s |40.056MiB|
|ring_2exp4_9vars_6ite_unsat.smt2                                                           | 599.958s |38.088MiB|
|ring_2exp12_9vars_8ite_unsat.smt2                                                          | 599.952s |50.448MiB|
|ring_2exp14_9vars_8ite_unsat.smt2                                                          | 599.945s |41.16MiB|
|ring_2exp10_9vars_8ite_unsat.smt2                                                          | 599.938s |48.652MiB|
|ring_2exp6_8vars_5ite_unsat.smt2                                                           | 599.922s |37.996MiB|
|ring_2exp4_7vars_6ite_unsat.smt2                                                           | 494.179s |45.188MiB|
|ring_2exp4_9vars_7ite_unsat.smt2                                                           | 297.943s |29.904MiB|
|ring_2exp4_8vars_7ite_unsat.smt2                                                           | 165.720s |28.916MiB|
|ring_2exp12_9vars_7ite_unsat.smt2                                                          | 160.196s |29.108MiB|
|ring_2exp8_9vars_7ite_unsat.smt2                                                           | 146.661s |30.72MiB|
|ring_2exp10_9vars_7ite_unsat.smt2                                                          | 144.675s |30.036MiB|
|ring_2exp16_9vars_7ite_unsat.smt2                                                          | 143.278s |28.264MiB|
|ring_2exp14_9vars_7ite_unsat.smt2                                                          | 143.201s |28.792MiB|
|ring_2exp14_8vars_7ite_unsat.smt2                                                          | 121.756s |27.936MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp4_9vars_8ite_unsat.smt2                                                           | 599.973s |37.996MiB|
|ring_2exp6_9vars_7ite_unsat.smt2                                                           | 599.971s |46.96MiB|
|ring_2exp8_9vars_8ite_unsat.smt2                                                           | 599.971s |46.404MiB|
|ring_2exp16_9vars_8ite_unsat.smt2                                                          | 599.967s |43.064MiB|
|ring_2exp6_9vars_8ite_unsat.smt2                                                           | 599.964s |42.08MiB|
|ring_2exp6_8vars_7ite_unsat.smt2                                                           | 599.961s |40.056MiB|
|ring_2exp4_9vars_6ite_unsat.smt2                                                           | 599.958s |38.088MiB|
|ring_2exp12_9vars_8ite_unsat.smt2                                                          | 599.952s |50.448MiB|
|ring_2exp14_9vars_8ite_unsat.smt2                                                          | 599.945s |41.16MiB|
|ring_2exp10_9vars_8ite_unsat.smt2                                                          | 599.938s |48.652MiB|
|ring_2exp6_8vars_5ite_unsat.smt2                                                           | 599.922s |37.996MiB|
|ring_2exp4_7vars_6ite_unsat.smt2                                                           | 494.179s |45.188MiB|
|ring_2exp4_9vars_7ite_unsat.smt2                                                           | 297.943s |29.904MiB|
|ring_2exp4_8vars_7ite_unsat.smt2                                                           | 165.720s |28.916MiB|
|ring_2exp12_9vars_7ite_unsat.smt2                                                          | 160.196s |29.108MiB|
|ring_2exp8_9vars_7ite_unsat.smt2                                                           | 146.661s |30.72MiB|
|ring_2exp10_9vars_7ite_unsat.smt2                                                          | 144.675s |30.036MiB|
|ring_2exp16_9vars_7ite_unsat.smt2                                                          | 143.278s |28.264MiB|
|ring_2exp14_9vars_7ite_unsat.smt2                                                          | 143.201s |28.792MiB|
|ring_2exp14_8vars_7ite_unsat.smt2                                                          | 121.756s |27.936MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.116MiB|20.116MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.248MiB|20.248MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.48MiB|20.48MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.384MiB|20.384MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |20.524MiB|20.524MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.52MiB|20.52MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.672MiB|20.672MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.48MiB|20.48MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |20.624MiB|20.624MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |20.824MiB|20.824MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |20.904MiB|20.904MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |21.384MiB|21.384MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.768MiB|20.768MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |20.848MiB|20.848MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |21.108MiB|21.108MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |20.964MiB|20.964MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |22.228MiB|22.228MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |24.208MiB|24.208MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |21.024MiB|21.024MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |21.048MiB|21.048MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.116MiB|20.116MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.248MiB|20.248MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.48MiB|20.48MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.384MiB|20.384MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |20.524MiB|20.524MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.52MiB|20.52MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.672MiB|20.672MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.48MiB|20.48MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |20.624MiB|20.624MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |20.824MiB|20.824MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |20.904MiB|20.904MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |21.384MiB|21.384MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.768MiB|20.768MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |20.848MiB|20.848MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |21.108MiB|21.108MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |20.964MiB|20.964MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |22.228MiB|22.228MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |24.208MiB|24.208MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |21.024MiB|21.024MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |21.048MiB|21.048MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.116MiB|20.116MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.248MiB|20.248MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.48MiB|20.48MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.384MiB|20.384MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |20.524MiB|20.524MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.52MiB|20.52MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.672MiB|20.672MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.48MiB|20.48MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |20.624MiB|20.624MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |20.824MiB|20.824MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |20.904MiB|20.904MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |21.384MiB|21.384MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.768MiB|20.768MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |20.848MiB|20.848MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |21.108MiB|21.108MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |20.964MiB|20.964MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |22.228MiB|22.228MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |24.208MiB|24.208MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |21.024MiB|21.024MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |21.048MiB|21.048MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.116MiB|20.116MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.248MiB|20.248MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.48MiB|20.48MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.384MiB|20.384MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |20.524MiB|20.524MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.52MiB|20.52MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.672MiB|20.672MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.48MiB|20.48MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |20.624MiB|20.624MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |20.824MiB|20.824MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |20.904MiB|20.904MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |21.384MiB|21.384MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.768MiB|20.768MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |20.848MiB|20.848MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |21.108MiB|21.108MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |20.964MiB|20.964MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |22.228MiB|22.228MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |24.208MiB|24.208MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |21.024MiB|21.024MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |21.048MiB|21.048MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp12_9vars_8ite_unsat.smt2                                                          | 599.952s |50.448MiB|
|ring_2exp10_9vars_8ite_unsat.smt2                                                          | 599.938s |48.652MiB|
|ring_2exp6_9vars_7ite_unsat.smt2                                                           | 599.971s |46.96MiB|
|ring_2exp8_9vars_8ite_unsat.smt2                                                           | 599.971s |46.404MiB|
|ring_2exp4_7vars_6ite_unsat.smt2                                                           | 494.179s |45.188MiB|
|ring_2exp16_9vars_8ite_unsat.smt2                                                          | 599.967s |43.064MiB|
|ring_2exp6_9vars_8ite_unsat.smt2                                                           | 599.964s |42.08MiB|
|ring_2exp14_9vars_8ite_unsat.smt2                                                          | 599.945s |41.16MiB|
|ring_2exp6_8vars_7ite_unsat.smt2                                                           | 599.961s |40.056MiB|
|ring_2exp4_9vars_6ite_unsat.smt2                                                           | 599.958s |38.088MiB|
|ring_2exp4_9vars_8ite_unsat.smt2                                                           | 599.973s |37.996MiB|
|ring_2exp6_8vars_5ite_unsat.smt2                                                           | 599.922s |37.996MiB|
|ring_2exp8_9vars_7ite_unsat.smt2                                                           | 146.661s |30.72MiB|
|ring_2exp10_9vars_7ite_unsat.smt2                                                          | 144.675s |30.036MiB|
|ring_2exp4_9vars_7ite_unsat.smt2                                                           | 297.943s |29.904MiB|
|ring_2exp10_9vars_6ite_unsat.smt2                                                          |  91.193s |29.34MiB|
|ring_2exp12_9vars_7ite_unsat.smt2                                                          | 160.196s |29.108MiB|
|ring_2exp4_8vars_7ite_unsat.smt2                                                           | 165.720s |28.916MiB|
|ring_2exp14_9vars_7ite_unsat.smt2                                                          | 143.201s |28.792MiB|
|ring_2exp16_9vars_7ite_unsat.smt2                                                          | 143.278s |28.264MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp12_9vars_8ite_unsat.smt2                                                          | 599.952s |50.448MiB|
|ring_2exp10_9vars_8ite_unsat.smt2                                                          | 599.938s |48.652MiB|
|ring_2exp6_9vars_7ite_unsat.smt2                                                           | 599.971s |46.96MiB|
|ring_2exp8_9vars_8ite_unsat.smt2                                                           | 599.971s |46.404MiB|
|ring_2exp4_7vars_6ite_unsat.smt2                                                           | 494.179s |45.188MiB|
|ring_2exp16_9vars_8ite_unsat.smt2                                                          | 599.967s |43.064MiB|
|ring_2exp6_9vars_8ite_unsat.smt2                                                           | 599.964s |42.08MiB|
|ring_2exp14_9vars_8ite_unsat.smt2                                                          | 599.945s |41.16MiB|
|ring_2exp6_8vars_7ite_unsat.smt2                                                           | 599.961s |40.056MiB|
|ring_2exp4_9vars_6ite_unsat.smt2                                                           | 599.958s |38.088MiB|
|ring_2exp4_9vars_8ite_unsat.smt2                                                           | 599.973s |37.996MiB|
|ring_2exp6_8vars_5ite_unsat.smt2                                                           | 599.922s |37.996MiB|
|ring_2exp8_9vars_7ite_unsat.smt2                                                           | 146.661s |30.72MiB|
|ring_2exp10_9vars_7ite_unsat.smt2                                                          | 144.675s |30.036MiB|
|ring_2exp4_9vars_7ite_unsat.smt2                                                           | 297.943s |29.904MiB|
|ring_2exp10_9vars_6ite_unsat.smt2                                                          |  91.193s |29.34MiB|
|ring_2exp12_9vars_7ite_unsat.smt2                                                          | 160.196s |29.108MiB|
|ring_2exp4_8vars_7ite_unsat.smt2                                                           | 165.720s |28.916MiB|
|ring_2exp14_9vars_7ite_unsat.smt2                                                          | 143.201s |28.792MiB|
|ring_2exp16_9vars_7ite_unsat.smt2                                                          | 143.278s |28.264MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |   1.487s  |   1.487s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |   2.625s  |   2.625s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |  18.283s  |  18.283s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_2ite_unsat.smt2                                                           |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_3ite_unsat.smt2                                                           |   1.438s  |   1.438s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_4ite_unsat.smt2                                                           |  12.408s  |  12.408s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_5ite_unsat.smt2                                                           |  15.656s  |  15.656s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_6ite_unsat.smt2                                                           |  48.892s  |  48.892s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_0ite_unsat.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_1ite_unsat.smt2                                                           |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_2ite_unsat.smt2                                                           |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_3ite_unsat.smt2                                                           |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_4ite_unsat.smt2                                                           |   1.646s  |   1.646s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_5ite_unsat.smt2                                                           |  28.308s  |  28.308s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_6ite_unsat.smt2                                                           |  74.571s  |  74.571s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_7ite_unsat.smt2                                                           | 107.134s  | 107.134s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_0ite_unsat.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_1ite_unsat.smt2                                                           |   0.685s  |   0.685s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_2ite_unsat.smt2                                                           |   1.050s  |   1.050s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_3ite_unsat.smt2                                                           |   1.301s  |   1.301s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_4ite_unsat.smt2                                                           |   4.400s  |   4.400s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_5ite_unsat.smt2                                                           |  29.691s  |  29.691s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_6ite_unsat.smt2                                                           |  91.193s  |  91.193s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_7ite_unsat.smt2                                                           | 144.675s  | 144.675s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_8ite_unsat.smt2                                                           | 599.938s  | 599.938s  |   0.000s  | 0.0%|
|ring_2exp12_3vars_0ite_unsat.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|ring_2exp12_3vars_1ite_unsat.smt2                                                           |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|ring_2exp12_3vars_2ite_unsat.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_0ite_unsat.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_1ite_unsat.smt2                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_2ite_unsat.smt2                                                           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_3ite_unsat.smt2                                                           |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_0ite_unsat.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_1ite_unsat.smt2                                                           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_2ite_unsat.smt2                                                           |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_3ite_unsat.smt2                                                           |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_4ite_unsat.smt2                                                           |   0.888s  |   0.888s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_0ite_unsat.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_1ite_unsat.smt2                                                           |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_2ite_unsat.smt2                                                           |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_3ite_unsat.smt2                                                           |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_4ite_unsat.smt2                                                           |   2.092s  |   2.092s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_5ite_unsat.smt2                                                           |  20.897s  |  20.897s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_0ite_unsat.smt2                                                           |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_1ite_unsat.smt2                                                           |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_2ite_unsat.smt2                                                           |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_3ite_unsat.smt2                                                           |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_4ite_unsat.smt2                                                           |  16.456s  |  16.456s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_5ite_unsat.smt2                                                           |  19.865s  |  19.865s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_6ite_unsat.smt2                                                           |  45.937s  |  45.937s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_0ite_unsat.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_1ite_unsat.smt2                                                           |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_2ite_unsat.smt2                                                           |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_3ite_unsat.smt2                                                           |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_4ite_unsat.smt2                                                           |   3.756s  |   3.756s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_5ite_unsat.smt2                                                           |  20.140s  |  20.140s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_6ite_unsat.smt2                                                           |  67.926s  |  67.926s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_7ite_unsat.smt2                                                           | 112.869s  | 112.869s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_0ite_unsat.smt2                                                           |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_1ite_unsat.smt2                                                           |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_2ite_unsat.smt2                                                           |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_3ite_unsat.smt2                                                           |   2.060s  |   2.060s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_4ite_unsat.smt2                                                           |  19.828s  |  19.828s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_5ite_unsat.smt2                                                           |  28.863s  |  28.863s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_6ite_unsat.smt2                                                           |  85.030s  |  85.030s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_7ite_unsat.smt2                                                           | 160.196s  | 160.196s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_8ite_unsat.smt2                                                           | 599.952s  | 599.952s  |   0.000s  | 0.0%|
|ring_2exp14_3vars_0ite_unsat.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp14_3vars_1ite_unsat.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|ring_2exp14_3vars_2ite_unsat.smt2                                                           |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_0ite_unsat.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_1ite_unsat.smt2                                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_2ite_unsat.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_3ite_unsat.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_0ite_unsat.smt2                                                           |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_1ite_unsat.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_2ite_unsat.smt2                                                           |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_3ite_unsat.smt2                                                           |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_4ite_unsat.smt2                                                           |   0.812s  |   0.812s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_0ite_unsat.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_1ite_unsat.smt2                                                           |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_2ite_unsat.smt2                                                           |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_3ite_unsat.smt2                                                           |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_4ite_unsat.smt2                                                           |   1.480s  |   1.480s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_5ite_unsat.smt2                                                           |   4.385s  |   4.385s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_0ite_unsat.smt2                                                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_1ite_unsat.smt2                                                           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_2ite_unsat.smt2                                                           |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_3ite_unsat.smt2                                                           |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_4ite_unsat.smt2                                                           |   1.435s  |   1.435s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_5ite_unsat.smt2                                                           |  22.995s  |  22.995s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_6ite_unsat.smt2                                                           |  48.787s  |  48.787s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_0ite_unsat.smt2                                                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_1ite_unsat.smt2                                                           |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_2ite_unsat.smt2                                                           |   0.624s  |   0.624s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_3ite_unsat.smt2                                                           |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_4ite_unsat.smt2                                                           |   4.246s  |   4.246s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_5ite_unsat.smt2                                                           |  27.675s  |  27.675s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_6ite_unsat.smt2                                                           |  70.877s  |  70.877s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_7ite_unsat.smt2                                                           | 121.756s  | 121.756s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_0ite_unsat.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_1ite_unsat.smt2                                                           |   0.608s  |   0.608s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_2ite_unsat.smt2                                                           |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_3ite_unsat.smt2                                                           |   1.461s  |   1.461s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_4ite_unsat.smt2                                                           |   3.596s  |   3.596s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_5ite_unsat.smt2                                                           |  28.988s  |  28.988s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_6ite_unsat.smt2                                                           |  75.204s  |  75.204s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_7ite_unsat.smt2                                                           | 143.201s  | 143.201s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_8ite_unsat.smt2                                                           | 599.945s  | 599.945s  |   0.000s  | 0.0%|
|ring_2exp16_3vars_0ite_unsat.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|ring_2exp16_3vars_1ite_unsat.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ring_2exp16_3vars_2ite_unsat.smt2                                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_0ite_unsat.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_1ite_unsat.smt2                                                           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_2ite_unsat.smt2                                                           |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_3ite_unsat.smt2                                                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_0ite_unsat.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_1ite_unsat.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_2ite_unsat.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_3ite_unsat.smt2                                                           |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_4ite_unsat.smt2                                                           |   0.891s  |   0.891s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_0ite_unsat.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_1ite_unsat.smt2                                                           |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_2ite_unsat.smt2                                                           |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_3ite_unsat.smt2                                                           |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_4ite_unsat.smt2                                                           |   1.877s  |   1.877s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_5ite_unsat.smt2                                                           |  18.671s  |  18.671s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_0ite_unsat.smt2                                                           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_1ite_unsat.smt2                                                           |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_2ite_unsat.smt2                                                           |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_3ite_unsat.smt2                                                           |   0.703s  |   0.703s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_4ite_unsat.smt2                                                           |   1.727s  |   1.727s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_5ite_unsat.smt2                                                           |  15.445s  |  15.445s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_6ite_unsat.smt2                                                           |  46.918s  |  46.918s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_0ite_unsat.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_1ite_unsat.smt2                                                           |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_2ite_unsat.smt2                                                           |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_3ite_unsat.smt2                                                           |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_4ite_unsat.smt2                                                           |   2.371s  |   2.371s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_5ite_unsat.smt2                                                           |  27.547s  |  27.547s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_6ite_unsat.smt2                                                           |  71.552s  |  71.552s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_7ite_unsat.smt2                                                           | 120.776s  | 120.776s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_0ite_unsat.smt2                                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_1ite_unsat.smt2                                                           |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_2ite_unsat.smt2                                                           |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_3ite_unsat.smt2                                                           |   1.301s  |   1.301s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_4ite_unsat.smt2                                                           |  13.620s  |  13.620s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_5ite_unsat.smt2                                                           |  28.473s  |  28.473s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_6ite_unsat.smt2                                                           |  75.833s  |  75.833s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_7ite_unsat.smt2                                                           | 143.278s  | 143.278s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_8ite_unsat.smt2                                                           | 599.967s  | 599.967s  |   0.000s  | 0.0%|
|ring_2exp4_3vars_0ite_unsat.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp4_3vars_1ite_unsat.smt2                                                            |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp4_3vars_2ite_unsat.smt2                                                            |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_0ite_unsat.smt2                                                            |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_1ite_unsat.smt2                                                            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_2ite_unsat.smt2                                                            |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_3ite_unsat.smt2                                                            |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_0ite_unsat.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_1ite_unsat.smt2                                                            |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_2ite_unsat.smt2                                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_3ite_unsat.smt2                                                            |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_4ite_unsat.smt2                                                            |   1.700s  |   1.700s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_0ite_unsat.smt2                                                            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_1ite_unsat.smt2                                                            |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_2ite_unsat.smt2                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_3ite_unsat.smt2                                                            |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_4ite_unsat.smt2                                                            |   1.885s  |   1.885s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_5ite_unsat.smt2                                                            |   3.344s  |   3.344s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_0ite_unsat.smt2                                                            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_1ite_unsat.smt2                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_2ite_unsat.smt2                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_3ite_unsat.smt2                                                            |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_4ite_unsat.smt2                                                            |   1.606s  |   1.606s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_5ite_unsat.smt2                                                            |   4.271s  |   4.271s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_6ite_unsat.smt2                                                            | 494.179s  | 494.179s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_0ite_unsat.smt2                                                            |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_1ite_unsat.smt2                                                            |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_2ite_unsat.smt2                                                            |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_3ite_unsat.smt2                                                            |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_4ite_unsat.smt2                                                            |   2.109s  |   2.109s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_5ite_unsat.smt2                                                            |  16.058s  |  16.058s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_6ite_unsat.smt2                                                            |  88.769s  |  88.769s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_7ite_unsat.smt2                                                            | 165.720s  | 165.720s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_0ite_unsat.smt2                                                            |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_1ite_unsat.smt2                                                            |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_2ite_unsat.smt2                                                            |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_3ite_unsat.smt2                                                            |   0.796s  |   0.796s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_4ite_unsat.smt2                                                            |   2.986s  |   2.986s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_5ite_unsat.smt2                                                            |   3.951s  |   3.951s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_6ite_unsat.smt2                                                            | 599.958s  | 599.958s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_7ite_unsat.smt2                                                            | 297.943s  | 297.943s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_8ite_unsat.smt2                                                            | 599.973s  | 599.973s  |   0.000s  | 0.0%|
|ring_2exp6_3vars_0ite_unsat.smt2                                                            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp6_3vars_1ite_unsat.smt2                                                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ring_2exp6_3vars_2ite_unsat.smt2                                                            |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_0ite_unsat.smt2                                                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_1ite_unsat.smt2                                                            |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_2ite_unsat.smt2                                                            |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_3ite_unsat.smt2                                                            |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_0ite_unsat.smt2                                                            |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_1ite_unsat.smt2                                                            |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_2ite_unsat.smt2                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_3ite_unsat.smt2                                                            |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_4ite_unsat.smt2                                                            |   2.062s  |   2.062s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_0ite_unsat.smt2                                                            |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_1ite_unsat.smt2                                                            |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_2ite_unsat.smt2                                                            |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_3ite_unsat.smt2                                                            |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_4ite_unsat.smt2                                                            |  14.491s  |  14.491s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_5ite_unsat.smt2                                                            |  22.492s  |  22.492s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_0ite_unsat.smt2                                                            |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_1ite_unsat.smt2                                                            |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_2ite_unsat.smt2                                                            |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_3ite_unsat.smt2                                                            |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_4ite_unsat.smt2                                                            |  18.298s  |  18.298s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_5ite_unsat.smt2                                                            |  16.385s  |  16.385s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_6ite_unsat.smt2                                                            |  47.992s  |  47.992s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_0ite_unsat.smt2                                                            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_1ite_unsat.smt2                                                            |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_2ite_unsat.smt2                                                            |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_3ite_unsat.smt2                                                            |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_4ite_unsat.smt2                                                            |   3.691s  |   3.691s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_5ite_unsat.smt2                                                            | 599.922s  | 599.922s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_6ite_unsat.smt2                                                            |  90.506s  |  90.506s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_7ite_unsat.smt2                                                            | 599.961s  | 599.961s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_0ite_unsat.smt2                                                            |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_1ite_unsat.smt2                                                            |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_2ite_unsat.smt2                                                            |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_3ite_unsat.smt2                                                            |   1.655s  |   1.655s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_4ite_unsat.smt2                                                            |   3.661s  |   3.661s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_5ite_unsat.smt2                                                            |  28.563s  |  28.563s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_6ite_unsat.smt2                                                            |  69.460s  |  69.460s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_7ite_unsat.smt2                                                            | 599.971s  | 599.971s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_8ite_unsat.smt2                                                            | 599.964s  | 599.964s  |   0.000s  | 0.0%|
|ring_2exp8_3vars_0ite_unsat.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp8_3vars_1ite_unsat.smt2                                                            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|ring_2exp8_3vars_2ite_unsat.smt2                                                            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_0ite_unsat.smt2                                                            |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_1ite_unsat.smt2                                                            |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_2ite_unsat.smt2                                                            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_3ite_unsat.smt2                                                            |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_0ite_unsat.smt2                                                            |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_1ite_unsat.smt2                                                            |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_2ite_unsat.smt2                                                            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_3ite_unsat.smt2                                                            |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_4ite_unsat.smt2                                                            |   1.145s  |   1.145s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_0ite_unsat.smt2                                                            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_1ite_unsat.smt2                                                            |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_2ite_unsat.smt2                                                            |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_3ite_unsat.smt2                                                            |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_4ite_unsat.smt2                                                            |   3.198s  |   3.198s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_5ite_unsat.smt2                                                            |  19.080s  |  19.080s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_0ite_unsat.smt2                                                            |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_1ite_unsat.smt2                                                            |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_2ite_unsat.smt2                                                            |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_3ite_unsat.smt2                                                            |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_4ite_unsat.smt2                                                            |  18.858s  |  18.858s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_5ite_unsat.smt2                                                            |  23.116s  |  23.116s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_6ite_unsat.smt2                                                            |  47.794s  |  47.794s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_0ite_unsat.smt2                                                            |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_1ite_unsat.smt2                                                            |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_2ite_unsat.smt2                                                            |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_3ite_unsat.smt2                                                            |   2.082s  |   2.082s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_4ite_unsat.smt2                                                            |  13.977s  |  13.977s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_5ite_unsat.smt2                                                            |  19.781s  |  19.781s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_6ite_unsat.smt2                                                            |  73.359s  |  73.359s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_7ite_unsat.smt2                                                            | 111.120s  | 111.120s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_0ite_unsat.smt2                                                            |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_1ite_unsat.smt2                                                            |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_2ite_unsat.smt2                                                            |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_3ite_unsat.smt2                                                            |   1.754s  |   1.754s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_4ite_unsat.smt2                                                            |  26.453s  |  26.453s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_5ite_unsat.smt2                                                            |  28.582s  |  28.582s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_6ite_unsat.smt2                                                            |  78.337s  |  78.337s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_7ite_unsat.smt2                                                            | 146.661s  | 146.661s  |   0.000s  | 0.0%|
</details>
