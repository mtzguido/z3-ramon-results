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
Job tag: rings_with_z3-4.14.0
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 3c47fd96cf5645d0c42b2c819d9e9a84380aa721
Z3 branch: 
Z3 options: "-T:600 -st"
Z3 inputs: inputs/rings
Z3 commit message: bump timeout for jobs

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: rings_with_z3-4.14.0
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 3c47fd96cf5645d0c42b2c819d9e9a84380aa721
Z3 branch: 
Z3 options: "-T:600 -st"
Z3 inputs: inputs/rings
Z3 commit message: bump timeout for jobs

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           | 300.888s  | 300.888s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           | 261.753s  | 261.753s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           | 599.209s  | 599.209s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           | 128.815s  | 128.815s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           | 599.921s  | 599.921s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           | 599.927s  | 599.927s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           | 599.963s  | 599.963s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           | 599.733s  | 599.733s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           | 599.963s  | 599.963s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           | 599.794s  | 599.794s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           | 300.888s  | 300.888s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           | 261.753s  | 261.753s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           | 599.209s  | 599.209s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           | 128.815s  | 128.815s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           | 599.921s  | 599.921s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           | 599.927s  | 599.927s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           | 599.963s  | 599.963s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           | 599.733s  | 599.733s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           | 599.963s  | 599.963s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           | 599.794s  | 599.794s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           | 300.888s  | 300.888s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           | 261.753s  | 261.753s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           | 599.209s  | 599.209s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           | 128.815s  | 128.815s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           | 599.921s  | 599.921s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           | 599.927s  | 599.927s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           | 599.963s  | 599.963s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           | 599.733s  | 599.733s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           | 599.963s  | 599.963s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           | 599.794s  | 599.794s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           | 300.888s  | 300.888s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           | 261.753s  | 261.753s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           | 599.209s  | 599.209s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           | 128.815s  | 128.815s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           | 599.921s  | 599.921s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           | 599.927s  | 599.927s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           | 599.963s  | 599.963s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           | 599.733s  | 599.733s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           | 599.963s  | 599.963s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           | 599.794s  | 599.794s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp8_7vars_1ite_unsat.smt2                                                           | 599.971s |42.344MiB|
|ring_2exp10_7vars_5ite_unsat.smt2                                                          | 599.967s |47.148MiB|
|ring_2exp12_9vars_4ite_unsat.smt2                                                          | 599.967s |47.52MiB|
|ring_2exp8_6vars_2ite_unsat.smt2                                                           | 599.965s |44.172MiB|
|ring_2exp4_8vars_4ite_unsat.smt2                                                           | 599.964s |38.816MiB|
|ring_2exp8_8vars_7ite_unsat.smt2                                                           | 599.964s |42.708MiB|
|ring_2exp16_9vars_3ite_unsat.smt2                                                          | 599.964s |50.276MiB|
|ring_2exp10_6vars_5ite_unsat.smt2                                                          | 599.963s |42.964MiB|
|ring_2exp8_9vars_7ite_unsat.smt2                                                           | 599.963s |47.216MiB|
|ring_2exp16_7vars_1ite_unsat.smt2                                                          | 599.963s |45.708MiB|
|ring_2exp10_6vars_3ite_unsat.smt2                                                          | 599.963s |44.844MiB|
|ring_2exp16_8vars_2ite_unsat.smt2                                                          | 599.962s |47.916MiB|
|ring_2exp6_9vars_1ite_unsat.smt2                                                           | 599.961s |48.276MiB|
|ring_2exp12_7vars_2ite_unsat.smt2                                                          | 599.961s |45.212MiB|
|ring_2exp6_9vars_3ite_unsat.smt2                                                           | 599.961s |43.912MiB|
|ring_2exp12_7vars_4ite_unsat.smt2                                                          | 599.960s |41.668MiB|
|ring_2exp12_8vars_2ite_unsat.smt2                                                          | 599.959s |49.76MiB|
|ring_2exp12_7vars_5ite_unsat.smt2                                                          | 599.958s |42.432MiB|
|ring_2exp12_9vars_3ite_unsat.smt2                                                          | 599.958s |50.5MiB|
|ring_2exp12_9vars_7ite_unsat.smt2                                                          | 599.958s |45.66MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp8_7vars_1ite_unsat.smt2                                                           | 599.971s |42.344MiB|
|ring_2exp10_7vars_5ite_unsat.smt2                                                          | 599.967s |47.148MiB|
|ring_2exp12_9vars_4ite_unsat.smt2                                                          | 599.967s |47.52MiB|
|ring_2exp8_6vars_2ite_unsat.smt2                                                           | 599.965s |44.172MiB|
|ring_2exp4_8vars_4ite_unsat.smt2                                                           | 599.964s |38.816MiB|
|ring_2exp8_8vars_7ite_unsat.smt2                                                           | 599.964s |42.708MiB|
|ring_2exp16_9vars_3ite_unsat.smt2                                                          | 599.964s |50.276MiB|
|ring_2exp10_6vars_5ite_unsat.smt2                                                          | 599.963s |42.964MiB|
|ring_2exp8_9vars_7ite_unsat.smt2                                                           | 599.963s |47.216MiB|
|ring_2exp16_7vars_1ite_unsat.smt2                                                          | 599.963s |45.708MiB|
|ring_2exp10_6vars_3ite_unsat.smt2                                                          | 599.963s |44.844MiB|
|ring_2exp16_8vars_2ite_unsat.smt2                                                          | 599.962s |47.916MiB|
|ring_2exp6_9vars_1ite_unsat.smt2                                                           | 599.961s |48.276MiB|
|ring_2exp12_7vars_2ite_unsat.smt2                                                          | 599.961s |45.212MiB|
|ring_2exp6_9vars_3ite_unsat.smt2                                                           | 599.961s |43.912MiB|
|ring_2exp12_7vars_4ite_unsat.smt2                                                          | 599.960s |41.668MiB|
|ring_2exp12_8vars_2ite_unsat.smt2                                                          | 599.959s |49.76MiB|
|ring_2exp12_7vars_5ite_unsat.smt2                                                          | 599.958s |42.432MiB|
|ring_2exp12_9vars_3ite_unsat.smt2                                                          | 599.958s |50.5MiB|
|ring_2exp12_9vars_7ite_unsat.smt2                                                          | 599.958s |45.66MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.512MiB|20.512MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.328MiB|20.328MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.3MiB|20.3MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.516MiB|20.516MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |20.988MiB|20.988MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.964MiB|20.964MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.944MiB|20.944MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.524MiB|20.524MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |32.332MiB|32.332MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |34.368MiB|34.368MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |34.972MiB|34.972MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |29.572MiB|29.572MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.596MiB|20.596MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |39.248MiB|39.248MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |42.756MiB|42.756MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |44.844MiB|44.844MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |39.348MiB|39.348MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |42.964MiB|42.964MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |20.708MiB|20.708MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |41.372MiB|41.372MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.512MiB|20.512MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.328MiB|20.328MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.3MiB|20.3MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.516MiB|20.516MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |20.988MiB|20.988MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.964MiB|20.964MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.944MiB|20.944MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.524MiB|20.524MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |32.332MiB|32.332MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |34.368MiB|34.368MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |34.972MiB|34.972MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |29.572MiB|29.572MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.596MiB|20.596MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |39.248MiB|39.248MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |42.756MiB|42.756MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |44.844MiB|44.844MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |39.348MiB|39.348MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |42.964MiB|42.964MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |20.708MiB|20.708MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |41.372MiB|41.372MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.512MiB|20.512MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.328MiB|20.328MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.3MiB|20.3MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.516MiB|20.516MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |20.988MiB|20.988MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.964MiB|20.964MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.944MiB|20.944MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.524MiB|20.524MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |32.332MiB|32.332MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |34.368MiB|34.368MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |34.972MiB|34.972MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |29.572MiB|29.572MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.596MiB|20.596MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |39.248MiB|39.248MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |42.756MiB|42.756MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |44.844MiB|44.844MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |39.348MiB|39.348MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |42.964MiB|42.964MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |20.708MiB|20.708MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |41.372MiB|41.372MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.512MiB|20.512MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.328MiB|20.328MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.3MiB|20.3MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.516MiB|20.516MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |20.988MiB|20.988MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.964MiB|20.964MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.944MiB|20.944MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.524MiB|20.524MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |32.332MiB|32.332MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |34.368MiB|34.368MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |34.972MiB|34.972MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |29.572MiB|29.572MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.596MiB|20.596MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |39.248MiB|39.248MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |42.756MiB|42.756MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |44.844MiB|44.844MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |39.348MiB|39.348MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |42.964MiB|42.964MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |20.708MiB|20.708MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |41.372MiB|41.372MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp16_8vars_1ite_unsat.smt2                                                          | 599.940s |52.708MiB|
|ring_2exp12_9vars_3ite_unsat.smt2                                                          | 599.958s |50.5MiB|
|ring_2exp16_9vars_3ite_unsat.smt2                                                          | 599.964s |50.276MiB|
|ring_2exp8_9vars_3ite_unsat.smt2                                                           | 599.944s |50.16MiB|
|ring_2exp12_9vars_6ite_unsat.smt2                                                          | 599.945s |49.796MiB|
|ring_2exp10_9vars_7ite_unsat.smt2                                                          | 599.956s |49.764MiB|
|ring_2exp12_8vars_2ite_unsat.smt2                                                          | 599.959s |49.76MiB|
|ring_2exp16_9vars_2ite_unsat.smt2                                                          | 599.868s |49.456MiB|
|ring_2exp8_9vars_6ite_unsat.smt2                                                           | 599.947s |49.308MiB|
|ring_2exp6_9vars_1ite_unsat.smt2                                                           | 599.961s |48.276MiB|
|ring_2exp16_8vars_2ite_unsat.smt2                                                          | 599.962s |47.916MiB|
|ring_2exp12_9vars_4ite_unsat.smt2                                                          | 599.967s |47.52MiB|
|ring_2exp14_9vars_6ite_unsat.smt2                                                          | 599.952s |47.392MiB|
|ring_2exp12_9vars_1ite_unsat.smt2                                                          | 599.700s |47.3MiB|
|ring_2exp8_9vars_7ite_unsat.smt2                                                           | 599.963s |47.216MiB|
|ring_2exp10_7vars_5ite_unsat.smt2                                                          | 599.967s |47.148MiB|
|ring_2exp12_9vars_2ite_unsat.smt2                                                          | 599.858s |46.74MiB|
|ring_2exp14_9vars_1ite_unsat.smt2                                                          | 599.958s |46.648MiB|
|ring_2exp8_8vars_2ite_unsat.smt2                                                           | 599.937s |46.324MiB|
|ring_2exp14_8vars_7ite_unsat.smt2                                                          | 599.946s |45.912MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp16_8vars_1ite_unsat.smt2                                                          | 599.940s |52.708MiB|
|ring_2exp12_9vars_3ite_unsat.smt2                                                          | 599.958s |50.5MiB|
|ring_2exp16_9vars_3ite_unsat.smt2                                                          | 599.964s |50.276MiB|
|ring_2exp8_9vars_3ite_unsat.smt2                                                           | 599.944s |50.16MiB|
|ring_2exp12_9vars_6ite_unsat.smt2                                                          | 599.945s |49.796MiB|
|ring_2exp10_9vars_7ite_unsat.smt2                                                          | 599.956s |49.764MiB|
|ring_2exp12_8vars_2ite_unsat.smt2                                                          | 599.959s |49.76MiB|
|ring_2exp16_9vars_2ite_unsat.smt2                                                          | 599.868s |49.456MiB|
|ring_2exp8_9vars_6ite_unsat.smt2                                                           | 599.947s |49.308MiB|
|ring_2exp6_9vars_1ite_unsat.smt2                                                           | 599.961s |48.276MiB|
|ring_2exp16_8vars_2ite_unsat.smt2                                                          | 599.962s |47.916MiB|
|ring_2exp12_9vars_4ite_unsat.smt2                                                          | 599.967s |47.52MiB|
|ring_2exp14_9vars_6ite_unsat.smt2                                                          | 599.952s |47.392MiB|
|ring_2exp12_9vars_1ite_unsat.smt2                                                          | 599.700s |47.3MiB|
|ring_2exp8_9vars_7ite_unsat.smt2                                                           | 599.963s |47.216MiB|
|ring_2exp10_7vars_5ite_unsat.smt2                                                          | 599.967s |47.148MiB|
|ring_2exp12_9vars_2ite_unsat.smt2                                                          | 599.858s |46.74MiB|
|ring_2exp14_9vars_1ite_unsat.smt2                                                          | 599.958s |46.648MiB|
|ring_2exp8_8vars_2ite_unsat.smt2                                                           | 599.937s |46.324MiB|
|ring_2exp14_8vars_7ite_unsat.smt2                                                          | 599.946s |45.912MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           | 300.888s  | 300.888s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           | 261.753s  | 261.753s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           | 599.209s  | 599.209s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           | 128.815s  | 128.815s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           | 599.921s  | 599.921s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           | 599.927s  | 599.927s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           | 599.963s  | 599.963s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           | 599.733s  | 599.733s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           | 599.963s  | 599.963s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           | 599.794s  | 599.794s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_2ite_unsat.smt2                                                           | 599.919s  | 599.919s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_3ite_unsat.smt2                                                           | 599.751s  | 599.751s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_4ite_unsat.smt2                                                           | 599.737s  | 599.737s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_5ite_unsat.smt2                                                           | 599.967s  | 599.967s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_6ite_unsat.smt2                                                           | 599.956s  | 599.956s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_0ite_unsat.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_1ite_unsat.smt2                                                           | 599.800s  | 599.800s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_2ite_unsat.smt2                                                           | 599.824s  | 599.824s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_3ite_unsat.smt2                                                           | 599.934s  | 599.934s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_4ite_unsat.smt2                                                           | 599.614s  | 599.614s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_5ite_unsat.smt2                                                           | 599.950s  | 599.950s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_6ite_unsat.smt2                                                           | 599.740s  | 599.740s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_7ite_unsat.smt2                                                           | 599.713s  | 599.713s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_0ite_unsat.smt2                                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_1ite_unsat.smt2                                                           | 599.249s  | 599.249s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_2ite_unsat.smt2                                                           | 599.879s  | 599.879s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_3ite_unsat.smt2                                                           | 599.781s  | 599.781s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_4ite_unsat.smt2                                                           | 599.790s  | 599.790s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_5ite_unsat.smt2                                                           | 599.885s  | 599.885s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_6ite_unsat.smt2                                                           | 599.906s  | 599.906s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_7ite_unsat.smt2                                                           | 599.956s  | 599.956s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_8ite_unsat.smt2                                                           | 599.926s  | 599.926s  |   0.000s  | 0.0%|
|ring_2exp12_3vars_0ite_unsat.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp12_3vars_1ite_unsat.smt2                                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|ring_2exp12_3vars_2ite_unsat.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_0ite_unsat.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_1ite_unsat.smt2                                                           |   0.940s  |   0.940s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_2ite_unsat.smt2                                                           |   0.919s  |   0.919s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_3ite_unsat.smt2                                                           |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_0ite_unsat.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_1ite_unsat.smt2                                                           | 273.655s  | 273.655s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_2ite_unsat.smt2                                                           | 545.965s  | 545.965s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_3ite_unsat.smt2                                                           | 231.750s  | 231.750s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_4ite_unsat.smt2                                                           | 121.323s  | 121.323s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_0ite_unsat.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_1ite_unsat.smt2                                                           | 599.630s  | 599.630s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_2ite_unsat.smt2                                                           | 599.922s  | 599.922s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_3ite_unsat.smt2                                                           | 599.637s  | 599.637s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_4ite_unsat.smt2                                                           | 599.326s  | 599.326s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_5ite_unsat.smt2                                                           | 599.816s  | 599.816s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_0ite_unsat.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_1ite_unsat.smt2                                                           | 599.590s  | 599.590s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_2ite_unsat.smt2                                                           | 599.961s  | 599.961s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_3ite_unsat.smt2                                                           | 599.897s  | 599.897s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_4ite_unsat.smt2                                                           | 599.960s  | 599.960s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_5ite_unsat.smt2                                                           | 599.958s  | 599.958s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_6ite_unsat.smt2                                                           | 599.111s  | 599.111s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_0ite_unsat.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_1ite_unsat.smt2                                                           | 599.870s  | 599.870s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_2ite_unsat.smt2                                                           | 599.959s  | 599.959s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_3ite_unsat.smt2                                                           | 599.888s  | 599.888s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_4ite_unsat.smt2                                                           | 599.778s  | 599.778s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_5ite_unsat.smt2                                                           | 599.317s  | 599.317s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_6ite_unsat.smt2                                                           | 599.675s  | 599.675s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_7ite_unsat.smt2                                                           | 599.497s  | 599.497s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_0ite_unsat.smt2                                                           |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_1ite_unsat.smt2                                                           | 599.700s  | 599.700s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_2ite_unsat.smt2                                                           | 599.858s  | 599.858s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_3ite_unsat.smt2                                                           | 599.958s  | 599.958s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_4ite_unsat.smt2                                                           | 599.967s  | 599.967s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_5ite_unsat.smt2                                                           | 599.694s  | 599.694s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_6ite_unsat.smt2                                                           | 599.945s  | 599.945s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_7ite_unsat.smt2                                                           | 599.958s  | 599.958s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_8ite_unsat.smt2                                                           | 599.900s  | 599.900s  |   0.000s  | 0.0%|
|ring_2exp14_3vars_0ite_unsat.smt2                                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|ring_2exp14_3vars_1ite_unsat.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ring_2exp14_3vars_2ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_0ite_unsat.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_1ite_unsat.smt2                                                           |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_2ite_unsat.smt2                                                           |   0.876s  |   0.876s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_3ite_unsat.smt2                                                           |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_0ite_unsat.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_1ite_unsat.smt2                                                           | 356.127s  | 356.127s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_2ite_unsat.smt2                                                           | 227.846s  | 227.846s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_3ite_unsat.smt2                                                           | 129.374s  | 129.374s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_4ite_unsat.smt2                                                           | 113.384s  | 113.384s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_0ite_unsat.smt2                                                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_1ite_unsat.smt2                                                           | 599.774s  | 599.774s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_2ite_unsat.smt2                                                           | 599.494s  | 599.494s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_3ite_unsat.smt2                                                           | 599.913s  | 599.913s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_4ite_unsat.smt2                                                           | 599.927s  | 599.927s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_5ite_unsat.smt2                                                           | 599.676s  | 599.676s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_0ite_unsat.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_1ite_unsat.smt2                                                           | 599.780s  | 599.780s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_2ite_unsat.smt2                                                           | 599.938s  | 599.938s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_3ite_unsat.smt2                                                           | 599.883s  | 599.883s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_4ite_unsat.smt2                                                           | 599.730s  | 599.730s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_5ite_unsat.smt2                                                           | 599.808s  | 599.808s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_6ite_unsat.smt2                                                           | 599.691s  | 599.691s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_0ite_unsat.smt2                                                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_1ite_unsat.smt2                                                           | 599.863s  | 599.863s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_2ite_unsat.smt2                                                           | 599.643s  | 599.643s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_3ite_unsat.smt2                                                           | 599.717s  | 599.717s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_4ite_unsat.smt2                                                           | 599.159s  | 599.159s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_5ite_unsat.smt2                                                           | 599.564s  | 599.564s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_6ite_unsat.smt2                                                           | 599.703s  | 599.703s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_7ite_unsat.smt2                                                           | 599.946s  | 599.946s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_0ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_1ite_unsat.smt2                                                           | 599.958s  | 599.958s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_2ite_unsat.smt2                                                           | 599.871s  | 599.871s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_3ite_unsat.smt2                                                           | 599.744s  | 599.744s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_4ite_unsat.smt2                                                           | 599.324s  | 599.324s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_5ite_unsat.smt2                                                           | 599.883s  | 599.883s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_6ite_unsat.smt2                                                           | 599.952s  | 599.952s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_7ite_unsat.smt2                                                           | 599.689s  | 599.689s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_8ite_unsat.smt2                                                           | 599.948s  | 599.948s  |   0.000s  | 0.0%|
|ring_2exp16_3vars_0ite_unsat.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ring_2exp16_3vars_1ite_unsat.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp16_3vars_2ite_unsat.smt2                                                           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_0ite_unsat.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_1ite_unsat.smt2                                                           |   0.843s  |   0.843s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_2ite_unsat.smt2                                                           |   0.670s  |   0.670s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_3ite_unsat.smt2                                                           |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_0ite_unsat.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_1ite_unsat.smt2                                                           | 152.156s  | 152.156s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_2ite_unsat.smt2                                                           | 312.307s  | 312.307s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_3ite_unsat.smt2                                                           | 219.001s  | 219.001s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_4ite_unsat.smt2                                                           | 110.515s  | 110.515s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_0ite_unsat.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_1ite_unsat.smt2                                                           | 599.617s  | 599.617s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_2ite_unsat.smt2                                                           | 599.869s  | 599.869s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_3ite_unsat.smt2                                                           | 599.636s  | 599.636s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_4ite_unsat.smt2                                                           | 599.920s  | 599.920s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_5ite_unsat.smt2                                                           | 599.591s  | 599.591s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_0ite_unsat.smt2                                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_1ite_unsat.smt2                                                           | 599.963s  | 599.963s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_2ite_unsat.smt2                                                           | 599.803s  | 599.803s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_3ite_unsat.smt2                                                           | 599.933s  | 599.933s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_4ite_unsat.smt2                                                           | 599.841s  | 599.841s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_5ite_unsat.smt2                                                           | 599.762s  | 599.762s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_6ite_unsat.smt2                                                           | 599.941s  | 599.941s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_0ite_unsat.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_1ite_unsat.smt2                                                           | 599.940s  | 599.940s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_2ite_unsat.smt2                                                           | 599.962s  | 599.962s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_3ite_unsat.smt2                                                           | 599.827s  | 599.827s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_4ite_unsat.smt2                                                           | 599.902s  | 599.902s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_5ite_unsat.smt2                                                           | 599.846s  | 599.846s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_6ite_unsat.smt2                                                           | 599.910s  | 599.910s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_7ite_unsat.smt2                                                           | 599.952s  | 599.952s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_0ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_1ite_unsat.smt2                                                           | 599.921s  | 599.921s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_2ite_unsat.smt2                                                           | 599.868s  | 599.868s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_3ite_unsat.smt2                                                           | 599.964s  | 599.964s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_4ite_unsat.smt2                                                           | 599.781s  | 599.781s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_5ite_unsat.smt2                                                           | 599.206s  | 599.206s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_6ite_unsat.smt2                                                           | 599.755s  | 599.755s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_7ite_unsat.smt2                                                           | 599.298s  | 599.298s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_8ite_unsat.smt2                                                           | 599.954s  | 599.954s  |   0.000s  | 0.0%|
|ring_2exp4_3vars_0ite_unsat.smt2                                                            |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ring_2exp4_3vars_1ite_unsat.smt2                                                            |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|ring_2exp4_3vars_2ite_unsat.smt2                                                            |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_0ite_unsat.smt2                                                            |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_1ite_unsat.smt2                                                            |   1.116s  |   1.116s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_2ite_unsat.smt2                                                            |   1.019s  |   1.019s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_3ite_unsat.smt2                                                            |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_0ite_unsat.smt2                                                            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_1ite_unsat.smt2                                                            |   9.600s  |   9.600s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_2ite_unsat.smt2                                                            |  53.183s  |  53.183s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_3ite_unsat.smt2                                                            |   9.805s  |   9.805s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_4ite_unsat.smt2                                                            |  48.541s  |  48.541s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_0ite_unsat.smt2                                                            |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_1ite_unsat.smt2                                                            | 417.961s  | 417.961s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_2ite_unsat.smt2                                                            | 424.006s  | 424.006s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_3ite_unsat.smt2                                                            | 598.436s  | 598.436s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_4ite_unsat.smt2                                                            | 392.552s  | 392.552s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_5ite_unsat.smt2                                                            | 214.575s  | 214.575s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_0ite_unsat.smt2                                                            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_1ite_unsat.smt2                                                            | 195.085s  | 195.085s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_2ite_unsat.smt2                                                            | 184.007s  | 184.007s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_3ite_unsat.smt2                                                            | 599.697s  | 599.697s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_4ite_unsat.smt2                                                            | 599.207s  | 599.207s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_5ite_unsat.smt2                                                            | 599.911s  | 599.911s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_6ite_unsat.smt2                                                            | 599.731s  | 599.731s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_0ite_unsat.smt2                                                            |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_1ite_unsat.smt2                                                            | 221.061s  | 221.061s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_2ite_unsat.smt2                                                            | 413.221s  | 413.221s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_3ite_unsat.smt2                                                            | 599.707s  | 599.707s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_4ite_unsat.smt2                                                            | 599.964s  | 599.964s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_5ite_unsat.smt2                                                            | 599.937s  | 599.937s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_6ite_unsat.smt2                                                            | 599.953s  | 599.953s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_7ite_unsat.smt2                                                            | 599.613s  | 599.613s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_0ite_unsat.smt2                                                            |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_1ite_unsat.smt2                                                            | 599.947s  | 599.947s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_2ite_unsat.smt2                                                            | 599.950s  | 599.950s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_3ite_unsat.smt2                                                            | 599.955s  | 599.955s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_4ite_unsat.smt2                                                            | 599.928s  | 599.928s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_5ite_unsat.smt2                                                            | 599.706s  | 599.706s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_6ite_unsat.smt2                                                            | 599.942s  | 599.942s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_7ite_unsat.smt2                                                            | 599.733s  | 599.733s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_8ite_unsat.smt2                                                            | 599.935s  | 599.935s  |   0.000s  | 0.0%|
|ring_2exp6_3vars_0ite_unsat.smt2                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|ring_2exp6_3vars_1ite_unsat.smt2                                                            |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ring_2exp6_3vars_2ite_unsat.smt2                                                            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_0ite_unsat.smt2                                                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_1ite_unsat.smt2                                                            |   0.837s  |   0.837s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_2ite_unsat.smt2                                                            |   1.412s  |   1.412s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_3ite_unsat.smt2                                                            |   1.028s  |   1.028s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_0ite_unsat.smt2                                                            |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_1ite_unsat.smt2                                                            | 599.915s  | 599.915s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_2ite_unsat.smt2                                                            | 599.952s  | 599.952s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_3ite_unsat.smt2                                                            | 599.792s  | 599.792s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_4ite_unsat.smt2                                                            | 193.054s  | 193.054s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_0ite_unsat.smt2                                                            |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_1ite_unsat.smt2                                                            | 599.925s  | 599.925s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_2ite_unsat.smt2                                                            | 599.778s  | 599.778s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_3ite_unsat.smt2                                                            | 599.917s  | 599.917s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_4ite_unsat.smt2                                                            | 599.898s  | 599.898s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_5ite_unsat.smt2                                                            | 599.905s  | 599.905s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_0ite_unsat.smt2                                                            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_1ite_unsat.smt2                                                            | 599.485s  | 599.485s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_2ite_unsat.smt2                                                            | 599.684s  | 599.684s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_3ite_unsat.smt2                                                            | 599.823s  | 599.823s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_4ite_unsat.smt2                                                            | 599.489s  | 599.489s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_5ite_unsat.smt2                                                            | 599.946s  | 599.946s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_6ite_unsat.smt2                                                            | 599.832s  | 599.832s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_0ite_unsat.smt2                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_1ite_unsat.smt2                                                            | 599.820s  | 599.820s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_2ite_unsat.smt2                                                            | 599.532s  | 599.532s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_3ite_unsat.smt2                                                            | 599.933s  | 599.933s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_4ite_unsat.smt2                                                            | 599.620s  | 599.620s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_5ite_unsat.smt2                                                            | 597.468s  | 597.468s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_6ite_unsat.smt2                                                            | 599.950s  | 599.950s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_7ite_unsat.smt2                                                            | 599.847s  | 599.847s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_0ite_unsat.smt2                                                            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_1ite_unsat.smt2                                                            | 599.961s  | 599.961s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_2ite_unsat.smt2                                                            | 599.343s  | 599.343s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_3ite_unsat.smt2                                                            | 599.961s  | 599.961s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_4ite_unsat.smt2                                                            | 599.831s  | 599.831s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_5ite_unsat.smt2                                                            | 599.701s  | 599.701s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_6ite_unsat.smt2                                                            | 599.872s  | 599.872s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_7ite_unsat.smt2                                                            | 599.830s  | 599.830s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_8ite_unsat.smt2                                                            | 598.488s  | 598.488s  |   0.000s  | 0.0%|
|ring_2exp8_3vars_0ite_unsat.smt2                                                            |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp8_3vars_1ite_unsat.smt2                                                            |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ring_2exp8_3vars_2ite_unsat.smt2                                                            |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_0ite_unsat.smt2                                                            |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_1ite_unsat.smt2                                                            |   0.850s  |   0.850s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_2ite_unsat.smt2                                                            |   1.085s  |   1.085s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_3ite_unsat.smt2                                                            |   0.869s  |   0.869s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_0ite_unsat.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_1ite_unsat.smt2                                                            | 309.884s  | 309.884s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_2ite_unsat.smt2                                                            | 599.782s  | 599.782s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_3ite_unsat.smt2                                                            | 599.578s  | 599.578s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_4ite_unsat.smt2                                                            |  96.721s  |  96.721s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_0ite_unsat.smt2                                                            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_1ite_unsat.smt2                                                            | 599.948s  | 599.948s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_2ite_unsat.smt2                                                            | 599.965s  | 599.965s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_3ite_unsat.smt2                                                            | 599.903s  | 599.903s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_4ite_unsat.smt2                                                            | 599.508s  | 599.508s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_5ite_unsat.smt2                                                            | 599.858s  | 599.858s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_0ite_unsat.smt2                                                            |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_1ite_unsat.smt2                                                            | 599.971s  | 599.971s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_2ite_unsat.smt2                                                            | 599.924s  | 599.924s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_3ite_unsat.smt2                                                            | 599.948s  | 599.948s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_4ite_unsat.smt2                                                            | 599.811s  | 599.811s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_5ite_unsat.smt2                                                            | 599.824s  | 599.824s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_6ite_unsat.smt2                                                            | 599.949s  | 599.949s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_0ite_unsat.smt2                                                            |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_1ite_unsat.smt2                                                            | 598.651s  | 598.651s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_2ite_unsat.smt2                                                            | 599.937s  | 599.937s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_3ite_unsat.smt2                                                            | 599.808s  | 599.808s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_4ite_unsat.smt2                                                            | 599.914s  | 599.914s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_5ite_unsat.smt2                                                            | 599.567s  | 599.567s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_6ite_unsat.smt2                                                            | 598.471s  | 598.471s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_7ite_unsat.smt2                                                            | 599.964s  | 599.964s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_0ite_unsat.smt2                                                            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_1ite_unsat.smt2                                                            | 598.793s  | 598.793s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_2ite_unsat.smt2                                                            | 598.893s  | 598.893s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_3ite_unsat.smt2                                                            | 599.944s  | 599.944s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_4ite_unsat.smt2                                                            | 599.715s  | 599.715s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_5ite_unsat.smt2                                                            | 599.922s  | 599.922s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_6ite_unsat.smt2                                                            | 599.947s  | 599.947s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_7ite_unsat.smt2                                                            | 599.963s  | 599.963s  |   0.000s  | 0.0%|
</details>
