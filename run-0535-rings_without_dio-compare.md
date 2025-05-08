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
Job tag: rings_without_dio
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: dd211bade9ecb681c2714d6de997f4c91bdf7a2e
Z3 branch: 
Z3 options: "-T:600 -st lp.dio=false"
Z3 inputs: inputs/rings
Z3 commit message: filter out terms that are not solved

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: rings_without_dio
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: dd211bade9ecb681c2714d6de997f4c91bdf7a2e
Z3 branch: 
Z3 options: "-T:600 -st lp.dio=false"
Z3 inputs: inputs/rings
Z3 commit message: filter out terms that are not solved

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   1.098s  |   1.098s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   1.360s  |   1.360s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.954s  |   0.954s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           | 313.179s  | 313.179s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           | 253.529s  | 253.529s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           | 599.902s  | 599.902s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           | 136.456s  | 136.456s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           | 599.604s  | 599.604s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           | 599.922s  | 599.922s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           | 599.945s  | 599.945s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           | 599.273s  | 599.273s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           | 599.930s  | 599.930s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           | 599.496s  | 599.496s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   1.098s  |   1.098s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   1.360s  |   1.360s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.954s  |   0.954s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           | 313.179s  | 313.179s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           | 253.529s  | 253.529s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           | 599.902s  | 599.902s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           | 136.456s  | 136.456s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           | 599.604s  | 599.604s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           | 599.922s  | 599.922s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           | 599.945s  | 599.945s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           | 599.273s  | 599.273s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           | 599.930s  | 599.930s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           | 599.496s  | 599.496s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   1.098s  |   1.098s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   1.360s  |   1.360s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.954s  |   0.954s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           | 313.179s  | 313.179s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           | 253.529s  | 253.529s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           | 599.902s  | 599.902s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           | 136.456s  | 136.456s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           | 599.604s  | 599.604s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           | 599.922s  | 599.922s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           | 599.945s  | 599.945s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           | 599.273s  | 599.273s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           | 599.930s  | 599.930s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           | 599.496s  | 599.496s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   1.098s  |   1.098s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   1.360s  |   1.360s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.954s  |   0.954s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           | 313.179s  | 313.179s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           | 253.529s  | 253.529s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           | 599.902s  | 599.902s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           | 136.456s  | 136.456s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           | 599.604s  | 599.604s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           | 599.922s  | 599.922s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           | 599.945s  | 599.945s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           | 599.273s  | 599.273s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           | 599.930s  | 599.930s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           | 599.496s  | 599.496s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp16_8vars_6ite_unsat.smt2                                                          | 599.957s |38.12MiB|
|ring_2exp16_9vars_8ite_unsat.smt2                                                          | 599.948s |42.196MiB|
|ring_2exp16_8vars_7ite_unsat.smt2                                                          | 599.947s |37.664MiB|
|ring_2exp8_6vars_2ite_unsat.smt2                                                           | 599.946s |44.968MiB|
|ring_2exp8_8vars_2ite_unsat.smt2                                                           | 599.946s |46.044MiB|
|ring_2exp12_7vars_4ite_unsat.smt2                                                          | 599.946s |41.82MiB|
|ring_2exp12_9vars_3ite_unsat.smt2                                                          | 599.945s |50.712MiB|
|ring_2exp10_6vars_3ite_unsat.smt2                                                          | 599.945s |44.388MiB|
|ring_2exp16_7vars_6ite_unsat.smt2                                                          | 599.944s |43.84MiB|
|ring_2exp16_7vars_1ite_unsat.smt2                                                          | 599.944s |45.508MiB|
|ring_2exp12_9vars_6ite_unsat.smt2                                                          | 599.944s |49.244MiB|
|ring_2exp6_9vars_1ite_unsat.smt2                                                           | 599.943s |47.7MiB|
|ring_2exp12_7vars_2ite_unsat.smt2                                                          | 599.943s |44.552MiB|
|ring_2exp4_9vars_2ite_unsat.smt2                                                           | 599.943s |41.964MiB|
|ring_2exp14_9vars_6ite_unsat.smt2                                                          | 599.943s |46.884MiB|
|ring_2exp4_9vars_6ite_unsat.smt2                                                           | 599.942s |37.896MiB|
|ring_2exp4_9vars_8ite_unsat.smt2                                                           | 599.940s |37.792MiB|
|ring_2exp12_9vars_7ite_unsat.smt2                                                          | 599.940s |45.116MiB|
|ring_2exp8_9vars_5ite_unsat.smt2                                                           | 599.940s |38.64MiB|
|ring_2exp8_9vars_3ite_unsat.smt2                                                           | 599.939s |50.092MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp16_8vars_6ite_unsat.smt2                                                          | 599.957s |38.12MiB|
|ring_2exp16_9vars_8ite_unsat.smt2                                                          | 599.948s |42.196MiB|
|ring_2exp16_8vars_7ite_unsat.smt2                                                          | 599.947s |37.664MiB|
|ring_2exp8_6vars_2ite_unsat.smt2                                                           | 599.946s |44.968MiB|
|ring_2exp8_8vars_2ite_unsat.smt2                                                           | 599.946s |46.044MiB|
|ring_2exp12_7vars_4ite_unsat.smt2                                                          | 599.946s |41.82MiB|
|ring_2exp12_9vars_3ite_unsat.smt2                                                          | 599.945s |50.712MiB|
|ring_2exp10_6vars_3ite_unsat.smt2                                                          | 599.945s |44.388MiB|
|ring_2exp16_7vars_6ite_unsat.smt2                                                          | 599.944s |43.84MiB|
|ring_2exp16_7vars_1ite_unsat.smt2                                                          | 599.944s |45.508MiB|
|ring_2exp12_9vars_6ite_unsat.smt2                                                          | 599.944s |49.244MiB|
|ring_2exp6_9vars_1ite_unsat.smt2                                                           | 599.943s |47.7MiB|
|ring_2exp12_7vars_2ite_unsat.smt2                                                          | 599.943s |44.552MiB|
|ring_2exp4_9vars_2ite_unsat.smt2                                                           | 599.943s |41.964MiB|
|ring_2exp14_9vars_6ite_unsat.smt2                                                          | 599.943s |46.884MiB|
|ring_2exp4_9vars_6ite_unsat.smt2                                                           | 599.942s |37.896MiB|
|ring_2exp4_9vars_8ite_unsat.smt2                                                           | 599.940s |37.792MiB|
|ring_2exp12_9vars_7ite_unsat.smt2                                                          | 599.940s |45.116MiB|
|ring_2exp8_9vars_5ite_unsat.smt2                                                           | 599.940s |38.64MiB|
|ring_2exp8_9vars_3ite_unsat.smt2                                                           | 599.939s |50.092MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.372MiB|20.372MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.296MiB|20.296MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.192MiB|20.192MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.512MiB|20.512MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |21.032MiB|21.032MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.92MiB|20.92MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.792MiB|20.792MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.516MiB|20.516MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |32.12MiB|32.12MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |34.336MiB|34.336MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |34.576MiB|34.576MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |29.628MiB|29.628MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.552MiB|20.552MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |39.108MiB|39.108MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |42.28MiB|42.28MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |44.388MiB|44.388MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |38.268MiB|38.268MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |43.04MiB|43.04MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |20.776MiB|20.776MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |41.28MiB|41.28MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.372MiB|20.372MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.296MiB|20.296MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.192MiB|20.192MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.512MiB|20.512MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |21.032MiB|21.032MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.92MiB|20.92MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.792MiB|20.792MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.516MiB|20.516MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |32.12MiB|32.12MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |34.336MiB|34.336MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |34.576MiB|34.576MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |29.628MiB|29.628MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.552MiB|20.552MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |39.108MiB|39.108MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |42.28MiB|42.28MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |44.388MiB|44.388MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |38.268MiB|38.268MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |43.04MiB|43.04MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |20.776MiB|20.776MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |41.28MiB|41.28MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.372MiB|20.372MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.296MiB|20.296MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.192MiB|20.192MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.512MiB|20.512MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |21.032MiB|21.032MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.92MiB|20.92MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.792MiB|20.792MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.516MiB|20.516MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |32.12MiB|32.12MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |34.336MiB|34.336MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |34.576MiB|34.576MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |29.628MiB|29.628MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.552MiB|20.552MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |39.108MiB|39.108MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |42.28MiB|42.28MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |44.388MiB|44.388MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |38.268MiB|38.268MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |43.04MiB|43.04MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |20.776MiB|20.776MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |41.28MiB|41.28MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.372MiB|20.372MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.296MiB|20.296MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.192MiB|20.192MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.512MiB|20.512MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |21.032MiB|21.032MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.92MiB|20.92MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.792MiB|20.792MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.516MiB|20.516MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |32.12MiB|32.12MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |34.336MiB|34.336MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |34.576MiB|34.576MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |29.628MiB|29.628MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.552MiB|20.552MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |39.108MiB|39.108MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |42.28MiB|42.28MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |44.388MiB|44.388MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |38.268MiB|38.268MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |43.04MiB|43.04MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |20.776MiB|20.776MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |41.28MiB|41.28MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp12_9vars_3ite_unsat.smt2                                                          | 599.945s |50.712MiB|
|ring_2exp16_8vars_1ite_unsat.smt2                                                          | 599.907s |50.536MiB|
|ring_2exp8_9vars_3ite_unsat.smt2                                                           | 599.939s |50.092MiB|
|ring_2exp12_9vars_6ite_unsat.smt2                                                          | 599.944s |49.244MiB|
|ring_2exp12_8vars_2ite_unsat.smt2                                                          | 599.932s |48.72MiB|
|ring_2exp10_9vars_7ite_unsat.smt2                                                          | 599.931s |48.372MiB|
|ring_2exp8_9vars_6ite_unsat.smt2                                                           | 599.921s |48.068MiB|
|ring_2exp16_9vars_2ite_unsat.smt2                                                          | 599.909s |47.868MiB|
|ring_2exp6_9vars_1ite_unsat.smt2                                                           | 599.943s |47.7MiB|
|ring_2exp14_9vars_1ite_unsat.smt2                                                          | 599.919s |47.232MiB|
|ring_2exp8_9vars_7ite_unsat.smt2                                                           | 599.923s |47.2MiB|
|ring_2exp16_9vars_3ite_unsat.smt2                                                          | 599.921s |47.064MiB|
|ring_2exp14_9vars_6ite_unsat.smt2                                                          | 599.943s |46.884MiB|
|ring_2exp12_9vars_1ite_unsat.smt2                                                          | 599.875s |46.528MiB|
|ring_2exp10_7vars_5ite_unsat.smt2                                                          | 599.927s |46.156MiB|
|ring_2exp16_8vars_2ite_unsat.smt2                                                          | 599.934s |46.084MiB|
|ring_2exp8_8vars_2ite_unsat.smt2                                                           | 599.946s |46.044MiB|
|ring_2exp10_9vars_2ite_unsat.smt2                                                          | 599.911s |45.608MiB|
|ring_2exp16_7vars_1ite_unsat.smt2                                                          | 599.944s |45.508MiB|
|ring_2exp12_9vars_2ite_unsat.smt2                                                          | 599.570s |45.272MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp12_9vars_3ite_unsat.smt2                                                          | 599.945s |50.712MiB|
|ring_2exp16_8vars_1ite_unsat.smt2                                                          | 599.907s |50.536MiB|
|ring_2exp8_9vars_3ite_unsat.smt2                                                           | 599.939s |50.092MiB|
|ring_2exp12_9vars_6ite_unsat.smt2                                                          | 599.944s |49.244MiB|
|ring_2exp12_8vars_2ite_unsat.smt2                                                          | 599.932s |48.72MiB|
|ring_2exp10_9vars_7ite_unsat.smt2                                                          | 599.931s |48.372MiB|
|ring_2exp8_9vars_6ite_unsat.smt2                                                           | 599.921s |48.068MiB|
|ring_2exp16_9vars_2ite_unsat.smt2                                                          | 599.909s |47.868MiB|
|ring_2exp6_9vars_1ite_unsat.smt2                                                           | 599.943s |47.7MiB|
|ring_2exp14_9vars_1ite_unsat.smt2                                                          | 599.919s |47.232MiB|
|ring_2exp8_9vars_7ite_unsat.smt2                                                           | 599.923s |47.2MiB|
|ring_2exp16_9vars_3ite_unsat.smt2                                                          | 599.921s |47.064MiB|
|ring_2exp14_9vars_6ite_unsat.smt2                                                          | 599.943s |46.884MiB|
|ring_2exp12_9vars_1ite_unsat.smt2                                                          | 599.875s |46.528MiB|
|ring_2exp10_7vars_5ite_unsat.smt2                                                          | 599.927s |46.156MiB|
|ring_2exp16_8vars_2ite_unsat.smt2                                                          | 599.934s |46.084MiB|
|ring_2exp8_8vars_2ite_unsat.smt2                                                           | 599.946s |46.044MiB|
|ring_2exp10_9vars_2ite_unsat.smt2                                                          | 599.911s |45.608MiB|
|ring_2exp16_7vars_1ite_unsat.smt2                                                          | 599.944s |45.508MiB|
|ring_2exp12_9vars_2ite_unsat.smt2                                                          | 599.570s |45.272MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   1.098s  |   1.098s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   1.360s  |   1.360s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.954s  |   0.954s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           | 313.179s  | 313.179s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           | 253.529s  | 253.529s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           | 599.902s  | 599.902s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           | 136.456s  | 136.456s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           | 599.604s  | 599.604s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           | 599.922s  | 599.922s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           | 599.945s  | 599.945s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           | 599.273s  | 599.273s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           | 599.930s  | 599.930s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           | 599.496s  | 599.496s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_2ite_unsat.smt2                                                           | 599.239s  | 599.239s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_3ite_unsat.smt2                                                           | 599.084s  | 599.084s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_4ite_unsat.smt2                                                           | 599.144s  | 599.144s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_5ite_unsat.smt2                                                           | 599.927s  | 599.927s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_6ite_unsat.smt2                                                           | 599.934s  | 599.934s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_0ite_unsat.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_1ite_unsat.smt2                                                           | 599.809s  | 599.809s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_2ite_unsat.smt2                                                           | 599.905s  | 599.905s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_3ite_unsat.smt2                                                           | 599.935s  | 599.935s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_4ite_unsat.smt2                                                           | 599.729s  | 599.729s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_5ite_unsat.smt2                                                           | 599.937s  | 599.937s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_6ite_unsat.smt2                                                           | 599.501s  | 599.501s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_7ite_unsat.smt2                                                           | 599.648s  | 599.648s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_0ite_unsat.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_1ite_unsat.smt2                                                           | 599.924s  | 599.924s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_2ite_unsat.smt2                                                           | 599.911s  | 599.911s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_3ite_unsat.smt2                                                           | 599.603s  | 599.603s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_4ite_unsat.smt2                                                           | 599.281s  | 599.281s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_5ite_unsat.smt2                                                           | 599.774s  | 599.774s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_6ite_unsat.smt2                                                           | 599.727s  | 599.727s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_7ite_unsat.smt2                                                           | 599.931s  | 599.931s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_8ite_unsat.smt2                                                           | 599.755s  | 599.755s  |   0.000s  | 0.0%|
|ring_2exp12_3vars_0ite_unsat.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp12_3vars_1ite_unsat.smt2                                                           |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|ring_2exp12_3vars_2ite_unsat.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_0ite_unsat.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_1ite_unsat.smt2                                                           |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_2ite_unsat.smt2                                                           |   1.057s  |   1.057s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_3ite_unsat.smt2                                                           |   0.910s  |   0.910s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_0ite_unsat.smt2                                                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_1ite_unsat.smt2                                                           | 286.601s  | 286.601s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_2ite_unsat.smt2                                                           | 571.003s  | 571.003s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_3ite_unsat.smt2                                                           | 242.836s  | 242.836s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_4ite_unsat.smt2                                                           | 129.757s  | 129.757s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_0ite_unsat.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_1ite_unsat.smt2                                                           | 599.876s  | 599.876s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_2ite_unsat.smt2                                                           | 599.783s  | 599.783s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_3ite_unsat.smt2                                                           | 599.888s  | 599.888s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_4ite_unsat.smt2                                                           | 599.697s  | 599.697s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_5ite_unsat.smt2                                                           | 598.251s  | 598.251s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_0ite_unsat.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_1ite_unsat.smt2                                                           | 599.712s  | 599.712s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_2ite_unsat.smt2                                                           | 599.943s  | 599.943s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_3ite_unsat.smt2                                                           | 599.803s  | 599.803s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_4ite_unsat.smt2                                                           | 599.946s  | 599.946s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_5ite_unsat.smt2                                                           | 599.926s  | 599.926s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_6ite_unsat.smt2                                                           | 599.832s  | 599.832s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_0ite_unsat.smt2                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_1ite_unsat.smt2                                                           | 599.838s  | 599.838s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_2ite_unsat.smt2                                                           | 599.932s  | 599.932s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_3ite_unsat.smt2                                                           | 599.909s  | 599.909s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_4ite_unsat.smt2                                                           | 599.754s  | 599.754s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_5ite_unsat.smt2                                                           | 599.898s  | 599.898s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_6ite_unsat.smt2                                                           | 599.913s  | 599.913s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_7ite_unsat.smt2                                                           | 599.426s  | 599.426s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_0ite_unsat.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_1ite_unsat.smt2                                                           | 599.875s  | 599.875s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_2ite_unsat.smt2                                                           | 599.570s  | 599.570s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_3ite_unsat.smt2                                                           | 599.945s  | 599.945s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_4ite_unsat.smt2                                                           | 599.925s  | 599.925s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_5ite_unsat.smt2                                                           | 599.818s  | 599.818s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_6ite_unsat.smt2                                                           | 599.944s  | 599.944s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_7ite_unsat.smt2                                                           | 599.940s  | 599.940s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_8ite_unsat.smt2                                                           | 599.921s  | 599.921s  |   0.000s  | 0.0%|
|ring_2exp14_3vars_0ite_unsat.smt2                                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|ring_2exp14_3vars_1ite_unsat.smt2                                                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|ring_2exp14_3vars_2ite_unsat.smt2                                                           |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_0ite_unsat.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_1ite_unsat.smt2                                                           |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_2ite_unsat.smt2                                                           |   0.919s  |   0.919s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_3ite_unsat.smt2                                                           |   0.874s  |   0.874s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_0ite_unsat.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_1ite_unsat.smt2                                                           | 364.475s  | 364.475s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_2ite_unsat.smt2                                                           | 238.363s  | 238.363s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_3ite_unsat.smt2                                                           | 138.338s  | 138.338s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_4ite_unsat.smt2                                                           | 120.690s  | 120.690s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_0ite_unsat.smt2                                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_1ite_unsat.smt2                                                           | 599.819s  | 599.819s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_2ite_unsat.smt2                                                           | 599.765s  | 599.765s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_3ite_unsat.smt2                                                           | 599.814s  | 599.814s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_4ite_unsat.smt2                                                           | 599.905s  | 599.905s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_5ite_unsat.smt2                                                           | 598.538s  | 598.538s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_0ite_unsat.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_1ite_unsat.smt2                                                           | 599.661s  | 599.661s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_2ite_unsat.smt2                                                           | 599.934s  | 599.934s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_3ite_unsat.smt2                                                           | 599.741s  | 599.741s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_4ite_unsat.smt2                                                           | 599.844s  | 599.844s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_5ite_unsat.smt2                                                           | 599.541s  | 599.541s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_6ite_unsat.smt2                                                           | 599.919s  | 599.919s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_0ite_unsat.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_1ite_unsat.smt2                                                           | 599.778s  | 599.778s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_2ite_unsat.smt2                                                           | 599.769s  | 599.769s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_3ite_unsat.smt2                                                           | 599.669s  | 599.669s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_4ite_unsat.smt2                                                           | 599.207s  | 599.207s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_5ite_unsat.smt2                                                           | 599.854s  | 599.854s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_6ite_unsat.smt2                                                           | 599.911s  | 599.911s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_7ite_unsat.smt2                                                           | 599.927s  | 599.927s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_0ite_unsat.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_1ite_unsat.smt2                                                           | 599.919s  | 599.919s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_2ite_unsat.smt2                                                           | 599.411s  | 599.411s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_3ite_unsat.smt2                                                           | 599.899s  | 599.899s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_4ite_unsat.smt2                                                           | 599.829s  | 599.829s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_5ite_unsat.smt2                                                           | 599.921s  | 599.921s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_6ite_unsat.smt2                                                           | 599.943s  | 599.943s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_7ite_unsat.smt2                                                           | 599.879s  | 599.879s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_8ite_unsat.smt2                                                           | 599.738s  | 599.738s  |   0.000s  | 0.0%|
|ring_2exp16_3vars_0ite_unsat.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp16_3vars_1ite_unsat.smt2                                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ring_2exp16_3vars_2ite_unsat.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_0ite_unsat.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_1ite_unsat.smt2                                                           |   1.025s  |   1.025s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_2ite_unsat.smt2                                                           |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_3ite_unsat.smt2                                                           |   0.934s  |   0.934s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_0ite_unsat.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_1ite_unsat.smt2                                                           | 159.168s  | 159.168s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_2ite_unsat.smt2                                                           | 320.020s  | 320.020s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_3ite_unsat.smt2                                                           | 231.711s  | 231.711s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_4ite_unsat.smt2                                                           | 117.661s  | 117.661s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_0ite_unsat.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_1ite_unsat.smt2                                                           | 599.923s  | 599.923s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_2ite_unsat.smt2                                                           | 599.841s  | 599.841s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_3ite_unsat.smt2                                                           | 599.784s  | 599.784s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_4ite_unsat.smt2                                                           | 599.825s  | 599.825s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_5ite_unsat.smt2                                                           | 599.902s  | 599.902s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_0ite_unsat.smt2                                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_1ite_unsat.smt2                                                           | 599.944s  | 599.944s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_2ite_unsat.smt2                                                           | 599.876s  | 599.876s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_3ite_unsat.smt2                                                           | 599.894s  | 599.894s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_4ite_unsat.smt2                                                           | 599.873s  | 599.873s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_5ite_unsat.smt2                                                           | 599.840s  | 599.840s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_6ite_unsat.smt2                                                           | 599.944s  | 599.944s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_0ite_unsat.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_1ite_unsat.smt2                                                           | 599.907s  | 599.907s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_2ite_unsat.smt2                                                           | 599.934s  | 599.934s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_3ite_unsat.smt2                                                           | 596.950s  | 596.950s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_4ite_unsat.smt2                                                           | 599.915s  | 599.915s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_5ite_unsat.smt2                                                           | 599.759s  | 599.759s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_6ite_unsat.smt2                                                           | 599.957s  | 599.957s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_7ite_unsat.smt2                                                           | 599.947s  | 599.947s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_0ite_unsat.smt2                                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_1ite_unsat.smt2                                                           | 599.296s  | 599.296s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_2ite_unsat.smt2                                                           | 599.909s  | 599.909s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_3ite_unsat.smt2                                                           | 599.921s  | 599.921s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_4ite_unsat.smt2                                                           | 599.623s  | 599.623s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_5ite_unsat.smt2                                                           | 599.416s  | 599.416s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_6ite_unsat.smt2                                                           | 599.904s  | 599.904s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_7ite_unsat.smt2                                                           | 599.673s  | 599.673s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_8ite_unsat.smt2                                                           | 599.948s  | 599.948s  |   0.000s  | 0.0%|
|ring_2exp4_3vars_0ite_unsat.smt2                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ring_2exp4_3vars_1ite_unsat.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|ring_2exp4_3vars_2ite_unsat.smt2                                                            |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_0ite_unsat.smt2                                                            |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_1ite_unsat.smt2                                                            |   1.372s  |   1.372s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_2ite_unsat.smt2                                                            |   0.802s  |   0.802s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_3ite_unsat.smt2                                                            |   0.946s  |   0.946s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_0ite_unsat.smt2                                                            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_1ite_unsat.smt2                                                            |  53.935s  |  53.935s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_2ite_unsat.smt2                                                            |  55.513s  |  55.513s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_3ite_unsat.smt2                                                            |  58.563s  |  58.563s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_4ite_unsat.smt2                                                            |  51.358s  |  51.358s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_0ite_unsat.smt2                                                            |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_1ite_unsat.smt2                                                            | 397.529s  | 397.529s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_2ite_unsat.smt2                                                            | 442.251s  | 442.251s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_3ite_unsat.smt2                                                            | 598.038s  | 598.038s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_4ite_unsat.smt2                                                            | 411.767s  | 411.767s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_5ite_unsat.smt2                                                            | 182.982s  | 182.982s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_0ite_unsat.smt2                                                            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_1ite_unsat.smt2                                                            | 255.863s  | 255.863s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_2ite_unsat.smt2                                                            | 190.647s  | 190.647s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_3ite_unsat.smt2                                                            | 599.808s  | 599.808s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_4ite_unsat.smt2                                                            | 598.749s  | 598.749s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_5ite_unsat.smt2                                                            | 599.843s  | 599.843s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_6ite_unsat.smt2                                                            | 599.797s  | 599.797s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_0ite_unsat.smt2                                                            |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_1ite_unsat.smt2                                                            | 242.171s  | 242.171s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_2ite_unsat.smt2                                                            | 440.809s  | 440.809s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_3ite_unsat.smt2                                                            | 599.925s  | 599.925s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_4ite_unsat.smt2                                                            | 599.858s  | 599.858s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_5ite_unsat.smt2                                                            | 599.914s  | 599.914s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_6ite_unsat.smt2                                                            | 599.934s  | 599.934s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_7ite_unsat.smt2                                                            | 599.879s  | 599.879s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_0ite_unsat.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_1ite_unsat.smt2                                                            | 599.922s  | 599.922s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_2ite_unsat.smt2                                                            | 599.943s  | 599.943s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_3ite_unsat.smt2                                                            | 599.929s  | 599.929s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_4ite_unsat.smt2                                                            | 599.835s  | 599.835s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_5ite_unsat.smt2                                                            | 599.853s  | 599.853s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_6ite_unsat.smt2                                                            | 599.942s  | 599.942s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_7ite_unsat.smt2                                                            | 599.176s  | 599.176s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_8ite_unsat.smt2                                                            | 599.940s  | 599.940s  |   0.000s  | 0.0%|
|ring_2exp6_3vars_0ite_unsat.smt2                                                            |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ring_2exp6_3vars_1ite_unsat.smt2                                                            |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp6_3vars_2ite_unsat.smt2                                                            |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_0ite_unsat.smt2                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_1ite_unsat.smt2                                                            |   1.437s  |   1.437s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_2ite_unsat.smt2                                                            |   1.593s  |   1.593s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_3ite_unsat.smt2                                                            |   1.195s  |   1.195s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_0ite_unsat.smt2                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_1ite_unsat.smt2                                                            | 595.633s  | 595.633s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_2ite_unsat.smt2                                                            | 599.910s  | 599.910s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_3ite_unsat.smt2                                                            | 599.858s  | 599.858s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_4ite_unsat.smt2                                                            | 246.184s  | 246.184s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_0ite_unsat.smt2                                                            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_1ite_unsat.smt2                                                            | 599.827s  | 599.827s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_2ite_unsat.smt2                                                            | 598.604s  | 598.604s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_3ite_unsat.smt2                                                            | 599.876s  | 599.876s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_4ite_unsat.smt2                                                            | 599.766s  | 599.766s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_5ite_unsat.smt2                                                            | 599.601s  | 599.601s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_0ite_unsat.smt2                                                            |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_1ite_unsat.smt2                                                            | 599.767s  | 599.767s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_2ite_unsat.smt2                                                            | 599.797s  | 599.797s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_3ite_unsat.smt2                                                            | 599.898s  | 599.898s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_4ite_unsat.smt2                                                            | 599.690s  | 599.690s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_5ite_unsat.smt2                                                            | 599.911s  | 599.911s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_6ite_unsat.smt2                                                            | 599.626s  | 599.626s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_0ite_unsat.smt2                                                            |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_1ite_unsat.smt2                                                            | 599.644s  | 599.644s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_2ite_unsat.smt2                                                            | 599.751s  | 599.751s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_3ite_unsat.smt2                                                            | 599.712s  | 599.712s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_4ite_unsat.smt2                                                            | 599.723s  | 599.723s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_5ite_unsat.smt2                                                            | 599.857s  | 599.857s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_6ite_unsat.smt2                                                            | 599.933s  | 599.933s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_7ite_unsat.smt2                                                            | 599.763s  | 599.763s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_0ite_unsat.smt2                                                            |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_1ite_unsat.smt2                                                            | 599.943s  | 599.943s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_2ite_unsat.smt2                                                            | 599.684s  | 599.684s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_3ite_unsat.smt2                                                            | 599.938s  | 599.938s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_4ite_unsat.smt2                                                            | 599.927s  | 599.927s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_5ite_unsat.smt2                                                            | 599.779s  | 599.779s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_6ite_unsat.smt2                                                            | 599.817s  | 599.817s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_7ite_unsat.smt2                                                            | 599.768s  | 599.768s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_8ite_unsat.smt2                                                            | 599.907s  | 599.907s  |   0.000s  | 0.0%|
|ring_2exp8_3vars_0ite_unsat.smt2                                                            |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ring_2exp8_3vars_1ite_unsat.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|ring_2exp8_3vars_2ite_unsat.smt2                                                            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_0ite_unsat.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_1ite_unsat.smt2                                                            |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_2ite_unsat.smt2                                                            |   1.224s  |   1.224s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_3ite_unsat.smt2                                                            |   1.015s  |   1.015s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_0ite_unsat.smt2                                                            |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_1ite_unsat.smt2                                                            | 315.602s  | 315.602s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_2ite_unsat.smt2                                                            | 599.832s  | 599.832s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_3ite_unsat.smt2                                                            | 599.373s  | 599.373s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_4ite_unsat.smt2                                                            | 140.395s  | 140.395s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_0ite_unsat.smt2                                                            |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_1ite_unsat.smt2                                                            | 599.922s  | 599.922s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_2ite_unsat.smt2                                                            | 599.946s  | 599.946s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_3ite_unsat.smt2                                                            | 599.878s  | 599.878s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_4ite_unsat.smt2                                                            | 599.885s  | 599.885s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_5ite_unsat.smt2                                                            | 599.667s  | 599.667s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_0ite_unsat.smt2                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_1ite_unsat.smt2                                                            | 599.924s  | 599.924s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_2ite_unsat.smt2                                                            | 599.827s  | 599.827s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_3ite_unsat.smt2                                                            | 599.928s  | 599.928s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_4ite_unsat.smt2                                                            | 599.867s  | 599.867s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_5ite_unsat.smt2                                                            | 599.739s  | 599.739s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_6ite_unsat.smt2                                                            | 599.934s  | 599.934s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_0ite_unsat.smt2                                                            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_1ite_unsat.smt2                                                            | 599.276s  | 599.276s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_2ite_unsat.smt2                                                            | 599.946s  | 599.946s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_3ite_unsat.smt2                                                            | 599.770s  | 599.770s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_4ite_unsat.smt2                                                            | 599.922s  | 599.922s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_5ite_unsat.smt2                                                            | 599.584s  | 599.584s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_6ite_unsat.smt2                                                            | 599.896s  | 599.896s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_7ite_unsat.smt2                                                            | 599.929s  | 599.929s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_0ite_unsat.smt2                                                            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_1ite_unsat.smt2                                                            | 599.886s  | 599.886s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_2ite_unsat.smt2                                                            | 599.913s  | 599.913s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_3ite_unsat.smt2                                                            | 599.939s  | 599.939s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_4ite_unsat.smt2                                                            | 599.517s  | 599.517s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_5ite_unsat.smt2                                                            | 599.940s  | 599.940s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_6ite_unsat.smt2                                                            | 599.921s  | 599.921s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_7ite_unsat.smt2                                                            | 599.923s  | 599.923s  |   0.000s  | 0.0%|
</details>
